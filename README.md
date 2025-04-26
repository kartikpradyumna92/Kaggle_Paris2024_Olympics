# Kaggle Paris 2024 Olympics: Statistical Inference and Data Storytelling
Statistical Inference and Data Story telling on Paris 2024 Olympics. Understand the data around Paris 2024 Olympics and visualize interesting findings, perform statistical inference.<br><br>
Kaggle Dataset - https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games/data
<br><br>
Kaggle notebook - https://www.kaggle.com/code/kartikpradyumna92/olympics-2024-statistical-and-visual-analysis
<br><br>


__*Conclusion Notes*__
This data was around the evnts and athletes part of Paris 2024 Olympics. I looked at it from few point of views (POV) to perform Statistical and visual analysis.

<h3>from Events POV</h3>
      *      Ranked events based on the occurrence. Most events are Athletics events since it bins all track and field events, followed by swimming.
![Events histogram ](Paris_2024_Olympics_result_images/events_line_chart.png)      

<h3>from Schedule POV</h3>
      *      Time series plot to see total events everyday and cumulative event to understand percentage completion each day.
            Comapred with Basketball event schedule and trend is highly correlated
![Schedule line chart](Paris_2024_Olympics_result_images/schedule_line_chart.png)
<br>
<h3>from Overall Athletes POV</h3>
      *     Identified that we had a 12 year and 70 year old athlete competiting,
            Most athletes are part of track and field discipline, followed by swimming, football.
            Gender parity is not a lot in top ten Countries in terms of total athletes representing their country but overall there were more male athletes than female athletes.
            Most common age of the player is 27 and variance of age across gender is almost similar with little difference.<br>
      *     Interesting find was that Variance of athletes coming from China is low, lowest age being 12 and highest age being 37. <br>
      *     <u>T-test</u> - check if there is statiscal signifance in mean Age of Female and Male athletes. p-value = 6.675129492779651e-13 and is < 0.05 hence concluding that there statistical difference between mean age of male and Female athletes.<br><br>

![Athletes per Discipline per Country](Paris_2024_Olympics_result_images/athletes_per_discipline_per_country.png)
![Violin Chart of age per gender](Paris_2024_Olympics_result_images/violin_chart_athletes_age_per_gender.png)
![Country level data story](Paris_2024_Olympics_result_images/sub_plot_country_level.png)
<br><br>
<h3>from Medals POV</h3>
      *     Interesting identification was seeing various athletes like Yufei Zhang winning multiple medals.

![Gold Medalist Summary](Paris_2024_Olympics_result_images/gold_medalists_summary.png)
<br>
![Silver Medalist Summary](Paris_2024_Olympics_result_images/silver_medalists_summary.png)
<br>
![Bronze Medalist Summary](Paris_2024_Olympics_result_images/bronze_medalists_summary.png)
<br><br>
      *     <u>Chi-Square test for Independence</u> - check if category features- Country and Medal type are independent to each other. p value = 2.7226041047105514e-40 and is < 0.05 hence concluding country an athlete represents significantly affects the type of medal won (Gold, Silver, Bronze) at Paris 2024 Olympics.
<br><br>
<h3>from 1 athlete POV- Novak Djokovic</h3>
     *      As a viewer, I am interested in games my favorite athlete is playing. I am a fan of Novak Djokovic and seeing him win his 1st Gold medal in his possibly last Olympics was very satisfying.
            Scatter plot to visualize his journey towards that Gold medal and athletes he played along the way.

![Novak Djokovic's Journey to Olympics Gold.](Paris_2024_Olympics_result_images/novak_djokovic_journey.png)

<br>
