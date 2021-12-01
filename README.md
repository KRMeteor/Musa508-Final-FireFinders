# Musa508-Final-Firefighters

## Authors

Ben Aiken - Record Video
Ziyuan Cai - Create Markdown

## Use Case Questions

1. **What is the use case?**

- Citizens – What risk do citizens have where they are currently living?  If looking to move or buy property, what is the risk in the new location?

2. **How could data make a difference in answering this question? Do you have a sense for the business as usual decision making?** 

- Current decision making strategies – depends on who is responsible for the land – federal land is managed by US Forest Service, local firefighters manage other land.

3. **What datasets have you identified to help you answer this question?** 

- Weather
- Elevation
- Land use
- Land ownership
- MEDHHINC of municipalities

4. **What kind of model would you build and what is the dependent variable?** 

- DV – Fire Risk
- Spatial and temporal Lag
- Logistic Regression

5. **How will you validate this model (cross-validation & goodness of fit metrics that relate to the business process)?**  

- Spatial cross-validation
 
6. **How do you think that stakeholders would want to consume this data?**  

- Phone app/website where you put your address

6. **What are the use cases for your app and what should the app do?**  

- The app would give each address a fire risk score and a brief description about that score.
- Citizens could use the app to determine their risk at home or anywhere else in the state.
