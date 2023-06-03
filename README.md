# BanglaHateBert

## Introduction
BanglaHateBert is a dataset specifically created for Bangla (Bengali) language that focuses on hate speech detection. This dataset consists of a large collection of approximately 7.5k+ samples labeled as hate speech and an additional 7.5k+ samples labeled as non-hate speech. The dataset is designed to serve as a benchmark for evaluating hate speech detection models in the Bangla language.

## Dataset Details
The dataset includes various types of text data such as posts from social media platforms like Facebook and YouTube, as well as comments from news platforms. Each data sample in the dataset is associated with three columns:

1. Post: This column contains the text content extracted from different sources, such as Facebook, YouTube, or news comments.
2. Label: The label column indicates whether the given text sample is categorized as hate speech (labeled as 1) or non-hate speech (labeled as 0).
3. Categories: The categories column provides more specific information about the type of hate speech, with labels such as xe (xenophobia), ho (homophobia), pe (personal, including defamation-de and insult-in), se (sexual), po (political), ge (geopolitical), re (religion), and ra (racism) , no-normal(non-hatespeech).

## Citation
If you use this dataset in your research or work, please cite the following paper:

Md Saroar Jahan, Mainul Haque, Nabil Arhab, and Mourad Oussalah. "BanglaHateBERT: BERT for Abusive Language Detection in Bengali." In Proceedings of the Second International Workshop on Resources and Techniques for User Information in Abusive Language Analysis, pages 8-15, 2022.

By citing the paper, you acknowledge the authors' contribution and provide proper credit for the dataset.

@inproceedings{jahan2022banglahatebert,
  title={BanglaHateBERT: BERT for Abusive Language Detection in Bengali},
  author={Jahan, Md Saroar and Haque, Mainul and Arhab, Nabil and Oussalah, Mourad},
  booktitle={Proceedings of the Second International Workshop on Resources and Techniques for User Information in Abusive Language Analysis},
  pages={8--15},
  year={2022}
}
