# Well-log-Analysis-Reservoir-Properties

Development of Predictive models of petrophysical properties using Machine Learning (ML) Algorithms on Well-log Data

Reservoir characteriza4on is an essen4al part of the hydrocarbon explora4on industry as it plays a significant role in our understanding of underground fluid behavior and reservoirs. Petrophysics is one of these approaches that have been used to develop different models and es4mate these proper4es. Porosity and permeability assessment plays a significant role in reservoir characteriza4on. Therefore, the main objec4ve of this thesis is to predict and assess these parameters using machine learning algorithms.
The main objec4ve of this thesis is to es4mate reservoir proper4es, such as porosity, permeability, and satura4on, and evaluate them using well-log data. The evalua4on of the results will be conducted by comparing the predicted outcomes with laboratory data. Different models, including laboratory measurements and well-log measurements, are used to measure these parameters. However, it has been demonstrated that these approaches cannot be considered fully reliable, and therefore, the results may not be accurate in all cases. Problema4c situa4ons arise par4cularly in forma4ons such as carbonate reservoirs, where heterogeneity is an inherent characteris4c.
In the first part of the study, various predic4ve models, including Random Forest (RF), Gradient Boos4ng (GB), and K-Nearest Neighbor (K-NN), were developed. The basic well log data, such as gamma ray, resis4vity, density, neutron porosity, acous4c slowness, and photoelectric factor, were used as predictors, while the Nuclear Magne4c Resonance (NMR) log was used as the target variable for the machine learning algorithms. The NMR log provides a fairly accurate measurement of different types of porosity, such as total, effec4ve, and free-fluid porosity. Determinis4c models, such as Timur-Coates, originally developed for sandstone reservoirs, were u4lized to es4mate permeability and satura4on as func4ons of the three different porosity types es4mated from the predic4ve models. Subsequently, the predicted parameters, including free fluid, effec4ve, and total porosi4es, as well as permeability and satura4on, were compared to the measured data for evalua4on purposes.
In the second part of the study, the NMR log was bypassed, and permeability was directly used as the target variable for machine learning models. Other basic well-log data were u4lized as predictors. This approach allows for the direct es4ma4on of reservoir parameters using machine learning, which can be highly beneficial as it removes determinis4c correla4ons, such as those found in the Timur-Coates model. In this part, a machine learning approach called Least Square Support Vector Regressor (LSSVR) was developed.
The outcomes of each part and the different models were evaluated using various regression metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and the Coefficient of Determina4on (R2) values. The results indicate acceptable to highly accurate predic4ons for various cases, ranging from the test dataset to the en4re dataset encompassing all five wells, as well as the evalua4on of individual wells included in the training phase. However, when applying the models to a different well that was not included in the training phase, the results showed nega4ve but s4ll somewhat acceptable outcomes.
The Python code in the form of a Jupyter notebook is available on GitHub and is open to the public for
enhanced accessibility and collabora4on, facilita4ng poten4al future developments.
