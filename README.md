# NumpyTutorial


``NumPy`` is a fundamental Python library for numerical computing. It provides support for arrays, matrices, and high-level mathematical functions to operate on these arrays efficiently. NumPy is particularly powerful for tasks involving numerical operations and data manipulation, commonly used in fields such as scientific computing, machine learning, data analysis, and more.


### Some key features of NumPy include:

- Multi-dimensional arrays: NumPy provides an ndarray object, which is a powerful N-dimensional array that allows for efficient storage and manipulation of homogeneous data.
- Mathematical functions: NumPy offers a wide range of mathematical functions for operations like arithmetic, trigonometry, statistics, linear algebra, Fourier analysis, and more.
- Broadcasting: NumPy allows for arithmetic operations between arrays of different shapes and sizes, intelligently broadcasting the smaller array to match the larger one, which enables concise and efficient code.
- Integration with other libraries: NumPy is often used in conjunction with other libraries like SciPy (for scientific computing), Matplotlib (for plotting), Pandas (for data analysis), and scikit-learn (for machine learning).

### *why we use numpy over lists?*
- the main difference comes from the speed so the lists are very slow meanwhile numpy is very fast 

- In lists I can not do element-wise maths operations as i do in numpy 
```python
    lists : 
    a = [1 , 3 , 5]
    b = [1 , 2 , 4]
    a *b = error 
```
```python
    Numpy: 
    a = np.array([1 , 3 , 5])
    b = np.array([1 , 2 , 6])
    a*b = np.array([1 , 6 , 30])

```
##### *Why numpy is faster?*
- numpy use `fixed types` and lists use `bulit_in type` for python 
- `fixed types` Faster to read less bytes of memory and no type checking when iterating through objects 
- Numpy utilizes contiguous memory (objects in memory next to each other)

