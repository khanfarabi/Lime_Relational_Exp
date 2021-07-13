# Lime_Relational_Exp

In this project, we are explaining the predictions made by Machine Learning Model using LIME (https://github.com/marcotcr/lime). Here we have tried to represent LIME relational explanations. The Yelp review data is used in this experiment and the data is available in the link (https://drive.google.com/drive/folders/1o-UmrtdLdYVTvUhWd75khzSqppP1upPq?usp=sharing)

# Run the Code
The  path of the data files need to be setup according the system in the notebook. In the nodebook, in a cell  run the command Run_program() to get the output. To get the visualized outcomes in Relational_LIme_Exp notebooke run the command Run_program_all().

# Demo Output 
Review 142 is Truly Predicted: Positive 

LIME Relational Explanation:'161:0.029526448662763192', '109:0.029526448662763192', '155:0.029526448662763192', '150:0.029526448662763192', '7:8.855816846352782e-31'. Here 161,109,155,150, and 7 are related reviews to 142 and have positive contribution to the prediction. 

LIME Words Explanation: 'cheese:0.029526448662763192','immediately:0.029526448662763192,'definitely:0.029526448662763192'. Here chees,immediately, and definitely are the word explanations
# Demo Visualized Output
# 1. Justification of the Prediction of the review query in terms of graph
The query review is currectly predicted as either positive or negative and from the relational graph as follows it is clear that, review 32 is truly predicted as negative as its related or connected review nodes either Samehotel or Sameuser relation are also negative reviews. 


![image](https://user-images.githubusercontent.com/25291998/125535746-41460d3a-e8b7-477d-bc5d-f1a75a0c1bbc.png)

# 2. Sameuser Relation

Here, we have the relational graph where the query 32 predicted as negative review connected to a node with respect to Sameuser relation


![image](https://user-images.githubusercontent.com/25291998/125535876-5de9f900-d3f8-48b8-8a2c-069ad4b9ccc0.png)


# 3. Samehotel Relation

Here, we have the relational graph where the query 7 predicted as positive review connected to the nodes with respect to Samehotel relation


![image](https://user-images.githubusercontent.com/25291998/125536221-48b53886-e064-4849-af1b-999008cfc5f0.png)

# 4. Word Explanations

Here are the words explanations by LIME for the review 0 to be truly predicted as positive review:


![image](https://user-images.githubusercontent.com/25291998/125536420-f9deabff-dd9c-4496-ba99-20202e85033f.png)








# Packages need to be installed
Python=3.6

Gensim=3.8

Jupyter Notebook
