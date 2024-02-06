- All tensors are immutable like Python numbers and strings: you can never update the contents of a tensor, only create a new one.


- Tensors have shapes. Some vocabulary:
	- **Shape**: The length (number of elements) of each of the axes of a tensor.
	- **Rank**: Number of tensor axes. A scalar has rank 0, a vector has rank 1, a matrix is rank 2.
	- **Axis** or **Dimension**: A particular dimension of a tensor.
	- **Size**: The total number of items in the tensor, the product of the shape vector's elements.


- Note that the [`Tensor.ndim`](https://www.tensorflow.org/api_docs/python/tf/Tensor#ndim) and [`Tensor.shape`](https://www.tensorflow.org/api_docs/python/tf/Tensor#shape) attributes don't return `Tensor` objects. If you need a `Tensor` use the [`tf.rank`](https://www.tensorflow.org/api_docs/python/tf/rank) or [`tf.shape`](https://www.tensorflow.org/api_docs/python/tf/shape) function. This difference is subtle, but it can be important when building graphs. 


- ![[Pasted image 20240206165242.png]]


- 