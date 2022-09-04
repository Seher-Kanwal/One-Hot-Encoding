![MasterHead](https://th.bing.com/th/id/R.7b318e5bf8c30ef67d8c28c74e3ee12e?rik=kYOYUfaKjSXk%2bg&pid=ImgRaw&r=0)

# One-Hot-Encoding
One hot encoding is a process by which categorical variables are converted into a form that could be provided to ML algorithms to do a better job in prediction.

Most Machine Learning algorithms cannot work with categorical data and needs to be converted into numerical data. Sometimes in datasets, we encounter columns that contain categorical features (string values) for example parameter food name will have categorical parameters like . These labels have no specific order of preference and also since the data is string labels, machine learning models misinterpreted that there is some sort of hierarchy in them.

In this technique, the categorical parameters will prepare separate columns for Apple, chicken and broccoli labels. So, wherever there is apple, the value will be 1 in Mapple column and 0 in chicken and broccolu columns, and vice-versa.

