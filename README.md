# Portfolio Summary

## Applied Machine Learning

### [Abalone Age Prediction](https://github.com/josifovskid/Abalone-Age-Prediction)

<p align="left">
    <img alt="Living abalone in a tank" src="images\abalone.jpg" width="400"/><br>
    Sharktopus, 2011, <i>Living abalone showing epipodium and tentacles, in display tank at Ty Warner Sea Center on Stearns Wharf, Santa Barbara, California.</i>, image, Wikimedia Commons, viewed 21 July 2020, <a href="https://commons.wikimedia.org/wiki/File:LivingAbalone.JPG">https://commons.wikimedia.org/wiki/File:LivingAbalone.JPG</a>.
</p>

Determining the age of abalone is an important task because it affects the revenue of the industry. The traditional approach is time-consuming, and different approaches are needed to speed up the process. This project aims to address that by determining the age of abalone from physical measurments with machine learning algorithms. The problem was treated as regression, and several regressors from the scikit-learn library were learned. The performance was evaluated with the R^2 score, and RMSE. The best performing model is Random Forest, and has R^2 = 0.552064, and RMSE = 2.041903, which suggests that more work is needed.

### [Exoplantes Detection](https://github.com/josifovskid/Exoplanets-Detection)

<p align="left">
    <img alt="Exoplanet 2M1207b" src="images/exoplanet.jpg" width="400"/><br>
    ESO, 2004, <i>Composite image showing the first directly imaged exoplanet 2M1207b (the red spot on the lower left), orbiting the brown dwarf 2M1207 (centre).</i>, image, exoplanets.nasa.gov, viewed 30 August 2020, <a href="https://exoplanets.nasa.gov/resources/300/2m1207b-first-image-of-an-exoplanet/">https://exoplanets.nasa.gov/resources/300/2m1207b-first-image-of-an-exoplanet/</a>.
</p>

- Developed a solution to classifying astronomical objects detected with NASA's Kepler mission as an exoplanet, or not in Python with sklearn.
- Results: The $F_1$ score of the chosen model - Random Forest - is 0.9840.

### [Global Temperature Forecasting](https://github.com/djosifovski/Global-Temperature-Forecasting)

Using Facebook's Prophet, forecast the global average temperature change in the years 2020-2040.

### [Loan Prediction](https://github.com/djosifovski/Loan-Prediction)

Predict whether someone is reliable for a loan. The winning model is XGBoost with $F_{1}$ score of 0.96.

### [Telco Customer Churn Prediction](https://github.com/djosifovski/Telco-Customer-Churn-Prediction)

Predict whether a client will leave or remain in the company. The winning model is optimized XGBoost classifier with $F_{1}$ score of 0.8643.

### [Tornado Magnitude Prediction](https://github.com/djosifovski/Tornado-Magnitude-Prediction)

Predict the magnitude of a tornado. Was experimented with a stacking regressor with the following regressors: Lasso regression, Linear SVR, and XGBoost regregssor. It turned out that the stacking regressor isn't the most optimal model for the application, but rather the XGBoost is with the highest $R^{2}$ score of 0.593262.

## Scientific Computing

### [Modeling Population Dynamics](https://github.com/josifovskid/Modeling-Population-Dynamics)

<p align="left">
    <img alt="Model of lynx-hare interaction" src="images/lynx_hare_model.png" width="800"/><br><i>Model of lynx-hare interaction.</i>
</p>

- Analyzed three different mathematical models of interactions between species: intraspecific competition, interspecific competition, and predation in MATLAB with the function pplane8.
- Modeled three study cases for each interaction:
  - spreading of SARS-CoV-2 in People's Republic of China as logistic growth,
  - competition between two species of paramecium for the same resource, and
  - predation between canadian lynx and horseshoe hare in the Hudson Bay from 1845 to 1935 in Python.

## Computational Physics 

### [Falling Stick](https://github.com/josifovskid/Falling-Stick)

<p align="left">
    <img alt="Falling stick" src="images/falling_stick.png" width="400"/><br>
    2017, <i>Force diagram of falling stick.</i>, image, Physics Stack Exchange, viewed 14 July 2020, Adapted from <a href="https://physics.stackexchange.com/questions/367918/how-does-the-rods-centre-of-mass-change-while-falling">https://physics.stackexchange.com/questions/367918/how-does-the-rods-centre-of-mass-change-while-falling</a>.
</p>

- Derived the Lagrangian of a falling stick.
- Numerically calculated the time the stick takes to fall down.
- Checked the numerical computation experimentally, and confirmed it.
