# Lime_Relational_Exp

In this project, we are explaining the predictions made by Machine Learning Model using LIME (https://github.com/marcotcr/lime). Here we have tried to represent LIME relational explanations. The Yelp review data is used in this experiment and the data is available in the link (https://drive.google.com/drive/folders/1o-UmrtdLdYVTvUhWd75khzSqppP1upPq?usp=sharing)

# Run the Code
The  path of the data files need to be setup according the system in the notebook. In the nodebook, in a cell  run the command Run_program() to get the output.

# Demo Output 
Review 142 is Truly Predicted: Positive 

LIME Relational Explanation:'161:0.029526448662763192', '109:0.029526448662763192', '155:0.029526448662763192', '150:0.029526448662763192', '7:8.855816846352782e-31'. Here 161,109,155,150, and 7 are related reviews to 142 and have positive contribution to the prediction. 

LIME Words Explanation: 'cheese:0.029526448662763192','immediately:0.029526448662763192,'definitely:0.029526448662763192'. Here chees,immediately, and definitely are the word explanations
