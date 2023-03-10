# DataPersistenceBias
This repository contains the data for the WebSci23 paper "**The Impact of Data Persistence Bias on Social Media Studies**". The datasets are the 30 datasets manually curated (``<name>.csv.bz2``), the control dataset (``control.csv.bz2``), and the trends dataset (``american_trends.csv.bz2``). For framing data, please refer to https://github.com/juliamendelsohn/framing

Each dataset has the following fields:

``id``: tweet id

``exists``: whether the tweet was recollectible in October 2021. 

``trend``: (Trends dataset) the name of the Twitter trend

``before``: (Trends dataset) whether the tweet was posted before the trend made to the trends list.

Due to developer agreement, we do not share the content of the tweets, their sentiment scores, the presence of hate speech related content and the author's political stance. However, for legitimate research purpose, we can disclose these data privately. Contact tugrulcanelmas at gmail.com to get request access to such data. 

Please cite our paper if you use our data.

``
@article{elmas2023impact,
  title={The Impact of Data Persistence Bias on Social Media Studies},
  author={Elmas, Tu{\u{g}}rulcan},
  journal={arXiv preprint arXiv:2303.00902},
  year={2023}
}
``
