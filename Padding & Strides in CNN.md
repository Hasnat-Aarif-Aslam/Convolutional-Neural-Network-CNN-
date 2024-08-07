# **Why use padding**
* `During convolution operation, the side pexels are not used that much while the middle pexels are more involved in convolved operations`

* `if something important is present in the sides, it may not get detected accurately`

* `The resulting feature map is smaller than the original image, if we apply more convolution operations on it, the feature map will further gets reduced (loss of information)`

![image](https://github.com/user-attachments/assets/82436d1b-d8b2-4079-866c-365efa7bbd1b)


# **What is padding**
![image](https://github.com/user-attachments/assets/c69ed5ad-9b9b-4409-9e0d-56f733418f79)

![image](https://github.com/user-attachments/assets/e33c4273-3a37-4b6a-be36-89b13a137f79)


* `We will add zero, also called zero padding`
![image](https://github.com/user-attachments/assets/6dc6a7d6-e177-4bf2-85f4-7399d2b345f7)
![image](https://github.com/user-attachments/assets/42974aeb-6a49-4981-9242-302d9bca11cf)


# **Types of padding**
* `Valid (No padding) [ n - m + 1 ]`
  
* `Same (Padding) [ Refer 2nd image where we find the padding value]`

* `Here w/o padding we have loose some information`
![image](https://github.com/user-attachments/assets/e066ebad-a535-4f44-92a3-e64cfc3e7cae)
![image](https://github.com/user-attachments/assets/0027a1fa-684e-446d-8752-7042966200a8)

* `With padding, the original size remains intact`
![image](https://github.com/user-attachments/assets/8eedf8a2-fef9-44c6-88a0-352b4a5e0e57)
![image](https://github.com/user-attachments/assets/f077c6bd-8e1d-42e2-abb5-3ef0f2822b1a)


# **What are strides**
* `also called strided convolution`
![image](https://github.com/user-attachments/assets/cc5b3443-f083-40f2-9e86-83078527788e)
![image](https://github.com/user-attachments/assets/9970fb1c-827d-4e04-bfc2-b664759fbb39)
![image](https://github.com/user-attachments/assets/d72e87e8-3177-489c-a5f7-8a56ad027b35)


![image](https://github.com/user-attachments/assets/14d8f400-97a0-4114-a76b-94e14fe89914)

![image](https://github.com/user-attachments/assets/8d63c132-93cc-4d43-ba4f-318f6d0f4acb)
![image](https://github.com/user-attachments/assets/6e86936a-4157-4ed2-8bfa-d8ecfcddad85)









