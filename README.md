# MalayPrag: Overview

This repository contains the dataset accompanying:

**Can LLMs Handle Discourse Particles? A Case Study of Colloquial Malay**
*Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP 2026), Main Conference.*

## Authors

**Mariah Al Giptiah Binte Yusoff**<sup>1,&ast;</sup>, **Jakin Tan**<sup>1,&ast;</sup>, **Bocheng Chen**<sup>2</sup>, **Guangliang Liu**<sup>3</sup>, and **Xi Chen**<sup>1</sup>

<sup>1</sup> Nanyang Technological University, Singapore  
<sup>2</sup> University of Mississippi, USA  
<sup>3</sup> Indiana University Indianapolis, USA  

&ast; These authors contributed equally.

## Dataset

MALAYPRAG is a dataset of colloquial Malay utterances for studying the discourse particles *kan* and *ke*. The dataset contains 1,137 utterances across three particle conditions: *kan*, *ke*, and neutral.

| Split     |   *kan* |    *ke* | Neutral |     Total |
| --------- | ------: | ------: | ------: | --------: |
| GOLD      |      63 |      60 |      64 |       187 |
| SILVER    |     345 |     239 |     366 |       950 |
| **Total** | **408** | **299** | **430** | **1,137** |

Please refer to the accompanying paper and its appendices for details on data collection, annotation, dataset construction, pragmatic attributes and functions, and evaluation.

## Files

* `GOLD.csv` — GOLD dataset containing items with majority-agreed annotations from three annotators.
* `SILVER.csv` — SILVER dataset providing the remaining annotated data.

For definitions of the dataset fields and annotation labels, please refer to the paper and its appendices.

## Citation

If you use MALAYPRAG, please cite:

```bibtex
@inproceedings{Mariah2026discourse,
    title     = {Can {LLM}s Handle Discourse Particles? A Case Study of Colloquial Malay},
    author    = {Mariah, Al Giptiah Binte Yusoff and
                 Tan, Jakin and
                 Chen, Bocheng and
                 Liu, Guangliang and
                 Chen, Xi},
    booktitle = {Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing},
    year      = {2026}
}
```
Thank you!
