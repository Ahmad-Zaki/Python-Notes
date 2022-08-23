# Iterators and Generators   <a href="https://colab.research.google.com/github/Ahmad-Zaki/Python-Notes/blob/main/Iterators%20and%20Generators/iterators-and-generators.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" title="Open and Execute in Google Colaboratory"></a>

Iterators are objects that you can loop\iterate upon, which means that we can go over all the values that it contains.

In Python, An iterable object is an object that implements `__iter__`, which is expected to return an iterator object. An iterator object implements `__next__`, which is expected to return the next element of the iterable object that it's created from, and to raise a StopIteration exception when no more elements are available.

Python generators are a simple way of creating iterators. Generator functions allow you to declare a function that behaves like an iterator, i.e. it can be used in a for loop. A generator is, simply put, a function which can stop whatever it is doing at an arbitrary point in its body, return a value back to the caller, and, later on, resume from the point it had `frozen' and merrily proceed as if nothing had happened.
