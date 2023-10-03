# Seasonal Flu Vaccine Model


# Business Understanding

According to the [World Health Organization](https://www.who.int/teams/immunization-vaccines-and-biologicals/essential-programme-on-immunization/implementation/global-routine-immunization-strategies-and-practices-(grisp)#:~:text=Immunizations%20are%20among%20the%20most,deaths%20and%20disease%20prevalence%20radically), "Immunizations are among the most successful and cost-effective health interventions ever devised."

Immunization is an important factor not only in preventing infectious diseases in individuals, but also in promoting overall public health, as herd immunity can prevent dangerous viral mutations, keep healthcare systems from becoming overwhelmed, and protect the most vulnerable members of our population (including young children, elderly people, and individuals with impaired immunity).


This model is designed to predict the likelihood that an individual receives his or her seasonal flu vaccine. 

Hypothetically, this model could be used to predict the specific probability of a certain individual (or group of individuals) to be vaccinated for the flu. However, for practical purposes, it is unlikely that a healthcare provider would have information on all 35 features that are included in the dataset used for this model. 

**Instead, this model will be used to identify features that are the strongest predictors of vaccination status. Healthcare providers can use this knowledge to identify individuals who are unlikely to get vaccinated and provide appropriate interventions in order to improve vaccination rates.**


# Data Understanding

The dataset used for this analysis contains the responses of 26,707 individuals to the [National 2009 H1N1 Flu Survey](./survey.pdf), which was produced by the Centers for Disease Control and Prevention, the National Center for Immunization and Respiratory Diseases, and the National Center for Health Statistics. This survey is conducted via telephone and responses are anonymous.

### Features

The features include individuals' behavior, demographics, and opinions/knowledge. They are outlined in full in the [Jupyter Notebook](./notebook.ipynb).

**Behavioral Features:** For example, whether or not the individual frequently washes hands or uses hand sanitizer.

**Demographic Features:** For example, the individual's age, education, race, and sex.

**Opinion/Knowledge Features:** For example, the individual's opinion about the effectiveness of the seasonal flu vaccine.

**Healthcare Features:** For example, whether the individual's doctor recommended the seasonal flu vaccine.

Most features are binary, but some use rating scales or categorical responses. 

Additional discussion of the distribution of these features and handling of missing data is included in the sections below and in the [Jupyter Notebook](./notebook.ipynb).

### Target Variable

The target variable is a binary variable that indicates whether an individual did (1) or did not (0) receive their seasonal flu vaccine.


## Additional Resources

The full analysis can be viewed in the [Jupyter Notebook](./notebook.ipynb). This repository also contains a [presentation](./presentation.pdf) of the findings.

For additional information, contact Caroline Surratt via [email](mailto:carolinecsurratt@gmail.com).


## Repository Structure

```
├── data
├── notebook.ipynb
├── presentation.pdf
└── README.md
```

