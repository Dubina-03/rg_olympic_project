# RG_olympic_project
This is a visualization project
- Data: With the help of the Selenium library (python), I collected information about the finalists of the Olympic Games in rhythmic gymnastics from the website https://olympics.com/en/. The dataset is stored in a csv file "data_rg.csv". 
  - Fields: 
	  * game - the name of Olympic Game, 
    * name - the name of the athlete, 
    * place - the result of the athlete, 
    * country - the country represented by the athlete, 
    * score - the score received by the athlete
- Visualization: I used Tableau Public to create visualizations
  - Table: the table contains information about the prize-winners of each Olympic Game. The colours are created by the Country field
  - Map: the Country field (generated latitude and longitude) was used to create the map. The map can be filtered by Olympic Games. And you can see the number of all athletes by country that were in the final.
  - Bars: the Country field & the count of athletes. Bars divided by the number of results of different types.
  - Link to visualization: https://public.tableau.com/views/OlympicGamesinRhythmicGymnasticsDashboard/OlympicGamesinRhythmicGymnasticsDashboard?:language=en-GB&:display_count=n&:origin=viz_share_link
