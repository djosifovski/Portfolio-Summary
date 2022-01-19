# Portfolio Summary

## Applied Machine Learning

### [Abalone Age Prediction](https://github.com/josifovskid/Abalone-Age-Prediction)

<p align="left">
    <img alt="Living abalone in a tank" src="images\abalone.jpg" width="200"/><br>
    Sharktopus, 2011, <i>Living abalone showing epipodium and tentacles, in display tank at Ty Warner Sea Center on Stearns Wharf, Santa Barbara, California.</i>, image, Wikimedia Commons, viewed 21 July 2020, <a href="https://commons.wikimedia.org/wiki/File:LivingAbalone.JPG">https://commons.wikimedia.org/wiki/File:LivingAbalone.JPG</a>.
</p>

- Determining the age of abalone is an important task because it affects the revenue of the industry. The traditional approach is time-consuming, and different approaches are needed to speed up the process. The motivation for this project is to address that by determining the age of abalone from physical measurments with machine learning models.
- This is a regression type of problem in which a subset of learning algoritms were trained from `scikit-learn` and regression algorithm from `XGBoost`. As a single number evaluation metric R^2 is used, and after fine-tuning the models, the most optimal model is Support Vector Regressor where R^2=0.655027.

### [Exoplantes Detection](https://github.com/josifovskid/Exoplanets-Detection)

<p align="left">
    <img alt="Exoplanet 2M1207b" src="images/exoplanet.jpg" width="200"/><br>
    ESO, 2004, <i>Composite image showing the first directly imaged exoplanet 2M1207b (the red spot on the lower left), orbiting the brown dwarf 2M1207 (centre).</i>, image, exoplanets.nasa.gov, viewed 30 August 2020, <a href="https://exoplanets.nasa.gov/resources/300/2m1207b-first-image-of-an-exoplanet/">https://exoplanets.nasa.gov/resources/300/2m1207b-first-image-of-an-exoplanet/</a>.
</p>

- Exoplanets are planets that can be found outside the Solar System, i.e., they are revolving about other star. It is very difficult to detect planets that are many light years away from Earth because they are relatively small and are a lot fainter compared to the star they are revolving about. In 2009 NASA launched the Kepler space telescope to look for exoplanets. The motivation for this project is according to data collected by the space telescope of the astronomical objects to classify whether the object is an exoplanet or not. This could be another tool that astronomers use to verify if they have observed a new exoplanet.
- This is a binary classification type of problem in which a subset of learning algoritms were trained from `scikit-learn`, and stacking classifier with cross-validation from `mlxtend`. As a single number evaluation metric F_1 is used, and after fine-tuning the models, the most optimal model is Random Forest where F_1=0.996860.

### [Global Temperature Forecasting](https://github.com/djosifovski/Global-Temperature-Forecasting)

Using Facebook's Prophet, forecast the global average temperature change in the years 2020-2040.

### [Loan Prediction](https://github.com/djosifovski/Loan-Prediction)

Predict whether someone is reliable for a loan. The winning model is XGBoost with $F_{1}$ score of 0.96.

### [Telco Customer Churn Prediction](https://github.com/djosifovski/Telco-Customer-Churn-Prediction)

Predict whether a client will leave or remain in the company. The winning model is optimized XGBoost classifier with $F_{1}$ score of 0.8643.

### [Tornado Magnitude Prediction](https://github.com/djosifovski/Tornado-Magnitude-Prediction)

<p align="left">
    <img alt="Tornado near Anadarko, Oklahoma" src="images\tornado.jpg" width="200"/><br>
    Daphne Zaras, 2006, <i>One of several tornadoes observed by the VORTEX1 project team on May 3, 1999, in central Oklahoma. Note the tube-like condensation funnel, attached to the rotating cloud base, surrounded by a translucent dust cloud.</i>, image, Wikimedia Commons, viewed 19 January 2022, <a href="https://commons.wikimedia.org/wiki/File:Dszpics1.jpg">https://commons.wikimedia.org/wiki/File:Dszpics1.jpg</a>.
</p>

- Predict the magnitude of a tornado.
- This is a regression type of problem in which a stacking regressor with the following regressors: Lasso regression, Linear SVR, and XGBoost regregssor from `scikit-learn` and `XGBoost` was trained. As a single number evaluation metric R^2 is used. It turned out that the stacking regressor isn't the most optimal model for the application, but rather the XGBoost is with the highest $R^{2}$ score of 0.593262.

### [Venus Volcanoes Detection](https://github.com/djosifovski/Venus-Volcanoes-Detection)

NASA's Magellan spacecraft was a space probe to map the Venusian surface, and to measure the planetary gravitational field. The resulting images of the space mission provide insights into the Venusian geology. In this project there are some images of the Venusian surface that contain a volcano (or volcanoes), and the goal of the project is to classify the images in two classes: with or without volcano. The image classification is done with a convolutional neural network built with `TensorFlow` library. The best validation AUC is 0.9738.

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
