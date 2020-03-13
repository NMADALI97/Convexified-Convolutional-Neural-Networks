# Convexified-Convolutional-Neural-Networks



Spoken Digit Recognition using  [Convexified Convolutional Neural Networks](https://arxiv.org/abs/1609.01000).The class of convexified convolutional neural networks (CCNNs), which capture the parameter sharing of convolutional neural networks in a convex manner. By representing the nonlinear convolutional filters as vectors in a reproducing kernel Hilbert space, the CNN parameters can be represented as a low-rank matrix, which can be relaxed to obtain a convex optimization problem. For learning two-layer convolutional neural networks, we prove that the generalization error obtained by a convexified CNN converges to that of the best possible CNN. For learning deeper networks, we train CCNNs in a layer-wise manner. Empirically, CCNNs achieve performance competitive with CNNs trained by backpropagation, SVMs, fully-connected neural networks, stacked denoising auto-encoders, and other baseline methods. 

## Author(s)

MADALI Nabil  .

### Current status
- 4 speakers
- 2,000 recordings (50 of each digit per speaker)
- English pronunciations

### Organization
Files are named in the following format:
`{digitLabel}_{speakerName}_{index}.wav`
Example: `7_jackson_32.wav`


### Metadata
`metadata.py` contains meta-data regarding the speakers gender and accents.


## References

```
@incollection{pillutla-etal:casimir:neurips2018,
title = {A {S}moother {W}ay to {T}rain {S}tructured {P}rediction {M}odels},
author = {Pillutla, Krishna and
          Roulet, Vincent and 
          Kakade, Sham M. and
          Harchaoui, Zaid},
booktitle = {Advances in Neural Information Processing Systems 31},
year = {2018},
}
```
