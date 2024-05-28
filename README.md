We build PINNs models on:
- 2D_deepxde: we using Deepxde uses TensorFlow as the default backend: The results are quite similar to CFD simulation. Deepxde supports both Adam and L-bfgs so the total loss is reduced to quite small, leading to good results.
- 2D_tensorflow: The results are not as good as Deepxde, probably because tensorflow does not support the L-bfgs optimization method so we only use Adam.

Results by deepxde: img/PINNs

Results by CFD: img/CFD
