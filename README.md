# STUDY-OF-NUMPY-IN-PYTHON
Here is your complete **README.md** content for:

---

#  EXPERIMENT NO: 8

# TITLE: Tools for EDA – NumPy

**Name:** Amey Waghmare
**PRN:** 25070123009
**Batch:** A1

---

#  AIM

To study and implement various NumPy functions used in Exploratory Data Analysis (EDA) such as array creation, array attributes, mathematical operations, and statistical functions.

---

#  THEORY 

##  Introduction to NumPy

NumPy (Numerical Python) is a powerful open-source Python library used for numerical computations. It provides support for:

* Multi-dimensional arrays
* Mathematical operations
* Statistical analysis
* Linear algebra operations
* Random number generation

NumPy is widely used in **Data Science, Machine Learning, Artificial Intelligence, and Exploratory Data Analysis (EDA)**.



##  What is EDA?

EDA (Exploratory Data Analysis) is the process of analyzing datasets to summarize their main characteristics, often using statistical and visualization methods.

NumPy plays a fundamental role in EDA because it allows:

* Efficient storage of numerical data
* Fast mathematical operations
* Easy computation of statistical measures



##  NumPy Arrays

The core object of NumPy is the **ndarray (N-dimensional array)**.

Unlike Python lists:

* NumPy arrays are faster
* They consume less memory
* They support vectorized operations

Example:

`python
import numpy as np

a = np.array([10,20,30,40])
b = np.array([[1,2,3,4],[2,3,4,5]])


Here:

* `a` is a 1-D array
* `b` is a 2-D array (matrix)

---

##  Array Attributes

### 1️ `ndim`

Returns number of dimensions.

* `a.ndim` → 1
* `b.ndim` → 2

---

### 2️ `shape`

Returns size of array in each dimension.

* `a.shape` → (4,)
* `b.shape` → (2,4)

---

### 3️ `dtype`

Returns data type of array elements.

* `a.dtype` → int64

---

##  Special Array Creation Functions

###  Zeros Array

Creates array filled with 0.

```python
np.zeros((2,3))
```

###  Ones Array

Creates array filled with 1.

```python
np.ones((2,3))
```

###  Identity Matrix

```python
np.eye(7)
```

Creates 7×7 identity matrix.

---

##  Range Functions

###  `arange()`

Creates array with step value.

```python
np.arange(2,20,7)
```

Output:

```
[2, 9, 16]
```

---

###  `linspace()`

Creates evenly spaced numbers between two values.

```python
np.linspace(0,7,5)
```

Output:

```
[0. , 1.75, 3.5 , 5.25, 7.]
```

---

##  Arithmetic Operations

NumPy supports vectorized operations (element-wise operations).

```python
a + 7
a * 7
```

This automatically performs operation on every element.

Example:

```
a + 7 → [17 27 37 47]
a * 7 → [70 140 210 280]
```

---

##  Statistical Functions (Important for EDA)

These functions help in summarizing the dataset.

###  Mean (Average)

```python
np.mean(a)
```

###  Median

```python
np.median(a)
```

###  Maximum Value

```python
np.max(a)
```

###  Minimum Value

```python
np.min(a)
```

### Sum

```python
np.sum(a)
```

These statistical functions are extremely useful in:

* Data summarization
* Data preprocessing
* Feature analysis

---

#  SYNTAX

##  Import NumPy

```python
import numpy as np
```

---

##  Create Array

```python
np.array(object)
```

---

##  Array Attributes

```python
array.ndim
array.shape
array.dtype
```

---

##  Special Arrays

```python
np.zeros((rows,columns))
np.ones((rows,columns))
np.eye(n)
```

---

##  Range Functions

```python
np.arange(start,stop,step)
np.linspace(start,stop,number_of_values)
```

---

##  Arithmetic Operations

```python
array + value
array * value
```

---

##  Statistical Functions

```python
np.mean(array)
np.median(array)
np.max(array)
np.min(array)
np.sum(array)
```

---

#  CONCLUSION

In this experiment, various NumPy functions used in Exploratory Data Analysis were successfully implemented.

We studied:

* Array creation
* Array properties
* Mathematical operations
* Statistical analysis functions

This experiment helped in understanding how NumPy simplifies numerical computations and forms the foundation for data analysis and machine learning.


