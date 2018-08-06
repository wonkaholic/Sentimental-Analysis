# Sentimental-Analysis

<p><b>Read Data and KPI.ipynb</b></p>
<p>First, I read the raw file, and checked if there's missing labels or texts in the file.</p>
<p>Then I check the KPIs distribution with plots.</p>


<p><b>Sentiment Analysis-Final.ipynb</b></p>
<p>I removed the N/A and unnecessary columns. </p>
<p>Then I created two new KPIs, I also checked the distribution of the KPIs. in real life, I might use log10 transformation to normalize the dataset, however, I applied Random Forest in the end, so transformation is not required.</p>
<p>I did tokenization, stemming, lemmatizing for data cleansing, and vectorization as final step before building the model.</p>
<p>Then I applied Random Forest, and I would like to see the result of different hyper tunning parameters.</p>
