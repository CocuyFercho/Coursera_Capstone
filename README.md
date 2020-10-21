# Coursera_Capstone
This is the final project for IBM Data Science Specialisation. The project analyses historical data for car crashes and associated severity for New Zealand. A model is build using the available data and is used to predict possible outcomes of crashes under different conditions.

Please note:
The execution of the notebook's final version takes SEVERAL HOURS. It is possible to reduce the execution time by commenting some of the most time consumming calculations:
  
  1) In the section features correlation, comment out the generation of the correlation matrices, especially the ones using the full dataset,
  
  2) In the function loop_clasf_engine comment out some of the classifiers, especially the KNeighborsClassifier which takes a long time to calculate.


### This notebook requires the following the libraries:
- Basic calculation libraries: numpy, pandas, matplotlib, seaborn, scipy and time
- Manipulation of imbalanced dataset: imblearn (https://imbalanced-learn.org/stable/)
- Classifiers and support functions: sklearn (train_test-split, chi2, all the classifiers included in the programme and several metric functions)
- Encoding: category_encoders (http://contrib.scikit-learn.org/category_encoders/index.html)
- Correlation algorithms: dython (http://shakedzy.xyz/dython/), phik (https://phik.readthedocs.io/en/latest/index.html)

For more information refer to the notebook or the project report</b>
