[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/EwosxQto)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=11751680)
# project-2

Project 2
Get the country-specific covid case data from [here](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv). (Note pandas allows you to load a csv file from a URL. Make sure to use the "raw" link to the file on github.)

1. Pick four countries. Show the time series plot of new cases per day for the four countries from the day of the first nonzero case day. (Note we do not want to show cumulative cases by day.)
2. Plot a smoothed version of the country specific data using a smoother such as a moving average, lowess or spline.
3. Let  e  be the difference between your observed case counts and the smoothed version. Plot e over time. (e is called the "residual").
4. From the same website, download the daily death data. Calculate the overall case fatality rate = total deaths / total cases.
5. For your four countries, plot the estimate of the case fatality rate up to that day in the outbreak, starting from the day of the first case. That is, for day  d  plot the number of deaths divided by the number of cases occuring up to day  d. 
6. Create your report in an ipython document and check the document into the github classroom repository for project 2. Make sure to actually run the document so that the figures and results are present.

