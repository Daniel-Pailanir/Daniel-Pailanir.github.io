---
layout: home
title: Some Code
subtitle: Just for fun!
---

## Stata Programs
### [**tscb**](https://github.com/Daniel-Pailanir/TSCB-CCV) - Two-Stage Cluster Bootstrap Variance
Written with [Damian Clarke](https://www.damianclarke.net/). Stata implementation of the Two-Stage Cluster Bootstrap (TSCB) estimator described in [Abadie et al (2023)](https://academic.oup.com/qje/article/138/1/1/6750017?login=true). These programs return standard errors for regression analysis of some outcome on a treatment of interest using either simple OLS, or fixed effects models, while accounting for clustering by group.
{: .box-note}
**Note:** Install in Stata typing: _net install **tscb**, from("https://raw.githubusercontent.com/daniel-pailanir/tscb-ccv/master")_

### [**ccv**](https://github.com/Daniel-Pailanir/TSCB-CCV) - Causal Cluster Variance
Written with [Damian Clarke](https://www.damianclarke.net/). Stata implementation of the Causal Cluster Variance (CCV) estimator described in [Abadie et al (2023)](https://academic.oup.com/qje/article/138/1/1/6750017?login=true). These programs return standard errors for regression analysis of some outcome on a treatment of interest using either simple OLS, or fixed effects models, while accounting for clustering by group.
{: .box-note}
**Note:** Install in Stata typing: _net install **ccv**, from("https://raw.githubusercontent.com/daniel-pailanir/tscb-ccv/master")_

### [**sdid**](https://econpapers.repec.org/software/bocbocode/S459058.htm) - Synthetic Difference-in-Differences

Written with [Damian Clarke](https://www.damianclarke.net/). This Stata package implements the synthetic difference-in-differences estimation procedure, along with a range of inference procedures, following Arkhangelsky et al., (2021). Here we provide a native Stata implementation, principally written in Mata. This package is currently under active development. You can see the latest version and some examples in my repo [**sdid**](https://github.com/Daniel-Pailanir/sdid).

{: .box-note}
**Note:** Install in Stata typing: _ssc install **sdid**_

### [**recocl**](https://econpapers.repec.org/software/bocbocode/S458893.htm) - Recodes municipality's codes for Chile (CL)

Chile has changed his municipal code a couple of times. Currently, not all databases have the most current municipality code, therefore it is necessary to carry out a recoding of the municipality code for some municipalities in region I (Arica y Parinacota), VIII (Bío-Bío) and X (Los Ríos). This is exactly what recocl does.

{: .box-note}
**Note:** Install in Stata typing: _ssc install **recocl**_

### [**grvar**](https://econpapers.repec.org/software/bocbocode/s458802.htm) - Apply a non-constant growth rate to a variable

Calculate the future values of a variable from the initial value and a non-constant growth/decrease rate (e.g. inflation). It is useful when we want to fit a variable with a growth rate in a time serie or panel data.

{: .box-note}
**Note:** Install in Stata typing: _ssc install **grvar**_
