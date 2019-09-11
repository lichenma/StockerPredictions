# Stock Analysis in Python 

Exploring financial data with object-oriented programming and additive models. This project will follow a towardsdatascience article on `Stocker` - a Python class-based tool for stock analysis and prediction. 


## Getting started with Stocker 

After installing the required libraries, the first thing we need to do is import the Stocker class into our Python session. We can do this from an interactive Python session or a Jupyter Notebook started in the directory with the script.


```python
from stocker import Stocker
```

We now have the Stocker class in our Python session, and we can use it to create an instance of the class. In Python, an instance of a class is called an object and the act of creating an object is sometimes called instantiation or construction. In order to make a Stocker object we need to pass in the name of a valid stock ticker 