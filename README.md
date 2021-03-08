# sPhysNet

Dataset Construction to Explore Chemical Space with 3D Geometry and Deep Learning

![](Picture1.png)

## Table of Contents

- Project Organization
- Environment Setup
- Tutorial
- Reference

---
### 1. Project Organization

```
|- README.md                                <- this file
|- tutorial.ipynb                           <- A tutotial file for data preprocessing and sPhysNet training
|- PhysDime-Seq                             <- Main code of PhysNet architecture, irrelevent files are ommitted.
    |- Networks
    |- utils
    |- train.py
    |- test.py
    |- config-sPhysNet-Frag20-eMol9-QM.txt
    |- subjob-testing.pbs
|- dataProviders                            <- Main code for data preprocessing and loading, irrelevent files are ommitted
    |- GaussUtils
    |- DataPrepareUtils.py
    |- DummyIMDataset.py
    |- frag20_eMol9_split.pt
```

---

