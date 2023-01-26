# Critical_Data_Analysis

## Information regarding the Coursework

The coursework is based on undertaking an analysis of a real world data set. 
It is a shared assessment block for **Quantitative Data Analysis** and **Modern Data** taught in the *Brunel University London*.

For this Coursework we are working with **house-analysis.RDa** which has 90377 observation with 12 Variables.

Information regarding the Variables are below,

| Variable   (Column Name) | Description                                                                  |
|--------------------------|------------------------------------------------------------------------------|
| id                       | Property id                                                                  |
| Price                    | Sale price of the   property                                                 |
| mq                       | Total square meters   of the property                                        |
| Floor                    | Entrance floor of the   property                                             |
| n_rooms                  | Total number of rooms                                                        |
| n_bathrooms              | Total number of   bathrooms                                                  |
| has_terrace              | Property has a   terrace                                                     |
| has_alarm                | Property has an alarm                                                        |
| heating                  | Type of heating   (“autonomous”, “ other”)                                   |
| has_air_conditioning     | Property has Air   conditioning                                              |
| has_parking              | Property has parking                                                         |
| Is_furnished             |     Was the property sold with its contents (furnishings) or   not? (0,1)    |


## Objective

Our Objective for this Coursework is as follows,

* Create a subset of data from the **house-analysis.RDa**
* Organise and clean Data
  * subset the data into the specific data subset allocated
  * data quality analysis 
  * data cleaning
* Exploratory data analysis 
* Modelling
  * explain your analysis plan 
  * build a model for property price 
  * critique your model using relevant diagnostics 
  * based on the previous sections suggest improvements to your model
* Extension work
  * Model the likelihood of a property being furnished (using the is_furnished variable provided)


## How it was done

* We used **Linear Regression** model for the property price and critiqued the model using relevant diagnostics
* For the likelihood of property being furnished , we build a model based on the **Logistic Regression**