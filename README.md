# MinneMUDAC-2023-predict-MLB-attendance
Build predictive models for the game-by-game attendance for home games for all MLB teams for the 2023 season and identify factors that tend to influence home-game attendance. The 1st place solution at [MinneMUDAC 2023 Data Science Challenge](https://minneanalytics.org/minnemudac2023/).

## Contributors
A big thanks and credit to all the team members who made this project possible:
* Congyi Zhang (zhan8373@umn.edu)
* Jichen Liu (liu02354@umn.edu)
* Lan Chen (chen7613@umn.edu)
* Rio Pan (pan00246@umn.edu)
* Simin Liao (liao0150@umn.edu)

See the [contributors](https://github.umn.edu/liao0150/MinneMUDAC-2023-predict-MLB-attendance/blob/main/Contributors.md) file for details on each contributor's role in the project.

## Project Overview
Attendance is a crucial factor for the success of MLB teams. Accurately predicting attendance can have significant impacts on both long-term and short-term profitability and operational efficiency. However, the prediction of MLB attendance can be complicated due to multiple factors, leading to inaccurate forecasts and potentially suboptimal business decisions. 

To address this issue, we firstly utilize a pre-season attendance prediction model to help the MLB teams make attendance predictions before the season. The prediction results can help with long-term business planning like game scheduling, staff hiring and season ticket price adjustment. Furthermore, we provide a second model which includes data collected during the new season, such as latest game performance and player list, to dynamically predict attendance and facilitate short-term decsions making. Lastly, to identify important factors and understand how they affect attendance across teams, we interpret the important factors from feature importance graph.

## Project Deliverables
We integrate data from multiple sources and build features that can be grouped into 3 buckets: Team performance, player and calendar, see the code folder for details. Based on the features, we deliver the following models and results.
### Temporal Fusion Transfomer Model and 2023 Attendance Predictions

### In-Season Attendance Prediction Modle (LightGBM)
### Feature Importance, Partial Dependence Plot and intepretation



## Links
* Code: 
* [Deck](https://github.umn.edu/liao0150/MinneMUDAC-2023-predict-MLB-attendance/tree/main/presentation)
* [Presentation video](https://www.youtube.com/watch?v=OOTj8_1UaQA)
