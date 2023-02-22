# CS-4403-Assignment-2

## The Task

### School Discipline
ProPublica conducts "Investigative Journalism in the Public Interest".  As part of this pursuit they maintain a significant store of datasets, and add new ones regularly.

A few days ago, they published a new dataset which contains records with respect to school discipline in the State of New Mexico in the United States:

https://www.propublica.org/datastore/dataset/new-mexico-school-discipline

Please read their terms of use at https://www.propublica.org/datastore/terms and ensure you are willing and able to comply with these terms. They are not onerous and the key requirements are that you will not re-share the dataset or monetize it.

Then download the dataset. It will be in ZIP format, and once unzipped is just shy of 44 MB.

The actual data is in XLS format and, if you like, have a look at the data within that application. There is a README which you should review to understand the other documents in the folder.

Have a look at the pandas API page for the  read_excel() function and note the numerous parameters you can set for importing Excel data into a dataframe:

https://pandas.pydata.org/docs/reference/api/pandas.read_excel.html

This short tutorial likely covers the key bits you will be interested in: 

https://www.digitalocean.com/community/tutorials/pandas-read_excel-reading-excel-file-in-python

Examine the numerous columns of data in the dataset and think about potential correlations that you might test between certain features and dependent variables such as the type of discipline response and its severity, or some spectrum of a combination of them that makes sense.

Build a predictive model with features you select and use a train/test approach to assess the accuracy of your model.   Try subsets of the dataset if they constitute an appropriate population to model. Try out different algorithms.  Where possible, use a feature importance analysis to draw some conclusions from your model. Test your model with some customized  new data to test hunches you may have about the model.

Lock in a great grade by playing with SHAP values as part of your analysis:

https://towardsdatascience.com/using-shap-values-to-explain-how-your-machine-learning-model-works-732b3f40e137

Be mindful of the types of data in some of the columns and how you can go about preserving their information, while making them consumable by your model.
