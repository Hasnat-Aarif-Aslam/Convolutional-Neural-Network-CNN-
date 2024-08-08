# **Problems With Convolution**

# **Memory Issue**
![image](https://github.com/user-attachments/assets/ba03fd0a-b496-4d63-bb2a-35cd8b2fe6d5)

# **Translation Variance**
# `When we apply convolution operation, the detected features are loaction dependent, which causes:`
  * `Translation Variance: The model's output changes when the input is shifted (i.e., the position of the object in the image affects the result).`

`What we need is:`
  * `Translation Invariance: The model's output remains consistent regardless of shifts in the input (i.e., the position of the object in the image does not affect the result).`
![image](https://github.com/user-attachments/assets/8b88ff9b-9b73-44b7-b89b-0896b9aa1383)


# **Pooling comes after the convolution**
* `AFTER HAVING FEATURE MAP, WE APPLY RELU TO INTRODUCE NON-LINEARITY`
![image](https://github.com/user-attachments/assets/fe3afbd3-9b6e-4112-9296-b9c8a97728fe)
![image](https://github.com/user-attachments/assets/291dc00f-9a87-42da-905a-2960610f38c8)


* `TYPES OF POOLING:`

* `MAX POOLING`

* `MIN POOLING`

* `AVG POOLING`
![image](https://github.com/user-attachments/assets/ece98e16-b12d-4bb1-9996-103a0318010b)

* `L2 POOLING`
![image](https://github.com/user-attachments/assets/bb6caf5c-01ad-4cce-b360-7491e91894fa)

* `GLOBAL AVERAGE POOLING`
![image](https://github.com/user-attachments/assets/93f2a211-28a8-41e1-9558-aa10d0c25a47)

* `GLOBAL MAX POOLING`
![image](https://github.com/user-attachments/assets/365fc5f6-6d49-4809-8fda-d5a6ce21e52d)

# **When to Use Each Pooling Method**

* Max Pooling:
  Use to capture the most prominent feature in each pooling window, enhancing strong activations. Ideal for object detection and image classification.
  
* Min Pooling:
  Use in specialized tasks where capturing the least significant feature is important, such as certain anomaly detection problems.

* Average Pooling:
  Use to smooth the feature map and reduce noise while maintaining overall feature structure. Suitable for tasks requiring generalized feature representation within each pooling window.

* Global Average Pooling:
  Use to condense the entire feature map into a single average value for each feature map, often before dense layers in classification tasks, to reduce dimensionality and improve generalization.

* Global Max Pooling:
  Use to condense the feature map into a single maximum value, highlighting the most significant activation before the final classification.

* L2 Pooling:
  Use to capture the energy (magnitude) of the features in the pooling window, providing a balance between capturing strong features and smoothing. Suitable for tasks where the magnitude of activations needs to be preserved and smoothed.

# **Source**
https://deeplizard.com/resource/pavq7noze3

# **Pooling on RGB images**
* `pooling is applied individually on each feature map`
![image](https://github.com/user-attachments/assets/bdda37f3-95a9-4444-a72a-6c1c473a159e)


# **Code**
![image](https://github.com/user-attachments/assets/bcd10837-4924-4b23-9e4c-131d1dbe508f)
![image](https://github.com/user-attachments/assets/1c260dad-7b0f-4e5b-a2a3-50f8c42169bf)
![image](https://github.com/user-attachments/assets/1ab2de6c-0ae9-4d9c-81bc-6243b1fda57f)


# **Advantages**
* `by applying 2x2 pooling_size we got 113 x 113 x 100`
![image](https://github.com/user-attachments/assets/08ca36da-6ca8-47f6-8936-30abd4bf6898)

* `Both have digit 8, but after pooling the results are same`
![image](https://github.com/user-attachments/assets/fa262e1d-a661-42d3-a8c7-76bbf5cad313)

* `Enhanced Features only in Max pooling`
![image](https://github.com/user-attachments/assets/ac556dbb-daba-4bab-98ce-c1cb164849f0)

* **Dis-advantages**
![image](https://github.com/user-attachments/assets/26dffe34-60fe-4214-abda-7141de1ce1f1)

