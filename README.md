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
- 2022
	- [Speech- and Language-Based Classification of Alzheimer's Disease: A Systematic Review.](https://doi.org/10.3390/bioengineering9010027) - Inês Vigo, Luis Coelho, Sara S. Reis, Bioengineering, (2022), Cited By: 1
	- [A Systematic Review of Alzheimer's disease detection based on speech and natural language processing](https://doi.org/10.1109/RADIOELEKTRONIKA54537.2022.9764938) - Adam Ševčík, M. Rusko, 2022 32nd International Conference Radioelektronika (RADIOELEKTRONIKA), (2022), Cited By: 1
- 2020
	- [Artificial Intelligence, Speech, and Language Processing Approaches to Monitoring Alzheimer’s Disease: A Systematic Review](https://doi.org/10.3233/JAD-200888) - Sofia de la Fuente Garcia, C. Ritchie, S. Luz, Journal of Alzheimer's disease : JAD, (2020), Cited By: 39
- 2018
	- [A Review of Alzheimer's Disease Classification Using Neuropsychological Data and Machine Learning](https://doi.org/10.1109/CISP-BMEI.2018.8633126) - Gang Lyu, 2018 11th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI), (2018), Cited By: 8

### 2. Special challenges

#### a. ADReSS 2020 InterSpeech
- 2020
	- [Multiscale System for Alzheimer's Dementia Recognition Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2781) - E. Edwards, Charles Dognin, B. Bollepalli, M. Singh, INTERSPEECH, (2020), Cited By: 12
	- [A Comparison of Acoustic and Linguistics Methodologies for Alzheimer's Dementia Recognition](https://doi.org/10.21437/interspeech.2020-2635) - N. Cummins, Yilin Pan, Zhao Ren, J. Fritsch, Venkata Srikanth Nallanthighal, H. Christensen, D. Blackburn, Björn Schuller, M. Magimai.-Doss, H. Strik, Aki Härmä, INTERSPEECH, (2020), Cited By: 24
	- [Using State of the Art Speaker Recognition and Natural Language Processing Technologies to Detect Alzheimer's Disease and Assess its Severity](https://doi.org/10.21437/interspeech.2020-2587) - R. Pappagari, Jaejin Cho, L. Moro-Velázquez, N. Dehak, INTERSPEECH, (2020), Cited By: 24
	- [To BERT or Not To BERT: Comparing Speech and Language-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2020-2557) - Aparna Balagopalan, Benjamin Eyre, F. Rudzicz, Jekaterina Novikova, INTERSPEECH, (2020), Cited By: 42
	- [Comparing Natural Language Processing Techniques for Alzheimer's Dementia Prediction in Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2729) - T. Searle, Zina M. Ibrahim, R. Dobson, INTERSPEECH, (2020), Cited By: 14
	- [Exploring MMSE Score Prediction Using Verbal and Non-Verbal Cues](https://doi.org/10.21437/interspeech.2020-3085) - S. Farzana, Natalie Parde, INTERSPEECH, (2020), Cited By: 7
	- [Multimodal Inductive Transfer Learning for Detection of Alzheimer's Dementia and its Severity](https://doi.org/10.21437/interspeech.2020-3137) - Utkarsh Sarawgi, Wazeer Zulfikar, Nouran Soliman, P. Maes, INTERSPEECH, (2020), Cited By: 23
	- [Automated Screening for Alzheimer's Dementia Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-3158) - Muhammad Shehram Shah Syed, Zafi Sherhan Syed, M. Lech, E. Pirogova, INTERSPEECH, (2020), Cited By: 27
	- [Tackling the ADReSS Challenge: A Multimodal Approach to the Automated Recognition of Alzheimer's Dementia](https://doi.org/10.21437/interspeech.2020-2202) - Matej Martinc, Senja Pollak, INTERSPEECH, (2020), Cited By: 11
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, INTERSPEECH, (2020), Cited By: 32
	- [Alzheimer's Dementia Recognition through Spontaneous Speech: The ADReSS Challenge](https://doi.org/10.21437/interspeech.2020-2571) - S. Luz, F. Haider, Sofia de la Fuente, Davida Fromm, B. MacWhinney, INTERSPEECH, (2020), Cited By: 98
	- [Multi-Modal Fusion with Gating Using Audio, Lexical and Disfluency Features for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/Interspeech.2020-2721) - Morteza Rohanian, J. Hough, Matthew Purver, INTERSPEECH, (2020), Cited By: 26

#### b. ADReSS 2020 Frontiers
- 2021
	- [Temporal Integration of Text Transcripts and Acoustic Features for Alzheimer's Diagnosis Based on Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.642647) - Matej Martinc, F. Haider, Senja Pollak, S. Luz, Frontiers in Aging Neuroscience, (2021), Cited By: 5
	- [Language Impairment in Alzheimer’s Disease—Robust and Explainable Evidence for AD-Related Deterioration of Spontaneous Speech Through Multilingual Machine Learning](https://doi.org/10.3389/fnagi.2021.642033) - Hali Lindsay, J. Tröger, A. König, Frontiers in Aging Neuroscience, (2021), Cited By: 2
	- [Acoustic and Language Based Deep Learning Approaches for Alzheimer's Dementia Detection From Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.623607) - P. Mahajan, V. Baths, Frontiers in Aging Neuroscience, (2021), Cited By: 12
	- [Cognitive and Structural Correlates of Conversational Speech Timing in Mild Cognitive Impairment and Mild-to-Moderate Alzheimer’s Disease: Relevance for Early Detection Approaches](https://doi.org/10.3389/fnagi.2021.637404) - C. De Looze, Amir Dehsarvi, L. Crosby, Aisling Vourdanou, R. Coen, B. Lawlor, R. Reilly, Frontiers in Aging Neuroscience, (2021), Cited By: 1
	- [Classifying Alzheimer's Disease Using Audio and Text-Based Representations of Speech](https://doi.org/10.3389/fpsyg.2020.624137) - R'mani Haulcy, James R. Glass, Frontiers in Psychology, (2021), Cited By: 11
	- [Recognition of Alzheimer’s Dementia From the Transcriptions of Spontaneous Speech Using fastText and CNN Models](https://doi.org/10.3389/fcomp.2021.624558) - Amit Meghanani, S. AnoopC., A. Ramakrishnan, Frontiers in Computer Science, (2021), Cited By: 3
	- [Towards Computer-Based Automated Screening of Dementia Through Spontaneous Speech](https://doi.org/10.3389/fpsyg.2020.623237) - K. Chlasta, K. Wołk, Frontiers in Psychology, (2021), Cited By: 4
	- [Multimodal Capture of Patient Behaviour for Improved Detection of Early Dementia: Clinical Feasibility and Preliminary Results](https://doi.org/10.3389/fcomp.2021.642633) - Patrik Jonell, Birger Moëll, K. Håkansson, G. Henter, Taras Kuchurenko, O. Mikheeva, G. Hagman, Jasper Holleman, M. Kivipelto, H. Kjellström, Joakim Gustafson, J. Beskow, Frontiers in Computer Science, (2021), Cited By: 3
	- [Using a Discourse Task to Explore Semantic Ability in Persons With Cognitive Impairment](https://doi.org/10.3389/fnagi.2020.607449) - M. Antonsson, Kristina Lundholm Fors, M. Eckerström, D. Kokkinakis, Frontiers in Aging Neuroscience, (2021), Cited By: 2
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - Jiahong Yuan, Xingyu Cai, Yuchen Bian, Z. Ye, Kenneth Ward Church, Frontiers in Computer Science, (2021), Cited By: 6
	- [Editorial: Alzheimer’s Dementia Recognition through Spontaneous Speech](https://doi.org/10.3389/fcomp.2021.780169) - S. Luz, F. Haider, Sofia de la Fuente Garcia, Davida Fromm, B. MacWhinney, Frontiers in Computer Science, (2021), Cited By: 3
	- [Exploring Deep Transfer Learning Techniques for Alzheimer’s Dementia Detection](https://doi.org/10.3389/fcomp.2021.624683) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Frontiers in Computer Science, (2021), Cited By: 8
	- [A Comparison of Connected Speech Tasks for Detecting Early Alzheimer’s Disease and Mild Cognitive Impairment Using Natural Language Processing and Machine Learning](https://doi.org/10.3389/fcomp.2021.634360) - Natasha Clarke, T. Barrick, P. Garrard, Frontiers in Computer Science, (2021), Cited By: 6
	- [Towards an Automatic Speech-Based Diagnostic Test for Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2021.624594) - Roozbeh Sadeghian, J. D. Schaffer, S. Zahorian, Frontiers in Computer Science, (2021), Cited By: 2
	- [Alzheimer’s Dementia Recognition From Spontaneous Speech Using Disfluency and Interactional Features](https://doi.org/10.3389/fcomp.2021.640669) - Shamila Nasreen, Morteza Rohanian, J. Hough, Matthew Purver, Frontiers in Computer Science, (2021), Cited By: 8
	- [Analysis and Classification of Word Co-Occurrence Networks From Alzheimer’s Patients and Controls](https://doi.org/10.3389/fcomp.2021.649508) - Tristan Millington, S. Luz, Frontiers in Computer Science, (2021), Cited By: 5
	- [Learning Language and Acoustic Models for Identifying Alzheimer’s Dementia From Speech](https://doi.org/10.3389/fcomp.2021.624659) - Zehra Shah, Jeffrey Sawalha, Mashrura Tasnim, S. Qi, Eleni Stroulia, R. Greiner, Frontiers in Computer Science, (2021), Cited By: 7
	- [Comparing Pre-trained and Feature-Based Models for Prediction of Alzheimer's Disease Based on Speech](https://doi.org/10.3389/fnagi.2021.635945) - Aparna Balagopalan, Benjamin Eyre, Jessica Robin, F. Rudzicz, Jekaterina Novikova, Frontiers in Aging Neuroscience, (2021), Cited By: 9
	- [Crossing the “Cookie Theft” Corpus Chasm: Applying What BERT Learns From Outside Data to the ADReSS Challenge Dementia Detection Task](https://doi.org/10.3389/fcomp.2021.642517) - Yue Guo, Changye Li, Carol L. Roan, Serguei V. S. Pakhomov, T. Cohen, Frontiers in Computer Science, (2021), Cited By: 5
- 2020
	- [Longitudinal Speech Biomarkers for Automated Alzheimer's Detection](https://doi.org/10.3389/fcomp.2021.624694) - Jordi Laguarta, B. Subirana, Frontiers in Computer Science, (2020), Cited By: 12
	- [Dual-Task Training Affect Cognitive and Physical Performances and Brain Oscillation Ratio of Patients With Alzheimer’s Disease: A Randomized Controlled Trial](https://doi.org/10.3389/fnagi.2020.605317) - Elnaz Parvin, F. Mohammadian, Sadegh Amani-shalamzari, M. Bayati, Behnaz Tazesh, Frontiers in Aging Neuroscience, (2020), Cited By: 6

#### c. ADReSSo 2021
- 2021
	- [Using the Outputs of Different Automatic Speech Recognition Paradigms for Acoustic- and BERT-Based Alzheimer's Dementia Detection Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1519) - Yilin Pan, B. Mirheidari, Jennifer M. Harris, J. Thompson, Matthew Jones, J. Snowden, Daniel Blackburn, H. Christensen, Interspeech, (2021), Cited By: 8
	- [Automatic Detection and Assessment of Alzheimer Disease Using Speech and Language Technologies in Low-Resource Scenarios](https://doi.org/10.21437/interspeech.2021-1850) - R. Pappagari, Jaejin Cho, Sonal Joshi, L. Moro-Velázquez, Piotr Żelasko, J. Villalba, N. Dehak, Interspeech, (2021), Cited By: 8
	- [WavBERT: Exploiting Semantic and Non-Semantic Speech Using Wav2vec and BERT for Dementia Detection](https://doi.org/10.21437/interspeech.2021-332) - Youxiang Zhu, Abdelrahman Obyat, Xiaohui Liang, J. Batsis, R. Roth, Interspeech, (2021), Cited By: 6
	- [Tackling the ADRESSO Challenge 2021: The MUET-RMIT System for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1572) - Zafi Sherhan Syed, Muhammad Shehram Shah Syed, M. Lech, E. Pirogova, Interspeech, (2021), Cited By: 3
	- [Automatic Detection of Alzheimer's Disease Using Spontaneous Speech Only](https://doi.org/10.21437/interspeech.2021-2002) - Jun Chen, Jieping Ye, Fengyi Tang, Jiayu Zhou, Interspeech, (2021), Cited By: 2
	- [Alzheimer's Disease Detection from Spontaneous Speech through Combining Linguistic Complexity and (Dis)Fluency Features with Pretrained Language Models](https://doi.org/10.21437/interspeech.2021-1415) - Y. Qiao, Xuefeng Yin, Daniel Wiechmann, Elma Kerz, Interspeech, (2021), Cited By: 3
	- [Comparing Acoustic-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2021-759) - Aparna Balagopalan, Jekaterina Novikova, Interspeech, (2021), Cited By: 6
	- [Influence of the Interviewer on the Automatic Assessment of Alzheimer's Disease in the Context of the ADReSSo Challenge](https://doi.org/10.21437/interspeech.2021-1589) - P. A. Pérez-Toro, S. Bayerl, T. Arias-Vergara, J.C. Vásquez-Correa, P. Klumpp, M. Schuster, E. Nöth, J. R. Orozco-Arroyave, K. Riedhammer, Interspeech, (2021), Cited By: 3
	- [Alzheimer Disease Recognition Using Speech-Based Embeddings From Pre-Trained Models](https://doi.org/10.21437/interspeech.2021-753) - Lara Gauder, Leonardo Pepino, L. Ferrer, P. Riera, Interspeech, (2021), Cited By: 6
	- [Detecting cognitive decline using speech only: The ADReSSo Challenge](https://doi.org/10.1101/2021.03.24.21254263) - S. Luz, F. Haider, Sofia de la Fuente, Davida Fromm, B. MacWhinney, medRxiv, (2021), Cited By: 31
	- [Alzheimer's Dementia Recognition Using Acoustic, Lexical, Disfluency and Speech Pause Features Robust to Noisy Inputs](https://doi.org/10.21437/interspeech.2021-1633) - Morteza Rohanian, J. Hough, Matt Purver, Interspeech, (2021), Cited By: 10
	- [Modular Multi-Modal Attention Network for Alzheimer's Disease Detection Using Patient Audio and Language Data](https://doi.org/10.21437/interspeech.2021-2024) - Ning Wang, Yupeng Cao, Shuai Hao, Zongru Shao, K.P. Subbalakshmi, Interspeech, (2021), Cited By: 4

### 3. Novel research topics in dementia

#### ASR
- 2022
	- [Evaluating Web-Based Automatic Transcription for Alzheimer Speech Data: Transcript Comparison and Machine Learning Analysis.](https://doi.org/10.2196/33460) - Thomas Soroski, Thiago da Cunha Vasco, Sally May Newton‐Mason, Saffrin Granby, Caitlin Lewis, Anuj Harisinghani, Matteo Rizzo, C. Conati, Gabriel Murray, G. Carenini, Thalia S. Field, Hyeju Jang, JMIR aging, (2022), Cited By: 0
	- [Conformer Based Elderly Speech Recognition System for Alzheimer's Disease Detection](https://doi.org/10.48550/arXiv.2206.13232) - Tianzi Wang, Jiajun Deng, Mengzhe Geng, Zi Ye, Shoukang Hu, Yi Wang, Mingyu Cui, Zengrui Jin, Xunying Liu, Helen M. Meng, Interspeech 2022, (2022), Cited By: 1
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, TSD, (2022), Cited By: 0
- 2020
	- [Improving Detection of Alzheimer's Disease Using Automatic Speech Recognition to Identify High-Quality Segments for More Robust Feature Extraction](https://doi.org/10.21437/interspeech.2020-2698) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, INTERSPEECH, (2020), Cited By: 5
- 2019
	- [Impact of ASR on Alzheimer’s Disease Detection: All Errors are Equal, but Deletions are More Equal than Others](https://doi.org/10.18653/v1/2020.wnut-1.21) - Aparna Balagopalan, Ksenia Shkaruta, Jekaterina Novikova, WNUT, (2019), Cited By: 6
- 2018
	- [A Speech Recognition-based Solution for the Automatic Detection of Mild Cognitive Impairment from Spontaneous Speech](https://doi.org/10.2174/1567205014666171121114930) - L. Tóth, I. Hoffmann, G. Gosztolya, V. Vincze, Gréta Szatlóczki, Zoltán Bánréti, M. Pákáski, J. Kálmán, Current Alzheimer research, (2018), Cited By: 106
- 2015
	- [Automatic detection of mild cognitive impairment from spontaneous speech using ASR](https://www.semanticscholar.org/paper/651fd60a871cd7f06511da049427cd7702965884) - L. Tóth, G. Gosztolya, V. Vincze, I. Hoffmann, Gréta Szatlóczki, Edit Biró, Fruzsina Zsura, M. Pákáski, J. Kálmán, INTERSPEECH, (2015), Cited By: 76

#### Data Augmentation
- 2022
	- [Data Augmentation for Dementia Detection in Spoken Language](https://doi.org/10.48550/arXiv.2206.12879) - Anna Hl'edikov'a, Dominika Woszczyk, Alican Acman, Soteris Demetriou, Björn Schuller, Interspeech 2022, (2022), Cited By: 0
- 2021
	- [Robustness and Sensitivity of BERT Models Predicting Alzheimer’s Disease from Text](https://doi.org/10.18653/v1/2021.wnut-1.37) - Jekaterina Novikova, WNUT, (2021), Cited By: 4
	- [Automatic Speech Classifier for Mild Cognitive Impairment and Early Dementia](https://doi.org/10.1145/3469089) - Flavio Bertini, Davide Allevi, Gianluca Lutero, D. Montesi, L. Calzà, ACM Trans. Comput. Heal., (2021), Cited By: 2
- 2020
	- [Data augmentation using generative networks to identify dementia](https://arxiv.org/abs/2004.05989) - B. Mirheidari, Yilin Pan, D. Blackburn, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, H. Christensen, ArXiv, (2020), Cited By: 1

#### Dialog Act
- 2020
	- [Modeling Dialogue in Conversational Cognitive Health Screening Interviews](https://www.semanticscholar.org/paper/cf0c7194c5342f4d167e95c54685f5f564a7d12b) - S. Farzana, Mohammad Valizadeh, Natalie Parde, LREC, (2020), Cited By: 4

#### Emotion
- 2021
	- [Audio-Visual Recognition of Emotional Engagement of People with Dementia](https://doi.org/10.21437/interspeech.2021-567) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, Interspeech, (2021), Cited By: 3
- 2020
	- [Towards Engagement Recognition of People with Dementia in Care Settings](https://doi.org/10.1145/3382507.3418856) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, ICMI, (2020), Cited By: 7

#### Explainable
- 2022
	- [Dementia Detection Using Language Models and Transfer Learning](https://doi.org/10.1145/3520084.3520108) - Mondher Bouazizi, Chuheng Zheng, T. Ohtsuki, ICSIM, (2022), Cited By: 0
- 2021
	- [Explainable Identification of Dementia From Transcripts Using Transformer Networks](https://doi.org/10.1109/JBHI.2022.3172479) - Loukas Ilias, D. Askounis, IEEE Journal of Biomedical and Health Informatics, (2021), Cited By: 2
	- [Towards Interpretability of Speech Pause in Dementia Detection Using Adversarial Learning](https://doi.org/10.1109/icassp43922.2022.9747006) - Youxiang Zhu, Bang Tran, Xiaohui Liang, J. Batsis, R. Roth, ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2021), Cited By: 0
- 2020
	- [Acoustic Feature Extraction with Interpretable Deep Neural Network for Neurodegenerative Related Disorder Classification](https://doi.org/10.21437/interspeech.2020-2684) - Yilin Pan, B. Mirheidari, Z. C. Tu, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, D. Blackburn, H. Christensen, INTERSPEECH, (2020), Cited By: 4
	- [Exploiting Fully Convolutional Network and Visualization Techniques on Spontaneous Speech for Dementia Detection](https://arxiv.org/abs/2008.07052) - Youxiang Zhu, Xiaohui Liang, ArXiv, (2020), Cited By: 2
- 2019
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, MLHC, (2019), Cited By: 10

#### Eye-tracking

#### Information Unit
- 2016
	- [Vector-space topic models for detecting Alzheimer’s disease](https://doi.org/10.18653/v1/P16-1221) - Maria Yancheva, F. Rudzicz, ACL, (2016), Cited By: 46

#### Intermediate Pretraining
- 2022
	- [Domain-aware Intermediate Pretraining for Dementia Detection with Limited Data](https://doi.org/10.21437/interspeech.2022-10862) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Interspeech 2022, (2022), Cited By: 0

#### Novel Speech Tasks
- 2022
	- [Going Beyond the Cookie Theft Picture Test: Detecting Cognitive Impairments using Acoustic Features](https://doi.org/10.48550/arXiv.2206.05018) - Franziska Braun, Andreas Erzigkeit, H. Lehfeld, T. Hillemacher, K. Riedhammer, S. Bayerl, TSD, (2022), Cited By: 0

#### Pause&Disfluencies
- 2022
	- [How You Say It Matters: Measuring the Impact of Verbal Disfluency Tags on Automated Dementia Detection](https://doi.org/10.18653/v1/2022.bionlp-1.4) - S. Farzana, Ashwin Deshpande, Natalie Parde, BIONLP, (2022), Cited By: 0
- 2021
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - Jiahong Yuan, Xingyu Cai, Yuchen Bian, Z. Ye, Kenneth Ward Church, Frontiers in Computer Science, (2021), Cited By: 6
	- [Speech pause distribution as an early marker for Alzheimer's disease](https://doi.org/10.1101/2020.12.28.20248875) - P. Pastoriza-Domínguez, I. G. Torre, F. Diéguez-Vide, I. Gómez-Ruiz, S. Geladó, J. Bello-López, A. Ávila-Rivera, J. Matías‐Guiu, V. Pytel, A. Hernández-Fernández, medRxiv, (2021), Cited By: 6
- 2020
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, INTERSPEECH, (2020), Cited By: 32
	- [An Automated Approach to Examining Pausing in the Speech of People With Dementia](https://doi.org/10.1177/1533317520939773) - Rachel A. Sluis, Daniel Angus, Janet Wiles, A. Back, Tingting Amy Gibson, J. Liddle, Peter Worthy, D. Copland, A. Angwin, American journal of Alzheimer's disease and other dementias, (2020), Cited By: 9
- 2009
	- [Examining Pauses in Alzheimer's Discourse](https://doi.org/10.1177/1533317508328138) - B. Davis, M. Maclagan, American journal of Alzheimer's disease and other dementias, (2009), Cited By: 43

#### Perplexity
- 2019
	- [Detecting Alzheimer's Disease from Continuous Speech Using Language Models.](https://doi.org/10.3233/JAD-190452) - Zhiqiang Guo, Zhenhua Ling, Yunxia Li, Journal of Alzheimer's disease : JAD, (2019), Cited By: 11
	- [Perplexity – a new predictor of cognitive changes in spoken language? – results of the Interdisciplinary Longitudinal Study on Adult Development and Aging (ILSE)](https://doi.org/10.1515/lingvan-2018-0026) - C. Frankenberg, Jochen Weiner, Tanja Schultz, M. Knebel, C. Degen, H. Wahl, J. Schroeder, Linguistics Vanguard, (2019), Cited By: 18
- 2018
	- [Language Modelling for the Clinical Semantic Verbal Fluency Task](https://www.semanticscholar.org/paper/88188082df9ec54d05753d88f3b4f92f31f86a9e) - N. Linz, J. Tröger, Hali Lindsay, A. König, P. Robert, J. Peter, J. Alexandersson, , (2018), Cited By: 3

#### Speech and Writing
- 2021
	- [A Longitudinal Multi-modal Dataset for Dementia Monitoring and Diagnosis](https://arxiv.org/abs/2109.01537) - Dimitris Gkoumas, Bo Wang, A. Tsakalidis, M. Wolters, A. Zubiaga, Matthew Purver, M. Liakata, ArXiv, (2021), Cited By: 1

#### Telephone Interview
- 2022
	- [Accuracy of telephone screening tools to identify dementia patients remotely: systematic review](https://doi.org/10.1177/20542704221115956) - Charlotte Olivia Riley, B. McKinstry, K. Fairhurst, JRSM open, (2022), Cited By: 0
- 2021
	- [Dementia risks identified by vocal features via telephone conversations: A novel machine learning prediction model](https://doi.org/10.1371/journal.pone.0253988) - A. Shimoda, Yue Li, H. Hayashi, N. Kondo, PloS one, (2021), Cited By: 9
	- [Diagnostic accuracy of the telephone interview for cognitive status (TICS) for the detection of dementia in primary care in the Netherlands](https://doi.org/10.1002/alz.052760) - H. Abdulrahman, Alzheimer's & dementia : the journal of the Alzheimer's Association, (2021), Cited By: 0
- 2007
	- [Validation of the Telephone Interview for Cognitive Status (TICS) in Japanese](https://doi.org/10.1002/GPS.1812) - Y. Konagaya, Y. Washimi, H. Hattori, A. Takeda, Tomoyuki Watanabe, T. Ohta, International journal of geriatric psychiatry, (2007), Cited By: 31
- 1988
	- [The telephone interview for cognitive status](https://www.semanticscholar.org/paper/f29b4c35e8b57cebb570eaadbee1bdb95fd5d716) - J. Brandt, M. Spencer, M. Folstein, , (1988), Cited By: 653

#### Voice Assistant
- 2022
	- [Evaluating voice-assistant commands for dementia detection](https://doi.org/10.1016/j.csl.2021.101297) - Xiaohui Liang, J. Batsis, Youxiang Zhu, Tiffany Driesse, R. Roth, D. Kotz, B. MacWhinney, Comput. Speech Lang., (2022), Cited By: 1
	- [Alzheimer's Dementia Detection through Spontaneous Dialogue with Proactive Robotic Listeners](https://doi.org/10.1109/HRI53351.2022.9889375) - Yuanchao Li, Catherine Lai, Divesh Lala, Koji Inoue, T. Kawahara, 2022 17th ACM/IEEE International Conference on Human-Robot Interaction (HRI), (2022), Cited By: 1
- 2017
	- [An Avatar-Based System for Identifying Individuals Likely to Develop Dementia](https://doi.org/10.21437/INTERSPEECH.2017-690) - B. Mirheidari, D. Blackburn, K. Harkness, Traci Walker, A. Venneri, M. Reuber, H. Christensen, INTERSPEECH, (2017), Cited By: 23

### 4. Regular papers
- 2022
	- [Using Spectral Sequence-to-Sequence Autoencoders to Assess Mild Cognitive Impairment](https://doi.org/10.1109/icassp43922.2022.9746148) - Mercedes Vetráb, José Vicente Egas López, R. Balogh, N. Imre, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2022), Cited By: 0
	- [Automatic Selection of Discriminative Features for Dementia Detection in Cantonese-Speaking People](https://doi.org/10.21437/interspeech.2022-10122) - Xiaoquan Ke, M. Mak, Helen M. Meng, Interspeech 2022, (2022), Cited By: 0
	- [A Dementia Classification Based on Speech Analysis of Casual Talk During a Clinical Interview](https://doi.org/10.1109/LifeTech53646.2022.9754933) - Shunya Hanai, Shohei Kato, Takuto Sakuma, R. Ohdake, M. Masuda, Hirohisa Watanabe, 2022 IEEE 4th Global Conference on Life Sciences and Technologies (LifeTech), (2022), Cited By: 0
	- [Automated detection of mild cognitive impairment and dementia from voice recordings: A natural language processing approach.](https://doi.org/10.1002/alz.12721) - S. Amini, Boran Hao, Lifu Zhang, M. Song, Aman Gupta, C. Karjadi, V. Kolachalama, R. Au, I. Paschalidis, Alzheimer's & dementia : the journal of the Alzheimer's Association, (2022), Cited By: 0
	- [Cognitive Digital Biomarkers from Automated Transcription of Spoken Language](https://doi.org/10.14283/jpad.2022.66) - N. Tavabi, D. Stück, A. Signorini, C. Karjadi, T. A. Hanai, M. Sandoval, C. Lemke, J. Glass, S. Hardy, M. Lavallee, B. Wasserman, T. F. Ang, C. Nowak, R. Kainkaryam, L. Foschini, R. Au, The Journal of Prevention of Alzheimer's Disease, (2022), Cited By: 0
	- [Deep Learning Approaches for Detecting Alzheimer’s Dementia from Conversational Speech of ILSE Study](https://doi.org/10.21437/interspeech.2022-10942) - Ayimnisagul Ablimit, Karen Scholz, Tanja Schultz, Interspeech 2022, (2022), Cited By: 0
	- [A Pre-trained Neural Network to Predict Alzheimer’s Disease at an Early Stage](https://doi.org/10.14569/ijacsa.2022.0130524) - Ragavamsi Davuluri, Ragupathy Rengaswamy, International Journal of Advanced Computer Science and Applications, (2022), Cited By: 0
	- [Impact of Acoustic Noise on Alzheimer's Disease Detection from Speech: Should You Let Baby Cry?](https://doi.org/10.48550/arXiv.2203.17110) - Jekaterina Novikova, ArXiv, (2022), Cited By: 0
	- [Predicting Scores on the Mini-Mental State Examination (MMSE) from Spontaneous Speech](https://doi.org/10.3390/bs12090339) - A. Bueno-Cayo, Minerva del Rio Carmona, Rosa Castell-Enguix, Isabel Iborra-Marmolejo, Mike Murphy, T. Q. Irigaray, José Francisco Cervera, C. Moret-Tatay, Behavioral sciences, (2022), Cited By: 0
	- [A Transfer Learning Method for Detecting Alzheimer's Disease Based on Speech and Natural Language Processing](https://doi.org/10.3389/fpubh.2022.772592) - Ning-hong Liu, Kexue Luo, Zhenming Yuan, Yan Chen, Frontiers in Public Health, (2022), Cited By: 1
	- [Exploring Dementia Detection from Speech: Cross Corpus Analysis](https://doi.org/10.1109/icassp43922.2022.9747167) - Ayimnisagul Ablimit, Catarina Botelho, A. Abad, Tanja Schultz, I. Trancoso, ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2022), Cited By: 0
	- [An Evaluation on Information Composition in Dementia Detection Based on Speech](https://doi.org/10.1109/ACCESS.2022.3203068) - Chuheng Zheng, Mondher Bouazizi, T. Ohtsuki, IEEE Access, (2022), Cited By: 0
	- [Semantic Feature Extraction Using SBERT for Dementia Detection](https://doi.org/10.3390/brainsci12020270) - Yamanki Santander-Cruz, Sebastián Salazar-Colores, W. J. Paredes-García, Humberto Guendulain-Arenas, S. Tovar-Arriaga, Brain sciences, (2022), Cited By: 1
	- [Exploring linguistic feature and model combination for speech recognition based automatic AD detection](https://doi.org/10.48550/arXiv.2206.13758) - Yi Wang, Tianzi Wang, Zi Ye, Lingwei Meng, Shoukang Hu, Xixin Wu, Xunying Liu, Helen M. Meng, Interspeech 2022, (2022), Cited By: 1
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, TSD, (2022), Cited By: 0
- 2021
	- [Towards AI-powered Language Assessment Tools](https://doi.org/10.21203/RS.3.RS-246079/V1) - M. Parsa, Muhammad Raisul Alam, Alex Mihailidis, , (2021), Cited By: 1
	- [Detecting Alzheimer’s Disease from Speech Using Neural Networks with Bottleneck Features and Data Augmentation](https://doi.org/10.1109/ICASSP39728.2021.9413566) - Zhaoci Liu, Zhiqiang Guo, Zhenhua Ling, Yunxia Li, ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2021), Cited By: 2
	- [Multi-Task Estimation of Age and Cognitive Decline from Speech](https://doi.org/10.1109/ICASSP39728.2021.9414642) - Yilin Pan, Venkata Srikanth Nallanthighal, D. Blackburn, H. Christensen, Aki Härmä, ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2021), Cited By: 3
	- [Development of the Cuhk Elderly Speech Recognition System for Neurocognitive Disorder Detection Using the Dementiabank Corpus](https://doi.org/10.1109/ICASSP39728.2021.9413634) - Zi Ye, Shoukang Hu, Jinchao Li, Xurong Xie, Mengzhe Geng, Jianwei Yu, Junhao Xu, Boyang Xue, Shansong Liu, Xunying Liu, H. Meng, ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2021), Cited By: 16
	- [Detecting Dementia from Speech and Transcripts using Transformers](https://arxiv.org/abs/2110.14769) - Loukas Ilias, D. Askounis, J. Psarras, ArXiv, (2021), Cited By: 2
	- [Identifying Cognitive Impairment Using Sentence Representation Vectors](https://doi.org/10.21437/interspeech.2021-915) - B. Mirheidari, Yilin Pan, Daniel Blackburn, R. O'Malley, H. Christensen, Interspeech, (2021), Cited By: 2
	- [An Evaluation of Machine Learning Classifiers for Prediction of Alzheimer's Disease, Mild Cognitive Impairment and Normal Cognition](https://doi.org/10.1109/ICTC52510.2021.9620780) - Payam Hosseinzadeh Kasani, Sara Hosseinzadeh Kasani, Yeshin Kim, C. Yun, S. Choi, Jae-Won Jang, 2021 International Conference on Information and Communication Technology Convergence (ICTC), (2021), Cited By: 1
	- [Linguistic Parameters of Spontaneous Speech for Identifying Mild Cognitive Impairment and Alzheimer Disease](https://doi.org/10.1162/coli_a_00428) - V. Vincze, Martina Katalin Szabó, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, CL, (2021), Cited By: 2
	- [Correlating natural language processing and automated speech analysis with clinician assessment to quantify speech-language changes in mild cognitive impairment and Alzheimer’s dementia](https://doi.org/10.1186/s13195-021-00848-x) - Anthony Yeung, A. Iaboni, E. Rochon, M. Lavoie, Calvin Santiago, Maria Yancheva, Jekaterina Novikova, Mengdan Xu, Jessica Robin, Liam D. Kaufman, Fariya Mostafa, Alzheimer's research & therapy, (2021), Cited By: 13
	- [A Comparative Study of Acoustic and Linguistic Features Classification for Alzheimer's Disease Detection](https://doi.org/10.1109/ICASSP39728.2021.9414147) - Jinchao Li, Jianwei Yu, Zi Ye, Simon Wong, M. Mak, B. Mak, Xunying Liu, Helen M. Meng, ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2021), Cited By: 10
	- [Exploring neural models for predicting dementia from language](https://doi.org/10.1016/J.CSL.2020.101181) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Comput. Speech Lang., (2021), Cited By: 2
	- [Exploiting linguistic information from Nepali transcripts for early detection of Alzheimer's disease using natural language processing and machine learning techniques](https://doi.org/10.1016/j.ijhcs.2021.102761) - Surabhi Adhikari, Surendrabikram Thapa, Usman Naseem, Priyanka Singh, H. Huo, Gnana Bharathy, Mukesh Prasad, Int. J. Hum. Comput. Stud., (2021), Cited By: 3
- 2020
	- [Transformer-based deep neural network language models for Alzheimer’s disease detection from targeted speech](https://doi.org/10.21203/rs.3.rs-49267/v1) - A. Roshanzamir, H. Aghajan, M. Baghshah, , (2020), Cited By: 1
	- [Uncertainty-Aware Multi-Modal Ensembling for Severity Prediction of Alzheimer's Dementia](https://arxiv.org/abs/2010.01440) - Utkarsh Sarawgi, Wazeer Zulfikar, Rishab Khincha, P. Maes, ArXiv, (2020), Cited By: 1
	- [An Assessment of Paralinguistic Acoustic Features for Detection of Alzheimer's Dementia in Spontaneous Speech](https://doi.org/10.1109/JSTSP.2019.2955022) - F. Haider, S. de la Fuente, S. Luz, IEEE Journal of Selected Topics in Signal Processing, (2020), Cited By: 57
	- [Combining Prosodic, Voice Quality and Lexical Features to Automatically Detect Alzheimer's Disease](https://arxiv.org/abs/2011.09272) - Mireia Farr'us, Joan Codina-Filbà, ArXiv, (2020), Cited By: 4
	- [Predicting Prodromal Dementia Using Linguistic Patterns and Deficits](https://doi.org/10.1109/ACCESS.2020.3029907) - Ahmed H. Alkenani, Yuefeng Li, Yue Xu, Qing Zhang, IEEE Access, (2020), Cited By: 2
	- [Using narratives in differential diagnosis of neurodegenerative syndromes.](https://doi.org/10.1016/j.jcomdis.2020.105994) - Yasmeen Faroqi-Shah, Ashlyn Treanor, N. Ratner, B. Ficek, K. Webster, K. Tsapkini, Journal of communication disorders, (2020), Cited By: 6
	- [Linguistic markers predict onset of Alzheimer's disease](https://doi.org/10.1016/j.eclinm.2020.100583) - Elif Eyigoz, Sachin Mathur, Mar Santamaria, G. Cecchi, M. Naylor, EClinicalMedicine, (2020), Cited By: 46
- 2019
	- [Multilingual prediction of Alzheimer’s disease through domain adaptation and concept-based language modelling](https://doi.org/10.18653/v1/N19-1367) - Kathleen C. Fraser, N. Linz, Bai Li, K. L. Fors, F. Rudzicz, A. König, J. Alexandersson, P. Robert, D. Kokkinakis, NAACL, (2019), Cited By: 11
	- [Multilingual word embeddings for the assessment of narrative speech in mild cognitive impairment](https://doi.org/10.1016/j.csl.2018.07.005) - Kathleen C. Fraser, K. L. Fors, D. Kokkinakis, Comput. Speech Lang., (2019), Cited By: 34
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, MLHC, (2019), Cited By: 10
	- [Automatic Hierarchical Attention Neural Network for Detecting AD](https://doi.org/10.21437/interspeech.2019-1799) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, INTERSPEECH, (2019), Cited By: 19
	- [Detecting dementia in Mandarin Chinese using transfer learning from a parallel corpus](https://doi.org/10.18653/v1/N19-1199) - Bai Li, Y. Hsu, F. Rudzicz, NAACL, (2019), Cited By: 8
	- [Detecting Alzheimer's Disease by estimating attention and elicitation path through the alignment of spoken picture descriptions with the picture prompt](https://arxiv.org/abs/1910.00515) - B. Mirheidari, Yilin Pan, Traci Walker, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, ArXiv, (2019), Cited By: 5
	- [An Automatic Assessment System for Alzheimer’s Disease Based on Speech Using Feature Sequence Generator and Recurrent Neural Network](https://doi.org/10.1038/s41598-019-56020-x) - Yi-Wei Chien, Sheng-Yi Hong, W. Cheah, Li-Hung Yao, Yu-Ling Chang, L. Fu, Scientific Reports, (2019), Cited By: 22
	- [Predicting MCI Status From Multimodal Language Data Using Cascaded Classifiers](https://doi.org/10.3389/fnagi.2019.00205) - Kathleen C. Fraser, Kristina Lundholm Fors, M. Eckerström, Fredrik Öhman, D. Kokkinakis, Front. Aging Neurosci., (2019), Cited By: 33
	- [Automatic Diagnosis of Alzheimer’s Disease Using Neural Network Language Models](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, Sebastian Wankerl, E. Nöth, ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2019), Cited By: 27
	- [An Attention-Based Hybrid Network for Automatic Detection of Alzheimer's Disease from Narrative Speech](https://doi.org/10.21437/interspeech.2019-2872) - Jun Chen, Ji Zhu, Jieping Ye, INTERSPEECH, (2019), Cited By: 20
- 2018
	- [Augmenting word2vec with latent Dirichlet allocation within a clinical application](https://doi.org/10.18653/v1/N19-1414) - Akshay Budhkar, F. Rudzicz, NAACL, (2018), Cited By: 8
	- [Detecting cognitive impairments by agreeing on interpretations of linguistic features](https://doi.org/10.18653/v1/N19-1146) - Zining Zhu, Jekaterina Novikova, F. Rudzicz, NAACL, (2018), Cited By: 22
	- [Speech Processing for Early Alzheimer Disease Diagnosis: Machine Learning Based Approach](https://doi.org/10.1109/aiccsa.2018.8612831) - Randa Ben Ammar, Yassine Ben Ayed, 2018 IEEE/ACS 15th International Conference on Computer Systems and Applications (AICCSA), (2018), Cited By: 9
	- [Detecting Signs of Dementia Using Word Vector Representations](https://doi.org/10.21437/Interspeech.2018-1764) - B. Mirheidari, D. Blackburn, Traci Walker, A. Venneri, M. Reuber, H. Christensen, INTERSPEECH, (2018), Cited By: 37
	- [Deep language space neural network for classifying mild cognitive impairment and Alzheimer-type dementia](https://doi.org/10.1371/journal.pone.0205636) - S. Orimaye, Jojo Sze-Meng Wong, Chee Piau Wong, PloS one, (2018), Cited By: 32
	- [Detecting Alzheimer's Disease Using Gated Convolutional Neural Network from Audio Data](https://doi.org/10.21437/Interspeech.2018-1713) - Tifani Warnita, Nakamasa Inoue, K. Shinoda, INTERSPEECH, (2018), Cited By: 24
	- [Learning multiview embeddings for assessing dementia](https://doi.org/10.18653/v1/D18-1304) - C. Pou-Prom, F. Rudzicz, EMNLP, (2018), Cited By: 13
- 2017
	- [Longitudinal Monitoring and Detection of Alzheimer's Type Dementia from Spontaneous Speech Data](https://doi.org/10.1109/CBMS.2017.41) - S. Luz, 2017 IEEE 30th International Symposium on Computer-Based Medical Systems (CBMS), (2017), Cited By: 29
	- [INVESTIGATING PREDICTORS OF COGNITIVE DECLINE USING MACHINE LEARNING](https://doi.org/10.1016/j.jalz.2017.06.1257) - R. Casanova, Santiago Saldana, M. Lutz, B. Plassman, M. Kuchibhatla, K. Hayden, Alzheimer's & Dementia, (2017), Cited By: 24
- 2016
	- [Detecting Mild Cognitive Impairment from Spontaneous Speech by Correlation-Based Phonetic Feature Selection](https://doi.org/10.21437/Interspeech.2016-384) - G. Gosztolya, L. Tóth, Tamás Grósz, V. Vincze, I. Hoffmann, Gréta Szatlóczki, M. Pákáski, J. Kálmán, INTERSPEECH, (2016), Cited By: 29
- 2015
	- [Linguistic Features Identify Alzheimer's Disease in Narrative Speech.](https://doi.org/10.3233/JAD-150520) - Kathleen C. Fraser, J. Meltzer, F. Rudzicz, Journal of Alzheimer's disease : JAD, (2015), Cited By: 419

### 5. Related works in other domains

#### Aphasia
- 2020
	- [BlaBla: Linguistic Feature Extraction for Clinical Analysis in Multiple Languages](https://doi.org/10.21437/interspeech.2020-2880) - Abhishek Shivkumar, J. Weston, R. Lenain, E. Fristed, INTERSPEECH, (2020), Cited By: 1

#### Asthma
- 2020
	- [Analysis of Acoustic Features for Speech Sound Based Classification of Asthmatic and Healthy Subjects](https://doi.org/10.1109/ICASSP40776.2020.9054062) - Shivani Yadav, Merugu Keerthana, D. Gope, U. Krishnaswamy, P. Ghosh, ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2020), Cited By: 12

#### Disfluency
- 2020
	- [Re-framing Incremental Deep Language Models for Dialogue Processing with Multi-task Learning](https://doi.org/10.18653/V1/2020.COLING-MAIN.43) - Morteza Rohanian, J. Hough, COLING, (2020), Cited By: 3
- 2019
	- [Neural Constituency Parsing of Speech Transcripts](https://doi.org/10.18653/v1/N19-1282) - Paria Jamshid Lou, Yufei Wang, Mark Johnson, NAACL, (2019), Cited By: 13

#### Parkinson’s Disease
- 2021
	- [Supervised Speech Representation Learning for Parkinson's Disease Classification](https://arxiv.org/abs/2106.00531) - Parvaneh Janbakhshi, I. Kodrasi, ITG Conference on Speech Communication, (2021), Cited By: 2
- 2020
	- [Using X-Vectors to Automatically Detect Parkinson’s Disease from Speech](https://doi.org/10.1109/ICASSP40776.2020.9053770) - L. Moro-Velázquez, J. Villalba, N. Dehak, ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), (2020), Cited By: 22


***

_This file was generated by [awesome-paper-list-generator](https://github.com/billzyx/awesome-paper-list-generator), on 2022-10-05_
