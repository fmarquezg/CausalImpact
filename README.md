# CausalImpact

#### An R package for causal inference using Bayesian structural time-series models

This R package implements an approach to estimating the causal effect of a designed intervention on a time series. For example, how many additional daily clicks were generated by an advertising campaign? Answering a questions like this can be difficult when a randomized experiment is not available. The package overcomes this difficulty using a structural Bayesian time-series model to estimate how the response metric would have evolved after the intervention if the intervention had never occurred. For details, see: [Brodersen et al. (*under review*)](http://research.google.com/pubs/pub41854.html).

#### Installation

```R
install.packages("devtools")
library(devtools)
devtools::install_github("google/CausalImpact")
```

#### Documentation and examples

See: CausalImpact.html

#### Discussion forum

https://groups.google.com/d/forum/CausalImpact