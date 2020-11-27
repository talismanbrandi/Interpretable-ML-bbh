# Interpretable-ML-bbh
A repository for application of BDTs and Shapley values to associated bbh production at HL-LHC and FCC-hh

- There are three Jupyter notebooks and all the data needed to do the full analysis.  
- The simulations directory contains the MadGraph simulations for HL-LHC and FCC-hh
- The plots directory contains all the plots used in the draft.


```
.
├── LICENSE
├── Notebooks
│   ├── Final_Analysis.ipynb             # Main analysis notebook with BDT and SHAP
│   ├── Fit-2P.ipynb                     # PyMC3 Bayesian MCMC fit
│   ├── models
│   │   ├── FCC-BDT
│   │   └── HL-LHC-BDT
│   └── plotMaker.ipynb                  # Notebook for making plots
├── plots
│   ├── bcp100.pdf
│   ├── bcp14.pdf
│   ├── corr-diff-yb2-zh.png
│   ├── ht-5-channel.pdf
│   ├── ht-zh-yb2.pdf
│   ├── kappa_b-2P-FCC.pdf
│   ├── kappa_b-2P-HL-LHC.pdf
│   ├── kappa_b-2PO-FCC.pdf
│   ├── kappa_b-2PO-HL-LHC.pdf
│   ├── maa-5-channel.pdf
│   ├── mb1h-5-channel.pdf
│   ├── mb1h-zh-yb2.pdf
│   ├── mbb-zh-yb2.pdf
│   ├── ptaa-5-channel.pdf
│   ├── ptaa-zh-yb2.pdf
│   ├── ptb1-5-channel.pdf
│   ├── ptb1-zh-yb2.pdf
│   ├── shap-5-FCC.pdf
│   ├── shap-5.pdf
│   ├── shape-mb1h-ht.pdf
│   ├── shape-mb1h-mbb.pdf
│   ├── shape-mb1h-ptaa.pdf
│   ├── shape-mb1h-ptb1.pdf
│   ├── shap-yt2-yb2.pdf
│   ├── shap-zh-yb2.pdf
│   ├── sig100.pdf
│   ├── sig14.pdf
│   ├── yt2-yb2-BDT-dist.pdf
│   ├── zh-yb2-BDT-dist.pdf
│   └── zh_yb2.png
├── README.md
└── simulations
    ├── Correlations
    │   ├── yb2.txt
    │   └── zh.txt
    ├── FCC-hh
    │   ├── bbxaa_1.csv
    │   ├── bbxaa_2.csv
    │   ├── yb2_1.csv
    │   ├── yb2_2.csv
    │   ├── ybyt_1.csv
    │   ├── ybyt_2.csv
    │   ├── yt2_1.csv
    │   ├── yt2_2.csv
    │   └── zh.csv
    └── HL-LHC
        ├── bbxaa.csv
        ├── yb2.csv
        ├── ybyt.csv
        ├── yt2.csv
        └── zh.csv
```