---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

{% include base_path %}

# Hi, welcome!
I am currently employed as a statistician at Pharmaron. 

I obtained my PhD from the University of Toronto in 2022 under the supervision of Prof. Patrick Brown. Prior to that, I completed my MSc in Biostatistics at the University of Toronto. 

Since March 2024, I have been working as a part-time researcher with Prof. Patrick Brown and am open to research opportunities and collaboration in applied statistics and software development. 


## Research
My PhD work involves development of R softwares using GPU’s parallel computing power and statistical computing methods in geostatsistical models.
My main interests include deep learning, statistical software, and computational statistics. Additionally, I am intrigued by inference problems within statistical methods in medical research.


## Publications and Working Papers
Ruoyong Xu, Patrick Brown (2024). ["Profile likelihoods for parameters in trans-Gaussian geostatistical models."](https://authors.elsevier.com/sd/article/S2211-6753(24)00012-5)
Spatial Statistics, p. 100821.

Ruoyong Xu, Patrick Brown (2025). ["clrng: A tool set for parallel random number generation on GPUs in R."] Link will be available later. Accepted for publication at Journal of Statistical Computation and Simulation. 

Ruoyong Xu, Patrick Brown, Nancy Baxter, Anna M. Sawka (2021).
[“Online Public Interest in Cancer During the COVID-19 Pandemic”.](https://ascopubs.org/doi/10.1200/CCI.21.00036)
JCO CCI 5, p. 695–700.



## Software
* clrng: builds on gpuR and utilizes the clRNG ('OpenCL') library to provide efficient tools to generate random numbers in parallel on a GPU and save the results as R objects, and ensuring high-quality random numbers even when R is used interactively or in an ad-hoc manner.
  * [github](https://github.com/ruoyongxu/clrng), [CRAN](https://cran.r-project.org/web/packages/clrng/index.html), [arXiv (method)](https://arxiv.org/abs/2201.06604)
     
* gpuBatchMatrix: an R package that performs parallel batch matrix operations on GPU, particularly tailored for geostatistical model evaluations.
  * [github](https://github.com/ruoyongxu/gpuBatchMatrix)
 
* gpuLik: leverages GPUs for parallel computation of profile likelihoods, specifically designed for Gaussian spatial models.
  * [github](https://github.com/ruoyongxu/gpuLik),  [journal supplementary file](https://authors.elsevier.com/sd/article/S2211-6753(24)00012-5)

* gpuR: provides GPU enabled functions for 'R' objects in a simple and approachable manner. New 'gpu\*' and 'vcl\*' classes have been provided to wrap typical 'R' objects (e.g. vector, matrix), in both host and device spaces, to mirror typical 'R' syntax without the need to know 'OpenCL'.
  * [github](https://github.com/eborgnine/gpuR),  [CRAN](https://cran.r-project.org/web/packages/gpuR/index.html)


## Thesis:
["Statistical Computing With Graphics Processing Units."](https://tspace.library.utoronto.ca/bitstream/1807/126927/1/Xu_Ruoyong_202303_PhD_thesis.pdf), 2023






