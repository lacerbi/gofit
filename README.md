# Absolute goodness of fit (gofit)

`gofit` computes the absolute goodness of fit via entropy estimation for discrete data.

The underlying idea is that the entropy of the data represents a hard upper bound to the goodness of fit. In other words, no model can do better than the intrinsic variability of the data. This allows to define an *absolute* goodness-of-fit metric.

The method was used in Shen & Ma (2016), and is slightly extended in Acerbi et al. (2017). See Acerbi et al. (2017), Appendix C, for a detailed description.

## References

1. Shen, S., & Ma, W. J. (2016). A detailed comparison of optimality and simplicity in perceptual decision making. *Psychological Review* 123(4): 452-80.
2. Acerbi, L., Dokka, K., Angelaki, D. E. & Ma, W. J. (2017). Bayesian comparison of explicit and implicit causal inference strategies in  multisensory heading perception. *bioRxiv preprint*.
