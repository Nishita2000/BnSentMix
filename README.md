<div align="center">

# BnSentMix: A Diverse Bengali-English Code-Mixed Dataset for Sentiment Analysis

</div>

<p align="center">
  <a href="*sadiaalam@iut-dhaka.edu*"><strong>Sadia Alam</strong></a>
  ·
  <a href="https://farhanishmam.github.io/"><strong>Md Farhan Ishmam</strong></a>
  ·
  <a href="navidhasin@iut-dhaka.edu"><strong>Navid Hasin Alvee</strong></a>
  ·
  <a href="shahnewaz@iut-dhaka.edu"><strong>Md Shahnewaz Siddique</strong></a>
  ·
  <a href="https://cse.iutoic-dhaka.edu/profile/azam/"><strong>Md Azam Hossain</strong></a>
  ·
   <a href="https://cse.iutoic-dhaka.edu/profile/raihan-kamal/"><strong>Abu Raihan Mostofa Kamal</strong></a>
</p>

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2408.08964-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2408.08964)
![paper](https://img.shields.io/badge/Paper_Status-In--Review-yellow)
[![codeRepo](https://img.shields.io/badge/Code-Repository-blue?logo=GitHub)](https://github.com/Nishita2000/BnSentMix)

</div>

We introduce BnSentMix, a sentiment analysis dataset of code-mixed Bengali-English consisting of 20,000 samples and 4 sentiment labels. 
Code-mixed Bengali-English texts consist of Bengali and English words written in English characters. 
We also propose a novel pipeline to filter code-mixed Bengali-English texts using pre-trained language models. 

---

## Dataset Overview

Column Title | Description
------------ | -------------
`Data Sources` | Facebook, YouTube, E-commerce Sites
`#Samples` | 20000
`Sentiment Labels` | Positive, Negative, Neutral, Mixed
`Filtering Method` | Automated using `mBERT`
`#Annotators` | 64
`Annotation/Sample` | 2 or 3 (if tie)

## Dataset Statistics

| Statistic               | Value  |
|-------------------------|--------|
| Mean Character Length    | 62.77  |
| Max Character Length     | 1985   |
| Min Character Length     | 14     |
| Mean Word Count          | 11.65  |
| Max Word Count           | 368    |
| Min Word Count           | 4      |
| Unique Word Count        | 37734  |
| Unique Sentence Count    | 21873  |

## Sentiment Composition

<img src="./assets/overview.png" alt="Image Not Found" width="650"/>

## Results

<img src="./assets/overview.png" alt="Image Not Found" width="650"/>

## Citation

If you find this work useful, please cite our paper:

```bib
@misc{alam2024bnsentmixdiversebengalienglishcodemixed,
      title={BnSentMix: A Diverse Bengali-English Code-Mixed Dataset for Sentiment Analysis}, 
      author={Sadia Alam and Md Farhan Ishmam and Navid Hasin Alvee and Md Shahnewaz Siddique and Md Azam Hossain and Abu Raihan Mostofa Kamal},
      year={2024},
      eprint={2408.08964},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2408.08964}, 
}
```

