---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/emeklivandal
slides: example
summary: An example of using the in-built project page.
tags:
- Jupyter Notebook
title: Senior Design Project
url_code: "https://github.com/AlparslanErol/Senior_Design_Project"
url_pdf: ""
url_slides: ""
url_video: ""
---

# Senior_Design_Project
Boğaziçi University Electrical Electronics Engineering EE 492 Senior Design Project

# Summary

  Machine learning is considered an important method for the detection of anomaly network traffic by an intrusion detection system (IDS). The three big and common schemes borrowed from the machine-learning community in recent academic research are neural networks, support vector machines (SVM) and decision-making trees or forests with boosting and ensemble methods.\
 \
  In this paper, some machine learning and deep dearning algorithms such supervised learning as  gaussian naive bayes (GNB), decision-making trees (DT), ada boost classifier (ABC), random forest (RF), light gradient boosting (LGB) and such unsupervised deep learning method as Auto-Encoder (AE) are implemented with a uniform environment and the purpose of exploring the practice and issues of using these approaches in detecting anomaly behaviors. After data preprocessing and feature selection part some manipulation are implemented to the dataset. GNB, DT, ABC, RF and LGB are implemented and found that LGB has the best performance. Then deep dive into LGB model and used binary and multiclass classisficaiton methods with parameter tuning. Because of balance importance cross entropy and for data unbalancy between normal and attack type variables, focal loss is used to down-weight for normal type data and get the best solutions. Also an unsupervised learning (AE) added to the list and all this algorithms are compared.\
\
  The experiments were conducted on the intrusion detection dataset called KDD’99 cup dataset. After exploratory data analysis, it is found that, 1 feature has no impact on target, 3 feature have highly correlated with each other, ~78% of initial data are duplicated and some features are not important for target when they are compared with the important features.\
  The comparison of the different machine learning model results with and without dimensionality reduction is also done.
  
  # Conclusion
  
  The main purpose of this project is to developed machine learning models that can detect different anomaly attack types. Some machine learning and deep dearning algorithms such supervised learning as  gaussian naive bayes (GNB), decision-making trees (DT), ada boost classifier (ABC), random forest (RF), light gradient boosting (LGB) and such unsupervised deep learning method as Auto-Encoder (AE) are implemented with a uniform environment and the purpose of exploring the practice and issues of using these approaches in detecting anomaly behaviors. After data preprocessing and feature selection part some manipulation are implemented to the dataset. GNB, DT, ABC, RF and LGB are implemented and found that LGB has the best performance. Then deep dive into LGB model and used binary and multiclass classisficaiton methods with parameter tuning. Because of balance importance cross entropy and for data unbalancy between normal and attack type variables, focal loss is used to down-weight for normal type data and get the best solutions. Also an unsupervised learning (AE) added to the list and all this algorithms are compared and all results are given above.\
\
  For future project, after precise feature extraction to BOUN (Boğaziçi University) network attack dataset, light gradient boosting model with focal loss and parameter optimization can use for supervised learning or auto-encoder can be used for unsupervised learning.
  
# Bibliography

[1]	T. Ohashi, (2014). “Wireless base station, wireless apparatus, wireless controlling apparatus, and communication method” US Patent 8,676,263.\
[2]	 I. Kotenko and A. Ulanov, ``Agent-based simulation of DDOS attacks and defense mechanisms,'' Int. J. Comput. , vol. 4, no. 2, pp. 113123, 2014.\
[3]	Alterawiki.com. (2014). CPRI Compression - Altera Wiki. [online] Available at: http://www.alterawiki.com/wiki/CPRI_Compression [Accessed 24 Sep. 2016].\
[4]	Liu, S. and Huang, B. (2010). “CPRI link multiplex transmission method and system”. US Patent 7,680,149.\
[5]	Jiang, Y., Guo, X. and Xia, Y. (2011). “Method and device for transferring multi-standard radio service data”. US Patent 8,018,910.\
[6]	Akhter, M. and Darnell, B. (2015). “Method and apparatus for efficient baseband unit processing in a communication system”. US Patent 9,215,296.\
[7]	W. Lee, S. J. Stolfo, K. W. Mok, “A Data Mining Framework for Building Intrusion Detection Models”, IEEE Symposium on Security and Privacy, Oakland, California, 1999a, pp. 120-132.\
[8]	R. Agarwal, and M. V. Joshi, “PNrule: A New Framework for Learning Classifier Models in Data Mining”, Technical Report TR 00-015, Department of Computer Science, University of Minnesota, 2000.\
[9]	I. Levin, “KDD-99 Classifier Learning Contest LLSoft’s Results Overview”, SIGKDD Explorations, ACM SIGKDD, January 2000, Vol. 1 (2), pp. 67-75.\
[10]	 L. Ertoz, M. Steinbach, and V. Kumar, “Finding Clusters of Different Sizes, Shapes, and Densities in Noisy, High Dimensional Data”, Technical Report.\
[11]	 D. Y. Yeung, and C. Chow, “Parzen-window Network Intrusion Detectors”, Sixteenth International Conference on Pattern Recognition, Quebec City, Canada, August 2002, pp. 11-15.\
[12]	 K. Kendall, “A Database of Computer Attacks for the Evaluation of Intrusion Detection Systems”, Master's Thesis, MIT, Boston, MA, 1998.\
[13]	 Hinton G, Deng L, Yu D, Dahl GE, Mohamed, "Deep neural networks for acoustic modeling in speech recognition," IEEE Signal Process, vol. 29, no. 6, p. 82-97, 2012.\
[14]	 L. Arnold, S. Rebecchi, S. Chevallier, H. Paugam-Moisy, "An Introduction to Deep Learning," in European Symposium on Artificial Neural Networks, Bruges (Belgium), 2011.\
[15]	 Protić, D. (2018). Review of KDD Cup '99, NSL-KDD and Kyoto 2006+ datasets. Vojnotehnicki glasnik, 66(3), pp.580-596.\
[16]	 Hasan, Md. Al & Nasser, Mohammed & Ahmad, Shamim & Molla, Md. Khademul. (2016). Feature Selection for Intrusion Detection Using Random Forest. Journal of Information Security. 07. 129-140. 10.4236/jis.2016.73009.\
[17]	 Lin, T., Goyal, P., Girshick, R., He, K. and Dollar, P. (2018). Focal loss for dense object detection. IEEE Transactions on Pattern Analysis and Machine Intelligence, pp.1-1.\

