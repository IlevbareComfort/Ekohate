# EkoHate: Abusive Language and Hate Speech Detection for Code-switched Political Discussions on Nigerian Twitter

[![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-2024.woah--1.3-blue)](https://aclanthology.org/2024.woah-1.3/)
[![WOAH 2024](https://img.shields.io/badge/WOAH-2024-orange)](https://aclanthology.org/volumes/2024.woah-1/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Paper:** [EkoHate: Abusive Language and Hate Speech Detection for Code-switched Political Discussions on Nigerian Twitter](https://aclanthology.org/2024.woah-1.3/)
> Comfort Ilevbare, Jesujoba Alabi, David Ifeoluwa Adelani, Firdous Bakare, Oluwatoyin Abiola, Oluwaseyi Adeyemo
> *Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024), pages 28–37, Mexico City, Mexico.*

## Overview

**EkoHate** is an abusive language and hate speech dataset built around political discussions on Nigerian Twitter (now X). The name draws from *Eko*, the Yoruba name for Lagos, Nigeria's most populous and economically significant state, and the focal point of the data collection.

The dataset was constructed in the context of the **2023 Nigerian governorship election in Lagos State**, capturing tweets directed at the three major gubernatorial candidates and their followers. It is the first dedicated resource for detecting offensive speech in Nigerian political discourse, addressing a significant gap in NLP resources for African languages and code-switched text.


## Task

The core task is **abusive language and hate speech detection** on code-switched social media text. The dataset supports two classification settings:

- **Binary classification** : distinguishing *normal* from *offensive* content
- **Fine-grained four-label classification** : providing a more nuanced categorization of offensive speech

Models are evaluated under both **supervised** and **cross-lingual transfer learning** settings.


## Dataset

Tweets were collected from Nigerian Twitter during the lead-up to and during the **2023 Lagos State governorship election**, targeting discussions around the three main candidates and their supporters. The text is code-switched, predominantly mixing **English and Yoruba** (and sometimes Nigerian Pidgin), reflecting natural online communication patterns among Nigerian users.

## Annotation Scheme

The dataset was annotated using a hierarchical hate speech annotation framework.

### Labels

- Normal
- Hateful
- Contempt
- Abusive

The annotation process was manually conducted and validated for consistency across code-switched Nigerian social media conversations.

## Dataset Access

The EkoHate dataset is not publicly distributed due to ethical and privacy considerations surrounding hate speech and social media data.

Researchers interested in accessing the dataset for academic or research purposes can request access via:

📧 ilevbarecomfort@gmail.com

### Cross-dataset Transfer

EkoHate transfers well to other publicly available offensive language benchmarks, including:

- **OLID** (Offensive Language Identification Dataset)
- **HateUS2020** (US political hate speech)
- **FountaHate**

This demonstrates that the dataset generalises beyond Nigerian political discourse to political discussions in other regions.

## Citation

If you use EkoHate in your work, please cite:

```bibtex
@inproceedings{ilevbare-etal-2024-ekohate,
    title = "{E}ko{H}ate: Abusive Language and Hate Speech Detection for Code-switched Political Discussions on {N}igerian {T}witter",
    author = "Ilevbare, Comfort  and
      Alabi, Jesujoba  and
      Adelani, David Ifeoluwa  and
      Bakare, Firdous  and
      Abiola, Oluwatoyin  and
      Adeyemo, Oluwaseyi",
    booktitle = "Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.woah-1.3/",
    doi = "10.18653/v1/2024.woah-1.3",
    pages = "28--37",
}
```


## Links

- 📄 [Paper (ACL Anthology)](https://aclanthology.org/2024.woah-1.3/)
- 📑 [PDF](https://aclanthology.org/2024.woah-1.3.pdf)
- 🔗 [DOI: 10.18653/v1/2024.woah-1.3](https://doi.org/10.18653/v1/2024.woah-1.3)
