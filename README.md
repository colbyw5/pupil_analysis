### Pupil Diameter Profile Estimation Among Navy Sailors Undergoing Training Exercises via Functional Data Analysis

**Background**: A growing body of literature in Cognitive Psychology uses subject pupil diameter to track task engagement over time.  The data and code in this repository was used as part of a Master's Thesis practicum utilizing Functional Data Analysis to assess Pupil Diameter profile in subjects undergoing a training exercise.  Tracking engagement over time informs educators on the aspects of training material that increase/decrease subject engagement, which has been associated with subject performance.

Language: R Version 3.5.3

**Data**: Pupil Diameter was collected as Navy Sailors (n = 21) underwent a distance learning training exercise. Sailors were assigned one of three videos, which lasted roughly 9 minutes each.  Pupil diameter profiles was estiamted vis Functional Mixed Effects (FMM) modelling, a Functional Data Analysis technique used to estiamte individual trajectories while utilizing information from other subjects' data

**Methods**:  Data cleaning followed the process established in this 2019 research paper: https://link.springer.com/article/10.3758/s13428-018-1075-y. Once outliers were removed an missing values imputed where appropriate, mean pupil diameter was re-sampled in 2 second bins.

FDA is a methodology used to model indexed outcomes that vary over time using curves, thus focusing on the curve as a basic unit of analysis. Advances in data collection technology have made continuous data streams in experimental settings available to researchers, which has led to an increased use of FDA methods in longitudinal analyses. Using a curve as the unit of analysis provides a compromise between the cross-sectional methodology and the crude pattern analysis approach. In recent years, FDA has been used in a variety of medical applications, including modeling fetal heart rate over time, forecasting mortality and fertility rates, and predicting trends in the incidence rate of fall-related injuries29–31. 

In 2002 Guo introduced functional random effects, thus extending functional regression models to mixed effects modeling32. In simple terms, functional mixed effects modeling (FMM) estimates population-average and subject-specific functions for a given set of covariate values.  Visual inspection of fitted population-average and subject-specific curves reveal the dynamics of between-subject functional variation over time. A 2002 study used functional mixed effects modelling to compare the pattern of cortisol release, a hormone associated with increased stress levels, in fibromyalgia (FM) patients relative to a control group and found the cortisol levels to be higher in FM patients.

The research presented in this paper estimates the fitted curves for blink rate and mean pupil size over time while subjects watch submarine training videos used in a Navy distance learning program. Fitting curves to blink rate and pupil size patterns via FMM allows us to visually inspect estimated population-average and subject-specific profiles given the established relationship between engagement and pupil size.

**Results**:

**Discussion**:
