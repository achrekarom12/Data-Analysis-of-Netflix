# Data Analysis of Netflix Movies and TV Shows
Dataset used: https://www.kaggle.com/datasets/shivamb/netflix-shows
<br>
Problem Statement: To perform data preprocessing and cleaning on the given data and to conclude some useful insights about the data. <br>
This repository contains three main modules: <br>
<ol>
<li> Exploratory Data analysis for Netflix dataset </li>
Functions Covered: 
<ul>
  <li>head()</li>
  <li>tail()</li>
  <li>size</li>
  <li>shape</li>
  <li>columns</li>
  <li>dtypes</li>
  <li>info()</li>
  <li>duplicated()</li>
  <li>isnull()</li>
  <li>sum()</li>
  <li>sns.heatmap()</li>
  <li>isin()</li>
  <li>str.contains</li>
  <li>pd.to_datetime</li>
  <li>drop()</li>
  <li>value_counts()</li>
  <li>count()</li>
  <li>plot()</li>
  <li>groupby()</li>
  <li>sns.countplot</li>
  <li>AND, OR Operators</li>
  <li>unique()</li>
  <li>dropna()</li>
  <li>copy()</li>
  <li>astype()</li>
  <li>pd.concat()</li>
  <li>sort_values()</li>
  <li>max()</li>
  <li>to_csv()</li>
</ul>
<br>
<li> Conclusive study and Inferences </li>
In this section we tried to find solution to some problems that will help in taking decisions. Below are the list of questions that we found could be useful for gaining insights.
<ul>
  <li>If producer wants to release a TV show then when it should be realesed in the year?</li>
  <li>If producer wants to release a movie then when it should be realesed in the year?</li>
  <li>Which ratings have overall influence in the movie market? Which is the most targeted audience in recent years?</li>
  <li>Give yearwise count of movies released.</li>
  <li>Which country has produced more number of titles?</li>
  <li>What viewers prefer most? Are they interested in long movies or short movies?</li>
  <li>Which genre is more in demand for movies?</li>
  <li>Worldcloud for genres</li>
</ul>
<br>

<li> Recommendation System </li>
Component Procedures of a Recommender:<br>
Recommenders mostly have 3 components i.e<br>
<ol>
<li> Candidate Generations: This method is responsible for generating smaller subsets of candidates to recommend to a user, given a huge pool of thousands of items. </li>
<li> Scoring Systems: Candidate Generations can be done by different Generators, so, we need to standardize everything and try to assign a score to each of the items in the subsets. This is done by the Scoring system. </li>
<li> Re-Ranking Systems: After the scoring is done, along with it the system takes into account other additional constraints to produce the final rankings. </li>
</ol>
There are two types of Candidate Generation Systems which are:
<ol>
<li> Content based filtering </li>
<li> Collaborative filtering </li>
</ol>
<br>
<br>
<h3>Concept of Cosine Similarity:</h3>
Cosine Similarity simply measures the similarity between two input vectors. The cosine similarity is described mathematically as the division between the dot product of vectors and the product of the euclidean norms or magnitude of each vector. 
<p align='center'><img width="459" alt="image" src="https://user-images.githubusercontent.com/88442486/194811882-9da84d06-68a7-47a6-beeb-5b7eb25814fe.png">
</p>
The similarity measurement is a measure of the cosine of the angle between the two non-zero vectors A and B.
Suppose the angle between the two vectors was 90 degrees. In that case, the cosine similarity will have a value of 0; this means that the two vectors are orthogonal or perpendicular to each other.
As the cosine similarity measurement gets closer to 1, then the angle between the two vectors A and B is smaller. The images below depict this more clearly.<br>
<p align='center'><img width="678" alt="image" src="https://user-images.githubusercontent.com/88442486/194812267-91a8588e-7da3-4079-ac63-4b57eb8a8efc.png">
<br>
</p>


<li> Tableau Dashboard for the Netflix Dataset </li>
It is an informative realtime dashboard for seeing all of the information regarding Netflix at glance.
<br>

Tableau Dashboard:
<img width="1470" alt="Screenshot 2022-10-08 at 9 11 54 AM" src="https://user-images.githubusercontent.com/88442486/194690365-38e31063-0a3f-4e05-810c-19fa8c647d7b.png">
