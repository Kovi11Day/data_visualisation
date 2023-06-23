# data_visualisation
Download and unzip all files and the tableau visualisations should work.
Overview of the visualisations:

VISUALISATION 1

The first visualisation for this project requires analysing the popularity of baby names over time.

We have chosen to implement this solution in tableau since it is simpler to grasp than d3 and it performs better than Altair (depending on the machines executing them, Altair may freeze during interactions).

However, with Tableau we encountered the constraint of not being able to link different filters to ‘buttons’ which would allow us to apply different filters to the same visualisation. We bypassed the problem by using a second visualisation as a ‘filter’.

![visualisation1](https://github.com/Kovi11Day/data_visualisation/assets/11020824/279b1736-0755-480b-91a6-168cce697065)


The above visualisation is the overall results of the more popular, le less popular and the names that have trended from unpopular to popular over time. In this visualisation we had the option to simply display all the names, however, during interaction, the response time is lower and the data takes time to load.

![visualisation2_popular](https://github.com/Kovi11Day/data_visualisation/assets/11020824/ce11e38f-8e8e-47a9-900c-e9d964634e3d)


The bottom left bar chart enables us to interact with the line chart of names and to filter the data according the the popular names. The bar chart within itself allows us to see, at-a-glance, the most popular names. Additionally clicking one of the names allows us to see its trend in the line chart.

![visualisation3_unpopular](https://github.com/Kovi11Day/data_visualisation/assets/11020824/0b57d1eb-ae45-4de2-b12f-13820caf129f)

In the same way, the barchart at the bottom right allows us to filter the unpopular names.

![visualisation4_pop_to_unpop](https://github.com/Kovi11Day/data_visualisation/assets/11020824/243b7d3f-afc6-4b01-85e9-8feb32c5ec81)

Finally, the above image allows us to see the trend of names that have gone from unpopular to popular. We can clearly see the peak of popularity of the name, we select. Again, the bar chart shows the 5 top names that have this specific trend.

VISUALISATION 2

Our visualisation is the map.  Again we use the bar charts only for the filtering.

<img width="986" alt="popular" src="https://github.com/Kovi11Day/data_visualisation/assets/11020824/870eebca-bcac-4565-af7a-2ec67f1af2fc">

We can see that with the 10 most popular names, they are popular over the whole country.



When filtering on an unpopular name, we can see that they are not present in all departments. For example, AB is present in depertment 59. The map automatically scales, se we have a zoomed view of department 59

<img width="984" alt="unpopular" src="https://github.com/Kovi11Day/data_visualisation/assets/11020824/22942927-3508-4344-aec9-11d2af630c55">

VISUALISATION 3

<img width="987" alt="Capture d’écran 2023-06-22 à 22 19 25" src="https://github.com/Kovi11Day/data_visualisation/assets/11020824/948e09b9-f604-4f68-85e3-01b5378748ad">


The above visualisation the evolution of the 2 different genders of a certain name. 


Note that the bar chart is only used for interaction purposes, it does not represent a ‘second visualisation. It allows us to analyse the trend of a specific name.



We can see that André has very different trend according to its gender.

