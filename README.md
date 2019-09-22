# MachineLearning

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:
1. Preprocess the raw data
2. Tune the models
3. Compare two or more models

Instructions:
A. Preprocess the Data

Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.

B. Tune Model Parameters

Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.

C. Reporting

Data from : https://www.kaggle.com/nasa/kepler-exoplanet-search-results
Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

Context
The Kepler Space Observatory is a NASA-build satellite that was launched in 2009. The telescope is dedicated to searching for exoplanets in star systems besides our own, with the ultimate goal of possibly finding other habitable planets besides our own. The original mission ended in 2013 due to mechanical failures, but the telescope has nevertheless been functional since 2014 on a "K2" extended mission.

Kepler had verified 1284 new exoplanets as of May 2016. As of October 2017 there are over 3000 confirmed exoplanets total (using all detection methods, including ground-based ones). The telescope is still active and continues to collect new data on its extended mission.

Content
This dataset is a cumulative record of all observed Kepler "objects of interest" — basically, all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.

This dataset has an extensive data dictionary, which can be accessed here. Highlightable columns of note are:

kepoi_name: A KOI is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry that appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis
kepler_name: [These names] are intended to clearly indicate a class of objects that have been confirmed or validated as planets—a step up from the planet candidate designation.
koi_disposition: The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED.
koi_pdisposition: The disposition Kepler data analysis has towards this exoplanet candidate. One of FALSE POSITIVE, NOT DISPOSITIONED, and CANDIDATE.
koi_score: A value between 0 and 1 that indicates the confidence in the KOI disposition. For CANDIDATEs, a higher value indicates more confidence in its disposition, while for FALSE POSITIVEs, a higher value indicates less confidence in that disposition.
Acknowledgements
This dataset was published as-is by NASA. You can access the original table here. More data from the Kepler mission is available from the same source here.

Inspiration
How often are exoplanets confirmed in the existing literature disconfirmed by measurements from Kepler? How about the other way round?
What general characteristics about exoplanets (that we can find) can you derive from this dataset?
What exoplanets get assigned names in the literature? What is the distribution of confidence scores?
See also: the Kepler Labeled Time Series and Open Exoplanets Catalogue datasets.
