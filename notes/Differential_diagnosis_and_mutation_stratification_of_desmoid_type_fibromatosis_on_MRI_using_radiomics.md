## [Differential diagnosis and mutation stratification of desmoid-type fibromatosis on MRI using radiomics](https://www.ejradiology.com/article/S0720-048X(20)30455-1/fulltext)

Retrospective study to distinquish desmoit-type fibromatosis (DTF) from soft tissue sarcomas (STS) using Radiomics. Additionally, paper attempts to predict CTNNB1 mutation status. Both phenotyping and molecular subtyping is very important in disease progression. Hence the importance to distinquish groups and provide a non-invasive surrogate to contribute to diagnosis, prognosis and treatment planning. Pipeline consisted image segmentation, feature extraction, automated ML decision model, use of ensemble of 50 best workflow from 100.000 candidates (different combinations of feature extraction and ML). Ensemble was able to provide accurate results for DTF and non-DTF distinquish, better than two radiologists, but wasn't able to accurately predict CTNNB1 mutation status.

#### Notes

- Small dataset < 203 patients
- T1-weighted MRI only (prior to treatment)
- Age and sex was able to accurately predict DTF or non-DTF due skewed dataset, thereby not representative of clinical pracitise. Age and sex wasn't used in the Radiomics model.
- Not able to predict CTNNB1 status, hinting towards absence of MRI appearance. However sample size was relatively small and some patient might have been incorrectly allocated as sanger sequencing is not always sensitive enough. Also MRI images originated from 68 different scanners, improves generalizability at cost of radiomics performance.

