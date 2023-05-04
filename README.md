# Awesome Dementia Detection

> Dementia detection from speech via machine learning.

## Contents

- [1. Survey papers](#1-survey-papers)
- [2. Special challenges](#2-special-challenges)
  * [a. ADReSS 2020 InterSpeech](#a-adress-2020-interspeech)
  * [b. ADReSS 2020 Frontiers](#b-adress-2020-frontiers)
  * [c. ADReSSo 2021](#c-adresso-2021)
- [3. Novel research topics in dementia](#3-novel-research-topics-in-dementia)
  * [ASR](#asr)
  * [Data Augmentation](#data-augmentation)
  * [Dialog Act](#dialog-act)
  * [Emotion](#emotion)
  * [Explainable](#explainable)
  * [Eye-tracking](#eye-tracking)
  * [Information Unit](#information-unit)
  * [Intermediate Pretraining](#intermediate-pretraining)
  * [Novel Speech Tasks](#novel-speech-tasks)
  * [Pause&Disfluencies](#pause-disfluencies)
  * [Perplexity](#perplexity)
  * [Speech and Writing](#speech-and-writing)
  * [Telephone Interview](#telephone-interview)
  * [Voice Assistant](#voice-assistant)
- [4. Regular papers](#4-regular-papers)
- [5. Related works in other domains](#5-related-works-in-other-domains)
  * [Aphasia](#aphasia)
  * [Asthma](#asthma)
  * [Disfluency](#disfluency)
  * [Parkinson’s Disease](#parkinson-s-disease)

## Papers

### 1. Survey papers
- 2023
	- [Machine Learning for Dementia Prediction: A Systematic Review and Future Research Directions](https://doi.org/10.1007/s10916-023-01906-7) - Ashir Javeed, A. Dallora, J. Berglund, Arif Ali, Liaqat Ali, P. Anderberg, Journal of medical systems, (2023), Cited By: 3
	- [DementiaBank: Theoretical Rationale, Protocol, and Illustrative Analyses.](https://doi.org/10.1044/2022_AJSLP-22-00281) - Alyssa M. Lanzi, Anna K Saylor, Davida Fromm, Houjun Liu, Brian MacWhinney, Matthew L. Cohen, American Journal of Speech-Language Pathology, (2023), Cited By: 0
- 2022
	- [Deep learning-based speech analysis for Alzheimer’s disease detection: a literature review](https://doi.org/10.1186/s13195-022-01131-3) - Qin Yang, Xin Li, Xinyun Ding, Feiyang Xu, Zhenhua Ling, Alzheimer's Research & Therapy, (2022), Cited By: 1
	- [Speech- and Language-Based Classification of Alzheimer's Disease: A Systematic Review.](https://doi.org/10.3390/bioengineering9010027) - Inês Vigo, Luís Coelho, Sara S. Reis, Bioengineering, (2022), Cited By: 4
	- [A Systematic Review of Alzheimer's disease detection based on speech and natural language processing](https://doi.org/10.1109/RADIOELEKTRONIKA54537.2022.9764938) - Adam Ševčík, M. Rusko, International Conference Radioelektronika, (2022), Cited By: 1
- 2020
	- [Artificial Intelligence, Speech, and Language Processing Approaches to Monitoring Alzheimer’s Disease: A Systematic Review](https://doi.org/10.3233/JAD-200888) - Sofia de la Fuente Garcia, C. Ritchie, S. Luz, Journal of Alzheimer's Disease, (2020), Cited By: 70
- 2018
	- [A Review of Alzheimer's Disease Classification Using Neuropsychological Data and Machine Learning](https://doi.org/10.1109/CISP-BMEI.2018.8633126) - Gang Lyu, 2018 11th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI), (2018), Cited By: 10

### 2. Special challenges

#### a. ADReSS 2020 InterSpeech
- 2020
	- [The INESC-ID Multi-Modal System for the ADReSS 2020 Challenge](https://doi.org/10.21437/interspeech.2020-2833) - A. Pompili, T. Rolland, A. Abad, Interspeech, (2020), Cited By: 25
	- [Multiscale System for Alzheimer's Dementia Recognition Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2781) - E. Edwards, Charles Dognin, B. Bollepalli, M. Singh, Interspeech, (2020), Cited By: 20
	- [A Comparison of Acoustic and Linguistics Methodologies for Alzheimer's Dementia Recognition](https://doi.org/10.21437/interspeech.2020-2635) - N. Cummins, Yilin Pan, Zhao Ren, J. Fritsch, Venkata Srikanth Nallanthighal, H. Christensen, D. Blackburn, Björn Schuller, M. Magimai.-Doss, H. Strik, Aki Härmä, Interspeech, (2020), Cited By: 31
	- [Using State of the Art Speaker Recognition and Natural Language Processing Technologies to Detect Alzheimer's Disease and Assess its Severity](https://doi.org/10.21437/interspeech.2020-2587) - R. Pappagari, Jaejin Cho, L. Moro-Velázquez, N. Dehak, Interspeech, (2020), Cited By: 37
	- [To BERT or Not To BERT: Comparing Speech and Language-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2020-2557) - Aparna Balagopalan, Benjamin Eyre, F. Rudzicz, Jekaterina Novikova, Interspeech, (2020), Cited By: 63
	- [Comparing Natural Language Processing Techniques for Alzheimer's Dementia Prediction in Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2729) - T. Searle, Zina M. Ibrahim, R. Dobson, Interspeech, (2020), Cited By: 22
	- [Exploring MMSE Score Prediction Using Verbal and Non-Verbal Cues](https://doi.org/10.21437/interspeech.2020-3085) - S. Farzana, Natalie Parde, Interspeech, (2020), Cited By: 10
	- [Multimodal Inductive Transfer Learning for Detection of Alzheimer's Dementia and its Severity](https://doi.org/10.21437/interspeech.2020-3137) - Utkarsh Sarawgi, Wazeer Zulfikar, Nouran Soliman, P. Maes, Interspeech, (2020), Cited By: 35
	- [Automated Screening for Alzheimer's Dementia Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-3158) - Muhammad Shehram Shah Syed, Zafi Sherhan Syed, M. Lech, E. Pirogova, Interspeech, (2020), Cited By: 37
	- [Tackling the ADReSS Challenge: A Multimodal Approach to the Automated Recognition of Alzheimer's Dementia](https://doi.org/10.21437/interspeech.2020-2202) - Matej Martinc, Senja Pollak, Interspeech, (2020), Cited By: 18
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, Interspeech, (2020), Cited By: 48
	- [Alzheimer's Dementia Recognition through Spontaneous Speech: The ADReSS Challenge](https://doi.org/10.21437/interspeech.2020-2571) - S. Luz, F. Haider, Sofia de la Fuente, Davida Fromm, B. MacWhinney, Interspeech, (2020), Cited By: 133
	- [Exploiting Multi-Modal Features From Pre-trained Networks for Alzheimer's Dementia Recognition](https://doi.org/10.21437/interspeech.2020-3153) - Junghyun Koo, Jie Hwan Lee, Jaewoo Pyo, Yujin Jo, Kyogu Lee, Interspeech, (2020), Cited By: 22
	- [Multi-Modal Fusion with Gating Using Audio, Lexical and Disfluency Features for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/Interspeech.2020-2721) - Morteza Rohanian, J. Hough, Matthew Purver, Interspeech, (2020), Cited By: 34

#### b. ADReSS 2020 Frontiers
- 2021
	- [Temporal Integration of Text Transcripts and Acoustic Features for Alzheimer's Diagnosis Based on Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.642647) - Matej Martinc, F. Haider, Senja Pollak, S. Luz, Frontiers in Aging Neuroscience, (2021), Cited By: 13
	- [Language Impairment in Alzheimer’s Disease—Robust and Explainable Evidence for AD-Related Deterioration of Spontaneous Speech Through Multilingual Machine Learning](https://doi.org/10.3389/fnagi.2021.642033) - Hali Lindsay, J. Tröger, A. König, Frontiers in Aging Neuroscience, (2021), Cited By: 8
	- [Acoustic and Language Based Deep Learning Approaches for Alzheimer's Dementia Detection From Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.623607) - Pranav Mahajan, V. Baths, Frontiers in Aging Neuroscience, (2021), Cited By: 21
	- [Cognitive and Structural Correlates of Conversational Speech Timing in Mild Cognitive Impairment and Mild-to-Moderate Alzheimer’s Disease: Relevance for Early Detection Approaches](https://doi.org/10.3389/fnagi.2021.637404) - C. De Looze, Amir Dehsarvi, L. Crosby, Aisling Vourdanou, R. Coen, B. Lawlor, R. Reilly, Frontiers in Aging Neuroscience, (2021), Cited By: 1
	- [Classifying Alzheimer's Disease Using Audio and Text-Based Representations of Speech](https://doi.org/10.3389/fpsyg.2020.624137) - R'mani Haulcy, James R. Glass, Frontiers in Psychology, (2021), Cited By: 24
	- [Recognition of Alzheimer’s Dementia From the Transcriptions of Spontaneous Speech Using fastText and CNN Models](https://doi.org/10.3389/fcomp.2021.624558) - Amit Meghanani, S. AnoopC., A. Ramakrishnan, Frontiers of Computer Science, (2021), Cited By: 10
	- [Towards Computer-Based Automated Screening of Dementia Through Spontaneous Speech](https://doi.org/10.3389/fpsyg.2020.623237) - K. Chlasta, K. Wołk, Frontiers in Psychology, (2021), Cited By: 9
	- [Multimodal Capture of Patient Behaviour for Improved Detection of Early Dementia: Clinical Feasibility and Preliminary Results](https://doi.org/10.3389/fcomp.2021.642633) - Patrik Jonell, Birger Moëll, K. Håkansson, G. Henter, Taras Kuchurenko, O. Mikheeva, G. Hagman, Jasper Holleman, M. Kivipelto, H. Kjellström, Joakim Gustafson, J. Beskow, Frontiers of Computer Science, (2021), Cited By: 10
	- [Using a Discourse Task to Explore Semantic Ability in Persons With Cognitive Impairment](https://doi.org/10.3389/fnagi.2020.607449) - M. Antonsson, Kristina Lundholm Fors, M. Eckerström, D. Kokkinakis, Frontiers in Aging Neuroscience, (2021), Cited By: 3
	- [Editorial: Alzheimer’s Dementia Recognition through Spontaneous Speech](https://doi.org/10.3389/fcomp.2021.780169) - S. Luz, F. Haider, Sofia de la Fuente Garcia, Davida Fromm, B. MacWhinney, Frontiers of Computer Science, (2021), Cited By: 6
	- [Exploring Deep Transfer Learning Techniques for Alzheimer’s Dementia Detection](https://doi.org/10.3389/fcomp.2021.624683) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Frontiers of Computer Science, (2021), Cited By: 14
	- [A Comparison of Connected Speech Tasks for Detecting Early Alzheimer’s Disease and Mild Cognitive Impairment Using Natural Language Processing and Machine Learning](https://doi.org/10.3389/fcomp.2021.634360) - Natasha Clarke, T. Barrick, P. Garrard, Frontiers of Computer Science, (2021), Cited By: 10
	- [Towards an Automatic Speech-Based Diagnostic Test for Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2021.624594) - Roozbeh Sadeghian, J. D. Schaffer, S. Zahorian, Frontiers of Computer Science, (2021), Cited By: 4
	- [Alzheimer’s Dementia Recognition From Spontaneous Speech Using Disfluency and Interactional Features](https://doi.org/10.3389/fcomp.2021.640669) - Shamila Nasreen, Morteza Rohanian, J. Hough, Matthew Purver, Frontiers of Computer Science, (2021), Cited By: 9
	- [Analysis and Classification of Word Co-Occurrence Networks From Alzheimer’s Patients and Controls](https://doi.org/10.3389/fcomp.2021.649508) - Tristan Millington, S. Luz, Frontiers of Computer Science, (2021), Cited By: 6
	- [Learning Language and Acoustic Models for Identifying Alzheimer’s Dementia From Speech](https://doi.org/10.3389/fcomp.2021.624659) - Zehra Shah, Jeffrey Sawalha, Mashrura Tasnim, S. Qi, Eleni Stroulia, R. Greiner, Frontiers of Computer Science, (2021), Cited By: 14
	- [Comparing Pre-trained and Feature-Based Models for Prediction of Alzheimer's Disease Based on Speech](https://doi.org/10.3389/fnagi.2021.635945) - Aparna Balagopalan, Benjamin Eyre, Jessica Robin, F. Rudzicz, Jekaterina Novikova, Frontiers in Aging Neuroscience, (2021), Cited By: 22
	- [Crossing the “Cookie Theft” Corpus Chasm: Applying What BERT Learns From Outside Data to the ADReSS Challenge Dementia Detection Task](https://doi.org/10.3389/fcomp.2021.642517) - Yue Guo, Changye Li, Carol L. Roan, Serguei V. S. Pakhomov, T. Cohen, Frontiers of Computer Science, (2021), Cited By: 10
- 2020
	- [Longitudinal Speech Biomarkers for Automated Alzheimer's Detection](https://doi.org/10.3389/fcomp.2021.624694) - Jordi Laguarta, B. Subirana, Frontiers of Computer Science, (2020), Cited By: 15
	- [Dual-Task Training Affect Cognitive and Physical Performances and Brain Oscillation Ratio of Patients With Alzheimer’s Disease: A Randomized Controlled Trial](https://doi.org/10.3389/fnagi.2020.605317) - Elnaz Parvin, F. Mohammadian, Sadegh Amani-shalamzari, M. Bayati, Behnaz Tazesh, Frontiers in Aging Neuroscience, (2020), Cited By: 9
- 2017
	- [Automated detection of unfilled pauses in speech of healthy and brain-damaged individuals](https://www.semanticscholar.org/paper/94d69b120bf5466447fde569ca676743b447fdf1) - Fedor Jalvingh, R. Jonkers, R. Ossewaarde, Y. Bastiaanse, , (2017), Cited By: 0

#### c. ADReSSo 2021
- 2021
	- [Using the Outputs of Different Automatic Speech Recognition Paradigms for Acoustic- and BERT-Based Alzheimer's Dementia Detection Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1519) - Yilin Pan, B. Mirheidari, Jennifer M. Harris, J. Thompson, Matthew Jones, J. Snowden, Daniel Blackburn, H. Christensen, Interspeech, (2021), Cited By: 15
	- [Automatic Detection and Assessment of Alzheimer Disease Using Speech and Language Technologies in Low-Resource Scenarios](https://doi.org/10.21437/interspeech.2021-1850) - R. Pappagari, Jaejin Cho, Sonal Joshi, L. Moro-Velázquez, Piotr Żelasko, J. Villalba, N. Dehak, Interspeech, (2021), Cited By: 11
	- [WavBERT: Exploiting Semantic and Non-Semantic Speech Using Wav2vec and BERT for Dementia Detection](https://doi.org/10.21437/interspeech.2021-332) - Youxiang Zhu, Abdelrahman Obyat, Xiaohui Liang, J. Batsis, R. Roth, Interspeech, (2021), Cited By: 10
	- [Tackling the ADRESSO Challenge 2021: The MUET-RMIT System for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1572) - Zafi Sherhan Syed, Muhammad Shehram Shah Syed, M. Lech, E. Pirogova, Interspeech, (2021), Cited By: 5
	- [Automatic Detection of Alzheimer's Disease Using Spontaneous Speech Only](https://doi.org/10.21437/interspeech.2021-2002) - Jun Chen, Jieping Ye, Fengyi Tang, Jiayu Zhou, Interspeech, (2021), Cited By: 6
	- [Alzheimer's Disease Detection from Spontaneous Speech through Combining Linguistic Complexity and (Dis)Fluency Features with Pretrained Language Models](https://doi.org/10.21437/interspeech.2021-1415) - Y. Qiao, Xuefeng Yin, Daniel Wiechmann, Elma Kerz, Interspeech, (2021), Cited By: 6
	- [Comparing Acoustic-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2021-759) - Aparna Balagopalan, Jekaterina Novikova, Interspeech, (2021), Cited By: 14
	- [Influence of the Interviewer on the Automatic Assessment of Alzheimer's Disease in the Context of the ADReSSo Challenge](https://doi.org/10.21437/interspeech.2021-1589) - Paula Andrea Pérez-Toro, Sebastian P. Bayerl, Tomas Arias-Vergara, Juan Camilo Vásquez-Correa, P. Klumpp, M. Schuster, E. Nöth, J. Orozco-Arroyave, K. Riedhammer, Interspeech, (2021), Cited By: 9
	- [Alzheimer Disease Recognition Using Speech-Based Embeddings From Pre-Trained Models](https://doi.org/10.21437/interspeech.2021-753) - Lara Gauder, Leonardo Pepino, L. Ferrer, P. Riera, Interspeech, (2021), Cited By: 10
	- [Detecting cognitive decline using speech only: The ADReSSo Challenge](https://doi.org/10.1101/2021.03.24.21254263) - S. Luz, F. Haider, Sofia de la Fuente, Davida Fromm, B. MacWhinney, medRxiv, (2021), Cited By: 52
	- [Alzheimer's Dementia Recognition Using Acoustic, Lexical, Disfluency and Speech Pause Features Robust to Noisy Inputs](https://doi.org/10.21437/interspeech.2021-1633) - Morteza Rohanian, J. Hough, Matt Purver, Interspeech, (2021), Cited By: 14
	- [Modular Multi-Modal Attention Network for Alzheimer's Disease Detection Using Patient Audio and Language Data](https://doi.org/10.21437/interspeech.2021-2024) - N. Wang, Yupeng Cao, Shuai Hao, Zongru Shao, K.P. Subbalakshmi, Interspeech, (2021), Cited By: 5

#### d.SPGC Challenge 2023
- 2023
	- [Cross-lingual Alzheimer's Disease detection based on paralinguistic and pre-trained features](https://doi.org/10.48550/arXiv.2303.07650) - Xuchu Chen, Yujiang Pu, Jinpeng Li, Weiqiang Zhang, arXiv.org, (2023), Cited By: 0
	- [Multilingual Alzheimer's Dementia Recognition through Spontaneous Speech: a Signal Processing Grand Challenge](https://doi.org/10.48550/arXiv.2301.05562) - S. Luz, F. Haider, Davida Fromm, Ioulietta Lazarou, Y. Kompatsiaris, B. MacWhinney, arXiv.org, (2023), Cited By: 2
	- [Cross-Lingual Transfer Learning for Alzheimer's Detection From Spontaneous Speech](https://doi.org/10.48550/arXiv.2303.03049) - Bastiaan Tamm, R. Vandenberghe, H. V. hamme, arXiv.org, (2023), Cited By: 0

### 3. Novel research topics in dementia

#### ASR
- 2022
	- [The Far Side of Failure: Investigating the Impact of Speech Recognition Errors on Subsequent Dementia Classification](https://doi.org/10.48550/arXiv.2211.07430) - Changye Li, T. Cohen, Serguei V. S. Pakhomov, arXiv.org, (2022), Cited By: 0
	- [End-to-End ASR-Enhanced Neural Network for Alzheimer’s Disease Diagnosis](https://doi.org/10.1109/icassp43922.2022.9747856) - Jiancheng Gui, Yikai Li, Kai Chen, Joanna Siebert, Qingcai Chen, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 1
	- [Evaluating Web-Based Automatic Transcription for Alzheimer Speech Data: Transcript Comparison and Machine Learning Analysis](https://doi.org/10.2196/33460) - Thomas Soroski, Thiago da Cunha Vasco, Sally May Newton‐Mason, Saffrin Granby, Caitlin Lewis, Anuj Harisinghani, Matteo Rizzo, C. Conati, Gabriel Murray, G. Carenini, Thalia S. Field, Hyeju Jang, JMIR Aging, (2022), Cited By: 1
	- [Conformer Based Elderly Speech Recognition System for Alzheimer's Disease Detection](https://doi.org/10.48550/arXiv.2206.13232) - Tianzi Wang, Jiajun Deng, Mengzhe Geng, Zi Ye, Shoukang Hu, Yi Wang, Mingyu Cui, Zengrui Jin, Xunying Liu, Helen M. Meng, Interspeech, (2022), Cited By: 5
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, International Conference on Text, Speech and Dialogue, (2022), Cited By: 0
- 2021
	- [Exploiting Pre-Trained ASR Models for Alzheimer's Disease Recognition Through Spontaneous Speech](https://arxiv.org/abs/2110.01493) - Ying Qin, W. Liu, Zhiyuan Peng, Si-Ioi Ng, Jingyu Li, Haibo Hu, Tan Lee, , (2021), Cited By: 3
- 2020
	- [Improving Detection of Alzheimer's Disease Using Automatic Speech Recognition to Identify High-Quality Segments for More Robust Feature Extraction](https://doi.org/10.21437/interspeech.2020-2698) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2020), Cited By: 9
- 2019
	- [Impact of ASR on Alzheimer’s Disease Detection: All Errors are Equal, but Deletions are More Equal than Others](https://doi.org/10.18653/v1/2020.wnut-1.21) - Aparna Balagopalan, Ksenia Shkaruta, Jekaterina Novikova, WNUT, (2019), Cited By: 6
- 2018
	- [A Speech Recognition-based Solution for the Automatic Detection of Mild Cognitive Impairment from Spontaneous Speech](https://doi.org/10.2174/1567205014666171121114930) - L. Tóth, I. Hoffmann, G. Gosztolya, V. Vincze, Gréta Szatlóczki, Zoltán Bánréti, M. Pákáski, J. Kálmán, Current Alzheimer Research, (2018), Cited By: 125
- 2015
	- [Automatic detection of mild cognitive impairment from spontaneous speech using ASR](https://www.semanticscholar.org/paper/651fd60a871cd7f06511da049427cd7702965884) - L. Tóth, G. Gosztolya, V. Vincze, I. Hoffmann, Gréta Szatlóczki, Edit Biró, Fruzsina Zsura, M. Pákáski, J. Kálmán, Interspeech, (2015), Cited By: 78

#### Data Augmentation
- 2022
	- [Data Augmentation for Dementia Detection in Spoken Language](https://doi.org/10.48550/arXiv.2206.12879) - Anna Hl'edikov'a, Dominika Woszczyk, Alican Acman, Soteris Demetriou, Björn Schuller, Interspeech, (2022), Cited By: 1
	- [Automatic Speech Classifier for Mild Cognitive Impairment and Early Dementia](https://doi.org/10.1145/3469089) - BertiniFlavio, AlleviDavide, LuteroGianluca, MontesiDanilo, CalzàLaura, , (2022), Cited By: 9
	- [Cognitive Assessment of Japanese Older Adults with Text Data Augmentation](https://doi.org/10.3390/healthcare10102051) - Toshiharu Igarashi, M. Nihei, Healthcare, (2022), Cited By: 1
- 2021
	- [Robustness and Sensitivity of BERT Models Predicting Alzheimer’s Disease from Text](https://doi.org/10.18653/v1/2021.wnut-1.37) - Jekaterina Novikova, WNUT, (2021), Cited By: 4
- 2020
	- [Data augmentation using generative networks to identify dementia](https://arxiv.org/abs/2004.05989) - B. Mirheidari, Yilin Pan, D. Blackburn, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, H. Christensen, arXiv.org, (2020), Cited By: 3

#### Dialog Act
- 2022
	- [Are Interaction Patterns Helpful for Task-Agnostic Dementia Detection? An Empirical Exploration](https://www.semanticscholar.org/paper/58b58e76a7394bc1028bde01992b943b4dbea255) - S. Farzana, Natalie Parde, SIGDIAL Conferences, (2022), Cited By: 0
- 2020
	- [Modeling Dialogue in Conversational Cognitive Health Screening Interviews](https://www.semanticscholar.org/paper/cf0c7194c5342f4d167e95c54685f5f564a7d12b) - S. Farzana, Mohammad Valizadeh, Natalie Parde, International Conference on Language Resources and Evaluation, (2020), Cited By: 7

#### Emotion
- 2021
	- [Audio-Visual Recognition of Emotional Engagement of People with Dementia](https://doi.org/10.21437/interspeech.2021-567) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, Interspeech, (2021), Cited By: 4
- 2020
	- [Towards Engagement Recognition of People with Dementia in Care Settings](https://doi.org/10.1145/3382507.3418856) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, International Conference on Multimodal Interaction, (2020), Cited By: 9

#### Explainable
- 2022
	- [Data-driven Approach to Differentiating between Depression and Dementia from Noisy Speech and Language Data](https://doi.org/10.48550/arXiv.2210.03303) - Malikeh Ehghaghi, F. Rudzicz, Jekaterina Novikova, WNUT, (2022), Cited By: 0
	- [Interpreting acoustic features for the assessment of Alzheimer’s disease using ForestNet](https://doi.org/10.1016/j.smhl.2022.100347) - P. A. Pérez-Toro, Dalia Rodríguez-Salas, T. Arias-Vergara, P. Klumpp, M. Schuster, E. Nöth, J. Orozco-Arroyave, A. Maier, Smart Health, (2022), Cited By: 0
	- [Dementia Detection Using Language Models and Transfer Learning](https://doi.org/10.1145/3520084.3520108) - Mondher Bouazizi, Chuheng Zheng, T. Ohtsuki, International Conferences on Software Engineering and Information Management, (2022), Cited By: 0
- 2021
	- [Explainable Identification of Dementia From Transcripts Using Transformer Networks](https://doi.org/10.1109/JBHI.2022.3172479) - Loukas Ilias, D. Askounis, IEEE journal of biomedical and health informatics, (2021), Cited By: 6
	- [Towards Interpretability of Speech Pause in Dementia Detection Using Adversarial Learning](https://doi.org/10.1109/icassp43922.2022.9747006) - Youxiang Zhu, Bang Tran, Xiaohui Liang, J. Batsis, R. Roth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 2
- 2020
	- [Acoustic Feature Extraction with Interpretable Deep Neural Network for Neurodegenerative Related Disorder Classification](https://doi.org/10.21437/interspeech.2020-2684) - Yilin Pan, B. Mirheidari, Z. C. Tu, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, D. Blackburn, H. Christensen, Interspeech, (2020), Cited By: 7
	- [Exploiting Fully Convolutional Network and Visualization Techniques on Spontaneous Speech for Dementia Detection](https://arxiv.org/abs/2008.07052) - Youxiang Zhu, Xiaohui Liang, arXiv.org, (2020), Cited By: 2
- 2019
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Machine Learning in Health Care, (2019), Cited By: 13

#### Eye-tracking
- 2022
	- [Dementia Detection by Fusing Speech and Eye-Tracking Representation](https://doi.org/10.1109/icassp43922.2022.9747054) - Zhengyan Sheng, Zhiqiang Guo, Xin Li, Yunxia Li, Zhenhua Ling, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 0
- 2020
	- [Non-Invasive Classification of Alzheimer's Disease Using Eye Tracking and Language](https://www.semanticscholar.org/paper/808412161cd6b5927916a0a6dcf8e03300ba4ae1) - Oswald Barral, Hyeju Jang, Sally May Newton‐Mason, Sheetal Shajan, Thomas Soroski, G. Carenini, C. Conati, Thalia Shoshana Field, Machine Learning in Health Care, (2020), Cited By: 4

#### Information Unit
- 2016
	- [Vector-space topic models for detecting Alzheimer’s disease](https://doi.org/10.18653/v1/P16-1221) - Maria Yancheva, F. Rudzicz, Annual Meeting of the Association for Computational Linguistics, (2016), Cited By: 47
- 1996
	- [Comparative Study of Oral and Written Picture Description in Patients with Alzheimer's Disease](https://doi.org/10.1006/brln.1996.0033) - B. Croisile, B. Ska, Marie-Josée Brabant, A. Duchêne, Y. Lepage, G. Aimard, M. Trillet, Brain and Language, (1996), Cited By: 178

#### Intermediate Pretraining
- 2022
	- [Domain-aware Intermediate Pretraining for Dementia Detection with Limited Data](https://doi.org/10.21437/interspeech.2022-10862) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Interspeech, (2022), Cited By: 1

#### Large Language Models
- 2022
	- [Predicting dementia from spontaneous speech using large language models](https://doi.org/10.1371/journal.pdig.0000168) - Felix Agbavor, Hualou Liang, PLOS Digital Health, (2022), Cited By: 4

#### Neural Architecture Search
- 2023
	- [Neural Architecture Search with Multimodal Fusion Methods for Diagnosing Dementia](https://doi.org/10.48550/arXiv.2302.05894) - Michail Chatzianastasis, Loukas Ilias, D. Askounis, M. Vazirgiannis, arXiv.org, (2023), Cited By: 0

#### Novel Speech Tasks
- 2022
	- [Going Beyond the Cookie Theft Picture Test: Detecting Cognitive Impairments using Acoustic Features](https://doi.org/10.1007/978-3-031-16270-1_36) - Franziska Braun, Andreas Erzigkeit, H. Lehfeld, T. Hillemacher, K. Riedhammer, S. Bayerl, International Conference on Text, Speech and Dialogue, (2022), Cited By: 2
	- [The Hong Kong Grocery Shopping Dialog Task (HK-GSDT): A Quick Screening Test for Neurocognitive Disorders](https://doi.org/10.3390/ijerph192013302) - Xianmin Gong, P. Wong, H. Fung, V. C. T. Mok, T. Kwok, Jean Woo, Ka Ho WONG, Helen Meng, International Journal of Environmental Research and Public Health, (2022), Cited By: 0
- 2021
	- [Using natural language processing in clinical research: The promise
 and challenges of translating into practical tools](https://doi.org/10.1037/tms0000145) - C. Diaz-Asper, B. Elvevåg, TMS Proceedings 2021, (2021), Cited By: 0

#### Pause&Disfluencies
- 2023
	- [Efficient Pause Extraction and Encode Strategy for Alzheimer’s Disease Detection Using Only Acoustic Features from Spontaneous Speech](https://doi.org/10.3390/brainsci13030477) - Jiamin Liu, Fan Fu, Liang Li, Junxiao Yu, Dacheng Zhong, Songsheng Zhu, Yuxuan Zhou, Bin Liu, Jianqing Li, Brain Science, (2023), Cited By: 0
- 2022
	- [How You Say It Matters: Measuring the Impact of Verbal Disfluency Tags on Automated Dementia Detection](https://doi.org/10.18653/v1/2022.bionlp-1.4) - S. Farzana, Ashwin Deshpande, Natalie Parde, Workshop on Biomedical Natural Language Processing, (2022), Cited By: 2
- 2021
	- [Speech pause distribution as an early marker for Alzheimer's disease](https://doi.org/10.1101/2020.12.28.20248875) - P. Pastoriza-Domínguez, I. G. Torre, F. Diéguez-Vide, I. Gómez-Ruiz, S. Geladó, J. Bello-López, A. Ávila-Rivera, J. Matías‐Guiu, V. Pytel, A. Hernández-Fernández, medRxiv, (2021), Cited By: 11
- 2020
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, Interspeech, (2020), Cited By: 48
	- [An Automated Approach to Examining Pausing in the Speech of People With Dementia](https://doi.org/10.1177/1533317520939773) - Rachel A. Sluis, Daniel Angus, Janet Wiles, A. Back, T. Gibson, J. Liddle, Peter Worthy, D. Copland, A. Angwin, American Journal of Alzheimers Disease & Other Dementias, (2020), Cited By: 12
- 2017
	- [Automated detection of unfilled pauses in speech of healthy and brain-damaged individuals](https://www.semanticscholar.org/paper/94d69b120bf5466447fde569ca676743b447fdf1) - Fedor Jalvingh, R. Jonkers, R. Ossewaarde, Y. Bastiaanse, , (2017), Cited By: 0
- 2009
	- [Examining Pauses in Alzheimer's Discourse](https://doi.org/10.1177/1533317508328138) - B. Davis, M. Maclagan, American Journal of Alzheimers Disease & Other Dementias, (2009), Cited By: 44

#### Perplexity
- 2023
	- [Semantic Coherence Markers for the Early Diagnosis of the Alzheimer Disease](https://doi.org/10.48550/arXiv.2302.01025) - Davide Colla, Matteo Delsanto, Marco Agosto, B. Vitiello, Daniele P. Radicioni, arXiv.org, (2023), Cited By: 0
- 2022
	- [GPT-D: Inducing Dementia-related Linguistic Anomalies by Deliberate Degradation of Artificial Neural Language Models](https://doi.org/10.48550/arXiv.2203.13397) - Changye Li, D. Knopman, Weizhe Xu, T. Cohen, Serguei V. S. Pakhomov, Annual Meeting of the Association for Computational Linguistics, (2022), Cited By: 3
- 2020
	- [A Tale of Two Perplexities: Sensitivity of Neural Language Models to Lexical Retrieval Deficits in Dementia of the Alzheimer’s Type](https://doi.org/10.18653/v1/2020.acl-main.176) - T. Cohen, Serguei V. S. Pakhomov, Annual Meeting of the Association for Computational Linguistics, (2020), Cited By: 14
- 2019
	- [Detecting Alzheimer's Disease from Continuous Speech Using Language Models.](https://doi.org/10.3233/JAD-190452) - Zhiqiang Guo, Zhenhua Ling, Yunxia Li, Journal of Alzheimer's Disease, (2019), Cited By: 15
	- [Perplexity – a new predictor of cognitive changes in spoken language? – results of the Interdisciplinary Longitudinal Study on Adult Development and Aging (ILSE)](https://doi.org/10.1515/lingvan-2018-0026) - C. Frankenberg, Jochen Weiner, Tanja Schultz, M. Knebel, C. Degen, H. Wahl, J. Schroeder, Linguistics Vanguard, (2019), Cited By: 20
- 2018
	- [Language Modelling for the Clinical Semantic Verbal Fluency Task](https://www.semanticscholar.org/paper/88188082df9ec54d05753d88f3b4f92f31f86a9e) - N. Linz, J. Tröger, Hali Lindsay, A. König, P. Robert, J. Peter, J. Alexandersson, , (2018), Cited By: 4
- 2017
	- [An N-Gram Based Approach to the Automatic Diagnosis of Alzheimer's Disease from Spoken Language](https://doi.org/10.21437/INTERSPEECH.2017-1572) - Sebastian Wankerl, E. Nöth, S. Evert, Interspeech, (2017), Cited By: 42
- 2005
	- [Natural Language Processing - IJCNLP 2005, Second International Joint Conference, Jeju Island, Korea, October 11-13, 2005, Proceedings](https://doi.org/10.1007/11562214) - Kam-Fai Wong, Jian Su, O. Kwong, International Joint Conference on Natural Language Processing, (2005), Cited By: 79

#### Prompt Learning
- 2022
	- [Exploiting prompt learning with pre-trained language models for Alzheimer's Disease detection](https://doi.org/10.48550/arXiv.2210.16539) - Yi Wang, Jiajun Deng, Tianzi Wang, Bo Zheng, Shoukang Hu, Xunying Liu, Helen M. Meng, arXiv.org, (2022), Cited By: 1

#### Representation Learning

#### Speech and Writing
- 2021
	- [A Longitudinal Multi-modal Dataset for Dementia Monitoring and Diagnosis](https://arxiv.org/abs/2109.01537) - Dimitris Gkoumas, Bo Wang, A. Tsakalidis, M. Wolters, A. Zubiaga, Matthew Purver, M. Liakata, arXiv.org, (2021), Cited By: 2

#### Telephone Interview
- 2022
	- [Accuracy of telephone screening tools to identify dementia patients remotely: systematic review](https://doi.org/10.1177/20542704221115956) - Charlotte Olivia Riley, B. McKinstry, K. Fairhurst, JRSM Open, (2022), Cited By: 1
- 2021
	- [Dementia risks identified by vocal features via telephone conversations: A novel machine learning prediction model](https://doi.org/10.1371/journal.pone.0253988) - A. Shimoda, Yue Li, H. Hayashi, N. Kondo, PLoS ONE, (2021), Cited By: 14
	- [Diagnostic accuracy of the telephone interview for cognitive status (TICS) for the detection of dementia in primary care in the Netherlands](https://doi.org/10.1002/alz.052760) - H. Abdulrahman, Alzheimer's & Dementia, (2021), Cited By: 0
- 2007
	- [Validation of the Telephone Interview for Cognitive Status (TICS) in Japanese](https://doi.org/10.1002/GPS.1812) - Y. Konagaya, Y. Washimi, H. Hattori, A. Takeda, Tomoyuki Watanabe, T. Ohta, International Journal of Geriatric Psychiatry, (2007), Cited By: 32
- 1988
	- [The telephone interview for cognitive status](https://www.semanticscholar.org/paper/f29b4c35e8b57cebb570eaadbee1bdb95fd5d716) - J. Brandt, M. Spencer, M. Folstein, , (1988), Cited By: 654

#### Voice Assistant
- 2022
	- [Evaluating voice-assistant commands for dementia detection](https://doi.org/10.1016/j.csl.2021.101297) - Xiaohui Liang, J. Batsis, Youxiang Zhu, Tiffany M. Driesse, R. Roth, D. Kotz, B. MacWhinney, Computer Speech and Language, (2022), Cited By: 6
	- [Alzheimer's Dementia Detection through Spontaneous Dialogue with Proactive Robotic Listeners](https://doi.org/10.1109/HRI53351.2022.9889375) - Yuanchao Li, Catherine Lai, Divesh Lala, K. Inoue, T. Kawahara, IEEE/ACM International Conference on Human-Robot Interaction, (2022), Cited By: 2
- 2017
	- [An Avatar-Based System for Identifying Individuals Likely to Develop Dementia](https://doi.org/10.21437/INTERSPEECH.2017-690) - B. Mirheidari, D. Blackburn, K. Harkness, Traci Walker, A. Venneri, M. Reuber, H. Christensen, Interspeech, (2017), Cited By: 25

### 4. Regular papers
- 2023
	- [Efficient Pause Extraction and Encode Strategy for Alzheimer’s Disease Detection Using Only Acoustic Features from Spontaneous Speech](https://doi.org/10.3390/brainsci13030477) - Jiamin Liu, Fan Fu, Liang Li, Junxiao Yu, Dacheng Zhong, Songsheng Zhu, Yuxuan Zhou, Bin Liu, Jianqing Li, Brain Science, (2023), Cited By: 0
	- [Dementia classification using attention mechanism on audio data](https://doi.org/10.1109/SAMI58000.2023.10044539) - Shkhanukova Milana, International Symposium on Applied Machine Intelligence and Informatics, (2023), Cited By: 0
	- [Alzheimer’s Dementia Speech (Audio vs. Text): Multi-Modal Machine Learning at High vs. Low Resolution](https://doi.org/10.3390/app13074244) - Prachee Priyadarshinee, Christopher Johann Clarke, J. Melechovský, Cindy Ming Ying Lin, B. B T, Jer-Ming Chen, Applied Sciences, (2023), Cited By: 0
	- [An automated speech analysis system for the detection of cognitive decline in elderly](https://doi.org/10.1007/s10772-023-10016-1) - C. Loizou, M. Pantzaris, International Journal of Speech Technology, (2023), Cited By: 0
	- [Performance of machine learning algorithms for dementia assessment: impacts of language tasks, recording media, and modalities](https://doi.org/10.1186/s12911-023-02122-6) - Mahboobeh (Mah) Parsapoor (Parsa), Muhammad Raisul Alam, Alex Mihailidis, BMC Medical Informatics and Decision Making, (2023), Cited By: 0
- 2022
	- [Automatic cognitive assessment: Combining sparse datasets with disparate cognitive scores](https://doi.org/10.21437/interspeech.2022-10205) - B. Mirheidari, Daniel Blackburn, H. Christensen, Interspeech, (2022), Cited By: 0
	- [Using Spectral Sequence-to-Sequence Autoencoders to Assess Mild Cognitive Impairment](https://doi.org/10.1109/icassp43922.2022.9746148) - Mercedes Vetráb, José Vicente Egas López, R. Balogh, N. Imre, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 0
	- [Automatic Selection of Discriminative Features for Dementia Detection in Cantonese-Speaking People](https://doi.org/10.21437/interspeech.2022-10122) - Xiaoquan Ke, M. Mak, Helen M. Meng, Interspeech, (2022), Cited By: 0
	- [Artificial Intelligence-Enabled End-To-End Detection and Assessment of Alzheimer’s Disease Using Voice](https://doi.org/10.3390/brainsci13010028) - Felix Agbavor, Hualou Liang, Brain Science, (2022), Cited By: 1
	- [Augmented Adversarial Self-Supervised Learning for Early-Stage Alzheimer's Speech Detection](https://doi.org/10.21437/interspeech.2022-943) - Longfei Yang, Wenqing Wei, Sheng Li, Jiyi Li, T. Shinozaki, Interspeech, (2022), Cited By: 0
	- [A Multimodal Approach for Dementia Detection from Spontaneous Speech with Tensor Fusion Layer](https://doi.org/10.1109/BHI56158.2022.9926818) - Loukas Ilias, D. Askounis, J. Psarras, 2022 IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI), (2022), Cited By: 0
	- [A Dementia Classification Based on Speech Analysis of Casual Talk During a Clinical Interview](https://doi.org/10.1109/LifeTech53646.2022.9754933) - Shunya Hanai, Shohei Kato, Takuto Sakuma, R. Ohdake, M. Masuda, Hirohisa Watanabe, Global Conference on Life Sciences and Technologies, (2022), Cited By: 0
	- [Automated detection of mild cognitive impairment and dementia from voice recordings: A natural language processing approach](https://doi.org/10.1002/alz.12721) - S. Amini, Boran Hao, Lifu Zhang, Mengting Song, Aman Gupta, C. Karjadi, V. Kolachalama, R. Au, I. Paschalidis, Alzheimer's & Dementia, (2022), Cited By: 4
	- [Cognitive Digital Biomarkers from Automated Transcription of Spoken Language](https://doi.org/10.14283/jpad.2022.66) - N. Tavabi, D. Stück, A. Signorini, C. Karjadi, T. Al Hanai, M. Sandoval, C. Lemke, J. Glass, S. Hardy, M. Lavallee, B. Wasserman, T. Ang, C. Nowak, R. Kainkaryam, L. Foschini, R. Au, The journal of prevention of Alzheimer's disease, (2022), Cited By: 1
	- [Computer-Aided Dementia Detection: How Informative Are Your Features?](https://doi.org/10.1109/RTSI55261.2022.9905097) - Edoardo Stoppa, G. Di Donato, Natalie Parde, M. Santambrogio, International Forum on Research and Technologies for Society and Industry Leveraging a better tomorrow, (2022), Cited By: 0
	- [Deep Learning Approaches for Detecting Alzheimer's Dementia from Conversational Speech of ILSE Study](https://doi.org/10.21437/interspeech.2022-10942) - Ayimnisagul Ablimit, K. Scholz, Tanja Schultz, Interspeech, (2022), Cited By: 0
	- [Automatic Audio-based Screening System for Alzheimer’s Disease Detection](https://doi.org/10.1109/SMC53654.2022.9945127) - Sheng-Ya Lin, Ho-Ling Chang, Jwu-Jia Hwang, Thiri Wai, Yu-Ling Chang, Li-Chen Fu, IEEE International Conference on Systems, Man and Cybernetics, (2022), Cited By: 0
	- [A Pre-trained Neural Network to Predict Alzheimer’s Disease at an Early Stage](https://doi.org/10.14569/ijacsa.2022.0130524) - Ragavamsi Davuluri, Ragupathy Rengaswamy, International Journal of Advanced Computer Science and Applications, (2022), Cited By: 2
	- [Automatically detection of multi-class Alzheimer disease using Deep Siamese Convolutional Neural Network](https://doi.org/10.1109/ASSIC55218.2022.10088299) - A. Vashishtha, A. K. Acharya, Sujata Swain, 2022 International Conference on Advancements in Smart, Secure and Intelligent Computing (ASSIC), (2022), Cited By: 0
	- [Multimodal fusion for alzheimer’s disease recognition](https://doi.org/10.1007/s10489-022-04255-z) - Yangwei Ying, Tao Yang, Hong Zhou, Applied intelligence (Boston), (2022), Cited By: 1
	- [Impact of Acoustic Noise on Alzheimer's Disease Detection from Speech: Should You Let Baby Cry?](https://doi.org/10.48550/arXiv.2203.17110) - Jekaterina Novikova, arXiv.org, (2022), Cited By: 0
	- [Predicting Scores on the Mini-Mental State Examination (MMSE) from Spontaneous Speech](https://doi.org/10.3390/bs12090339) - A. Bueno-Cayo, Minerva del Rio Carmona, Rosa Castell-Enguix, Isabel Iborra-Marmolejo, Mike Murphy, T. Q. Irigaray, José Francisco Cervera, C. Moret-Tatay, Behavioral Science, (2022), Cited By: 1
	- [Automated text‐level semantic markers of Alzheimer's disease](https://doi.org/10.1002/dad2.12276) - Camila Sanz, Facundo Carrillo, A. Slachevsky, G. Forno, Maria Luisa Gorno Tempini, Roque Villagra, A. Ibáñez, E. Tagliazucchi, Adolfo M. García, Alzheimer's & Dementia, (2022), Cited By: 5
	- [A Transfer Learning Method for Detecting Alzheimer's Disease Based on Speech and Natural Language Processing](https://doi.org/10.3389/fpubh.2022.772592) - Ning-hong Liu, Kexue Luo, Zhenming Yuan, Yan Chen, Frontiers in Public Health, (2022), Cited By: 2
	- [Exploring Dementia Detection from Speech: Cross Corpus Analysis](https://doi.org/10.1109/icassp43922.2022.9747167) - Ayimnisagul Ablimit, Catarina Botelho, A. Abad, Tanja Schultz, I. Trancoso, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 2
	- [An Evaluation on Information Composition in Dementia Detection Based on Speech](https://doi.org/10.1109/ACCESS.2022.3203068) - Chuheng Zheng, Mondher Bouazizi, T. Ohtsuki, IEEE Access, (2022), Cited By: 0
	- [Semantic Feature Extraction Using SBERT for Dementia Detection](https://doi.org/10.3390/brainsci12020270) - Yamanki Santander-Cruz, Sebastián Salazar-Colores, W. J. Paredes-García, Humberto Guendulain-Arenas, S. Tovar-Arriaga, Brain Science, (2022), Cited By: 7
	- [Exploring linguistic feature and model combination for speech recognition based automatic AD detection](https://doi.org/10.48550/arXiv.2206.13758) - Yi Wang, Tianzi Wang, Zi Ye, Lingwei Meng, Shoukang Hu, Xixin Wu, Xunying Liu, Helen M. Meng, Interspeech, (2022), Cited By: 4
	- [Detecting Alzheimer's Disease Based on Acoustic Features Extracted from Pre-trained Models](https://doi.org/10.1007/978-3-031-20503-3_22) - Kangdi Mei, Zhiqiang Guo, Zhaoci Liu, Lijuan Liu, Xin Li, Zhenhua Ling, CAAI International Conference on Artificial Intelligence, (2022), Cited By: 0
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, International Conference on Text, Speech and Dialogue, (2022), Cited By: 0
	- [Novel Framework for Alzheimer Early Diagnosis using Inductive Transfer Learning Techniques](https://doi.org/10.1109/eSmarTA56775.2022.9935379) - Himanshu Kumar Sahu, Santosh Kumar, S. Alsamhi, M. K. Chaube, E. Curry, 2022 2nd International Conference on Emerging Smart Technologies and Applications (eSmarTA), (2022), Cited By: 0
- 2021
	- [Towards AI-powered Language Assessment Tools](https://doi.org/10.21203/RS.3.RS-246079/V1) - M. Parsa, Muhammad Raisul Alam, Alex Mihailidis, , (2021), Cited By: 1
	- [Detecting Alzheimer’s Disease from Speech Using Neural Networks with Bottleneck Features and Data Augmentation](https://doi.org/10.1109/ICASSP39728.2021.9413566) - Zhaoci Liu, Zhiqiang Guo, Zhenhua Ling, Yunxia Li, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 5
	- [Multi-Task Estimation of Age and Cognitive Decline from Speech](https://doi.org/10.1109/ICASSP39728.2021.9414642) - Yilin Pan, Venkata Srikanth Nallanthighal, D. Blackburn, H. Christensen, Aki Härmä, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 4
	- [Development of the Cuhk Elderly Speech Recognition System for Neurocognitive Disorder Detection Using the Dementiabank Corpus](https://doi.org/10.1109/ICASSP39728.2021.9413634) - Zi Ye, Shoukang Hu, Jinchao Li, Xurong Xie, Mengzhe Geng, Jianwei Yu, Junhao Xu, Boyang Xue, Shansong Liu, Xunying Liu, H. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 21
	- [Detecting Dementia from Speech and Transcripts using Transformers](https://doi.org/10.1016/j.csl.2023.101485) - Loukas Ilias, D. Askounis, J. Psarras, Computer Speech and Language, (2021), Cited By: 4
	- [Identifying Cognitive Impairment Using Sentence Representation Vectors](https://doi.org/10.21437/interspeech.2021-915) - B. Mirheidari, Yilin Pan, Daniel Blackburn, R. O'Malley, H. Christensen, Interspeech, (2021), Cited By: 2
	- [An Evaluation of Machine Learning Classifiers for Prediction of Alzheimer's Disease, Mild Cognitive Impairment and Normal Cognition](https://doi.org/10.1109/ICTC52510.2021.9620780) - Payam Hosseinzadeh Kasani, Sara Hosseinzadeh Kasani, Yeshin Kim, C. Yun, S. Choi, Jae-Won Jang, Information and Communication Technology Convergence, (2021), Cited By: 1
	- [Linguistic Parameters of Spontaneous Speech for Identifying Mild Cognitive Impairment and Alzheimer Disease](https://doi.org/10.1162/coli_a_00428) - V. Vincze, Martina Katalin Szabó, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, International Conference on Computational Logic, (2021), Cited By: 2
	- [Correlating natural language processing and automated speech analysis with clinician assessment to quantify speech-language changes in mild cognitive impairment and Alzheimer’s dementia](https://doi.org/10.1186/s13195-021-00848-x) - Anthony Yeung, A. Iaboni, E. Rochon, M. Lavoie, Calvin Santiago, Maria Yancheva, Jekaterina Novikova, Mengdan Xu, Jessica Robin, Liam D. Kaufman, Fariya Mostafa, Alzheimer's Research & Therapy, (2021), Cited By: 17
	- [A Comparative Study of Acoustic and Linguistic Features Classification for Alzheimer's Disease Detection](https://doi.org/10.1109/ICASSP39728.2021.9414147) - Jinchao Li, Jianwei Yu, Zi Ye, Simon Wong, M. Mak, B. Mak, Xunying Liu, Helen M. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 13
	- [Exploring neural models for predicting dementia from language](https://doi.org/10.1016/J.CSL.2020.101181) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Computer Speech and Language, (2021), Cited By: 5
	- [Exploiting linguistic information from Nepali transcripts for early detection of Alzheimer's disease using natural language processing and machine learning techniques](https://doi.org/10.1016/j.ijhcs.2021.102761) - Surabhi Adhikari, Surendrabikram Thapa, Usman Naseem, Priyanka Singh, H. Huo, Gnana Bharathy, Mukesh Prasad, Int. J. Hum. Comput. Stud., (2021), Cited By: 7
- 2020
	- [Transformer-based deep neural network language models for Alzheimer’s disease detection from targeted speech](https://doi.org/10.21203/rs.3.rs-49267/v1) - A. Roshanzamir, H. Aghajan, M. Baghshah, , (2020), Cited By: 1
	- [Uncertainty-Aware Multi-Modal Ensembling for Severity Prediction of Alzheimer's Dementia](https://arxiv.org/abs/2010.01440) - Utkarsh Sarawgi, Wazeer Zulfikar, Rishab Khincha, P. Maes, arXiv.org, (2020), Cited By: 1
	- [An Assessment of Paralinguistic Acoustic Features for Detection of Alzheimer's Dementia in Spontaneous Speech](https://doi.org/10.1109/JSTSP.2019.2955022) - F. Haider, S. de la Fuente, S. Luz, IEEE Journal on Selected Topics in Signal Processing, (2020), Cited By: 75
	- [Combining Prosodic, Voice Quality and Lexical Features to Automatically Detect Alzheimer's Disease](https://arxiv.org/abs/2011.09272) - Mireia Farr'us, Joan Codina-Filbà, arXiv.org, (2020), Cited By: 4
	- [Predicting Prodromal Dementia Using Linguistic Patterns and Deficits](https://doi.org/10.1109/ACCESS.2020.3029907) - Ahmed H. Alkenani, Yuefeng Li, Yue Xu, Qing Zhang, IEEE Access, (2020), Cited By: 4
	- [Using narratives in differential diagnosis of neurodegenerative syndromes.](https://doi.org/10.1016/j.jcomdis.2020.105994) - Yasmeen Faroqi-Shah, Ashlyn Treanor, N. Ratner, B. Ficek, K. Webster, K. Tsapkini, Journal of Communication Disorders, (2020), Cited By: 10
	- [Linguistic markers predict onset of Alzheimer's disease](https://doi.org/10.1016/j.eclinm.2020.100583) - Elif Eyigoz, Sachin Mathur, Mar Santamaria, G. Cecchi, M. Naylor, EClinicalMedicine, (2020), Cited By: 64
- 2019
	- [Multilingual prediction of Alzheimer’s disease through domain adaptation and concept-based language modelling](https://doi.org/10.18653/v1/N19-1367) - Kathleen C. Fraser, N. Linz, Bai Li, K. L. Fors, F. Rudzicz, A. König, J. Alexandersson, P. Robert, D. Kokkinakis, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 11
	- [Multilingual word embeddings for the assessment of narrative speech in mild cognitive impairment](https://doi.org/10.1016/j.csl.2018.07.005) - Kathleen C. Fraser, K. L. Fors, D. Kokkinakis, Computer Speech and Language, (2019), Cited By: 38
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Machine Learning in Health Care, (2019), Cited By: 13
	- [Automatic Hierarchical Attention Neural Network for Detecting AD](https://doi.org/10.21437/interspeech.2019-1799) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2019), Cited By: 22
	- [Detecting dementia in Mandarin Chinese using transfer learning from a parallel corpus](https://doi.org/10.18653/v1/N19-1199) - Bai Li, Y. Hsu, F. Rudzicz, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 8
	- [Detecting Alzheimer's Disease by estimating attention and elicitation path through the alignment of spoken picture descriptions with the picture prompt](https://arxiv.org/abs/1910.00515) - B. Mirheidari, Yilin Pan, Traci Walker, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, arXiv.org, (2019), Cited By: 6
	- [An Automatic Assessment System for Alzheimer’s Disease Based on Speech Using Feature Sequence Generator and Recurrent Neural Network](https://doi.org/10.1038/s41598-019-56020-x) - Yi-Wei Chien, Sheng-Yi Hong, W. Cheah, Li-Hung Yao, Yu-Ling Chang, L. Fu, Scientific Reports, (2019), Cited By: 29
	- [Predicting MCI Status From Multimodal Language Data Using Cascaded Classifiers](https://doi.org/10.3389/fnagi.2019.00205) - Kathleen C. Fraser, Kristina Lundholm Fors, M. Eckerström, Fredrik Öhman, D. Kokkinakis, Frontiers in Aging Neuroscience, (2019), Cited By: 44
	- [Automatic Diagnosis of Alzheimer’s Disease Using Neural Network Language Models](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, Sebastian Wankerl, E. Nöth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2019), Cited By: 37
	- [An Attention-Based Hybrid Network for Automatic Detection of Alzheimer's Disease from Narrative Speech](https://doi.org/10.21437/interspeech.2019-2872) - Jun Chen, Ji Zhu, Jieping Ye, Interspeech, (2019), Cited By: 25
- 2018
	- [Augmenting word2vec with latent Dirichlet allocation within a clinical application](https://doi.org/10.18653/v1/N19-1414) - Akshay Budhkar, F. Rudzicz, North American Chapter of the Association for Computational Linguistics, (2018), Cited By: 8
	- [Detecting cognitive impairments by agreeing on interpretations of linguistic features](https://doi.org/10.18653/v1/N19-1146) - Zining Zhu, Jekaterina Novikova, F. Rudzicz, North American Chapter of the Association for Computational Linguistics, (2018), Cited By: 25
	- [Speech Processing for Early Alzheimer Disease Diagnosis: Machine Learning Based Approach](https://doi.org/10.1109/aiccsa.2018.8612831) - Randa Ben Ammar, Yassine Ben Ayed, ACS/IEEE International Conference on Computer Systems and Applications, (2018), Cited By: 16
	- [Detecting Signs of Dementia Using Word Vector Representations](https://doi.org/10.21437/Interspeech.2018-1764) - B. Mirheidari, D. Blackburn, Traci Walker, A. Venneri, M. Reuber, H. Christensen, Interspeech, (2018), Cited By: 44
	- [Deep language space neural network for classifying mild cognitive impairment and Alzheimer-type dementia](https://doi.org/10.1371/journal.pone.0205636) - S. Orimaye, Jojo Sze-Meng Wong, C. P. Wong, PLoS ONE, (2018), Cited By: 33
	- [Detecting Alzheimer's Disease Using Gated Convolutional Neural Network from Audio Data](https://doi.org/10.21437/Interspeech.2018-1713) - Tifani Warnita, Nakamasa Inoue, K. Shinoda, Interspeech, (2018), Cited By: 34
	- [Learning multiview embeddings for assessing dementia](https://doi.org/10.18653/v1/D18-1304) - C. Pou-Prom, F. Rudzicz, Conference on Empirical Methods in Natural Language Processing, (2018), Cited By: 13
- 2017
	- [Longitudinal Monitoring and Detection of Alzheimer's Type Dementia from Spontaneous Speech Data](https://doi.org/10.1109/CBMS.2017.41) - S. Luz, 2017 IEEE 30th International Symposium on Computer-Based Medical Systems (CBMS), (2017), Cited By: 31
	- [INVESTIGATING PREDICTORS OF COGNITIVE DECLINE USING MACHINE LEARNING](https://doi.org/10.1016/j.jalz.2017.06.1257) - R. Casanova, Santiago Saldana, M. Lutz, B. Plassman, M. Kuchibhatla, K. Hayden, Alzheimer's & Dementia, (2017), Cited By: 29
- 2016
	- [Detecting Mild Cognitive Impairment from Spontaneous Speech by Correlation-Based Phonetic Feature Selection](https://doi.org/10.21437/Interspeech.2016-384) - G. Gosztolya, L. Tóth, Tamás Grósz, V. Vincze, I. Hoffmann, Gréta Szatlóczki, M. Pákáski, J. Kálmán, Interspeech, (2016), Cited By: 32
- 2015
	- [Linguistic Features Identify Alzheimer's Disease in Narrative Speech.](https://doi.org/10.3233/JAD-150520) - Kathleen C. Fraser, J. Meltzer, F. Rudzicz, Journal of Alzheimer's Disease, (2015), Cited By: 479

### 5. Related works in other domains

#### Aphasia
- 2020
	- [BlaBla: Linguistic Feature Extraction for Clinical Analysis in Multiple Languages](https://doi.org/10.21437/interspeech.2020-2880) - Abhishek Shivkumar, J. Weston, R. Lenain, E. Fristed, Interspeech, (2020), Cited By: 3

#### Asthma
- 2020
	- [Analysis of Acoustic Features for Speech Sound Based Classification of Asthmatic and Healthy Subjects](https://doi.org/10.1109/ICASSP40776.2020.9054062) - Shivani Yadav, Merugu Keerthana, D. Gope, U. Krishnaswamy, P. Ghosh, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2020), Cited By: 15

#### Disfluency
- 2020
	- [Improving Disfluency Detection by Self-Training a Self-Attentive Model](https://doi.org/10.18653/v1/2020.acl-main.346) - Paria Jamshid Lou, Mark Johnson, Annual Meeting of the Association for Computational Linguistics, (2020), Cited By: 26
	- [Re-framing Incremental Deep Language Models for Dialogue Processing with Multi-task Learning](https://doi.org/10.18653/V1/2020.COLING-MAIN.43) - Morteza Rohanian, J. Hough, International Conference on Computational Linguistics, (2020), Cited By: 6
- 2019
	- [Neural Constituency Parsing of Speech Transcripts](https://doi.org/10.18653/v1/N19-1282) - Paria Jamshid Lou, Yufei Wang, Mark Johnson, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 15

#### Parkinson’s Disease
- 2021
	- [Supervised Speech Representation Learning for Parkinson's Disease Classification](https://arxiv.org/abs/2106.00531) - Parvaneh Janbakhshi, I. Kodrasi, ITG Conference on Speech Communication, (2021), Cited By: 3
- 2020
	- [Using X-Vectors to Automatically Detect Parkinson’s Disease from Speech](https://doi.org/10.1109/ICASSP40776.2020.9053770) - L. Moro-Velázquez, J. Villalba, N. Dehak, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2020), Cited By: 31


***

_This file was generated by [awesome-paper-list-generator](https://github.com/billzyx/awesome-paper-list-generator), on 2023-05-04_
