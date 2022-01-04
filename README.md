# Phishing-website-prediction

Phishing is a type of fraud wherein an attacker impersonates a reputable
company or person in order to get sensitive information such as login
credentials or account information via email or other communication
channels. Phishing is popular among attackers because it is easier to
persuade someone to click a malicious link that appears to be authentic
than it is to break through a computer's protection measures. <br/>

This project presents the applicability of Machine Learning algorithms in predicting
phishing attacks and concludes the positives and negatives. There are many Machine
Learning algorithms that are inspected to present the best machine learning algorithm to
predict and prevent the phishing attacks. We have extracted features from the URL like
Address Bar based Features, Abnormal Based Features, HTML & JavaScript based
Features and Domain based Features. We also present the numerical results of the machine
learning algorithms like Decision Tree, Random Forest, Support Vector Machine, K-Nearest
Neighbour, Logistic Regression, Naive Bayes, AdaBoost Classifier and Hybrid Ensembler.
And determine if a website is legitimate or not.

### Proposed Architecture

![image](https://user-images.githubusercontent.com/67074796/148006919-7454995c-8543-4d0a-9513-c37b3a551693.png)

In our work we use different
types of features from the given URL like: <br/><br/>
• URL-Based Features: The URL is the first thing to look at when determining whether
or not a website is phishing. As previously stated, phishing domain URLs contain
several distinguishing characteristics. When the URL is parsed, features linked to
these points are acquired.

• Page-Based Features: Page-Based Features make use of data from reputation
ranking systems to calculate information about pages. Some of these characteristics
indicate how trustworthy a website is.

• Content-Based Features: Obtaining these features necessitates an active scan of the
target domain. The contents of the page are analysed to see if the target domain is
being used for phishing.

And we will be using different machine learning algorithms like
• Logistic Regression
• Naive Bayes
• K-Nearest Neighbours
• Decision Tree
• SVM
• Random Forest
• AdaBoost
• Hybrid Ensembler
And compare the error percent and execution time and propose the best algorithm suited
with the additional features we think can be useful to accurately predict.

### Conclusion

![image](https://user-images.githubusercontent.com/67074796/148007392-4e2308a2-e953-4b43-a1d2-5063c503c7b0.png)

Phishing is a serious threat to users' personal information these days. Because detecting
phishing websites is a time-consuming task, the number of phishers is continually
expanding. To overcome the issue, researchers and experts worked on many approaches
and techniques, but it resulted in low rates of detection. We used a range of algorithm in our
work. Out of which Hybrid Ensembler gave the maximum training accuracy of “0.9863” and
test accuracy of “0.9620” and minimum training accuracy of “0.7096” and test accuracy of
“0.7015” as shown in the table below. Hence our Hybrid Ensembler is the best classifier for
predicting phishing websites.
