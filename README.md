# 2021_FSI_Korea
2021 금융데이터 경진 대회 (Financial Security Institute) Data Competition 

## Summary
Using Woori bank’s loan attraction data, a stacked classifer model was established to predict whether loans are attracted/given within six months. Utilization data are categorized data, with the bagging method having better f1 score prediction than the boosting method. In terms of F1 score, Gradient Boosting was 0.3912 and Random Forest was 0.6121, and using ensemble classifiers, the model was improved to 0.7177. The predicted accuracy of the ensemble model was 99%, but considering the fact that the data was imbalanced, the focus was more on F1 score performance. An analysis of the importance of the variables indicated that the variables related to cash flow were the most important variables, and observed the applicant's financial management status were important indicators for loan approval.

An additional PoF for visualising financial asset information was also presented. In addition to the data obtained from KB Card and Shinhan Bank, administrative/legal district codes and map information of publicly available data were also used. This allows us to identify which locations (dongs) have been affected differentially.

The Folium maps were constructed into html files with convenient time-sliders.



## In case ipynb files cant be viewed in github:

# Woori Loan Data:
https://nbviewer.jupyter.org/github/darchon30704/2021_FSI_Korea/blob/main/Woori.ipynb

![ROC Curve](https://github.com/darchon30704/2021_FSI_Korea/blob/main/images/roc.png?raw=true)

![Precision Recall Curve](https://github.com/darchon30704/2021_FSI_Korea/blob/main/images/prc.png?raw=true)

![Mean Feature Importance](https://github.com/darchon30704/2021_FSI_Korea/blob/main/images/Woori_FI.png?raw=true)

# KB Resteraunt Data:
https://nbviewer.jupyter.org/github/darchon30704/2021_FSI_Korea/blob/main/KB/KB_visualization.ipynb

## Sales of resteraunts
![KB Map](https://github.com/darchon30704/2021_FSI_Korea/blob/main/images/KBmap.png?raw=true)

# Shinhan Asset Information:
https://nbviewer.jupyter.org/github/darchon30704/2021_FSI_Korea/blob/main/shinhan/shinhan_visualization.ipynb

## Asset Information (Recieving, Expenditure, Income, etc..)
![Shinhan Map](https://github.com/darchon30704/2021_FSI_Korea/blob/main/images/shinhan_map.png?raw=true)
