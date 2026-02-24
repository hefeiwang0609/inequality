# Repository for inequality analysis project

A collection of causal inference and robustness analysis scripts based on Causal DML / DMLIV / Causal Forest.

## Environment Setup

1. 安装 [Miniconda](https://docs.conda.io/en/latest/miniconda.html) 或 Anaconda。

2. 在项目根目录下创建并激活环境：

```bash
cd /path/to/inequality-released
conda env create -f environment.yml
conda activate py312
```


## Notebooks


| Notebook | Content |
|----------|--------|
| `a_CausalDML_Baseline.ipynb` | **Baseline**: ATE of digital literacy on Kakwani via Causal Forest DML; correlation check; CATE distributions. |
| `b_DMLIV_BaseStation.ipynb` | **IV estimation**: DML-IV with base-station count as instrument; first-stage strength; IV-ATE. |
| `c_ATE_Robustness.ipynb` | **Robustness**: K-fold CV, number of trees, TOPSIS digital literacy, 1% winsorization, extra controls, leave-one-out Gini by city. |
| `d_ATE_Mechanism.ipynb` | **Mechanisms**: Effect of digital literacy on mediators (online social network, entrepreneurship). |



