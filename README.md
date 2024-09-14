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
	- [AI and Non AI Assessments for Dementia](https://doi.org/10.48550/arXiv.2307.01210) - M. Parsapoor, Hamed Ghodrati, Vincenzo Dentamaro, C. Madan, Ioulietta Lazarou, S. Nikolopoulos, Y. Kompatsiaris, arXiv.org, (2023), Cited By: 2
	- [Machine Learning for Dementia Prediction: A Systematic Review and Future Research Directions](https://doi.org/10.1007/s10916-023-01906-7) - Ashir Javeed, A. Dallora, J. Berglund, Arif Ali, Liaqat Ali, P. Anderberg, Journal of medical systems, (2023), Cited By: 45
	- [DementiaBank: Theoretical Rationale, Protocol, and Illustrative Analyses](https://doi.org/10.1044/2022_AJSLP-22-00281) - Alyssa M. Lanzi, Anna K Saylor, Davida Fromm, Houjun Liu, B. MacWhinney, Matthew L. Cohen, American Journal of Speech-Language Pathology, (2023), Cited By: 20
	- [Speech and language processing with deep learning for dementia diagnosis: A systematic review](https://doi.org/10.1016/j.psychres.2023.115538) - Mengke Shi, G. Cheung, Seyed Reza Shahamiri, Psychiatry Research, (2023), Cited By: 2
	- [Noninvasive automatic detection of Alzheimer's disease from spontaneous speech: a review](https://doi.org/10.3389/fnagi.2023.1224723) - Xiaoke Qi, Qing Zhou, Jian Dong, Wei Bao, Frontiers in Aging Neuroscience, (2023), Cited By: 0
	- [A Review of Alzheimer’s Disease Detection from Spontaneous Speech and Text](https://doi.org/10.1109/ICCC57789.2023.10165507) - M. K. Vrindha, V. Geethu, P. R. Anurenjan, S. Deepak, K. G. Sreeni, International Conference on Innovative Computing and Cloud Computing, (2023), Cited By: 0
- 2022
	- [Deep learning-based speech analysis for Alzheimer’s disease detection: a literature review](https://doi.org/10.1186/s13195-022-01131-3) - Qin Yang, Xin Li, Xinyun Ding, Feiyang Xu, Zhenhua Ling, Alzheimer's Research & Therapy, (2022), Cited By: 25
	- [Speech- and Language-Based Classification of Alzheimer’s Disease: A Systematic Review](https://doi.org/10.3390/bioengineering9010027) - Inês Vigo, Luís Coelho, Sara S. Reis, Bioengineering, (2022), Cited By: 25
	- [A Systematic Review of Alzheimer's disease detection based on speech and natural language processing](https://doi.org/10.1109/RADIOELEKTRONIKA54537.2022.9764938) - A. Ševčík, M. Rusko, International Conference Radioelektronika, (2022), Cited By: 4
- 2020
	- [Artificial Intelligence, Speech, and Language Processing Approaches to Monitoring Alzheimer’s Disease: A Systematic Review](https://doi.org/10.3233/JAD-200888) - Sofia de la Fuente Garcia, C. Ritchie, S. Luz, Journal of Alzheimer's Disease, (2020), Cited By: 124
- 2018
	- [A Review of Alzheimer's Disease Classification Using Neuropsychological Data and Machine Learning](https://doi.org/10.1109/CISP-BMEI.2018.8633126) - Gang Lyu, 2018 11th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI), (2018), Cited By: 11

### 2. Special challenges

#### a. ADReSS 2020 InterSpeech
- 2020
	- [The INESC-ID Multi-Modal System for the ADReSS 2020 Challenge](https://doi.org/10.21437/interspeech.2020-2833) - A. Pompili, T. Rolland, A. Abad, Interspeech, (2020), Cited By: 34
	- [Multiscale System for Alzheimer's Dementia Recognition Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2781) - E. Edwards, Charles Dognin, Bajibabu Bollepalli, M. Singh, Interspeech, (2020), Cited By: 31
	- [A Comparison of Acoustic and Linguistics Methodologies for Alzheimer's Dementia Recognition](https://doi.org/10.21437/interspeech.2020-2635) - N. Cummins, Yilin Pan, Zhao Ren, J. Fritsch, Venkata Srikanth Nallanthighal, H. Christensen, D. Blackburn, Björn Schuller, M. Magimai-Doss, H. Strik, Aki Härmä, Interspeech, (2020), Cited By: 51
	- [Using State of the Art Speaker Recognition and Natural Language Processing Technologies to Detect Alzheimer's Disease and Assess its Severity](https://doi.org/10.21437/interspeech.2020-2587) - R. Pappagari, Jaejin Cho, L. Moro-Velázquez, N. Dehak, Interspeech, (2020), Cited By: 56
	- [To BERT or Not To BERT: Comparing Speech and Language-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2020-2557) - Aparna Balagopalan, Benjamin Eyre, Frank Rudzicz, Jekaterina Novikova, Interspeech, (2020), Cited By: 106
	- [Comparing Natural Language Processing Techniques for Alzheimer's Dementia Prediction in Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-2729) - Thomas Searle, Zina M. Ibrahim, R. Dobson, Interspeech, (2020), Cited By: 36
	- [Exploring MMSE Score Prediction Using Verbal and Non-Verbal Cues](https://doi.org/10.21437/interspeech.2020-3085) - Shahla Farzana, Natalie Parde, Interspeech, (2020), Cited By: 19
	- [Multimodal Inductive Transfer Learning for Detection of Alzheimer's Dementia and its Severity](https://doi.org/10.21437/interspeech.2020-3137) - U. Sarawgi, W. Zulfikar, Nouran Soliman, P. Maes, Interspeech, (2020), Cited By: 51
	- [Automated Screening for Alzheimer's Dementia Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2020-3158) - Muhammad Shehram Shah Syed, Zafi Sherhan Syed, M. Lech, E. Pirogova, Interspeech, (2020), Cited By: 57
	- [Tackling the ADReSS Challenge: A Multimodal Approach to the Automated Recognition of Alzheimer's Dementia](https://doi.org/10.21437/interspeech.2020-2202) - Matej Martinc, S. Pollak, Interspeech, (2020), Cited By: 29
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, Interspeech, (2020), Cited By: 85
	- [Alzheimer's Dementia Recognition through Spontaneous Speech: The ADReSS Challenge](https://doi.org/10.21437/interspeech.2020-2571) - S. Luz, F. Haider, S. D. L. Fuente, Davida Fromm, B. MacWhinney, Interspeech, (2020), Cited By: 215
	- [Exploiting Multi-Modal Features From Pre-trained Networks for Alzheimer's Dementia Recognition](https://doi.org/10.21437/interspeech.2020-3153) - Junghyun Koo, Jie Hwan Lee, Jaewoo Pyo, Yujin Jo, Kyogu Lee, Interspeech, (2020), Cited By: 41
	- [Multi-Modal Fusion with Gating Using Audio, Lexical and Disfluency Features for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/Interspeech.2020-2721) - Morteza Rohanian, Julian Hough, Matthew Purver, Interspeech, (2020), Cited By: 52

#### b. ADReSS 2020 Frontiers
- 2021
	- [Temporal Integration of Text Transcripts and Acoustic Features for Alzheimer's Diagnosis Based on Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.642647) - Matej Martinc, F. Haider, S. Pollak, S. Luz, Frontiers in Aging Neuroscience, (2021), Cited By: 33
	- [Language Impairment in Alzheimer’s Disease—Robust and Explainable Evidence for AD-Related Deterioration of Spontaneous Speech Through Multilingual Machine Learning](https://doi.org/10.3389/fnagi.2021.642033) - Hali Lindsay, J. Tröger, A. König, Frontiers in Aging Neuroscience, (2021), Cited By: 33
	- [Acoustic and Language Based Deep Learning Approaches for Alzheimer's Dementia Detection From Spontaneous Speech](https://doi.org/10.3389/fnagi.2021.623607) - Pranav Mahajan, V. Baths, Frontiers in Aging Neuroscience, (2021), Cited By: 46
	- [Cognitive and Structural Correlates of Conversational Speech Timing in Mild Cognitive Impairment and Mild-to-Moderate Alzheimer’s Disease: Relevance for Early Detection Approaches](https://doi.org/10.3389/fnagi.2021.637404) - Céline De Looze, Amir Dehsarvi, L. Crosby, Aisling Vourdanou, R. Coen, B. Lawlor, R. Reilly, Frontiers in Aging Neuroscience, (2021), Cited By: 7
	- [Classifying Alzheimer's Disease Using Audio and Text-Based Representations of Speech](https://doi.org/10.3389/fpsyg.2020.624137) - R'mani Haulcy, James R. Glass, Frontiers in Psychology, (2021), Cited By: 60
	- [Recognition of Alzheimer’s Dementia From the Transcriptions of Spontaneous Speech Using fastText and CNN Models](https://doi.org/10.3389/fcomp.2021.624558) - Amit Meghanani, C. Anoop, Angarai Ganesan Ramakrishnan, Frontiers of Computer Science, (2021), Cited By: 23
	- [Towards Computer-Based Automated Screening of Dementia Through Spontaneous Speech](https://doi.org/10.3389/fpsyg.2020.623237) - K. Chlasta, K. Wołk, Frontiers in Psychology, (2021), Cited By: 21
	- [Multimodal Capture of Patient Behaviour for Improved Detection of Early Dementia: Clinical Feasibility and Preliminary Results](https://doi.org/10.3389/fcomp.2021.642633) - Patrik Jonell, Birger Moëll, K. Håkansson, G. Henter, Taras Kuchurenko, O. Mikheeva, G. Hagman, J. Holleman, M. Kivipelto, H. Kjellström, Joakim Gustafson, J. Beskow, Frontiers of Computer Science, (2021), Cited By: 13
	- [Using a Discourse Task to Explore Semantic Ability in Persons With Cognitive Impairment](https://doi.org/10.3389/fnagi.2020.607449) - M. Antonsson, Kristina Lundholm Fors, M. Eckerström, D. Kokkinakis, Frontiers in Aging Neuroscience, (2021), Cited By: 9
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - Jiahong Yuan, Xingyu Cai, Yuchen Bian, Z. Ye, Kenneth Ward Church, Frontiers of Computer Science, (2021), Cited By: 22
	- [Editorial: Alzheimer’s Dementia Recognition through Spontaneous Speech](https://doi.org/10.3389/fcomp.2021.780169) - S. Luz, F. Haider, Sofia de la Fuente Garcia, Davida Fromm, B. MacWhinney, Frontiers of Computer Science, (2021), Cited By: 26
	- [Exploring Deep Transfer Learning Techniques for Alzheimer’s Dementia Detection](https://doi.org/10.3389/fcomp.2021.624683) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Frontiers of Computer Science, (2021), Cited By: 29
	- [A Comparison of Connected Speech Tasks for Detecting Early Alzheimer’s Disease and Mild Cognitive Impairment Using Natural Language Processing and Machine Learning](https://doi.org/10.3389/fcomp.2021.634360) - Natasha Clarke, T. Barrick, P. Garrard, Frontiers of Computer Science, (2021), Cited By: 29
	- [Towards an Automatic Speech-Based Diagnostic Test for Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2021.624594) - Roozbeh Sadeghian, J. Schaffer, S. Zahorian, Frontiers of Computer Science, (2021), Cited By: 11
	- [Alzheimer’s Dementia Recognition From Spontaneous Speech Using Disfluency and Interactional Features](https://doi.org/10.3389/fcomp.2021.640669) - Shamila Nasreen, Morteza Rohanian, Julian Hough, Matthew Purver, Frontiers of Computer Science, (2021), Cited By: 27
	- [Analysis and Classification of Word Co-Occurrence Networks From Alzheimer’s Patients and Controls](https://doi.org/10.3389/fcomp.2021.649508) - Tristan Millington, S. Luz, Frontiers of Computer Science, (2021), Cited By: 12
	- [Learning Language and Acoustic Models for Identifying Alzheimer’s Dementia From Speech](https://doi.org/10.3389/fcomp.2021.624659) - Zehra Shah, Jeffrey Sawalha, Mashrura Tasnim, S. Qi, Eleni Stroulia, R. Greiner, Frontiers of Computer Science, (2021), Cited By: 31
	- [Comparing Pre-trained and Feature-Based Models for Prediction of Alzheimer's Disease Based on Speech](https://doi.org/10.3389/fnagi.2021.635945) - Aparna Balagopalan, Benjamin Eyre, Jessica Robin, Frank Rudzicz, Jekaterina Novikova, Frontiers in Aging Neuroscience, (2021), Cited By: 56
	- [Crossing the “Cookie Theft” Corpus Chasm: Applying What BERT Learns From Outside Data to the ADReSS Challenge Dementia Detection Task](https://doi.org/10.3389/fcomp.2021.642517) - Yue Guo, Changye Li, Carol L. Roan, Serguei V. S. Pakhomov, T. Cohen, Frontiers of Computer Science, (2021), Cited By: 26
- 2020
	- [Longitudinal Speech Biomarkers for Automated Alzheimer's Detection](https://doi.org/10.3389/fcomp.2021.624694) - Jordi Laguarta, B. Subirana, Frontiers of Computer Science, (2020), Cited By: 23
	- [Dual-Task Training Affect Cognitive and Physical Performances and Brain Oscillation Ratio of Patients With Alzheimer’s Disease: A Randomized Controlled Trial](https://doi.org/10.3389/fnagi.2020.605317) - Elnaz Parvin, F. Mohammadian, Sadegh Amani-shalamzari, M. Bayati, Behnaz Tazesh, Frontiers in Aging Neuroscience, (2020), Cited By: 24

#### c. ADReSSo 2021
- 2021
	- [Using the Outputs of Different Automatic Speech Recognition Paradigms for Acoustic- and BERT-Based Alzheimer's Dementia Detection Through Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1519) - Yilin Pan, B. Mirheidari, Jennifer M. Harris, J. Thompson, Matthew Jones, J. Snowden, Daniel Blackburn, H. Christensen, Interspeech, (2021), Cited By: 42
	- [Automatic Detection and Assessment of Alzheimer Disease Using Speech and Language Technologies in Low-Resource Scenarios](https://doi.org/10.21437/interspeech.2021-1850) - R. Pappagari, Jaejin Cho, Sonal Joshi, L. Moro-Velázquez, Piotr Żelasko, J. Villalba, N. Dehak, Interspeech, (2021), Cited By: 36
	- [WavBERT: Exploiting Semantic and Non-Semantic Speech Using Wav2vec and BERT for Dementia Detection](https://doi.org/10.21437/interspeech.2021-332) - Youxiang Zhu, Abdelrahman Obyat, Xiaohui Liang, J. Batsis, R. Roth, Interspeech, (2021), Cited By: 30
	- [Tackling the ADRESSO Challenge 2021: The MUET-RMIT System for Alzheimer's Dementia Recognition from Spontaneous Speech](https://doi.org/10.21437/interspeech.2021-1572) - Zafi Sherhan Syed, Muhammad Shehram Shah Syed, M. Lech, E. Pirogova, Interspeech, (2021), Cited By: 17
	- [Automatic Detection of Alzheimer's Disease Using Spontaneous Speech Only](https://doi.org/10.21437/interspeech.2021-2002) - Jun Chen, Jieping Ye, Fengyi Tang, Jiayu Zhou, Interspeech, (2021), Cited By: 29
	- [Alzheimer's Disease Detection from Spontaneous Speech through Combining Linguistic Complexity and (Dis)Fluency Features with Pretrained Language Models](https://doi.org/10.21437/interspeech.2021-1415) - Y. Qiao, Xuefeng Yin, Daniel Wiechmann, E. Kerz, Interspeech, (2021), Cited By: 16
	- [Comparing Acoustic-based Approaches for Alzheimer's Disease Detection](https://doi.org/10.21437/interspeech.2021-759) - Aparna Balagopalan, Jekaterina Novikova, Interspeech, (2021), Cited By: 32
	- [Influence of the Interviewer on the Automatic Assessment of Alzheimer's Disease in the Context of the ADReSSo Challenge](https://doi.org/10.21437/interspeech.2021-1589) - P. A. Pérez-Toro, S. Bayerl, T. Arias-Vergara, J. C. Vásquez-Correa, P. Klumpp, M. Schuster, Elmar Nöth, J. Orozco-Arroyave, K. Riedhammer, Interspeech, (2021), Cited By: 21
	- [Alzheimer Disease Recognition Using Speech-Based Embeddings From Pre-Trained Models](https://doi.org/10.21437/interspeech.2021-753) - L. Gauder, L. Pepino, Luciana Ferrer, P. Riera, Interspeech, (2021), Cited By: 24
	- [Detecting cognitive decline using speech only: The ADReSSo Challenge](https://doi.org/10.1101/2021.03.24.21254263) - S. Luz, F. Haider, S. D. L. Fuente, Davida Fromm, B. MacWhinney, medRxiv, (2021), Cited By: 109
	- [Alzheimer's Dementia Recognition Using Acoustic, Lexical, Disfluency and Speech Pause Features Robust to Noisy Inputs](https://doi.org/10.21437/interspeech.2021-1633) - Morteza Rohanian, Julian Hough, Matt Purver, Interspeech, (2021), Cited By: 33
	- [Modular Multi-Modal Attention Network for Alzheimer's Disease Detection Using Patient Audio and Language Data](https://doi.org/10.21437/interspeech.2021-2024) - Ning Wang, Yupeng Cao, Shuai Hao, Zongru Shao, K.P. Subbalakshmi, Interspeech, (2021), Cited By: 21

#### d. SPGC Challenge 2023
- 2024
	- [An Overview of the ADReSS-M Signal Processing Grand Challenge on Multilingual Alzheimer’s Dementia Recognition Through Spontaneous Speech](https://doi.org/10.1109/OJSP.2024.3378595) - Saturnino Luz, F. Haider, Davida Fromm, Ioulietta Lazarou, I. Kompatsiaris, B. MacWhinney, IEEE Open Journal of Signal Processing, (2024), Cited By: 2
- 2023
	- [Cross-Lingual Alzheimer’s Disease Detection Based on Paralinguistic and Pre-Trained Features](https://doi.org/10.1109/ICASSP49357.2023.10095522) - Xuchu Chen, Yujiang Pu, Jinpeng Li, Weiqiang Zhang, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 7
	- [Multilingual Alzheimer’s Dementia Recognition through Spontaneous Speech: A Signal Processing Grand Challenge](https://doi.org/10.1109/ICASSP49357.2023.10433923) - S. Luz, F. Haider, Davida Fromm, Ioulietta Lazarou, Y. Kompatsiaris, B. MacWhinney, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 14
	- [Exploring Language-Agnostic Speech Representations Using Domain Knowledge for Detecting Alzheimer’s Dementia](https://doi.org/10.1109/ICASSP49357.2023.10095593) - Zehra Shah, Shiguang Qi, Fei Wang, Mahtab Farrokh, Mashrura Tasnim, Eleni Stroulia, R. Greiner, Manos Plitsis, Athanasios Katsamanis, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 4
	- [The Ustc System for Adress-m Challenge](https://doi.org/10.1109/ICASSP49357.2023.10094714) - Kangdi Mei, Xinyun Ding, Yinlong Liu, Zhiqiang Guo, Feiyang Xu, Xin Li, Tuya Naren, Jiahong Yuan, Zhenhua Ling, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 5
	- [Cross-Lingual Transfer Learning for Alzheimer’s Detection from Spontaneous Speech](https://doi.org/10.1109/ICASSP49357.2023.10096770) - Bastiaan Tamm, R. Vandenberghe, H. V. hamme, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 8

#### e. TalkDual 2024
- 2024
	- [Combining Acoustic Feature Sets for Detecting Mild Cognitive Impairment in the Interspeech'24 TAUKADIAL Challenge](https://doi.org/10.21437/interspeech.2024-984) - G. Gosztolya, László Tóth, Interspeech, (2024), Cited By: 0
	- [Multilingual Speech and Language Analysis for the Assessment of Mild Cognitive Impairment: Outcomes from the Taukadial Challenge](https://doi.org/10.21437/interspeech.2024-2115) - P. A. Pérez-Toro, T. Arias-Vergara, P. Klumpp, Tobias Weise, Maria Schuster, E. Noeth, J. Orozco-Arroyave, Andreas Maier, Interspeech, (2024), Cited By: 0
	- [Leveraging Universal Speech Representations for Detecting and Assessing the Severity of Mild Cognitive Impairment Across Languages](https://doi.org/10.21437/interspeech.2024-2030) - A. Favaro, Tianyu Cao, N. Dehak, L. Moro-Velázquez, Interspeech, (2024), Cited By: 0
	- [Pre-trained Feature Fusion and Matching for Mild Cognitive Impairment Detection](https://doi.org/10.21437/interspeech.2024-2386) - Junwen Duan, Fangyuan Wei, Hongdong Li, Jin Liu, Interspeech, (2024), Cited By: 0
	- [CogniVoice: Multimodal and Multilingual Fusion Networks for Mild Cognitive Impairment Assessment from Spontaneous Speech](https://doi.org/10.48550/arXiv.2407.13660) - Jiali Cheng, Mohamed Elgaar, Nidhi Vakil, Hadi Amiri, Interspeech, (2024), Cited By: 0
	- [Cognitive Insights Across Languages: Enhancing Multimodal Interview Analysis](https://doi.org/10.48550/arXiv.2406.07542) - David Ortiz-Perez, José García Rodríguez, David Tomás, Interspeech, (2024), Cited By: 0
	- [The Interspeech 2024 TAUKADIAL Challenge: Multilingual Mild Cognitive Impairment Detection with Multimodal Approach](https://doi.org/10.21437/interspeech.2024-1352) - Benjamin Barrera-Altuna, Daeun Lee, Zaima Zarnaz, Jinyoung Han, Seungbae Kim, Interspeech, (2024), Cited By: 0
	- [Connected Speech-Based Cognitive Assessment in Chinese and English](https://doi.org/10.48550/arXiv.2406.10272) - Saturnino Luz, Sofia de la Fuente Garcia, F. Haider, Davida Fromm, B. MacWhinney, Alyssa Lanzi, Ya‐Ning Chang, Chia-Ju Chou, Yi‐Chien Liu, Interspeech, (2024), Cited By: 3
	- [Translingual Language Markers for Cognitive Assessment from Spontaneous Speech](https://doi.org/10.21437/interspeech.2024-1422) - Bao Hoang, Yijiang Pang, Hiroko Dodge, Jiayu Zhou, Interspeech, (2024), Cited By: 0

### 3. Novel research topics in dementia

#### ASR
- 2024
	- [The Influence of Automatic Speech Recognition on Linguistic Features and Automatic Alzheimer’s Disease Detection from Spontaneous Speech](https://www.semanticscholar.org/paper/43df611c507c53db91f4c7dcc9554862a96198b1) - Jonathan Heitz, Gerold Schneider, Nicolas Langer, International Conference on Language Resources and Evaluation, (2024), Cited By: 0
	- [Whisper-Based Transfer Learning for Alzheimer Disease Classification: Leveraging Speech Segments with Full Transcripts as Prompts](https://doi.org/10.1109/ICASSP48485.2024.10448004) - Jinpeng Li, Wei-Qiang Zhang, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2024), Cited By: 0
- 2022
	- [The Far Side of Failure: Investigating the Impact of Speech Recognition Errors on Subsequent Dementia Classification](https://doi.org/10.48550/arXiv.2211.07430) - Changye Li, T. Cohen, Serguei V. S. Pakhomov, arXiv.org, (2022), Cited By: 2
	- [End-to-End ASR-Enhanced Neural Network for Alzheimer’s Disease Diagnosis](https://doi.org/10.1109/icassp43922.2022.9747856) - Jiancheng Gui, Yikai Li, Kai Chen, Joanna Siebert, Qingcai Chen, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 3
	- [Evaluating Web-Based Automatic Transcription for Alzheimer Speech Data: Transcript Comparison and Machine Learning Analysis](https://doi.org/10.2196/33460) - Thomas Soroski, Thiago da Cunha Vasco, Sally May Newton‐Mason, Saffrin Granby, Caitlin Lewis, Anuj Harisinghani, Matteo Rizzo, C. Conati, Gabriel Murray, G. Carenini, Thalia S. Field, Hyeju Jang, JMIR Aging, (2022), Cited By: 6
	- [Conformer Based Elderly Speech Recognition System for Alzheimer's Disease Detection](https://doi.org/10.48550/arXiv.2206.13232) - Tianzi Wang, Jiajun Deng, Mengzhe Geng, Zi Ye, Shoukang Hu, Yi Wang, Mingyu Cui, Zengrui Jin, Xunying Liu, Helen M. Meng, Interspeech, (2022), Cited By: 19
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, International Conference on Text, Speech and Dialogue, (2022), Cited By: 4
- 2021
	- [Exploiting Pre-Trained ASR Models for Alzheimer's Disease Recognition Through Spontaneous Speech](https://arxiv.org/abs/2110.01493) - Ying Qin, W. Liu, Zhiyuan Peng, Si-Ioi Ng, Jingyu Li, Haibo Hu, Tan Lee, , (2021), Cited By: 9
- 2020
	- [Improving Detection of Alzheimer's Disease Using Automatic Speech Recognition to Identify High-Quality Segments for More Robust Feature Extraction](https://doi.org/10.21437/interspeech.2020-2698) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2020), Cited By: 14
- 2019
	- [Impact of ASR on Alzheimer’s Disease Detection: All Errors are Equal, but Deletions are More Equal than Others](https://doi.org/10.18653/v1/2020.wnut-1.21) - Aparna Balagopalan, Ksenia Shkaruta, Jekaterina Novikova, WNUT, (2019), Cited By: 7
- 2018
	- [A Speech Recognition-based Solution for the Automatic Detection of Mild Cognitive Impairment from Spontaneous Speech](https://doi.org/10.2174/1567205014666171121114930) - , Current Alzheimer Research, (2018), Cited By: 165
- 2015
	- [Automatic detection of mild cognitive impairment from spontaneous speech using ASR](https://doi.org/10.21437/Interspeech.2015-568) - L. Tóth, G. Gosztolya, V. Vincze, I. Hoffmann, Gréta Szatlóczki, Edit Biró, Fruzsina Zsura, M. Pákáski, J. Kálmán, Interspeech, (2015), Cited By: 85

#### Architecture
- 2024
	- [HAFFormer: A Hierarchical Attention-Free Framework for Alzheimer’s Disease Detection From Spontaneous Speech](https://doi.org/10.1109/ICASSP48485.2024.10446795) - Zhongren Dong, Zixing Zhang, Weixiang Xu, Jing Han, Jianjun Ou, Bjorn W. Schuller, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2024), Cited By: 0

#### Audio Words
- 2023
	- [Exploring the Topics of Audio Words for Detecting Alzheimer's Disease From Spontaneous Speech](https://doi.org/10.1109/LSP.2023.3334696) - Zhiqiang Guo, Zhenhua Ling, IEEE Signal Processing Letters, (2023), Cited By: 0

#### Coherence
- 2023
	- [A Digital Language Coherence Marker for Monitoring Dementia](https://doi.org/10.48550/arXiv.2310.09623) - Dimitris Gkoumas, Adam Tsakalidis, M. Liakata, Conference on Empirical Methods in Natural Language Processing, (2023), Cited By: 1

#### Data Augmentation
- 2023
	- [Multimodal Approaches for Alzheimer's Detection Using Patients' Speech and Transcript](https://doi.org/10.1007/978-3-031-43075-6_34) - Hongmin Cai, Xiaoke Huang, Zheng Liu, Wenxiong Liao, Haixing Dai, Zihao Wu, Dajiang Zhu, Hui Ren, Quanzheng Li, Tianming Liu, Xiang Li, BI, (2023), Cited By: 3
	- [CDA: A Contrastive Data Augmentation Method for Alzheimer's Disease Detection](https://doi.org/10.18653/v1/2023.findings-acl.114) - Junwen Duan, Fangyuan Wei, Jin Liu, Hongdong Li, Tianming Liu, Jianxin Wang, Annual Meeting of the Association for Computational Linguistics, (2023), Cited By: 3
- 2022
	- [Data Augmentation for Dementia Detection in Spoken Language](https://doi.org/10.48550/arXiv.2206.12879) - Anna Hl'edikov'a, Dominika Woszczyk, Alican Acman, Soteris Demetriou, Björn Schuller, Interspeech, (2022), Cited By: 7
	- [Cognitive Assessment of Japanese Older Adults with Text Data Augmentation](https://doi.org/10.3390/healthcare10102051) - Toshiharu Igarashi, M. Nihei, Healthcare, (2022), Cited By: 2
- 2021
	- [Robustness and Sensitivity of BERT Models Predicting Alzheimer’s Disease from Text](https://doi.org/10.18653/v1/2021.wnut-1.37) - Jekaterina Novikova, WNUT, (2021), Cited By: 7
	- [Automatic Speech Classifier for Mild Cognitive Impairment and Early Dementia](https://doi.org/10.1145/3469089) - Flavio Bertini, Davide Allevi, Gianluca Lutero, Danilo Montesi, L. Calzà, ACM Trans. Comput. Heal., (2021), Cited By: 26
- 2020
	- [Data augmentation using generative networks to identify dementia](https://arxiv.org/abs/2004.05989) - B. Mirheidari, Yilin Pan, D. Blackburn, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, H. Christensen, arXiv.org, (2020), Cited By: 4

#### Data Reliability
- 2024
	- [Clever Hans Effect Found in Automatic Detection of Alzheimer's Disease through Speech](https://doi.org/10.21437/interspeech.2024-1018) - Yin-Long Liu, Rui Feng, Jia-Hong Yuan, Z. Ling, Interspeech, (2024), Cited By: 0

#### Dialog Act
- 2022
	- [Are Interaction Patterns Helpful for Task-Agnostic Dementia Detection? An Empirical Exploration](https://doi.org/10.18653/v1/2022.sigdial-1.18) - Shahla Farzana, Natalie Parde, SIGDIAL Conferences, (2022), Cited By: 3
- 2020
	- [Modeling Dialogue in Conversational Cognitive Health Screening Interviews](https://www.semanticscholar.org/paper/cf0c7194c5342f4d167e95c54685f5f564a7d12b) - Shahla Farzana, Mohammad Valizadeh, Natalie Parde, International Conference on Language Resources and Evaluation, (2020), Cited By: 15

#### Domain Adapation
- 2023
	- [Towards Domain-Agnostic and Domain-Adaptive Dementia Detection from Spoken Language](https://doi.org/10.18653/v1/2023.acl-long.668) - Shahla Farzana, Natalie Parde, Annual Meeting of the Association for Computational Linguistics, (2023), Cited By: 2

#### Emotion
- 2021
	- [Audio-Visual Recognition of Emotional Engagement of People with Dementia](https://doi.org/10.21437/interspeech.2021-567) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, Interspeech, (2021), Cited By: 8
- 2020
	- [Towards Engagement Recognition of People with Dementia in Care Settings](https://doi.org/10.1145/3382507.3418856) - Lars Steinert, F. Putze, Dennis Küster, T. Schultz, International Conference on Multimodal Interaction, (2020), Cited By: 10

#### Explainable
- 2024
	- [Discovering Invariant Patterns of Cognitive Decline Via an Automated Analysis of the Cookie Thief Picture Description Task](https://doi.org/10.21437/odyssey.2024-29) - A. Favaro, N. Dehak, Thomas Thebaud, J. Villalba, Esther S Oh, L. Moro-Velázquez, The Speaker and Language Recognition Workshop, (2024), Cited By: 0
- 2023
	- [Explainable Alzheimer’s Disease Detection Using Linguistic Features from Automatic Speech Recognition](https://doi.org/10.1159/000531818) - Lijuan Tang, Zhenglin Zhang, Feifan Feng, Lizhuang Yang, Hai Li, Dementia and Geriatric Cognitive Disorders, (2023), Cited By: 1
- 2022
	- [Data-driven Approach to Differentiating between Depression and Dementia from Noisy Speech and Language Data](https://doi.org/10.48550/arXiv.2210.03303) - Malikeh Ehghaghi, Frank Rudzicz, Jekaterina Novikova, WNUT, (2022), Cited By: 3
	- [Interpreting acoustic features for the assessment of Alzheimer’s disease using ForestNet](https://doi.org/10.1016/j.smhl.2022.100347) - P. A. Pérez-Toro, Dalia Rodríguez-Salas, T. Arias-Vergara, P. Klumpp, M. Schuster, Elmar Nöth, J. Orozco-Arroyave, A. Maier, Smart Health, (2022), Cited By: 6
	- [Dementia Detection Using Language Models and Transfer Learning](https://doi.org/10.1145/3520084.3520108) - Mondher Bouazizi, Chuheng Zheng, T. Ohtsuki, International Conferences on Software Engineering and Information Management, (2022), Cited By: 2
- 2021
	- [Explainable Identification of Dementia From Transcripts Using Transformer Networks](https://doi.org/10.1109/JBHI.2022.3172479) - Loukas Ilias, D. Askounis, IEEE journal of biomedical and health informatics, (2021), Cited By: 19
	- [Towards Interpretability of Speech Pause in Dementia Detection Using Adversarial Learning](https://doi.org/10.1109/icassp43922.2022.9747006) - Youxiang Zhu, Bang Tran, Xiaohui Liang, J. Batsis, R. Roth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 5
- 2020
	- [Acoustic Feature Extraction with Interpretable Deep Neural Network for Neurodegenerative Related Disorder Classification](https://doi.org/10.21437/interspeech.2020-2684) - Yilin Pan, B. Mirheidari, Z. C. Tu, R. O'Malley, Traci Walker, A. Venneri, M. Reuber, D. Blackburn, H. Christensen, Interspeech, (2020), Cited By: 10
	- [Exploiting Fully Convolutional Network and Visualization Techniques on Spontaneous Speech for Dementia Detection](https://arxiv.org/abs/2008.07052) - Youxiang Zhu, Xiaohui Liang, arXiv.org, (2020), Cited By: 2
- 2019
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Machine Learning in Health Care, (2019), Cited By: 15

#### Eye-tracking
- 2022
	- [Dementia Detection by Fusing Speech and Eye-Tracking Representation](https://doi.org/10.1109/icassp43922.2022.9747054) - Zhengyan Sheng, Zhiqiang Guo, Xin Li, Yunxia Li, Zhenhua Ling, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 6
- 2020
	- [Non-Invasive Classification of Alzheimer's Disease Using Eye Tracking and Language](https://www.semanticscholar.org/paper/808412161cd6b5927916a0a6dcf8e03300ba4ae1) - Oswald Barral, Hyeju Jang, Sally May Newton‐Mason, Sheetal Shajan, Thomas Soroski, G. Carenini, C. Conati, Thalia Shoshana Field, Machine Learning in Health Care, (2020), Cited By: 14

#### Features
- 2023
	- [Context is not key: Detecting Alzheimer's disease with both classical and transformer-based neural language models](https://doi.org/10.1016/j.nlp.2023.100046) - Behrad Taghibeyglou, Frank Rudzicz, Natural Language Processing Journal, (2023), Cited By: 1

#### Federated Learning
- 2024
	- [A Comparative Analysis of Federated Learning for Speech-Based Cognitive Decline Detection](https://doi.org/10.21437/interspeech.2024-996) - Stefan Kalabakov, Monica Gonzalez-Machorro, F. Eyben, Björn W. Schuller, Bert Arnrich, Interspeech, (2024), Cited By: 0
- 2023
	- [FedCPC: An Effective Federated Contrastive Learning Method for Privacy Preserving Early-Stage Alzheimers Speech Detection](https://doi.org/10.1109/ASRU57964.2023.10389690) - Wenqing Wei, Zhengdong Yang, Yuan Gao, Jiyi Li, Chenhui Chu, Shogo Okada, Sheng Li, Automatic Speech Recognition & Understanding, (2023), Cited By: 0

#### Image-text
- 2023
	- [Evaluating Picture Description Speech for Dementia Detection using Image-text Alignment](https://doi.org/10.48550/arXiv.2308.07933) - Youxiang Zhu, Nan Lin, Xiaohui Liang, J. Batsis, R. Roth, B. MacWhinney, arXiv.org, (2023), Cited By: 0
	- [Dementia Detection from Speech: What If Language Models Are Not the Answer?](https://doi.org/10.3390/info15010002) - Mondher Bouazizi, Chuheng Zheng, Siyuan Yang, Tomoaki Ohtsuki, Inf., (2023), Cited By: 2

#### Information Unit
- 2016
	- [Vector-space topic models for detecting Alzheimer’s disease](https://doi.org/10.18653/v1/P16-1221) - Maria Yancheva, Frank Rudzicz, Annual Meeting of the Association for Computational Linguistics, (2016), Cited By: 58
- 1996
	- [Comparative Study of Oral and Written Picture Description in Patients with Alzheimer's Disease](https://doi.org/10.1006/brln.1996.0033) - B. Croisile, B. Ska, Marie-Josée Brabant, A. Duchêne, Y. Lepage, G. Aimard, M. Trillet, Brain and Language, (1996), Cited By: 201

#### Intermediate Pretraining
- 2022
	- [Domain-aware Intermediate Pretraining for Dementia Detection with Limited Data](https://doi.org/10.21437/interspeech.2022-10862) - Youxiang Zhu, Xiaohui Liang, J. Batsis, R. Roth, Interspeech, (2022), Cited By: 5

#### Large Language Models
- 2024
	- [Leveraging Large Language Models for Identifying Interpretable Linguistic Markers and Enhancing Alzheimer's Disease Diagnostics](https://doi.org/10.1101/2024.08.22.24312463) - T. Mo, J. Lam, V. Li, L. Cheung, medRxiv, (2024), Cited By: 0
	- [Performance Assessment of ChatGPT vs Bard in Detecting Alzheimer's Dementia](https://doi.org/10.48550/arXiv.2402.01751) - T. BalamuraliB., Jer-Ming Chen, arXiv.org, (2024), Cited By: 1
	- [Alzheimer's disease recognition from spontaneous speech using large language models](https://doi.org/10.4218/etrij.2023-0356) - Jeong‐Uk Bang, Seung‐Hoon Han, Byung‐Ok Kang, ETRI Journal, (2024), Cited By: 5
	- [Optimizing and Evaluating Pre- Trained Large Language Models for Alzheimer's Disease Detection](https://doi.org/10.1109/PDP62718.2024.00046) - Filippo Casu, Enrico Grosso, A. Lagorio, G. Trunfio, International Euromicro Conference on Parallel, Distributed and Network-Based Processing, (2024), Cited By: 1
- 2022
	- [Predicting dementia from spontaneous speech using large language models](https://doi.org/10.1371/journal.pdig.0000168) - Felix Agbavor, Hualou Liang, PLOS Digital Health, (2022), Cited By: 40

#### Longitudinal

#### Multi-lingual
- 2024
	- [Automatic Spontaneous Speech Analysis for the Detection of Cognitive Functional Decline in Older Adults: Multilanguage Cross-Sectional Study](https://doi.org/10.2196/50537) - E. Ambrosini, Chiara Giangregorio, Eugenio Lomurno, Sara Moccia, M. Milis, Christos Loizou, D. Azzolino, Matteo Cesari, Manuel Cid Gala, Carmen Galán de Isla, Jonathan Gomez-Raja, N. A. Borghese, Matteo Matteucci, Simona Ferrante, JMIR Aging, (2024), Cited By: 0
- 2023
	- [Automatic Assessment of Alzheimer's across Three Languages Using Speech and Language Features](https://doi.org/10.21437/interspeech.2023-2079) - P. A. Pérez-Toro, T. Arias-Vergara, Franziska Braun, F. Hönig, C. A. Tóbon-Quintero, D. Aguillón, F. Lopera, L. Hincapié-Henao, M. Schuster, K. Riedhammer, A. Maier, Elmar Nöth, J. Orozco-Arroyave, Interspeech, (2023), Cited By: 0

#### Multi-modal
- 2024
	- [Towards Scalable Remote Assessment of Mild Cognitive Impairment Via Multimodal Dialog](https://doi.org/10.21437/interspeech.2024-1541) - O. Roesler, J. Liscombe, Michael Neumann, H. Kothare, Abhishek Hosamath, Lakshmi Arbatti, Doug Habberstad, Christiane Suendermann-Oeft, Meredith Bartlett, Cathy Zhang, Nikhil Sukhdev, Kolja Wilms, Anusha Badathala, Sandrine Istas, Steve Ruhmel, Bryan Hansen, Madeline Hannan, David Henley, Arthur Wallace, Ira Shoulson, D. Suendermann-Oeft, Vikram Ramanarayanan, Interspeech, (2024), Cited By: 0
- 2023
	- [An Exploration of Multimodality and Data Augmentation for Dementia Classification](https://doi.org/10.48550/arXiv.2311.02819) - Kaiying Lin, Peter Washington, arXiv.org, (2023), Cited By: 0
	- [Context-Aware Attention Layers coupled with Optimal Transport Domain Adaptation methods for recognizing dementia from spontaneous speech](https://doi.org/10.48550/arXiv.2305.16406) - Loukas Ilias, D. Askounis, arXiv.org, (2023), Cited By: 0
	- [Transferring Speech-Generic and Depression-Specific Knowledge for Alzheimer’s Disease Detection](https://doi.org/10.1109/ASRU57964.2023.10389785) - Ziyun Cui, Wen Wu, Wei-Qiang Zhang, Ji Wu, Chao Zhang, Automatic Speech Recognition & Understanding, (2023), Cited By: 0
	- [Exploring Multimodal Approaches for Alzheimer's Disease Detection Using Patient Speech Transcript and Audio Data](https://doi.org/10.48550/arXiv.2307.02514) - Hongmin Cai, Xiaoke Huang, Zheng Liu, Wenxiong Liao, Haixing Dai, Zihao Wu, Dajiang Zhu, Hui Ren, Quanzheng Li, Tianming Liu, Xiang Li, arXiv.org, (2023), Cited By: 9
	- [ADMarker: A Multi-Modal Federated Learning System for Monitoring Digital Biomarkers of Alzheimer's Disease](https://doi.org/10.1145/3636534.3649370) - Xiaomin Ouyang, Xian Shuai, Yang Li, Lilin Pan, Xifan Zhang, Heming Fu, Sitong Cheng, Xinyan Wang, Shihua Cao, Jiang Xin, Hazel Mok, Zhenyu Yan, Doris Sau Fung Yu, Timothy Kwok, Guoliang Xing, ACM/IEEE International Conference on Mobile Computing and Networking, (2023), Cited By: 1

#### Neural Architecture Search
- 2023
	- [Neural Architecture Search with Multimodal Fusion Methods for Diagnosing Dementia](https://doi.org/10.1109/ICASSP49357.2023.10096579) - Michail Chatzianastasis, Loukas Ilias, D. Askounis, M. Vazirgiannis, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 1

#### Novel Speech Tasks
- 2022
	- [Going Beyond the Cookie Theft Picture Test: Detecting Cognitive Impairments using Acoustic Features](https://doi.org/10.1007/978-3-031-16270-1_36) - Franziska Braun, Andreas Erzigkeit, H. Lehfeld, T. Hillemacher, K. Riedhammer, S. Bayerl, International Conference on Text, Speech and Dialogue, (2022), Cited By: 8
	- [The Hong Kong Grocery Shopping Dialog Task (HK-GSDT): A Quick Screening Test for Neurocognitive Disorders](https://doi.org/10.3390/ijerph192013302) - Xianmin Gong, P. Wong, H. Fung, V. C. T. Mok, T. Kwok, Jean Woo, Ka Ho WONG, Helen Meng, International Journal of Environmental Research and Public Health, (2022), Cited By: 4

#### Pause&Disfluencies
- 2023
	- [Limited connectedness of spontaneous speech may be a marker of dementia due to Alzheimer’s disease](https://doi.org/10.3389/fnagi.2023.1252614) - M. R. Botezatu, Erika Miller, Andrew M. Kiselica, Frontiers in Aging Neuroscience, (2023), Cited By: 0
	- [Efficient Pause Extraction and Encode Strategy for Alzheimer’s Disease Detection Using Only Acoustic Features from Spontaneous Speech](https://doi.org/10.3390/brainsci13030477) - Jiamin Liu, Fan Fu, L. Li, Junxiao Yu, Dacheng Zhong, Songsheng Zhu, Yuxuan Zhou, Bin Liu, Jianqing Li, Brain Science, (2023), Cited By: 7
	- [Alzheimer Disease Classification through ASR-based Transcriptions: Exploring the Impact of Punctuation and Pauses](https://doi.org/10.21437/Interspeech.2023-1734) - Lucía Gómez-Zaragozá, Simone Wills, C. García, J. Marín-Morales, Mariano Alcañiz, H. Strik, Interspeech, (2023), Cited By: 3
- 2022
	- [Contrast-enhanced Automatic Cognitive Impairment Detection System with Pause-encoder](https://doi.org/10.1109/SMC53654.2022.9945085) - Sheng-Ya Lin, Ho-Ling Chang, Thiri Wai, Li-Chen Fu, Yu-Ling Chang, IEEE International Conference on Systems, Man and Cybernetics, (2022), Cited By: 1
	- [How You Say It Matters: Measuring the Impact of Verbal Disfluency Tags on Automated Dementia Detection](https://doi.org/10.18653/v1/2022.bionlp-1.4) - Shahla Farzana, Ashwin Deshpande, Natalie Parde, Workshop on Biomedical Natural Language Processing, (2022), Cited By: 8
- 2021
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - Jiahong Yuan, Xingyu Cai, Yuchen Bian, Z. Ye, Kenneth Ward Church, Frontiers of Computer Science, (2021), Cited By: 22
	- [Speech pause distribution as an early marker for Alzheimer's disease](https://doi.org/10.1101/2020.12.28.20248875) - P. Pastoriza-Domínguez, I. G. Torre, F. Diéguez-Vide, I. Gómez-Ruiz, S. Geladó, J. Bello-López, A. Ávila-Rivera, J. Matías-Guiu, V. Pytel, A. Hernández-Fernández, medRxiv, (2021), Cited By: 22
	- [Pause-Encoded Language Models for Recognition of Alzheimer’s Disease and Emotion](https://doi.org/10.1109/ICASSP39728.2021.9413548) - Jiahong Yuan, Xingyu Cai, Kenneth Ward Church, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 7
- 2020
	- [Disfluencies and Fine-Tuning Pre-Trained Language Models for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - Jiahong Yuan, Yuchen Bian, Xingyu Cai, Jiaji Huang, Z. Ye, Kenneth Ward Church, Interspeech, (2020), Cited By: 85
	- [An Automated Approach to Examining Pausing in the Speech of People With Dementia](https://doi.org/10.1177/1533317520939773) - Rachel A. Sluis, Daniel Angus, Janet Wiles, A. Back, T. Gibson, J. Liddle, Peter Worthy, D. Copland, A. Angwin, American Journal of Alzheimers Disease & Other Dementias, (2020), Cited By: 18
- 2009
	- [Examining Pauses in Alzheimer's Discourse](https://doi.org/10.1177/1533317508328138) - Boyd H. Davis, M. Maclagan, American Journal of Alzheimers Disease & Other Dementias, (2009), Cited By: 51

#### Perplexity
- 2024
	- [Too Big to Fail: Larger Language Models are Disproportionately Resilient to Induction of Dementia-Related Linguistic Anomalies](https://doi.org/10.48550/arXiv.2406.02830) - Changye Li, Zhecheng Sheng, Trevor Cohen, Serguei V. S. Pakhomov, Annual Meeting of the Association for Computational Linguistics, (2024), Cited By: 0
- 2023
	- [Semantic Coherence Markers for the Early Diagnosis of the Alzheimer Disease](https://doi.org/10.48550/arXiv.2302.01025) - Davide Colla, Matteo Delsanto, Marco Agosto, B. Vitiello, Daniele P. Radicioni, arXiv.org, (2023), Cited By: 0
- 2022
	- [GPT-D: Inducing Dementia-related Linguistic Anomalies by Deliberate Degradation of Artificial Neural Language Models](https://doi.org/10.48550/arXiv.2203.13397) - Changye Li, D. Knopman, Weizhe Xu, T. Cohen, Serguei V. S. Pakhomov, Annual Meeting of the Association for Computational Linguistics, (2022), Cited By: 16
- 2020
	- [A Tale of Two Perplexities: Sensitivity of Neural Language Models to Lexical Retrieval Deficits in Dementia of the Alzheimer’s Type](https://doi.org/10.18653/v1/2020.acl-main.176) - T. Cohen, Serguei V. S. Pakhomov, Annual Meeting of the Association for Computational Linguistics, (2020), Cited By: 20
- 2019
	- [Detecting Alzheimer's Disease from Continuous Speech Using Language Models.](https://doi.org/10.3233/JAD-190452) - Zhiqiang Guo, Zhenhua Ling, Yunxia Li, Journal of Alzheimer's Disease, (2019), Cited By: 24
	- [Perplexity – a new predictor of cognitive changes in spoken language? – results of the Interdisciplinary Longitudinal Study on Adult Development and Aging (ILSE)](https://doi.org/10.1515/lingvan-2018-0026) - C. Frankenberg, Jochen Weiner, Tanja Schultz, M. Knebel, C. Degen, H. Wahl, J. Schroeder, Linguistics Vanguard, (2019), Cited By: 16
	- [Automatic Diagnosis of Alzheimer’s Disease Using Neural Network Language Models](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, Sebastian Wankerl, Elmar Nöth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2019), Cited By: 53
- 2018
	- [Language Modelling for the Clinical Semantic Verbal Fluency Task](https://www.semanticscholar.org/paper/88188082df9ec54d05753d88f3b4f92f31f86a9e) - N. Linz, J. Tröger, Hali Lindsay, A. König, P. Robert, J. Peter, J. Alexandersson, , (2018), Cited By: 4
- 2017
	- [An N-Gram Based Approach to the Automatic Diagnosis of Alzheimer's Disease from Spoken Language](https://doi.org/10.21437/Interspeech.2017-1572) - Sebastian Wankerl, Elmar Nöth, S. Evert, Interspeech, (2017), Cited By: 45

#### Prompt Learning
- 2023
	- [Reformulating NLP tasks to Capture Longitudinal Manifestation of Language Disorders in People with Dementia](https://doi.org/10.48550/arXiv.2310.09897) - Dimitris Gkoumas, Matthew Purver, M. Liakata, Conference on Empirical Methods in Natural Language Processing, (2023), Cited By: 0
- 2022
	- [Exploiting Prompt Learning with Pre-Trained Language Models for Alzheimer’s Disease Detection](https://doi.org/10.1109/ICASSP49357.2023.10095993) - Yi Wang, Jiajun Deng, Tianzi Wang, Bo Zheng, Shoukang Hu, Xunying Liu, Helen M. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 6

#### Pronoun
- 2023
	- [Pronoun use in preclinical and early stages of Alzheimer's dementia](https://doi.org/10.1016/j.csl.2023.101573) - Dagmar Bittner, C. Frankenberg, Johannes Schröder, Computer Speech and Language, (2023), Cited By: 1

#### Representation Learning
- 2023
	- [Leveraging Pretrained Representations With Task-Related Keywords for Alzheimer’s Disease Detection](https://doi.org/10.1109/ICASSP49357.2023.10096205) - Jinchao Li, Kaitao Song, Junan Li, Bo Zheng, D. Li, Xixin Wu, Xunying Liu, Helen M. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 6
	- [SpeechFormer++: A Hierarchical Efficient Framework for Paralinguistic Speech Processing](https://doi.org/10.1109/TASLP.2023.3235194) - Weidong Chen, Xiaofen Xing, Xiangmin Xu, Jianxin Pang, Lan Du, IEEE/ACM Transactions on Audio Speech and Language Processing, (2023), Cited By: 15
- 2022
	- [SpeechFormer: A Hierarchical Efficient Framework Incorporating the Characteristics of Speech](https://doi.org/10.48550/arXiv.2203.03812) - Weidong Chen, Xiaofen Xing, Xiangmin Xu, Jianxin Pang, Lan Du, Interspeech, (2022), Cited By: 26

#### Semantic Similarity
- 2023
	- [Comparing global and local semantic coherence of spontaneous speech in persons with Alzheimer's disease and healthy controls.](https://doi.org/10.1016/j.acorp.2023.100064) - E. Burke, J. Gunstad, Phillip Hamrick, Applied Corpus Linguistics, (2023), Cited By: 4

#### Sequence Representation
- 2024
	- [Linguistic-Based Mild Cognitive Impairment Detection Using Informative Loss](https://doi.org/10.48550/arXiv.2402.01690) - A. P. Fard, Mohammad H. Mahoor, Muath Alsuhaibani, Hiroko H. Dodge, Comput. Biol. Medicine, (2024), Cited By: 0

#### Speech and Writing
- 2023
	- [Using personal writings to detect dementia: A text mining approach](https://doi.org/10.1177/14604582231204409) - Beni Asllani, Deborah M Mullen, Health Informatics Journal, (2023), Cited By: 0
- 2021
	- [A Longitudinal Multi-modal Dataset for Dementia Monitoring and Diagnosis](https://doi.org/10.1007/s10579-023-09718-4) - Dimitris Gkoumas, Bo Wang, Adam Tsakalidis, M. Wolters, A. Zubiaga, Matthew Purver, M. Liakata, Language Resources and Evaluation, (2021), Cited By: 3

#### Telephone Interview
- 2022
	- [Accuracy of telephone screening tools to identify dementia patients remotely: systematic review](https://doi.org/10.1177/20542704221115956) - Charlotte Olivia Riley, B. McKinstry, K. Fairhurst, JRSM Open, (2022), Cited By: 3
- 2021
	- [Dementia risks identified by vocal features via telephone conversations: A novel machine learning prediction model](https://doi.org/10.1371/journal.pone.0253988) - A. Shimoda, Yue Li, H. Hayashi, N. Kondo, PLoS ONE, (2021), Cited By: 28
	- [Diagnostic accuracy of the telephone interview for cognitive status (TICS) for the detection of dementia in primary care in the Netherlands](https://doi.org/10.1002/alz.052760) - H. Abdulrahman, Alzheimer's & Dementia, (2021), Cited By: 0
- 2015
	- [The Harvard Automated Phone Task: new performance-based activities of daily living tests for early Alzheimer's disease.](https://doi.org/10.14283/JPAD.2015.72) - G. Marshall, M. Dekhtyar, Jonathan Bruno, K. Jethwani, R. Amariglio, Keith A. Johnson, R. Sperling, D. Rentz, The journal of prevention of Alzheimer's disease, (2015), Cited By: 21
- 2007
	- [Validation of the Telephone Interview for Cognitive Status (TICS) in Japanese](https://doi.org/10.1002/gps.1812) - Y. Konagaya, Y. Washimi, H. Hattori, A. Takeda, Tomoyuki Watanabe, T. Ohta, International Journal of Geriatric Psychiatry, (2007), Cited By: 34
- 1988
	- [The telephone interview for cognitive status](https://www.semanticscholar.org/paper/f29b4c35e8b57cebb570eaadbee1bdb95fd5d716) - J. Brandt, M. Spencer, M. Folstein, , (1988), Cited By: 580

#### Voice Assistant
- 2023
	- [Speech patterns in responses to questions asked by an intelligent virtual agent can help to distinguish between people with early stage neurodegenerative disorders and healthy controls.](https://doi.org/10.1080/02699206.2023.2254458) - Gareth Walker, Nathan Pevy, R. O'Malley, Bahman Mihrheidari, Markus Reuber, Heidi Christensen, D. Blackburn, Clinical Linguistics & Phonetics, (2023), Cited By: 0
	- [Early Detection of Cognitive Decline Using Voice Assistant Commands](https://doi.org/10.1109/ICASSP49357.2023.10095825) - Elizabeth A. Kurtz, Youxiang Zhu, Tiffany M. Driesse, Bang Tran, J. Batsis, R. Roth, Xiaohui Liang, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 2
- 2022
	- [Evaluating voice-assistant commands for dementia detection](https://doi.org/10.1016/j.csl.2021.101297) - Xiaohui Liang, J. Batsis, Youxiang Zhu, Tiffany M. Driesse, R. Roth, D. Kotz, B. MacWhinney, Computer Speech and Language, (2022), Cited By: 19
	- [Alzheimer's Dementia Detection through Spontaneous Dialogue with Proactive Robotic Listeners](https://doi.org/10.1109/HRI53351.2022.9889375) - Yuanchao Li, Catherine Lai, Divesh Lala, K. Inoue, Tatsuya Kawahara, IEEE/ACM International Conference on Human-Robot Interaction, (2022), Cited By: 9
- 2017
	- [An Avatar-Based System for Identifying Individuals Likely to Develop Dementia](https://doi.org/10.21437/Interspeech.2017-690) - B. Mirheidari, D. Blackburn, K. Harkness, Traci Walker, A. Venneri, M. Reuber, H. Christensen, Interspeech, (2017), Cited By: 30

### 4. Regular papers
- 2024
	- [Comparison of AI with and without hand-crafted features to classify Alzheimer's disease in different languages](https://doi.org/10.1016/j.compbiomed.2024.108950) - Tong Min Kim, Junhyeok Son, J. Chun, Youngrong Lee, Dai-Jin Kim, I. Choi, Taehoon Ko, Seungjin Choi, Comput. Biol. Medicine, (2024), Cited By: 1
	- [Analysis of Voice Biomarkers for the Detection of Cognitive Impairment](https://doi.org/10.1109/ACCESS.2024.3442431) - Moisés R. Pacheco-Lorenzo, Heidi Christensen, Luis Anido-Rifón, M. J. Fernández-Iglesias, Sonia Valladares-Rodríguez, IEEE Access, (2024), Cited By: 0
	- [A novel speech analysis algorithm to detect cognitive impairment in a Spanish population](https://doi.org/10.3389/fneur.2024.1342907) - Alyssa N Kaser, L. Lacritz, Holly R. Winiarski, Peru Gabirondo, Jeffrey Schaffert, Alberto J. Coca, Javier Jiménez-Raboso, Tomas Rojo, Carla Zaldua, Iker Honorato, Dario Gallego, Emmanuel Rosario Nieves, L. Rosenstein, C. M. Cullum, Catherine C. Price, Jeffrey Brooks, Frontiers in Neurology, (2024), Cited By: 0
	- [LoSST-AD: A Longitudinal Corpus for Tracking Alzheimer’s Disease Related Changes in Spontaneous Speech](https://www.semanticscholar.org/paper/b48acc125e8ec208254e8210d9ee8b0c3466b72c) - Ulla Petti, Anna Korhonen, International Conference on Language Resources and Evaluation, (2024), Cited By: 0
	- [Automatic detection of Mild Cognitive Impairment using high-dimensional acoustic features in spontaneous speech](https://arxiv.org/abs/2408.16732) - Cong Zhang, Wenxing Guo, Hongsheng Dai, , (2024), Cited By: 0
	- [ML-Based Quantitative Analysis of Linguistic and Speech Features Relevant in Predicting Alzheimer’s Disease](https://doi.org/10.14201/adcaij.31625) - Tripti Tripathi, Rakesh Kumar, Advances in Distributed Computing and Artificial Intelligence Journal, (2024), Cited By: 0
	- [Screening for Alzheimer's Disease in Mainland China Based on Syntax Impairment](https://doi.org/10.1109/IALP63756.2024.10661175) - Yuwei Yang, Linlin Liang, Junhua Gan, Ying Shen, Zhiqiang Lu, Wen Shang, Wenmei Ji, Shiwei Cui, Gefei Feng, Yong Ma, Gangyi Feng, Zude Zhu, International Conference on Asian Language Processing, (2024), Cited By: 0
	- [Automatic speech analysis for detecting cognitive decline of older adults](https://doi.org/10.3389/fpubh.2024.1417966) - Lihe Huang, Hao Yang, Yiran Che, Jingjing Yang, Frontiers in Public Health, (2024), Cited By: 0
	- [Exploring the Efficacy of Text Embeddings in Early Dementia Diagnosis from Speech](https://doi.org/10.1109/HSI61632.2024.10613581) - Khaoula Ajroudi, Mohamed Ibn Khedher, O. Jemai, M. El-Yacoubi, International Conference on Human System Interaction, (2024), Cited By: 0
	- [Prosody-Driven Privacy-Preserving Dementia Detection](https://doi.org/10.48550/arXiv.2407.03470) - Dominika Woszczyk, Ranya Aloufi, Soteris Demetriou, Interspeech, (2024), Cited By: 0
	- [Utilizing Linguistic and Acoustic features from Arabic Transcripts for Early Detecting Alzheimer’s Disease Using Different Machine Learning Algorithms](https://doi.org/10.1109/ATSIP62566.2024.10639034) - Hanein O MohmedShareif, Abdullah M. Elmangoush, Ayyah A. Fadhl, M. A. Ali, International Conference on Advanced Technologies for Signal and Image Processing, (2024), Cited By: 0
	- [Machine Learning-Based Prediction Models for Cognitive Decline Progression: A Comparative Study in Multilingual Settings Using Speech Analysis](https://doi.org/10.14283/jarlife.2024.6) - B. Ceyhan, S. Bek, T. Önal-Süzek, JAR life, (2024), Cited By: 1
	- [Early dementia detection with speech analysis and machine learning techniques](https://doi.org/10.1007/s43621-024-00217-2) - Zerin Jahan, Surbhi Bhatia Khan, Mohammed Saraee, Discover Sustainability, (2024), Cited By: 0
	- [Understanding Dementia Speech: Towards an Adaptive Voice Assistant for Enhanced Communication](https://doi.org/10.1145/3660515.3661326) - Yong Ma, Oda Elise Nordberg, Yuchong Zhang, A. Rongve, Miroslav Bachinski, Morten Fjeld, Engineering Interactive Computing System, (2024), Cited By: 0
- 2023
	- [Natural language processing-driven framework for the early detection of language and cognitive decline](https://doi.org/10.1016/j.laheal.2023.09.002) - Kulvinder Panesar, María Beatriz Pérez Cabello de Alba, Language and Health, (2023), Cited By: 4
	- [Novel Screening Tool Using Non-linguistic Voice Features Derived from Simple Phrases to Detect Mild Cognitive Impairment and Dementia](https://doi.org/10.14283/jarlife.2023.12) - D. Mizuguchi, T. Yamamoto, Y. Omiya, K. Endo, K. Tano, M. Oya, S. Takano, JAR life, (2023), Cited By: 0
	- [A Path Signature Approach for Speech-based Dementia Detection](https://doi.org/10.1109/lsp.2023.3291651) - Yilin Pan, Mingyu Lu, Yanpei Shi, H. Zhang, IEEE Signal Processing Letters, (2023), Cited By: 0
	- [Reading and lexical–semantic retrieval tasks outperforms single task speech analysis in the screening of mild cognitive impairment and Alzheimer's disease](https://doi.org/10.1038/s41598-023-36804-y) - Israel Martínez-Nicolás, F. Martínez-Sánchez, O. Ivanova, J. J. Meilán, Scientific Reports, (2023), Cited By: 1
	- [Automatic Identification of Alzheimer's Disease using Lexical Features extracted from Language Samples](https://doi.org/10.48550/arXiv.2307.08070) - M. Kurdi, arXiv.org, (2023), Cited By: 1
	- [Alzheimer's Disease Detection from Spontaneous Speech and Text: A review](https://doi.org/10.48550/arXiv.2307.10005) - K. VrindhaM., V. Geethu, R. AnurenjanP., S. Deepak, G. SreeniK., arXiv.org, (2023), Cited By: 0
	- [Efficient Pause Extraction and Encode Strategy for Alzheimer’s Disease Detection Using Only Acoustic Features from Spontaneous Speech](https://doi.org/10.3390/brainsci13030477) - Jiamin Liu, Fan Fu, L. Li, Junxiao Yu, Dacheng Zhong, Songsheng Zhu, Yuxuan Zhou, Bin Liu, Jianqing Li, Brain Science, (2023), Cited By: 7
	- [Transferring Quantified Emotion Knowledge for the Detection of Depression in Alzheimer’s Disease Using Forestnets](https://doi.org/10.1109/ICASSP49357.2023.10095219) - P. A. Pérez-Toro, Dalia Rodríguez-Salas, T. Arias-Vergara, S. Bayerl, P. Klumpp, K. Riedhammer, Maria Schuster, E. Nöth, Andreas K. Maier, J. Orozco-Arroyave, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 4
	- [Dementia classification using attention mechanism on audio data](https://doi.org/10.1109/SAMI58000.2023.10044539) - Shkhanukova Milana, International Symposium on Applied Machine Intelligence and Informatics, (2023), Cited By: 0
	- [A Deep Learning-Based Multimodal Architecture to predict Signs of Dementia](https://doi.org/10.1016/j.neucom.2023.126413) - David Ortiz-Perez, Pablo Ruiz-Ponce, David Tomás, José Raúl Rodríguez Rodríguez, M. Vizcaya-Moreno, Marco Leo, Neurocomputing, (2023), Cited By: 2
	- [Early Detection of Alzheimer's Disease: The Importance of Speech Analysis](https://doi.org/10.1109/ICAAIC56838.2023.10140703) - Kritesh Rauniyar, Shuvam Thakur, Aayush Nevatia, P. G. Shambharkar, 2023 2nd International Conference on Applied Artificial Intelligence and Computing (ICAAIC), (2023), Cited By: 0
	- [Alzheimer’s Dementia Speech (Audio vs. Text): Multi-Modal Machine Learning at High vs. Low Resolution](https://doi.org/10.3390/app13074244) - Prachee Priyadarshinee, Christopher Johann Clarke, J. Melechovský, Cindy Ming Ying Lin, B. B. T., Jer-Ming Chen, Applied Sciences, (2023), Cited By: 7
	- [An automated speech analysis system for the detection of cognitive decline in elderly](https://doi.org/10.1007/s10772-023-10016-1) - C. Loizou, M. Pantzaris, International Journal of Speech Technology, (2023), Cited By: 0
	- [Feature Selection and Text Embedding for Detecting Dementia from Spontaneous Cantonese](https://doi.org/10.1109/ICASSP49357.2023.10095140) - Xiaoquan Ke, M. Mak, H. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2023), Cited By: 1
	- [Who needs context? Classical techniques for Alzheimer’s disease detection](https://doi.org/10.18653/v1/2023.clinicalnlp-1.13) - Behrad Taghibeyglou, Frank Rudzicz, Clinical Natural Language Processing Workshop, (2023), Cited By: 0
	- [Speech-based detection of multi-class Alzheimer's disease classification using machine learning](https://doi.org/10.1007/s41060-023-00475-9) - Tripti Tripathi, Rakesh Kumar, International Journal of Data Science and Analysis, (2023), Cited By: 0
	- [Distinguishable features of spontaneous speech in Alzheimer’s clinical syndrome and healthy controls](https://doi.org/10.1080/13825585.2023.2221020) - E. Burke, J. Gunstad, Olesia Pavlenko, Phillip Hamrick, Neuropsychology, development, and cognition. Section B, Aging, neuropsychology and cognition, (2023), Cited By: 2
	- [Detection of Mild Cognitive Impairment From Non-Semantic, Acoustic Voice Features: The Framingham Heart Study](https://doi.org/10.2196/55126) - Huitong Ding, Adrian Lister, C. Karjadi, Rhoda Au, Honghuang Lin, Brian Bischoff, Phillip H Hwang, JMIR Aging, (2023), Cited By: 0
	- [Performance of machine learning algorithms for dementia assessment: impacts of language tasks, recording media, and modalities](https://doi.org/10.1186/s12911-023-02122-6) - Mahboobeh (Mah) Parsapoor (Parsa), Muhammad Raisul Alam, Alex Mihailidis, BMC Medical Informatics and Decision Making, (2023), Cited By: 7
- 2022
	- [Automatic cognitive assessment: Combining sparse datasets with disparate cognitive scores](https://doi.org/10.21437/interspeech.2022-10205) - B. Mirheidari, Daniel Blackburn, H. Christensen, Interspeech, (2022), Cited By: 0
	- [Using Spectral Sequence-to-Sequence Autoencoders to Assess Mild Cognitive Impairment](https://doi.org/10.1109/icassp43922.2022.9746148) - Mercedes Vetráb, José Vicente Egas López, R. Balogh, N. Imre, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 2
	- [Automatic Selection of Discriminative Features for Dementia Detection in Cantonese-Speaking People](https://doi.org/10.21437/interspeech.2022-10122) - Xiaoquan Ke, M. Mak, Helen M. Meng, Interspeech, (2022), Cited By: 2
	- [Artificial Intelligence-Enabled End-To-End Detection and Assessment of Alzheimer’s Disease Using Voice](https://doi.org/10.3390/brainsci13010028) - Felix Agbavor, Hualou Liang, Brain Science, (2022), Cited By: 15
	- [Augmented Adversarial Self-Supervised Learning for Early-Stage Alzheimer's Speech Detection](https://doi.org/10.21437/interspeech.2022-943) - Longfei Yang, Wenqing Wei, Sheng Li, Jiyi Li, T. Shinozaki, Interspeech, (2022), Cited By: 3
	- [A Multimodal Approach for Dementia Detection from Spontaneous Speech with Tensor Fusion Layer](https://doi.org/10.1109/BHI56158.2022.9926818) - Loukas Ilias, D. Askounis, J. Psarras, 2022 IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI), (2022), Cited By: 5
	- [A Dementia Classification Based on Speech Analysis of Casual Talk During a Clinical Interview](https://doi.org/10.1109/LifeTech53646.2022.9754933) - Shunya Hanai, Shohei Kato, Takuto Sakuma, R. Ohdake, M. Masuda, Hirohisa Watanabe, Global Conference on Life Sciences and Technologies, (2022), Cited By: 3
	- [Automated detection of mild cognitive impairment and dementia from voice recordings: A natural language processing approach](https://doi.org/10.1002/alz.12721) - S. Amini, Boran Hao, Lifu Zhang, Mengting Song, Aman Gupta, C. Karjadi, V. Kolachalama, R. Au, I. Paschalidis, Alzheimer's & Dementia, (2022), Cited By: 27
	- [Cognitive Digital Biomarkers from Automated Transcription of Spoken Language](https://doi.org/10.14283/jpad.2022.66) - N. Tavabi, D. Stück, A. Signorini, C. Karjadi, T. Al Hanai, M. Sandoval, C. Lemke, J. Glass, S. Hardy, M. Lavallee, B. Wasserman, T. F. Ang, C. Nowak, R. Kainkaryam, L. Foschini, R. Au, The journal of prevention of Alzheimer's disease, (2022), Cited By: 11
	- [Computer-Aided Dementia Detection: How Informative Are Your Features?](https://doi.org/10.1109/RTSI55261.2022.9905097) - Edoardo Stoppa, Guido Walter Di Donato, Natalie Parde, M. Santambrogio, International Forum on Research and Technologies for Society and Industry Leveraging a better tomorrow, (2022), Cited By: 3
	- [Deep Learning Approaches for Detecting Alzheimer's Dementia from Conversational Speech of ILSE Study](https://doi.org/10.21437/interspeech.2022-10942) - Ayimnisagul Ablimit, K. Scholz, Tanja Schultz, Interspeech, (2022), Cited By: 3
	- [Automatic Audio-based Screening System for Alzheimer’s Disease Detection](https://doi.org/10.1109/SMC53654.2022.9945127) - Sheng-Ya Lin, Ho-Ling Chang, Jwu-Jia Hwang, Thiri Wai, Yu-Ling Chang, Li-Chen Fu, IEEE International Conference on Systems, Man and Cybernetics, (2022), Cited By: 0
	- [A Pre-trained Neural Network to Predict Alzheimer’s Disease at an Early Stage](https://doi.org/10.14569/ijacsa.2022.0130524) - Ragavamsi Davuluri, Ragupathy Rengaswamy, International Journal of Advanced Computer Science and Applications, (2022), Cited By: 5
	- [Revealing the Roles of Part-of-Speech Taggers in Alzheimer Disease Detection: Scientific Discovery Using One-Intervention Causal Explanation](https://doi.org/10.2196/36590) - Bingyang Wen, Ning Wang, K.P. Subbalakshmi, R. Chandramouli, JMIR Formative Research, (2022), Cited By: 0
	- [Multimodal fusion for alzheimer’s disease recognition](https://doi.org/10.1007/s10489-022-04255-z) - Yangwei Ying, Tao Yang, Hong Zhou, Applied intelligence (Boston), (2022), Cited By: 13
	- [Impact of Acoustic Noise on Alzheimer's Disease Detection from Speech: Should You Let Baby Cry?](https://doi.org/10.48550/arXiv.2203.17110) - Jekaterina Novikova, arXiv.org, (2022), Cited By: 0
	- [Predicting Scores on the Mini-Mental State Examination (MMSE) from Spontaneous Speech](https://doi.org/10.3390/bs12090339) - A. Bueno-Cayo, Minerva del Rio Carmona, Rosa Castell-Enguix, I. Iborra-Marmolejo, Mike Murphy, T. Q. Irigaray, José Francisco Cervera, C. Moret-Tatay, Behavioral Science, (2022), Cited By: 2
	- [Automated text‐level semantic markers of Alzheimer's disease](https://doi.org/10.1002/dad2.12276) - Camila Sanz, Facundo Carrillo, A. Slachevsky, G. Forno, Maria Luisa Gorno Tempini, Roque Villagra, A. Ibáñez, E. Tagliazucchi, Adolfo M. García, Alzheimer's & Dementia, (2022), Cited By: 16
	- [A Transfer Learning Method for Detecting Alzheimer's Disease Based on Speech and Natural Language Processing](https://doi.org/10.3389/fpubh.2022.772592) - Ning-hong Liu, Kexue Luo, Zhenming Yuan, Yan Chen, Frontiers in Public Health, (2022), Cited By: 20
	- [Exploring Dementia Detection from Speech: Cross Corpus Analysis](https://doi.org/10.1109/icassp43922.2022.9747167) - Ayimnisagul Ablimit, Catarina Botelho, A. Abad, Tanja Schultz, I. Trancoso, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2022), Cited By: 12
	- [An Evaluation on Information Composition in Dementia Detection Based on Speech](https://doi.org/10.1109/ACCESS.2022.3203068) - Chuheng Zheng, Mondher Bouazizi, T. Ohtsuki, IEEE Access, (2022), Cited By: 4
	- [Semantic Feature Extraction Using SBERT for Dementia Detection](https://doi.org/10.3390/brainsci12020270) - Yamanki Santander-Cruz, Sebastián Salazar-Colores, W. J. Paredes-García, Humberto Guendulain-Arenas, S. Tovar-Arriaga, Brain Science, (2022), Cited By: 25
	- [Exploring linguistic feature and model combination for speech recognition based automatic AD detection](https://doi.org/10.48550/arXiv.2206.13758) - Yi Wang, Tianzi Wang, Zi Ye, Lingwei Meng, Shoukang Hu, Xixin Wu, Xunying Liu, Helen M. Meng, Interspeech, (2022), Cited By: 12
	- [Detecting Alzheimer's Disease Based on Acoustic Features Extracted from Pre-trained Models](https://doi.org/10.1007/978-3-031-20503-3_22) - Kangdi Mei, Zhiqiang Guo, Zhaoci Liu, Lijuan Liu, Xin Li, Zhenhua Ling, CAAI International Conference on Artificial Intelligence, (2022), Cited By: 1
	- [Evaluation of Wav2Vec Speech Recognition for Speakers with Cognitive Disorders](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, Filip Polák, A. Bartoš, M. Zapletalová, Martin Víta, International Conference on Text, Speech and Dialogue, (2022), Cited By: 4
	- [Novel Framework for Alzheimer Early Diagnosis using Inductive Transfer Learning Techniques](https://doi.org/10.1109/eSmarTA56775.2022.9935379) - H. Sahu, Santosh Kumar, S. Alsamhi, M. K. Chaube, E. Curry, 2022 2nd International Conference on Emerging Smart Technologies and Applications (eSmarTA), (2022), Cited By: 5
- 2021
	- [Detecting Alzheimer’s Disease from Speech Using Neural Networks with Bottleneck Features and Data Augmentation](https://doi.org/10.1109/ICASSP39728.2021.9413566) - Zhaoci Liu, Zhiqiang Guo, Zhenhua Ling, Yunxia Li, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 15
	- [Multi-Task Estimation of Age and Cognitive Decline from Speech](https://doi.org/10.1109/ICASSP39728.2021.9414642) - Yilin Pan, Venkata Srikanth Nallanthighal, D. Blackburn, H. Christensen, Aki Härmä, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 7
	- [Development of the Cuhk Elderly Speech Recognition System for Neurocognitive Disorder Detection Using the Dementiabank Corpus](https://doi.org/10.1109/ICASSP39728.2021.9413634) - Zi Ye, Shoukang Hu, Jinchao Li, Xurong Xie, Mengzhe Geng, Jianwei Yu, Junhao Xu, Boyang Xue, Shansong Liu, Xunying Liu, H. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 31
	- [Detecting Dementia from Speech and Transcripts using Transformers](https://doi.org/10.1016/j.csl.2023.101485) - Loukas Ilias, D. Askounis, J. Psarras, Computer Speech and Language, (2021), Cited By: 21
	- [Identifying Cognitive Impairment Using Sentence Representation Vectors](https://doi.org/10.21437/interspeech.2021-915) - B. Mirheidari, Yilin Pan, Daniel Blackburn, R. O'Malley, H. Christensen, Interspeech, (2021), Cited By: 3
	- [An Evaluation of Machine Learning Classifiers for Prediction of Alzheimer's Disease, Mild Cognitive Impairment and Normal Cognition](https://doi.org/10.1109/ICTC52510.2021.9620780) - Payam Hosseinzadeh Kasani, Sara Hosseinzadeh Kasani, Yeshin Kim, C. Yun, S. Choi, Jae-Won Jang, Information and Communication Technology Convergence, (2021), Cited By: 3
	- [Linguistic Parameters of Spontaneous Speech for Identifying Mild Cognitive Impairment and Alzheimer Disease](https://doi.org/10.1162/coli_a_00428) - V. Vincze, Martina Katalin Szabó, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, International Conference on Computational Logic, (2021), Cited By: 7
	- [Correlating natural language processing and automated speech analysis with clinician assessment to quantify speech-language changes in mild cognitive impairment and Alzheimer’s dementia](https://doi.org/10.1186/s13195-021-00848-x) - Anthony Yeung, Andrea Iaboni, E. Rochon, M. Lavoie, Calvin Santiago, Maria Yancheva, Jekaterina Novikova, Mengdan Xu, Jessica Robin, Liam D. Kaufman, Fariya Mostafa, Alzheimer's Research & Therapy, (2021), Cited By: 46
	- [Acoustic and Linguistic Analyses to Assess Early-Onset and Genetic Alzheimer’s Disease](https://doi.org/10.1109/ICASSP39728.2021.9414009) - P. A. Pérez-Toro, J. C. Vásquez-Correa, T. Arias-Vergara, P. Klumpp, M. Sierra-Castrillón, M. E. Roldán-López, D. Aguillón, L. Hincapié-Henao, C. A. Tóbon-Quintero, T. Bocklet, M. Schuster, J. Orozco-Arroyave, Elmar Nöth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 7
	- [A Comparative Study of Acoustic and Linguistic Features Classification for Alzheimer's Disease Detection](https://doi.org/10.1109/ICASSP39728.2021.9414147) - Jinchao Li, Jianwei Yu, Zi Ye, Simon Wong, M. Mak, B. Mak, Xunying Liu, Helen M. Meng, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2021), Cited By: 22
	- [Exploring neural models for predicting dementia from language](https://doi.org/10.1016/J.CSL.2020.101181) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Computer Speech and Language, (2021), Cited By: 10
	- [Exploiting linguistic information from Nepali transcripts for early detection of Alzheimer's disease using natural language processing and machine learning techniques](https://doi.org/10.1016/j.ijhcs.2021.102761) - Surabhi Adhikari, Surendrabikram Thapa, Usman Naseem, Priyanka Singh, H. Huo, Gnana Bharathy, Mukesh Prasad, Int. J. Hum. Comput. Stud., (2021), Cited By: 27
- 2020
	- [Transformer-based deep neural network language models for Alzheimer’s disease detection from targeted speech](https://doi.org/10.21203/rs.3.rs-49267/v1) - A. Roshanzamir, H. Aghajan, M. Baghshah, , (2020), Cited By: 3
	- [Uncertainty-Aware Multi-Modal Ensembling for Severity Prediction of Alzheimer's Dementia](https://arxiv.org/abs/2010.01440) - U. Sarawgi, W. Zulfikar, Rishab Khincha, P. Maes, arXiv.org, (2020), Cited By: 2
	- [An Assessment of Paralinguistic Acoustic Features for Detection of Alzheimer's Dementia in Spontaneous Speech](https://doi.org/10.1109/JSTSP.2019.2955022) - F. Haider, S. de la Fuente, S. Luz, IEEE Journal on Selected Topics in Signal Processing, (2020), Cited By: 122
	- [Combining Prosodic, Voice Quality and Lexical Features to Automatically Detect Alzheimer's Disease](https://arxiv.org/abs/2011.09272) - Mireia Farr'us, Joan Codina-Filbà, arXiv.org, (2020), Cited By: 8
	- [Predicting Prodromal Dementia Using Linguistic Patterns and Deficits](https://doi.org/10.1109/ACCESS.2020.3029907) - Ahmed H. Alkenani, Yuefeng Li, Yue Xu, Qing Zhang, IEEE Access, (2020), Cited By: 6
	- [Using narratives in differential diagnosis of neurodegenerative syndromes.](https://doi.org/10.1016/j.jcomdis.2020.105994) - Yasmeen Faroqi-Shah, Ashlyn Treanor, N. Ratner, Bronte Ficek, K. Webster, K. Tsapkini, Journal of Communication Disorders, (2020), Cited By: 16
	- [Linguistic markers predict onset of Alzheimer's disease](https://doi.org/10.1016/j.eclinm.2020.100583) - Elif Eyigoz, Sachin Mathur, M. Santamaria, G. Cecchi, M. Naylor, EClinicalMedicine, (2020), Cited By: 108
- 2019
	- [Multilingual prediction of Alzheimer’s disease through domain adaptation and concept-based language modelling](https://doi.org/10.18653/v1/N19-1367) - Kathleen C. Fraser, N. Linz, Bai Li, K. L. Fors, Frank Rudzicz, A. König, J. Alexandersson, P. Robert, D. Kokkinakis, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 18
	- [Multilingual word embeddings for the assessment of narrative speech in mild cognitive impairment](https://doi.org/10.1016/j.csl.2018.07.005) - Kathleen C. Fraser, K. L. Fors, D. Kokkinakis, Computer Speech and Language, (2019), Cited By: 45
	- [A Neural Model for Predicting Dementia from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - Weirui Kong, Hyeju Jang, G. Carenini, Thalia Shoshana Field, Machine Learning in Health Care, (2019), Cited By: 15
	- [Automatic Hierarchical Attention Neural Network for Detecting AD](https://doi.org/10.21437/interspeech.2019-1799) - Yilin Pan, B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2019), Cited By: 29
	- [Detecting dementia in Mandarin Chinese using transfer learning from a parallel corpus](https://doi.org/10.18653/v1/N19-1199) - Bai Li, Y. Hsu, Frank Rudzicz, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 11
	- [Detecting Alzheimer's Disease by estimating attention and elicitation path through the alignment of spoken picture descriptions with the picture prompt](https://arxiv.org/abs/1910.00515) - B. Mirheidari, Yilin Pan, Traci Walker, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, arXiv.org, (2019), Cited By: 6
	- [An Automatic Assessment System for Alzheimer’s Disease Based on Speech Using Feature Sequence Generator and Recurrent Neural Network](https://doi.org/10.1038/s41598-019-56020-x) - Yi-Wei Chien, Sheng-Yi Hong, W. Cheah, Li-Hung Yao, Yu-Ling Chang, L. Fu, Scientific Reports, (2019), Cited By: 44
	- [Predicting MCI Status From Multimodal Language Data Using Cascaded Classifiers](https://doi.org/10.3389/fnagi.2019.00205) - Kathleen C. Fraser, Kristina Lundholm Fors, M. Eckerström, Fredrik Öhman, D. Kokkinakis, Frontiers in Aging Neuroscience, (2019), Cited By: 63
	- [Automatic Diagnosis of Alzheimer’s Disease Using Neural Network Language Models](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, Sebastian Wankerl, Elmar Nöth, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2019), Cited By: 53
	- [An Attention-Based Hybrid Network for Automatic Detection of Alzheimer's Disease from Narrative Speech](https://doi.org/10.21437/interspeech.2019-2872) - Jun Chen, Ji Zhu, Jieping Ye, Interspeech, (2019), Cited By: 32
- 2018
	- [Augmenting word2vec with latent Dirichlet allocation within a clinical application](https://doi.org/10.18653/v1/N19-1414) - Akshay Budhkar, Frank Rudzicz, North American Chapter of the Association for Computational Linguistics, (2018), Cited By: 9
	- [Detecting cognitive impairments by agreeing on interpretations of linguistic features](https://doi.org/10.18653/v1/N19-1146) - Zining Zhu, Jekaterina Novikova, Frank Rudzicz, North American Chapter of the Association for Computational Linguistics, (2018), Cited By: 25
	- [Speech Processing for Early Alzheimer Disease Diagnosis: Machine Learning Based Approach](https://doi.org/10.1109/aiccsa.2018.8612831) - Randa Ben Ammar, Yassine Ben Ayed, ACS/IEEE International Conference on Computer Systems and Applications, (2018), Cited By: 24
	- [Detecting Signs of Dementia Using Word Vector Representations](https://doi.org/10.21437/Interspeech.2018-1764) - B. Mirheidari, D. Blackburn, Traci Walker, A. Venneri, M. Reuber, H. Christensen, Interspeech, (2018), Cited By: 52
	- [Deep language space neural network for classifying mild cognitive impairment and Alzheimer-type dementia](https://doi.org/10.1371/journal.pone.0205636) - S. Orimaye, Jojo Sze-Meng Wong, C. P. Wong, PLoS ONE, (2018), Cited By: 46
	- [Detecting Alzheimer's Disease Using Gated Convolutional Neural Network from Audio Data](https://doi.org/10.21437/Interspeech.2018-1713) - Tifani Warnita, Nakamasa Inoue, K. Shinoda, Interspeech, (2018), Cited By: 38
	- [Learning multiview embeddings for assessing dementia](https://doi.org/10.18653/v1/D18-1304) - Chloé Pou-Prom, Frank Rudzicz, Conference on Empirical Methods in Natural Language Processing, (2018), Cited By: 14
- 2017
	- [Longitudinal Monitoring and Detection of Alzheimer's Type Dementia from Spontaneous Speech Data](https://doi.org/10.1109/CBMS.2017.41) - S. Luz, 2017 IEEE 30th International Symposium on Computer-Based Medical Systems (CBMS), (2017), Cited By: 39
	- [INVESTIGATING PREDICTORS OF COGNITIVE DECLINE USING MACHINE LEARNING](https://doi.org/10.1016/j.jalz.2017.06.1257) - R. Casanova, Santiago Saldana, M. Lutz, B. Plassman, M. Kuchibhatla, K. Hayden, Alzheimer's & Dementia, (2017), Cited By: 42
- 2016
	- [Detecting Mild Cognitive Impairment from Spontaneous Speech by Correlation-Based Phonetic Feature Selection](https://doi.org/10.21437/Interspeech.2016-384) - G. Gosztolya, L. Tóth, Tamás Grósz, V. Vincze, I. Hoffmann, Gréta Szatlóczki, M. Pákáski, J. Kálmán, Interspeech, (2016), Cited By: 35
- 2015
	- [Linguistic Features Identify Alzheimer's Disease in Narrative Speech.](https://doi.org/10.3233/JAD-150520) - Kathleen C. Fraser, Jed A. Meltzer, Frank Rudzicz, Journal of Alzheimer's Disease, (2015), Cited By: 597

### 5. Related works in other domains

#### Aphasia
- 2020
	- [BlaBla: Linguistic Feature Extraction for Clinical Analysis in Multiple Languages](https://doi.org/10.21437/interspeech.2020-2880) - Abhishek Shivkumar, J. Weston, R. Lenain, E. Fristed, Interspeech, (2020), Cited By: 6

#### Asthma
- 2020
	- [Analysis of Acoustic Features for Speech Sound Based Classification of Asthmatic and Healthy Subjects](https://doi.org/10.1109/ICASSP40776.2020.9054062) - Shivani Yadav, Merugu Keerthana, D. Gope, U. Krishnaswamy, P. Ghosh, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2020), Cited By: 23

#### Depression
- 2023
	- [Classifying Dementia in the Presence of Depression: A Cross-Corpus Study](https://doi.org/10.21437/interspeech.2023-1997) - Franziska Braun, S. Bayerl, P. A. P'erez-Toro, F. Hönig, H. Lehfeld, T. Hillemacher, Elmar Nöth, T. Bocklet, K. Riedhammer, Interspeech, (2023), Cited By: 2

#### Disfluency
- 2020
	- [Improving Disfluency Detection by Self-Training a Self-Attentive Model](https://doi.org/10.18653/v1/2020.acl-main.346) - Paria Jamshid Lou, Mark Johnson, Annual Meeting of the Association for Computational Linguistics, (2020), Cited By: 42
	- [Re-framing Incremental Deep Language Models for Dialogue Processing with Multi-task Learning](https://doi.org/10.18653/V1/2020.COLING-MAIN.43) - Morteza Rohanian, Julian Hough, International Conference on Computational Linguistics, (2020), Cited By: 10
- 2019
	- [Neural Constituency Parsing of Speech Transcripts](https://doi.org/10.18653/v1/N19-1282) - Paria Jamshid Lou, Yufei Wang, Mark Johnson, North American Chapter of the Association for Computational Linguistics, (2019), Cited By: 25

#### Parkinson’s Disease
- 2021
	- [Supervised Speech Representation Learning for Parkinson's Disease Classification](https://arxiv.org/abs/2106.00531) - Parvaneh Janbakhshi, I. Kodrasi, ITG Conference on Speech Communication, (2021), Cited By: 11
- 2020
	- [Using X-Vectors to Automatically Detect Parkinson’s Disease from Speech](https://doi.org/10.1109/ICASSP40776.2020.9053770) - L. Moro-Velázquez, J. Villalba, N. Dehak, IEEE International Conference on Acoustics, Speech, and Signal Processing, (2020), Cited By: 45


***

_This file was generated by [awesome-paper-list-generator](https://github.com/billzyx/awesome-paper-list-generator), on 2024-09-14_
