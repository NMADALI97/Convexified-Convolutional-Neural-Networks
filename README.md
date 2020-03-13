# Convexified-Convolutional-Neural-Networks



Spoken Digit Recognition using  [Convexified Convolutional Neural Networks](https://arxiv.org/abs/1609.01000).The class of convexified convolutional neural networks (CCNNs), which capture the parameter sharing of convolutional neural networks in a convex manner. By representing the nonlinear convolutional filters as vectors in a reproducing kernel Hilbert space, the CNN parameters can be represented as a low-rank matrix, which can be relaxed to obtain a convex optimization problem. For learning two-layer convolutional neural networks, we prove that the generalization error obtained by a convexified CNN converges to that of the best possible CNN. For learning deeper networks, we train CCNNs in a layer-wise manner. Empirically, CCNNs achieve performance competitive with CNNs trained by backpropagation, SVMs, fully-connected neural networks, stacked denoising auto-encoders, and other baseline methods. 

Codes are borrowed from [CCNN ](https://github.com/zhangyuc/CCNN),[free-spoken-digit-dataset](https://github.com/Jakobovski/free-spoken-digit-dataset).

## Author(s)

MADALI Nabil  .

# Free Spoken Digit Dataset (FSDD)
[![DOI](https://zenodo.org/badge/61622039.svg)](https://zenodo.org/badge/latestdoi/61622039)

A simple audio/speech dataset consisting of recordings of spoken digits in `wav` files at 8kHz. The recordings are trimmed so that they have near minimal silence at the beginnings and ends.

FSDD is an open dataset, which means it will grow over time as data is contributed.  In order to enable reproducibility and accurate citation the dataset is versioned using Zenodo DOI as well as `git tags`.


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
@article{DBLP:journals/corr/ZhangLW16b,
  author    = {Yuchen Zhang and
               Percy Liang and
               Martin J. Wainwright},
  title     = {Convexified Convolutional Neural Networks},
  journal   = {CoRR},
  volume    = {abs/1609.01000},
  year      = {2016},
  url       = {http://arxiv.org/abs/1609.01000},
  archivePrefix = {arXiv},
  eprint    = {1609.01000},
  timestamp = {Fri, 03 May 2019 12:59:45 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/ZhangLW16b.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}

```
