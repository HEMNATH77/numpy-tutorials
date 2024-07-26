<h1>Numpy-Tutorials </h2>

<h2>Introduction</h2>
    <p>NumPy is a fundamental library for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently.</p>

<h2>Table of Contents</h3>
 <ol> 
   <h3>1.Importing NumPy</h3>
      <h3>2.Creating NumPy Arrays</h3>
      <h3>3.Array Attributes</h3>
      <h3>4.Indexing and Slicing</h3>
      <h3>5.Mathematical Operations</h3>
      <h3>6. Statistical Functions</h3>
      <h3>7.Reshaping Arrays</h3>
      <h3>8.Loading and Saving Data</h3>
 </ol>
 <h3>1. Importing NumPy</h3>    
 <p>NumPy is typically imported into Python scripts or projects using the following convention:</p>
 <p> Command :  import numpy as np</h3></p>

 <h3>2. Creating NumPy Arrays</h3>
 <p> Creating arrays in NumPy is fundamental for any data manipulation or numerical computation tasks. </p>
<p> Common Example:   a = np.array[1,2,3,4] </p>
<h4>Zeros Array</h4>
<p> This Array creates a array of zeros with respect to the Shape and dimensions given </p>
<p> Format : Array = np.zeros(shape,Dimensions)</p>
<p> OR : Array = np.zeros(Dimensions(Row,column)</p>
<p>Example :  zeros_arr = np.zeros((3, 4)) </p>
<h4>Ones Array </h4>
<p> This Array creates a array of Ones with respect to the Shape and dimensions given </p>
<p> Format : Array = np.ones(shape,Dimensions)</p>
<p> OR : Array = np.ones(Dimensions(Row,column)</p>
<p>Example :  zeros_arr = np.ones((2,3)) </p>

<h3>3.Array Attributes</h3>
<h4>Shape </h4>
<p>Prints the Shape of the array</p>
<p> Command : Array.shape </p>
<h4>Size</h4>
<p>Prints the Size of the Array</p>
<p>Command : Array.Size</p>
<h4>Data Type</h4>
<p>Prints the Data Type of the Array</p>
<p>Command : Array.dtype </p>
<h4>Dimension </h4>
<p>Prints the Dimension of the Array</p>
<p>Command : Array.ndim</p>

<h3>4.Indexing and Slicing</h3>
<p>Indexing in NumPy refers to accessing individual elements of an array using their indices. NumPy arrays can be one-dimensional, two-dimensional, or multi-dimensional, and indexing works accordingly.</p>
<h4> Indexing for One Dimensional Array</h4>
<p>Example : </p>
<p>import numpy as np</p>
<p>a=([1,2,3,4,5])</p>
<p>a[0]</p> <p>output = 1</p> 
<h4>Indexing for  Multi dimensional Array</h4>
<p>For multi-dimensional arrays, you use a comma-separated tuple of indices</p>
<p>Example</p>
<p> a=([1,2],[3,4],[5,6],[7,8])</p>
<p>a[2:2]</p> <p>Output = 6 </p>
