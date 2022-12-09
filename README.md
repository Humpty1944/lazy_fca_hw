# Lazy fca HW OSDA
This is a brief description of the document  

**Datset**

The Adult Dataset (https://archive.ics.uci.edu/ml/datasets/Adult) was chosen for this task. It contains various basic data about people.

**Predicting quality**

An F1-score was used to determine the quality of the algorithm. There is a class imbalance in the dataset.

**Binarisation of data**

The dataset contains: numeric, categorical data. For both cases, new columns were created for each category, which will be
True if the original column had this value, otherwise False.

**Addition comparison**

Decision trees, random forests were used for the analysis.

**Conclusion**

It can be seen that random forest performs better than all 3 algorithms, although the decision tree is not far behind. Lazy_fca is in the same range of values as the two known algorithms, but the final result is lower (about 5%). This can be connected to the fact that the algorithm has not been optimised and there is room for improvement.
