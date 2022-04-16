# Function Decorators   <a href="https://colab.research.google.com/github/Ahmad-Zaki/Python-Notes/blob/main/Function%20Decorators/function-decorators.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" title="Open and Execute in Google Colaboratory"></a>

In Python, a decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.

If you didn't know: everything in python, including functions, are objects. Functions have attributes, can be assigned to variables, and even passed as arguments to (or returned from) other functions! This behavior is what allows us to use decorators in Python to add new functionality to an existing function without modifying its structure.

Before jumping straight to decorators, it is essential to understand this concept in order to understand how decorators work. Therefore, we'll go through some examples first and then start looking into decorators.