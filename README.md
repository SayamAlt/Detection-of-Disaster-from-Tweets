# Detection-of-Disaster-from-Tweets

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programmatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:


![Disaster Tweet](https://storage.googleapis.com/kaggle-media/competitions/tweet_screenshot.png)


The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

## Objective

Develop a machine learning model that predicts which Tweets are about real disasters and which ones aren’t. 

## Python's Libraries Used

<ul>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Seaborn</li>
  <li>Matplotlib.pyplot</li>
  <li>Warnings</li>
  <li>NLTK</li>
  <li>re</li>
  <li>string</li>
  <li>SymSpellPy</li>
  <li>Sklearn</li>
  <li>XGBoost</li>
  <li>WordCloud</li>
</ul>

## Predictive Accuracy of Machine Learning Models Used

<table>
  <tr>
    <td><b>Model Name</b></td>
    <td><b>Accuracy Score</b></td>
  </tr>
  <tr>
    <td>Random Forests Classifier</td>
    <td>79.06%</td>
  </tr>
  <tr>
    <td>Decision Tree Classifier</td>
    <td>75.38%</td>
  </tr>
  <tr>
    <td>Multinomial Naive Bayes</td>
    <td>80.53%</td>
  </tr>
  <tr>
    <td>Support Vector Classifier</td>
    <td>79.62%</td>
  </tr>
  <tr>
    <td>K Nearest Neighbors</td>
    <td>68.89%</td>
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>79.06%</td>
  </tr>
  <tr>
    <td>XG Boost Classifier</td>
    <td>77.64%</td>
  </tr>
</table>

## Best Performing Algorithm

<p>The Multinomial Naive Bayes made the most accurate predictions on detection of a real disaster from any tweet given in the dataset with an overall accuracy of almost 81%. This proves the effectiveness of the Multinomial Naive Bayes algorithm in text classification tasks.</p>

## Worst Performing Algorithm

<p>K Nearest Neighbors had the worst performance among all the ML algorithms used, having an accuracy of just over 68%.</p>

## Acknowledgments

This dataset was created by the company figure-eight and originally shared on their ['Data For Everyone'](https://appen.com/datasets-resource-center/) website here. 

