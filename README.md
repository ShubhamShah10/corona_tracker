![Corona Tracker Logo](https://dg1fd6ea8poyj.cloudfront.net/images/Logo_CORONATRACKER_Text_Logo.png)

A tool to help reduce the number of unnecessary hospital visits, educate the public on facts vs myths, and provide a health and wellbeing chart for logging their journey during these uncertain and tumultuous times.



## Table of Contents

<!-- TOC -->

- [We are in crisis and we need to act](#we-are-in-crisis-and-we-need-to-act)
- [Application Overview](#application-overview)
  - [Useful Github Repo Links](#useful-github-repo-links)
- [Frequently Asked Questions](#frequently-asked-questions)
  - [Who is this app for?](#who-is-this-app-for)
  - [What is the benefit this app is providing?](#what-is-the-benefit-this-app-is-providing)
  - [How is this app different from the others?](#how-is-this-app-different-from-the-others)
  - [What insights have been considered?](#what-insights-have-been-considered)
  - [Who are the stakeholders?](#who-are-the-stakeholders)
- [Questions?](#questions)
- [Appendix](#appendix)
  - [Design considerations](#design-considerations)
- [Licensing](#licensing)

<!-- /TOC -->

## We are in crisis and we need to act

The COVID-19 outbreak is a threat to the global population with formidable challenges to the health system. Social distancing measures and telemedicine have been established to mitigate clinic burden and reduce additional spread. The behavior of the general public plays an important part in effectively fighting the outbreak and in improving the situation for persons that need medical care. There is a pressing need to provide accurate information and appropriate suggestions to the general population in order to avoid causing overburden of hospitals across the globe.

After discussions with doctors, start ups, technologists, and academic researchers, we narrowed down some issues of critical importance that the application will address. Specifically, we list major concerns from a call with Ameer (Systems Architect) and Dr. Kristen Kent. There are several key facets of concern, namely __medical considerations__ (i.e. people aren't realizing the severity of this; it's getting real very fast; and doctors/medical professionals are ill-equipped to test for this), as well as __global concerns__ (i.e. the economy is sinking; resources are directly needed for equipment like isolation rooms and protective gear; there is a need for more ventilators and space; schools are closing; etc.).

Furthermore, the effects of social distancing and isolation and the impact of lost jobs and finances is already having a negative impact on the physical, mental, emotional, and spiritual well-being of our society. After learning all of this, we realized that there's a limited amount of time to act, and decisive action must be taken in order to do our part and help our neighbors and healthcare professionals on the ground working towards a solution, keeping people as healthy as possible, and strengthening the well being of our society.


## Frequently Asked Questions

### Who is this app for?

This app is for the global population going through this crisis: those who are feeling generally well, possibly not too well physically or mentally, and are concerned they may be carrying COVID-19 or are showing symptoms.

The target population of the application includes:
1. cell phone users between the ages of 25-45. These users will have a high likelihood of being caretakers of young children and older adults
2. high-risk populations with comorbidites including diabetes, obesity, kidney diseases, and immune system disorder

### What is the benefit this app is providing?

This application will address a global public health need by promoting accurate information to the general population and thereby help healthcare workers on the front lines to provide the necessary care to those in need.

### How is this app different from the others?

The differentiating characteristics of our web application include:
1. integrating education, measurement of education with key performance indicators, and insights via data analytics
2. decentralization and privatization which allows for data ownership by users
3. data interoperability which allows for modular and extensible features and a B2C approach to medical care
4. support of multiple languages to target developing regions with high levels of urbanization, poor medical infrastructure, yet high mobile phone connectivity

### What insights have been considered?

The team has been in consultation with individuals and stakeholders in the academic, medical, business, and technology sectors. The provided insights into our application development include:
1. understanding viral infection, disease pathogenesis, and public health guidelines followed by medical staff at a top tier NYC hospital
2. providing education to the general public and patients is crucial to avoid unnecessary ER visits and engage patients in their health
3. properly scoping our product to be an enterprise ready application by including key features based on expert feedback
4. developing useful survey content for users and stakeholders that can address public health and clinical research needs
5. building a decentralized platform to increase data ownership and privacy

### Who are the stakeholders?

- All individuals. This affects all society.
- Public health authorities. They need to inform, educate, and support citizens.
- Researchers. There is enormous implications for individual's wellbeing and health and so we must try to understand both how individuals are traversing their journey, and if education is significantly improving characteristics in a user's health/wellbeing chart.

## Appendix

### Design considerations

__CSS Design considerations__

We have decided to use regular CSS files to keep things simple for now. This allows for more contributors and less time to upskill to contribute.

Once the MVP is done the team can discuss if we want to transition it to [styled-components](https://styled-components.com) or something like CSS modules.

Folder paths:
- CSS files are located in `/client/src/css`
- Components are located in `/client/src/components`


