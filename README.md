# Predict-Blood-Donations

# 📝 Overview 
Forecasting blood supply is a serious and recurrent problem for blood collection managers.In this Project, work with data collected from the donor database of Blood TransfusionService Center.  The dataset, obtained from the Machine Learning Repository, consists of arandom sample of 748 donors. We use tpot library to automate your Machine Learning pipeline.

# 💪 Motivation
I started to learn Data science to explore my carrier in Data world. I learned different methodologies and tools to achieve and solve real world problems. Finally it is important to work on application (real world application) to actually make a difference.

# 📀 Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt

# 🛠⚙ Technology 
Windows

Jupyter Notebook

Programming Language: Python

Library: Numpy, Pandas, Sklearn, Operator, TPOT

# Conclusion

The demand for blood fluctuates throughout the year. As one prominent example, blood donations slow down during busy holiday seasons. An accurate forecast for the future supply of blood allows for an appropriate action to be taken ahead of time and therefore saving more lives.

In this notebook, we explored automatic model selection using TPOT and AUC score we got was 0.7850. This is better than simply choosing 0 all the time (the target incidence suggests that such a model would have 76% success rate). We then log normalized our training data and improved the AUC score by 0.5%. In the field of machine learning, even small improvements in accuracy can be important, depending on the purpose.

Another benefit of using logistic regression model is that it is interpretable. We can analyze how much of the variance in the response variable (target) can be explained by other variables in our dataset.
