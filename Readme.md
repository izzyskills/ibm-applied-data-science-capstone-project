# Applied Data Science Capstone
This Capstone is the 10th (final) course in [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) specialization, and it actually summarizes in the form of project all materials that have been learned during this specialization.
## Project background and context
SpaceX is the most successful company of the commercial space industry, making space travel affordable. The company advertises Falcon9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine the first stage will land, we can determine the cost of a launch. Based on public information and machine learning models, we are going to predict if SpaceX will reuse the first stage.
## Problems you want to find answers
* How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
* Does the rate of successful landings increase over the years?
* What is the best Classification algorithm that can be used for the prediction of the reuse of a first stage?

# Methodology:
1. ## Data Collection:
    The data was collected from publicly available records, the sources were:
    * SpaceX API
    * Wikipedia page on Falcon 9

2. ## Data wrangling:
    * Filtering the data
    * Dealing with missing values
    * Using One Hot Encoding to prepare the data to a binary classification
3. ## Exploratory Data Analysis (EDA) using visualization and SQL
4. ## Interactive visual analytics using Folium and Plotly Dash
5. ## Perform predictive analysis using classification models:
    * Building, tuning and evaluation of classification models to ensure the best results.
