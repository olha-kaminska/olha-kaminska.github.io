---
layout: default
---
<!--<h1 style="color:Tomato;text-align:justify;">Machine Learning and Natural Language Processing research</h1> -->
<!--<p.main-text style="margin-top:10px;text-align:justify;"></p.main-text>-->
<!--<p style="margin-top:10px;text-align:justify;"></p>-->

<h2>List of my papers</h2>

<h3>"Fuzzy Rough Nearest Neighbour Methods for Aspect-Based Sentiment Analysis" (2023)</h3>

***Authors:** [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)*

***Link:** [MDPI](https://www.mdpi.com/2154078)*

***DOI:** [10.3390/electronics12051088](https://doi.org/10.3390/electronics12051088)*

The most recent paper that published to the [Electronics](https://www.mdpi.com/journal/electronics) journal, particularly, the special issue [AI for Text Understanding](https://www.mdpi.com/journal/electronics/special_issues/AI_recognition) (Volume 12, 2023).

In this work we considered fuzzy-rough-based nearest-neighbours approaches used in the previous works (described below) for the new task - Aspect-Based Sentiment Analysis (ABSA).

The data for these paper were provided by [SentEmo project](http://www.sentemo.org/), where we considered FMCG (Fast Moving Consumer Goods) dataset of English products reviews .

**Abstract:**  
*Fine-grained sentiment analysis, known as Aspect-Based Sentiment Analysis (ABSA), establishes the polarity of a section of text concerning a particular aspect. Aspect, sentiment, and emotion categorisation are the three steps that make up the configuration of ABSA, which we looked into for the dataset of English reviews. In this work, due to the fuzzy nature of textual data, we investigated machine learning methods based on fuzzy rough sets, which we believe are more interpretable than complex state-of-the-art models. The novelty of this paper is the use of a pipeline that incorporates all three mentioned steps and applies Fuzzy-Rough Nearest Neighbour classification techniques with their extension based on ordered weighted average operators (FRNN-OWA), combined with text embeddings based on transformers. After some improvements in the pipeline’s stages, such as using two separate models for emotion detection, we obtain the correct results for the majority of test instances (up to 81.4%) for all three classification tasks. We consider three different options for the pipeline. In two of them, all three classification tasks are performed consecutively, reducing data at each step to retain only correct predictions, while the third option performs each step independently. This solution allows us to examine the prediction results after each step and spot certain patterns. We used it for an error analysis that enables us, for each test instance, to identify the neighbouring training samples and demonstrate that our methods can extract useful patterns from the data. Finally, we compare our results with another paper that performed the same ABSA classification for the Dutch version of the dataset and conclude that our results are in line with theirs or even slightly better.*

**BibTeX citation:**
>*@Article{electronics12051088,
AUTHOR = {Kaminska, Olha and Cornelis, Chris and Hoste, Veronique},
TITLE = {Fuzzy Rough Nearest Neighbour Methods for Aspect-Based Sentiment Analysis},
JOURNAL = {Electronics},
VOLUME = {12},
YEAR = {2023},
NUMBER = {5},
ARTICLE-NUMBER = {1088},
URL = {https://www.mdpi.com/2079-9292/12/5/1088},
ISSN = {2079-9292},
DOI = {10.3390/electronics12051088}}*

------------------------------------------------------------------

<h3>"Fuzzy Rough Nearest Neighbour Methods for Detecting Emotions, Hate Speech and Irony" (2023)</h3>

***Authors:** [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)*

***Link:** [sciencedirect.com](https://authors.elsevier.com/a/1gQ1l4ZQEBrJV)*

***Code:** [https://github.com/olha-kaminska/frnn_emotion_detection/tree/emotions_irony_hatespeech](https://github.com/olha-kaminska/frnn_emotion_detection/tree/emotions_irony_hatespeech)*

This paper was published to the [Information Sciences](https://www.sciencedirect.com/journal/information-sciences) journal (Volume 625, May 2023, Pages 521-535).

This work is an extension of the previous work (described below), where besides classification fuzzy-rough-based nearest-neighbours approaches we also considered regression methods.

Apart from emotion detection task from <a href="https://competitions.codalab.org/competitions/17751">SemEval-2018 Task 1: Affect in Tweets</a>, in this paper we also consider other language classification tasks: 
 - hate speech detection from [SemEval 2019 Task 5: Shared Task on Multilingual Detection of Hate](https://competitions.codalab.org/competitions/19935);
 - offensive language recognition from [SemEval 2019 Task 6: OffensEval](https://competitions.codalab.org/competitions/20011) (Identifying and Categorizing Offensive Language in Social Media);
 - irony detection from [SemEval-2018 Task 3: Irony detection in English tweets](https://competitions.codalab.org/competitions/17468).

**Abstract:**  
*Due to the ever-expanding volumes of information available on social media, the need for reliable and efficient automated text understanding mechanisms becomes evident. Unfortunately, most current approaches rely on black-box solutions rooted in deep learning technologies. In order to provide a more transparent and interpretable framework for extracting intrinsic text characteristics like emotions, hate speech and irony, we propose the integration of fuzzy rough set techniques and text embeddings. We apply our methods to different classification problems originating from Semantic Evaluation (SemEval) competitions, and demonstrate that their accuracy is on par with leading deep learning solutions.*

**BibTeX citation:**
>*@article{KAMINSKA2023521,
title = {Fuzzy rough nearest neighbour methods for detecting emotions, hate speech and irony},
journal = {Information Sciences},
volume = {625},
pages = {521-535},
year = {2023},
issn = {0020-0255},
doi = {https://doi.org/10.1016/j.ins.2023.01.054},
url = {https://www.sciencedirect.com/science/article/pii/S0020025523000543},
author = {Olha Kaminska and Chris Cornelis and Veronique Hoste}}*

------------------------------------------------------------------

<h3>"LT3 at SemEval-2022 Task 6: Fuzzy-Rough Nearest neighbor Classification for Sarcasm Detection" (2022)</h3>

***Authors:** [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)*

***Link:** [https://aclanthology.org/2022.semeval-1.138/](https://aclanthology.org/2022.semeval-1.138/)*

***Code:** [https://github.com/olha-kaminska/frnn_emotion_detection/tree/iSarcasmEval](https://github.com/olha-kaminska/frnn_emotion_detection/tree/iSarcasmEval)*

***Poster:** [https://github.com/olha-kaminska/frnn_emotion_detection/blob/5bc16e940849eeaf9f19c06380c89df955a52e82/iSarcasm_poster.pdf](https://github.com/olha-kaminska/frnn_emotion_detection/blob/5bc16e940849eeaf9f19c06380c89df955a52e82/iSarcasm_poster.pdf)*

The paper presents our solution for [SemEval 2022 - Task 6 (iSarcasmEval):](https://codalab.lisn.upsaclay.fr/competitions/1340) Intended Sarcasm Detection In English and Arabic. We participated in the SubTask A: given a text, determine whether it is sarcastic or non-sarcastic. Our solution took 9-th place on the competition leaderboard. 

**Abstract:**   
*This paper describes the approach developed by the LT3 team in the Intended Sarcasm Detection task at SemEval-2022 Task 6. We considered the binary classification subtask A for English data. The presented system is based on the fuzzy-rough nearest neighbor classification method using various text embedding techniques. Our solution reached 9th place in the official leader-board for English subtask A.*

**BibTeX citation:**
>*@inproceedings{kaminska2022lt3,
  title={LT3 at SemEval-2022 Task 6: Fuzzy-Rough Nearest Neighbor Classification for Sarcasm Detection},
  author={Kaminska, Olha and Cornelis, Chris and Hoste, Veronique},
  booktitle={Proceedings of the 16th International Workshop on Semantic Evaluation (SemEval-2022)},
  pages={987--992},
  year={2022}
}*

------------------------------------------------------------------

<h3>"Fuzzy-Rough Nearest Neighbour Approaches for Emotion Detection in Tweets" (2021)</h3>

***Authors:** [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)*

***Link:** [https://link.springer.com/chapter/10.1007/978-3-030-87334-9_20](https://link.springer.com/chapter/10.1007/978-3-030-87334-9_20)*

***Code:** [https://github.com/olha-kaminska/frnn_emotion_detection](https://github.com/olha-kaminska/frnn_emotion_detection)*

This paper was presented at [IJCRS 2021](http://ifsa-eusflat2021.eu/ijcrs_conf.html) conference, organized jointly with [IFSA-EUSFLAT 2021](http://ifsa-eusflat2021.eu/). The problem is again based on [SemEval-2018 Task 1: Affect in Tweets](https://competitions.codalab.org/competitions/17751) competition, particularly, the ordinal classification Task "EI-oc": Detecting Emotion Intensity.

**Abstract:**  
*Social media are an essential source of meaningful data used in different tasks such as sentiment analysis and emotion recognition. Mostly, these tasks are solved with deep learning methods. Due to the fuzzy nature of textual data, we consider using classification methods based on fuzzy rough sets.*
*Specifically, we develop an approach for the SemEval-2018 emotion detection task, based on the fuzzy rough nearest neighbour (FRNN) classifier enhanced with ordered weighted average (OWA) operators. We use tuned ensembles of FRNN-OWA models based on different text embedding methods. Our results are competitive with the best SemEval solutions based on more complicated deep learning methods.*

**BibTeX citation:**
>*@inproceedings{kaminska2021fuzzy,
  title={Fuzzy-Rough Nearest Neighbour Approaches for Emotion Detection in Tweets},
  author={Kaminska, Olha and Cornelis, Chris and Hoste, Veronique},
  booktitle={International Joint Conference on Rough Sets},
  pages={231--246},
  year={2021},
  organization={Springer}
}*

------------------------------------------------------------------

<h3>"Nearest neighbour approaches for Emotion Detection in Tweets" (2021)</h3>

***Authors:** [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)*

***Link:** [https://aclanthology.org/2021.wassa-1.22/](https://aclanthology.org/2021.wassa-1.22/)*

***Code:** [https://github.com/olha-kaminska/wknn_emotion_detection](https://github.com/olha-kaminska/wknn_emotion_detection)*

***Poster:** [https://olha-kaminska.github.io/WASSA2021_poster_Olha_Kaminska.pdf](https://olha-kaminska.github.io/WASSA2021_poster_Olha_Kaminska.pdf)*

This paper was presented at <a href="https://2021.eacl.org/">EACL 2021</a> during <a href="https://wt-public.emm4u.eu/wassa2021/">WASSA workshop</a> as a poster.

Here you can check <a href="https://competitions.codalab.org/competitions/17751">SemEval-2018 Task 1: Affect in Tweets</a> competition and it's <a href="https://competitions.codalab.org/competitions/17751#results">leaderboard</a>, where we participated in Task "EI-oc" (emotion intensity ordered classification) for English tweets. 

**Abstract:**  
*Emotion detection is an important task that can be applied to social media data to discover new knowledge. While the use of deep learning methods for this task has been prevalent, they are black-box models, making their decisions hard to interpret for a human operator. Therefore, in this paper, we propose an approach using weighted k Nearest Neighbours (kNN), a simple, easy to implement, and explainable machine learning model. These qualities can help to enhance results' reliability and guide error analysis. In particular, we apply the weighted kNN model to the shared emotion detection task in tweets from SemEval-2018. Tweets are represented using different text embedding methods and emotion lexicon vocabulary scores, and classification is done by an ensemble of weighted kNN models. Our best approaches obtain results competitive with state-of-the-art solutions and open up a promising alternative path to neural network methods.*

**BibTeX citation:**
>*@inproceedings{kaminska2021nearest,
  title={Nearest neighbour approaches for Emotion Detection in Tweets},
  author={Kaminska, Olha and Cornelis, Chris and Hoste, Veronique},
  booktitle={Proceedings of the Eleventh Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis},
  pages={203--212},
  year={2021}
  }*
