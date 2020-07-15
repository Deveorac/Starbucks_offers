
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Deveorac/Starbucks_offers">
    <img src="https://p0.pikist.com/photos/118/783/mobile-smartphone-technology-coffee.jpg" alt="Logo" width="240" height="200">
  </a>

  <h3 align="center">Starbucks Offer Predictions</h3>

  <p align="center">
     Prediction of Starbucks membership offers for the Udacity Data Scientist Nanodegree.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Skills](#skills)
* [Summary](#summary)
* [Findings](#findings)
* [Contact](#contact)


<!-- ABOUT THE PROJECT -->
## About The Project

The goal with this data is to identify trends in purchases and offer completion. Ideally, with this project, I will be able to predict whether a user will come into the store to purchase something because they received an offer.  

Read about this project in [Towards Data Science](https://towardsdatascience.com/to-offer-or-not-to-offer-a-starbucks-machine-learning-project-c21bf9c398bc). 
### Built With

* Jupyter Notebooks
* Pandas/Numpy
* Matplotlib
* Seaborn
* Scikit


<!-- SKILLS -->
## Skills

Data was provided by a Starbucks simulation through Udacity. Data was aggregated, cleaned, and analyzed via programmatic and visual analysis. 

The crux of this project is a machine learning implementation that seeks to predict the factors that are most impactful in determining whether an offer will be successful. 

<!-- METRICS -->
## Metrics

During preprocessing, a variety of changes were made to each of the DataFrames. New columns were created containing dummy variables for most of the categorical data, including offer type and gender. 

There were no duplicates in the dataset, but incorrectly coded ages were found and replaced. 

The dimensions of each dataframe increased in the number of columns but stayed consistent in the number of rows. 

<!-- SUMMARY -->
## Summary

Through this project, I was able to build a machine learning model and explore the data to find some key traits that would make an offer more likely to succeed.

Three machine learning models were used: Decision Tree Classifier, Logistic Regression, and Random Forest Classifier. Each was implemented on a 25% test split with default parameters. No changes were made as each model had a relatively strong predictive score, with the Random Forest Classifier having the best predictive power.

The initial goal was to use a Grid Search to optimize the machine learning algorithm. However, on first pass the Random Forest Classifier model provided very high predictive scores, so further optimization would have diminishing returns at this point, especially without more specific demographic data.

Each model made the following predictions for which factors are most impactful on whether an offer will be completed:

<img src="https://miro.medium.com/max/700/1*Y3Mai2jn2bQ6xJIJz_ra1Q.png">

As expected during the exploratory visual and programmatic analysis, the amount of the award has the greatest impact on whether it will be fulfilled. Income, membership start year, and user gender have little or no impact on whether an offer will be fulfilled. Additionally, as expected, marketing an offer on social media had a significant impact on whether it would be completed. The most successful offers were ran on all platforms and the least successful ones were not ran on social media.


<!-- FINDINGS -->
## Key Insights

- Females spend more money on average than males at Starbucks.
- Users who do not completely fill out their membership profile typically spend less, suggesting that they also would not benefit from “craft drink” related offers (i.e. try our new venti magic unicorn frappuccino with extra sprinkles and pixie dust and get 20 extra stars!).
- Offers where a discount is provided are more likely to be completed than buy-one-get-one offers.
- To get maximum completion, include social media in your distribution plan. The most successful and second-to-least successful offers were almost identical in all ways except that the most successful one was spread via social media and the other wasn’t.
- With machine learning, I validated that social media was an influential factor in whether an offer would be completed.
- Other important factors included offer duration, user age, and how much the reward was for. Unimportant factors included email, how long the user had been a member, and their gender.



<!-- CONTACT -->
## Contact

Mehrnaz Siavoshi - [@i_mehrnaz](https://twitter.com/i_mehrnaz)

Project Link: [https://github.com/Deveorac/Starbucks_offers](https://github.com/Deveorac/Starbucks_offers)








<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/mehrnazsiavoshi/
[product-screenshot]: images/screenshot.png
