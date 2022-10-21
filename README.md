# Rating prediction csgo
Rating prediction for the Esport game Counter Strike Global Offensive. A few regression models are used to determine the rating of professional players in the esport game Counter strike global offensive. This is done using scikit-learn library for python. Further fine tuning is done to improve the performance of these regression models which can then be compared to see which model performs best to predict ratings in Counter Strike Global offensive.
# Results
| Machine learning algorithm | Mean SquaredError (MSE) before tuning | Mean SquaredError (MSE) after tuning |
|----------------------------|---------------------------------------|--------------------------------------|
| Linear regression          | 3.05476−5                             | -                                    |
| Lasso regression           | 4.46812−3                             | 3.63461−5                            |
| Ridge regression           | 3.05911−5                             | 3.05463−5                            |
| ElasticNetregression       | 4.46812−3                             | 4.06730−5                            |
| Support Vectorregression   | 2.17564−3                             | 8.62296−4                            |
| Random Forestregression    | 7.26288−5                             | 6.41681−5                            |
