# Bike Sharing Model using Linear Regression
> The purpose of this project is to build a Linear Regression model to find out the demand for shared bikes with the available independent variables. It will be used by the bike-sharing provider BoomBikes to understand how exactly the demands vary with different features. So that they can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- The company wants to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### After performing the analysis and building a Linear Regression Model, we have reached to the following conclusions:
- The bike rental popularity increased in 2019 as compared to 2018.
- The bike rental is little high during the working days as compared to holidays.
- Bike sharing is high when weather is clear. 
- Bike sharing decreases when the windspeed increases. 
- Out of four seasons (Spring, Summer, Fall, Winter), bike sharing is more populate during Fall season.
- R-squared value on the train data is 0.82 and on test data is 0.81
- After building the model, we found that the error terms for Residuals are centered around 0.
- The model shows following factors are more beneficial in bike sharing:
    - Workingday     0.2327 
    - Temperature    0.3999  
    - Spring        -0.6842  
    - July          -0.2972  
    - September      0.2757  
    - Sunday         0.2749   
    - Light Snow    -1.3185   
    - Mist          -0.3647


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.8.8
- Jupyter Notebook - version 6.3.0
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- sklearn - version 0.24.1
- statsmodels - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- I would like to thank Upgrad and IIIT Bangalore for giving me a chance to work on this project.
- I would also like to thank the dataset providers for this project. Their information is as follows:
    - Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

    - @article{
        year={2013},
        issn={2192-6352},
        journal={Progress in Artificial Intelligence},
        doi={10.1007/s13748-013-0040-3},
        title={Event labeling combining ensemble detectors and background knowledge},
        url={http://dx.doi.org/10.1007/s13748-013-0040-3},
        publisher={Springer Berlin Heidelberg},
        keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
        author={Fanaee-T, Hadi and Gama, Joao},
        pages={1-15}
    }
    - Contact - For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)


## Contact
Created by Amrinder Singh Bajwa (amrinder_bajwa@hotmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->