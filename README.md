# Predicting defect concentration using pair distribution function (PDF) data 

Feature extraction and a neural network model are applied to predict the defect types and concentrations in experimental TiO2 samples. A dataset of TiO2 structures with vacancies and interstitials of oxygen and titanium is built and the structures are relaxed using energy minimization. The features of the calculated pair distribution functions (PDFs) of these defected structures are extracted using linear methods (principal component analysis, non-negative matrix factorization) and non-linear methods (autoencoder, convolutional neural network). The extracted features are used as the inputs to a neural network that maps the feature weights to the concentration of each defect type. The performance of this machine learning pipeline is validated by predicting the defect concentrations based on experimentally-measured TiO2 PDFs and comparing the results to brute-force predictions. A physics-based initialization of the autoencoder has the highest accuracy in predicting the defect concentrations. This model incorporates physical interpretability and predictability of material properties, enabling a more efficient material characterization process with scattering data.

Workflow
![flowchart2](https://user-images.githubusercontent.com/16943054/195750688-f6c40d3a-b1d3-47dd-9321-b428a8999893.PNG)

