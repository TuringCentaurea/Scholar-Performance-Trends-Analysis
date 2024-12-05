# Scholar Performance Trends: Pandemic Impact Analysis
## Project Background
Following the end of the pandemic, many activities worldwide gradually transitioned from online to offline modes, including changes in teaching methods in schools. This analysis examines the impact of this transition on students' overall performance. Specifically, it investigates data from a UTS course, using datasets from 2021 (676 students) and 2023 (874 students). This research goal aims to assess the impact of the shift in teaching methods, evaluate whether the course structure is well-designed, and determine if adjustments to the teaching model are necessary.     
## Executive Summary
An analysis of 1,550 academic records from 2021 and 2023 reveals a significant decline in student average overall performance following the transition from online to offline teaching modes. The proportion of high-performing students experienced the largest drop, decreasing by 30%, while mid-to-lower performance groups saw significant increases, with Group C rising by 15% and Group P by 10%. However, the transition had no notable impact on the proportions of top-performing or lowest-performing students. A correlation heatmap highlighted the effective design of the course structure, and further analysis confirmed that offering two test opportunities significantly improved average test scores by approximately 10 percentage points. These insights suggest that faculty and course administrators should conduct a more detailed investigation into the reasons behind the decline in high-achieving students, while retaining the current course structure and the strategy of offering two test opportunities, which have proven effective.
## Insights Deep Dive
### Trends in Overall Student Performance and Growth Rates Across Groups
* The average overall student performance experienced a significant decline, **decreasing by 10 points** when comparing 2021 and 2023.
* The percentage of top-performing students **dropped by 30% annually**, representing the most substantial change among student groups over the two years.
* In 2023, the percentages of mid-performing and lower-performing student groups also showed noticeable increases, **rising by 15% and 10%,** respectively, compared to 2021.
### Trends in Regular Test Performance and Growth Rates Across Groups
* The average performance in regular student tests experienced a significant decline, **decreasing by approximately 5 points** from 2021 to 2023.
* The percentage of top-performing students **dropped by 20% annually**, marking the most substantial change among student groups over the two years.
* In 2023, the percentages of upper-mid-performing and mid-performing student groups showed noticeable increases, **rising by 6% and 7%**, respectively, compared to 2021.
### Course Structure Analysis
* Each test shows the highest correlation with the previous test, indicating that the content of each test is most related to the material covered in the closest prior test.
* The final course test has the highest correlation with the final exam, at 0.48.
* The first course test has the lowest correlation with the final exam, at only 0.23.
### Analysis of the Importance of Offering Two Test Opportunities
* For students who took only one test, those who participated in the second test scored an average of 20 points lower than those who took the first test. This confirms that students tend to retain what they have learned more firmly in the short term.
* For students who took only one test, those who participated in the second test scored an average of 9 points lower on the final exam compared to those who took the first test. This highlights the importance of following the course schedule, as students who adhere to the planned course structure tend to gain a better understanding of the course material.
* For students who took both tests, the second test score was, on average, 15 points higher than the first test score.
### Prediction Models Based on Existing Data
* The most accurate models are the Neural Network Model and Logistic Regression Model, both with an accuracy rate of 45%.
## Recommendations
* **The Most Impacted High-Performing Student Group:** The group of highest-performing students experienced the greatest decline. Further research is needed to explore why this group was most affected by the transition, and whether this sharp 30% drop was solely due to the change in teaching modes.
* **Transition of Semester Test Modes:** Students' test scores decreased by approximately 5 points when transitioning from online to offline learning. The greatest impact was observed in the highest-performing group. For future course designs, the teaching team might consider reverting to online tests, which could raise students' average test scores back to pre-pandemic levels, from 80 (fairly good performance) to 85 (excellent performance).
* **Maintain the Current Course Structure:** The current course design shows the highest correlation between each test and the previous one. The final exam is most closely correlated with the last test, while the first test has the lowest correlation. This suggests that the course structure is well-organized and that students’ learning progresses logically throughout the semester. The teaching team should consider maintaining this current structure.
* **Maintain the Opportunity for Two Tests:** Offering students the chance to take two tests helps those who are actively engaged in their learning (participating in both tests) to achieve better results. Keeping this setup could further improve the performance of this group, leading to more positive academic outcomes.
* **Limitations of Current Data:** The accuracy of various models is currently only up to 45%. The existing data is insufficient to construct a model for predicting final exam scores. In the future, the course planning team will need to record more data (features) for model development.













