 Spear phishing has emerged as one of the most critical cybersecurity threats in the
 digital landscape, targeting individuals and organizations through highly personal
ized and deceptive emails designed to steal sensitive information or carry out mali
cious activities. Unlike traditional phishing attacks, spear phishing exploits context
specific knowledge and social engineering tactics, rendering conventional rule-based
 and signature-based detection systems largely ineffective. This thesis presents a com
prehensive machine learning-based detection framework enhanced with natural lan
guage processing (NLP) techniques to effectively identify and classify spear phishing
 emails. The study employs a variety of classical machine learning classifiers—Logistic
 Regression, Naive Bayes, Support Vector Machines (SVM), Decision Trees, K-Nearest
 Neighbors (KNN), Random Forest, and Gradient Boosting—applied to a combined
 dataset of near about 5,000 labeled emails from two publicly available sources. These
 emails were preprocessed and engineered to extract key features such as lexical pat
terns, header metadata, keyword frequency, sender-recipient relationships, and se
mantic cues within the message content. The feature selection process was informed
 by prior phishing research and known attack signatures. Using Python’s Scikit-learn
 library, each model was trained on 80% of the dataset and validated on the remaining
 20%. The evaluation metrics—accuracy, precision, recall, F1-score, confusion ma
trix, and AUC-ROC curves—provided a detailed analysis of the models’ performance.
 Logistic Regression and Naive Bayes achieved the highest accuracy (95%) and F1
score (0.95), while ensemble methods like Random Forest and Gradient Boosting also
 demonstrated strong results (F1-score of 0.93). Despite achieving high AUC scores,
 models like KNN and SVM showed comparatively lower recall, which is critical in
 minimizing false negatives. Beyond numerical performance, this research underscores
 the importance of integrating machine learning into real-world email filtering systems
 to detect spear phishing proactively.
 Keywords: Spear phishing, Privacy, Machine learning, Natural language processing,
 Phishing detection
