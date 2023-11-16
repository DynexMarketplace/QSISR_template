# "Quantum Single Image Super-Resolution" Template
This template shows you how to compute Quantum Single Image Super-Resolution (QSISR) on <strong>Dynex</strong>

Implementation of a Quantum Single Image Super-Resolution algorithm to use on the Dynex platform. One of the well-known classical approaches for SISR relies on the well-established patch-wise sparse modeling of the problem. Yet, this field’s current state of affairs is that deep neural networks (DNNs) have demonstrated far superior results than traditional approaches. Nevertheless, quantum computing is expected to become increasingly prominent for machine learning problems soon. Among the two paradigms of quantum computing, namely universal gate quantum computing and adiabatic quantum computing (AQC), the latter has been successfully applied to practical computer vision problems, in which quantum parallelism has been exploited to solve combinatorial optimization efficiently.

This algorithm demonstrates formulating quantum SISR as a sparse coding optimization problem, which is solved using the Dynex Neuromorphic Computing Platform via the Dynex SDK. This AQC-based algorithm is demonstrated to achieve improved SISR accuracy.

<p style="color: green;">FREE TEMPLATE (DYNEX DEVELOPERS)</p>

## Requirements

In addition to having the Dynex SDK installed and configured, the following packages are required:

```
pip install spams-bin
pip install easydict
pip install qubovert
pip install -U scikit-image
```

## Run

```
python run.py
``` 

Note: This is an example implementation to showcase the core functionality and efficiacy of the implemented algorithm. In real world applications, all QUBOs would be sampled in 1 batch in parallel on the platform, reducing sampling time to 1 run of a few seconds.

Dynex is the world’s first neuromorphic supercomputing blockchain based on the DynexSolve chip algorithm, a Proof-of-Useful-Work (PoUW) approach to solving real-world problems. The Dynex SDK is used to interact and compute on the Dynex Platform.
