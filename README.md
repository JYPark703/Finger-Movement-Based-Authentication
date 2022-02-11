# Finger-Movement-Based-Authentication

This is my Capstone project of Master.

This project may be sensitive to licenses, so I will only upload the ppt file.

---------------------------------

Currently, various authentication methods have been introducd in the real world.
Also, there is high interest in research on biotechnology and devices. 
So, our goal is to creat an user authentication app that uses finger movement EMG signals.

--------------------

## Brief Description of the Oeration

### 1. Receive the finger movement EMG signal

![Signal](https://user-images.githubusercontent.com/79488632/153547080-9b4e3f15-3b31-4044-acb1-2df0a1a9a6eb.png)

### 2. Classify the signal which finger moved

![Classification](https://user-images.githubusercontent.com/79488632/153547093-3ffd6664-7a79-4400-850e-d90379707694.png)

### 3. Authenticate the user with the classification result

![Authenticate](https://user-images.githubusercontent.com/79488632/153547099-c9a076fa-6872-4b95-922d-6a0b8848fc00.png)

--------------------
## App Structure

The app is devided 2 parts

### 1. Registration Part

![Registration](https://user-images.githubusercontent.com/79488632/153547122-21ce30b7-2aab-46af-8da7-86931af222e6.png)

### 2. Authentication Part

![Auth](https://user-images.githubusercontent.com/79488632/153547130-79ea8c30-9003-479e-8598-80566e707dfe.png)

---------------------
## Todo App

### 1. Registration Part

#### 1) Click the Registration button 

![R1](https://user-images.githubusercontent.com/79488632/153547145-5519dda1-2f81-4199-aec0-fdbf7a0d3172.jpg)

#### 2) Select the EMG device, and Click the Connect button

Then, the EMG device and the mobile device are connected through the Bluetooth protocol.

![R2](https://user-images.githubusercontent.com/79488632/153547152-c9992201-7aa7-43b9-997a-df35f76e6be5.jpg)

#### 3) Move your finger in your own sequence
You can see that the application receives the finger movement EMG signal.

![R3](https://user-images.githubusercontent.com/79488632/153547159-a069ccb3-fb2b-44bb-b237-6a3b3d0a9b30.jpg)

#### 4) Input your ID and Click the Register button

![R4](https://user-images.githubusercontent.com/79488632/153547164-df692fcc-4a50-4700-9c5f-5a2721f86684.jpg)

### 2. Authentication Part

#### 1) Click the Authentication button 


![A1](https://user-images.githubusercontent.com/79488632/153547191-0bce65e1-b2bc-4e3c-aa5f-f4b0590a5eb7.jpg)

#### 2) Select the EMG device, and Click the Connect button

Then, the EMG device and the mobile device are connected through the Bluetooth protocol.

![A2](https://user-images.githubusercontent.com/79488632/153547197-50d90f02-d7db-47d1-8afe-6feefa3308e8.jpg)

#### 3) Move your finger in your own sequence
To succeed in authentication, you must follow the same steps as when registering.

![A3](https://user-images.githubusercontent.com/79488632/153547202-b1bee1dd-fb98-4289-93d8-cecb3747a26a.jpg)

#### 4) Input your ID and Click the Authenticate button
If your ID matches your finger movements, authentication is successful.

![A4](https://user-images.githubusercontent.com/79488632/153547206-dce6ccaf-9f5d-4c2f-a1c3-d3d66daa9a7e.jpg)

Otherwise, authentication fails.

![A5](https://user-images.githubusercontent.com/79488632/153547209-57920a09-23ed-4b9d-9252-7edcb2b3f94c.jpg)
