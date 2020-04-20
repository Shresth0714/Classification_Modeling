# Classification_Modeling
Aim of this project is to build a machine learning model to predict whether a customer will subscribe to a new service.

**PROJECT APPRENTICE CHEF** - Halfway There Cross-Sell service

**AIM**: This project is to build a machine learning model to predict whether a customer will subscribe to Halfway There service.

**BACKGROUND**: Halfway There is a unique subscription in which subscribers will get half bottle of wine from the local California vineyard every Wednesday.

**WHY**: Apprentice Chef wants to diversify its revenue stream by adding a cross-sell service. Plus this will give Apprentice Chef competitive advantage based on its unique product offering of hard to find local wines.

**ASSUMPTION**: The dataset provided by the engineering team has used dataset engineering techniques and is statistically sound and represents the true picture of Apprentice Chef’s customers.

*Tried and tested various Machine Learning models to understand which will be used for the final approach, and GBM without tuning has the highest AUC value.*
~~~
Results:
	Model	                    Training Accuracy	Testing Accuracy	AUC Value
	GBM_without_tune               0.824	            0.797	            0.779
	Tuned GBM	               0.812	            0.793	            0.766
	Tuned Tree	               0.835	            0.774	            0.758
	Tuned Random Forest	       0.897	            0.737	            0.713
	Tuned Logestic Regression      0.791	            0.737	            0.703
  ~~~
