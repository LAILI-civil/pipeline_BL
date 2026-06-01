# An Efficient High-Precision Surrogate Model for Calculating the Failure Probability of Gas Pipelines

This project presents a novel approach to pipeline failure probability assessment using advanced deep learning techniques. Our model leverages the Transformer architecture to process and analyze massive time-series datasets, training on **44,985,600** data points to develop a high-precision surrogate model for pipeline reliability analysis.

---
The model demonstrates exceptional performance on our test dataset of **768,000** samples:
- Burst probability prediction: **94.5%** relative accuracy
- Leakage detection: **90%** accuracy

---
Our work has been integrated into an interactive web interface at:  
[https://laili-civil.github.io/pipeline_BL/](https://laili-civil.github.io/pipeline_BL/)  
Users can directly input pipeline parameters to calculate failure probabilities in real-time.

---
## Data Availability

The training and test datasets used in this study are publicly available. They are based on Monte Carlo simulations and have been deposited in Science Data Bank (ScienceDB) under the following DOI:

> **Gas/oil pipeline defect failure estimation data**  
> Li Lai, You Dong, Changqing Gong  
> Science Data Bank, 2026.  
> DOI: [10.57760/sciencedb.35348](https://doi.org/10.57760/sciencedb.35348)  
> CSTR: 31253.11.sciencedb.35348<span data-allow-html class='source-item source-aggregated' data-group-key='source-group-1' data-url='https://cstr.cn/31253.11.sciencedb.35348' data-id='turn0search1'><span data-allow-html class='source-item-num' data-group-key='source-group-1' data-id='turn0search1' data-url='https://cstr.cn/31253.11.sciencedb.35348'><span class='source-item-num-name' data-allow-html>cstr.cn</span><span data-allow-html class='source-item-num-count'></span></span></span>

This dataset contains Monte Carlo simulation results for corroded gas/oil pipelines, including burst and leakage failure probabilities, and serves as the benchmark for training and validating the surrogate model<span data-allow-html class='source-item source-aggregated' data-group-key='source-group-2' data-url='https://cstr.cn/31253.11.sciencedb.35348' data-id='turn0search1'><span data-allow-html class='source-item-num' data-group-key='source-group-2' data-id='turn0search1' data-url='https://cstr.cn/31253.11.sciencedb.35348'><span class='source-item-num-name' data-allow-html>cstr.cn</span><span data-allow-html class='source-item-num-count'></span></span></span>.

---
## Related Publication

This project is associated with the following research article:

> **An Efficient High-Precision Surrogate Model for Calculating the Failure Probability of Gas Pipelines**  
> Li LAI¹, Changqing GONG², Jiapeng FANG¹, Aijun WANG³, You DONG¹*  
> 1. Guangdong-Hong Kong Joint Laboratory for Marine Infrastructure, Department of Civil and Environmental Engineering, The Hong Kong Polytechnic University, Hong Kong, China  
> 2. Department of Civil and Environmental Engineering, Harbin Institute of Technology, Weihai, China  
> 3. Alibaba Group, Hangzhou, China  
> *Corresponding author: You DONG (E-mail: you.dong@polyu.edu.hk)

The paper presents the theoretical formulation, model architecture, and validation of the surrogate model, and is currently under review / in press (please refer to the published version for final citation details).

---
This project contributes to structural reliability engineering by providing an efficient, accurate, and accessible solution for gas pipeline failure probability calculation, ultimately supporting safer infrastructure management and maintenance decisions.
