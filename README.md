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

<li> Tableau Dashboard for the Netflix Dataset </li>
It is an informative realtime dashboard for seeing all of the information regarding Netflix at glance.
<br>
