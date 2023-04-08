# Classification Trees (Practice Exercise)

This practice assignment will reinforce important learning objectives, and allow you to take on more challenging core assignments.

Practice and tinker with this assignment until you're comfortable performing each of the tasks. Then, be sure to submit your output as described in the steps below.

This task uses a breast cancer data set that can be found here.(https://drive.google.com/file/d/1Zms1RfgkWrTp7S6_BFpeELYyvX1s2FSN/view)

The target vector is the diagnosis as either malignant (M) or benign (B).

The task is to use all of the followong classifiers to obtain the highest accuracy possible on the test set:

1. decision tree classifier

2. bagging classifier

3. random forest classifier

Refer to bagging and random forest regression. They work very similarly in a classification problem, but the final prediction is a majority vote of which class instead of an average of continuous values.


Note, that the following code can be used to import the classification tree models required:

from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import BaggingClassifier
from sklearn.ensemble import RandomForestClassifier
