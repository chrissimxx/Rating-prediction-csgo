# Rating prediction csgo
Rating prediction for the Esport game Counter Strike Global Offensive. A few regression models are used to determine the rating of professional players in the esport game Counter strike global offensive. This is done using scikit-learn library for python. Further fine tuning is done to improve the performance of these regression models which can then be compared to see which model performs best to predict ratings in Counter Strike Global offensive.
# Results
| Machine learning algorithm | Mean Squared Error (MSE) before tuning | Mean Squared Error (MSE) after tuning |
|----------------------------|----------------------------------------|---------------------------------------|
| Linear regression          | 3.05476E-05                            | -                                     |
| Lasso regression           | 4.46812E-03                            | 3.63461E-05                           |
| Ridge regression           | 3.05911E-05                            | 3.05463E-05                           |
| ElasticNet regression      | 4.46812E-03                            | 4.06730E-05                           |
| Support Vector regression  | 2.17564E-03                            | 8.62296E-04                           |
| Random Forest regression   | 7.26288E-05                            | 6.41681E-05                           |
