# **What are edges**
* Edges are change in intensity

![image](https://github.com/user-attachments/assets/6f17a4d9-d212-456c-b98f-f4dbcc1fb78e)

# **Convolve Operation for Single Channel Image:**

The pexels below shows that the image has half black and half white pexels. By using horizontal filter we will find the edge where the change in black & white occurs

This filter is to detect the horizontal edges
  
In CNN, we dont need to define the filter values, CNN automatically find those values while backpropagation

![image](https://github.com/user-attachments/assets/0a44357e-90cf-413f-9c1d-d14858db469a)

# **Resource**
https://deeplizard.com/resource/pavq7noze2


# **After convolve operation, the resultant image will of this size:**
![image](https://github.com/user-attachments/assets/53e8bb0b-250c-46b0-b30f-6d56919e3dd7)



# **Convolve Operation for 3 Channel Image:**
*  When we convolve for 3 channel image, we get a resultant image of (Single) 1 channel

![image](https://github.com/user-attachments/assets/311b89cb-2b59-44eb-8afa-71ab8ba6178a)
![image](https://github.com/user-attachments/assets/09f79143-d23d-4065-914f-dcbeda0f5126)


# **When we use multiple filters, we get multiple `FEATURE MAPS`**
* 4 x 4 x 2 (2 represents we have 2 Feature Maps)

* These FEATURE MAPS can then be used by other layers
