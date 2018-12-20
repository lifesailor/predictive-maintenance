# Predictive maintenance

A curated list of predictive maintenance resources. Inspired by [awesome-ml](https://github.com/sdukshis/awesome-ml) and [awesome-anomaly-detection](https://github.com/hoya012/awesome-anomaly-detection). 





## What is predictive maintenance?

[Predictive maintenance(PdM)](https://en.wikipedia.org/wiki/Predictive_maintenance) techniques are designed to help determine the condition of in-service equipment in order to predict when maintenance should be performed. 

The main promise of predictive maintenance is to allow convenient scheduling of corrective maintenance and to prevent unexpected equipment failures. The key is "the right information in the right time". 

[Prognostics](https://en.wikipedia.org/wiki/Prognostics), [Fault detection](https://en.wikipedia.org/wiki/Fault_detection_and_isolation) is similar concept to predictive maintenance. 







## Table of Content

1. Concept of predictive maintenance 

2. Predictive maintenance depending on the type of data.
   1. Vibration
   2. Sound

3. Predictive maintenance technique
   1. Signal Processing
   2. Anomaly Detection






## 1. Concept of predictive maintenance

#### Book

- An introduction to predictive maintenance | R.Keith Mobley | **[Elsevier Science(USA)' 2002]** | [pdf](http://www.irantpm.ir/wp-content/uploads/2008/02/an-introduction-to-predictive-maintenance.pdf)

  - This book clearly explains key concepts and basic techniques of predictive maintenance. At the first part of the book, it is explained that why predictive maintenance is important and how to justify it in financial aspects. The second part presents various techinques for each data type. Vibartion analysis, thermography, tribology, process parameters, ultrasonics, visual inspection, operating dynamics analysis are described in each chapter. 



#### Slide

- Introduction to Prognostics | N.Scott Clements | **[Annual Conference of the PHM Society' 2011]** | [pdf](https://www.phmsociety.org/sites/phmsociety.org/files/Tutorial%20Prognostics%20Clements.pdf)
- Introduction to Prognostics | Kai Goebel, Abhinav Saxena, Matt Daigle, Jose Celaya, Indranil Roychoudhury, Scott Clements |**[NASA Prognostics CoE' 2012]** | [pdf](http://ftp.phmsociety.org/sites/phmsociety.org/files/Tutorial_Prognostics.pdf)
  - The above slides explain prognostics is estimation of the remaining useful life of a component. Remaining useful life of a component can be expected to continue operating within its given specifications. The brief explanation of three methods for prognostics are provided.



#### Essay

- (ko) 2017 PHMAP Conference Review | Seulgi Lee | **[Data Mining & Quality Analytics Lab]** | [html](http://dmqm.korea.ac.kr/board/view.asp?B_CATEGORY=0&B_CODE=b_cReview&tID=105&sid=125&search_category=&searchstring=&gotopage=1&IDX=241)
  - I lack mechanically engineering and physical background. Such knowledge, of course, may be necessary, but the important thing is to properly predict the failure of the equipment. This resource gave me the courage to approach the problem as a data scientist, not as a mechanical engineer.





## 2. Predictive maintenance depending on the type of data

### 1. vibration

#### Slide

- Beginning vibration analysis with basic fundamentals | Jack Peters | **[CTC' 2015]** | [pdf](http://www.ctconline.com/pdf/pubTechPapers/01-Beginning%20Vibration%20Analysis.pdf)



#### Video

- Vibration Analysis Know-How: Quick Intro to Vibration Analysis | Jason Tranter | **[LUDECAINC' 2015]** | [Youtube](https://www.youtube.com/watch?v=ZyIyWrHVFkA)
  - Provides good introduction to vibration analysis



#### Publication

- Vibration Analysis and Diagnostic Guide | Jaafar Alsalaet | **[Unversity of Barash' 2012]** | [pdf](https://www.researchgate.net/profile/Jaafar_Alsalaet/publication/311420765_Vibration_Analysis_and_Diagnostic_Guide/links/584556ba08aeda696819fbb4/Vibration-Analysis-and-Diagnostic-Guide.pdf?origin=publication_detail)
- Vibration-based gearbox fault diagnosis using deep neural networks | Zhiqiang Chen, Shengcai Deng, Xudong Chen, Chuan Li, René-Vinicio Sanchez, Huafeng Qin| **[Journal of Vibroengineering' 2017]** | [pdf](https://www.researchgate.net/publication/318073540_Vibration-based_gearbox_fault_diagnosis_using_deep_neural_networks)
- Deep learning enabled fault diagnosis using time-frequency image analysis of rolling element bearings | David Verstraete, Andrés Ferrada, Enrique López Droguett, Viviana Meruane, Mohammad Modarre | **[Hindawi' 2017]** | [pdf](https://www.hindawi.com/journals/sv/2017/5067651/)
- Artificial intelligence for fault diagnosis of rotating machinery: A review | [pdf](https://www.sciencedirect.com/science/article/pii/S0888327018300748)
- Anomaly Detection in Rolling Element Bearings via Two-Dimensional Symbolic Aggregate Approximation | [pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.470.8629&rep=rep1&type=pdf)


### 2. sound

#### Interview

- Acoustic signals for predictive maintenance: An interview with Amnon Shenfeld of 3DSignals | Robin Whitlock | **[Renewable Energy Magazine' 2017]** [html](https://www.renewableenergymagazine.com/interviews/acoustic-signals-for-predictive-maintenance-an-interview-20170831)
  - The interview explains the advantage of using sound data for predictive maintenance. Only few sound sensors  or microphones you can pick up acoustic behavior of a whole bunch of machines, even track complex processes.



#### Publication

- Residual Error Based Anomaly Detection Using
  Auto-Encoder in SMD Machine Sound | Dong Yul Oh, Il Dong Yun | **[sensors' 2018]** | [pdf](https://www.mdpi.com/1424-8220/18/5/1308/pdf)
  - Transform the sound into a spectrogram and applied convolutional autoencoder to detect anomalies.

- Anomaly Detection Technique in Sound to Detect Faulty Equipment| Hisashi Uematsu, Yuma Koizumi, Shoichiro Saito, Akira Nakagawa, and Noboru Harada| **[NTT Technical review' 2017]** | [pdf](https://www.ntt-review.jp/archive/ntttechnical.php?contents=ntr201708fa5.pdf&mode=show_pdf)

  - Explains the reason why it is hard to apply supervised machine learning techinque for predictive maintenance using sound data. 

- Unsupervised Detection of Anomalous Sound based on Deep Learning and the Neyman-Pearson Lemma | Yuma Koizumi, Shoichiro Sait, Hisashi Uematsu, 
  Yuta Kawachi, and Noboru Harada | **[arXiv' 2018]** | [pdf](https://arxiv.org/pdf/1810.09133.pdf)

- Sound based fault detection system | Teemu Tossavainen | **[Aalto university' 2015]** | [pdf](<https://aaltodoc.aalto.fi/bitstream/handle/123456789/19221/master_Tossavainen_Teemu_2015.pdf?sequence=1&isAllowed=y>)




### 3. process parameter

#### Publication

- Recurrent auto-encoder model for large-scale industrial sensor signal analysis|Timothy Wong and Zhiyuan Luo| Royal Holloway | **[Arxiv' 2018]** | [pdf](https://arxiv.org/pdf/1807.03710.pdf) 







## 3. Predictive maintenance techinque

### 
