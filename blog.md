---
layout: default
---
<!--<h1 style="color:Tomato;text-align:justify;">Machine Learning and Natural Language Processing research</h1> -->
<!--<p.main-text style="margin-top:10px;text-align:justify;"></p.main-text>-->
<!--<p style="margin-top:10px;text-align:justify;"></p>-->

<h2>List of my papers</h2>

------------------------------------------------------------------

<h3>"Nearest neighbour approaches for Emotion Detection in Tweets"</h3>

This <a href="https://www.aclweb.org/anthology/2021.wassa-1.22/">paper</a> by <a href="https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ">Olha Kaminska</a>, <a href="https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ">Chris Cornelis</a> and <a href="https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ">Veronique Hoste</a> was presented at <a href="https://2021.eacl.org/">EACL 2021</a> during <a href="https://wt-public.emm4u.eu/wassa2021/">WASSA workshop</a> as a poster.

<a href="https://olha-kaminska.github.io/WASSA2021_poster_Olha_Kaminska.pdf">The poster</a> and <a href="https://github.com/olha-kaminska/wknn_emotion_detection">the GitHub repo</a> for this paper are available online.

Here you can check <a href="https://competitions.codalab.org/competitions/17751">SemEval-2018 Task 1: Affect in Tweets</a> competition and it's <a href="https://competitions.codalab.org/competitions/17751#results">leaderboard</a>, where we participated in Task "EI-oc" (emotion intensity ordered classification) for English tweets. 

<b>Abstract:</b>  
<i>Emotion detection is an important task that can be applied to social media data to discover new knowledge. While the use of deep learning methods for this task has been prevalent, they are black-box models, making their decisions hard to interpret for a human operator. Therefore, in this paper, we propose an approach using weighted k Nearest Neighbours (kNN), a simple, easy to implement, and explainable machine learning model. These qualities can help to enhance results' reliability and guide error analysis. In particular, we apply the weighted kNN model to the shared emotion detection task in tweets from SemEval-2018. Tweets are represented using different text embedding methods and emotion lexicon vocabulary scores, and classification is done by an ensemble of weighted kNN models. Our best approaches obtain results competitive with state-of-the-art solutions and open up a promising alternative path to neural network methods.</i>

------------------------------------------------------------------

<h3>"Fuzzy-Rough Nearest Neighbour Approaches for Emotion Detection in Tweets"</h3>

This [paper](https://arxiv.org/abs/2107.05392) was written by the same authors ([Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ)) as a further work of the previous one. It was presented at [IJCRS 2021](http://ifsa-eusflat2021.eu/ijcrs_conf.html) conference, organized jointly with [IFSA-EUSFLAT 2021](http://ifsa-eusflat2021.eu/). 

The problem is again based on [SemEval-2018 Task 1: Affect in Tweets](https://competitions.codalab.org/competitions/17751) competition, particularly, the ordinal classification Task "EI-oc": Detecting Emotion Intensity.

The code for this paper is available [here](https://github.com/olha-kaminska/frnn_emotion_detection).

<b>Abstract:</b>
*Social media are an essential source of meaningful data used in different tasks such as sentiment analysis and emotion recognition. Mostly, these tasks are solved with deep learning methods. Due to the fuzzy nature of textual data, we consider using classification methods based on fuzzy rough sets.*
*Specifically, we develop an approach for the SemEval-2018 emotion detection task, based on the fuzzy rough nearest neighbour (FRNN) classifier enhanced with ordered weighted average (OWA) operators. We use tuned ensembles of FRNN-OWA models based on different text embedding methods. Our results are competitive with the best SemEval solutions based on more complicated deep learning methods.*

------------------------------------------------------------------

<h3>"LT3 at SemEval-2022 Task 6: Fuzzy-Rough Nearest neighbor Classification for Sarcasm Detection"</h3>

The paper by [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ) for [SemEval 2022 - Task 6 (iSarcasmEval):](https://codalab.lisn.upsaclay.fr/competitions/1340) **Intended Sarcasm Detection In English and Arabic**. We participated in the *SubTask A:* Given a text, determine whether it is sarcastic or non-sarcastic.

This paper uses similar pipeline to the previous one but on different dataset. Our solution took 9-th place on the competition leaderboard. You can check our [code](https://github.com/olha-kaminska/frnn_emotion_detection/tree/iSarcasmEval) and [poster](https://github.com/olha-kaminska/frnn_emotion_detection/blob/5bc16e940849eeaf9f19c06380c89df955a52e82/iSarcasm_poster.pdf).

<b>Abstract:</b> 
*This paper describes the approach developed by the LT3 team in the Intended Sarcasm Detection task at SemEval-2022 Task 6. We considered the binary classification subtask A for English data. The presented system is based on the fuzzy-rough nearest neighbor classification method using various text embedding techniques. Our solution reached 9th place in the official leader-board for English subtask A.*

------------------------------------------------------------------

<h3>"Fuzzy Rough Nearest Neighbour Methods for Detecting Emotions, Hate Speech and Irony"</h3>

This paper by [Olha Kaminska](https://scholar.google.com/citations?hl=en&user=yRgJkEwAAAAJ), [Chris Cornelis](https://scholar.google.com/citations?hl=en&user=ln46HlkAAAAJ), and [Veronique Hoste](https://scholar.google.com/citations?hl=en&user=WxOsW3IAAAAJ) was sumbitted to the [Information Sciences](https://www.sciencedirect.com/journal/information-sciences) journal.

This paper is extension of the previous work, where besides classification fuzzy-rough-based nearest-neighbours approaches we also considered regression methods. The code is available [here](https://github.com/olha-kaminska/frnn_emotion_detection/tree/emotions_irony_hatespeech).

Apart from emotion detection task from <a href="https://competitions.codalab.org/competitions/17751">SemEval-2018 Task 1: Affect in Tweets</a>, in this paper we also consider other language classification tasks: 
 - hate speech detection from [SemEval 2019 Task 5: Shared Task on Multilingual Detection of Hate](https://competitions.codalab.org/competitions/19935);
 - offensive language recognition from [SemEval 2019 Task 6: OffensEval](https://competitions.codalab.org/competitions/20011) (Identifying and Categorizing Offensive Language in Social Media);
 - irony detection from [SemEval-2018 Task 3: Irony detection in English tweets](https://competitions.codalab.org/competitions/17468).

<b>Abstract:</b> 
*Due to the ever-expanding volumes of information available on social media, the need for reliable and efficient automated text understanding mechanisms becomes evident. Unfortunately, most current approaches rely on black-box solutions rooted in deep learning technologies. In order to provide a more transparent and interpretable framework for extracting intrinsic text characteristics like emotions, hate speech and irony, we propose the integration of fuzzy rough set techniques and text embeddings. We apply our methods to different classification problems originating from Semantic Evaluation (SemEval) competitions, and demonstrate that their accuracy is on par with leading deep learning solutions.*
