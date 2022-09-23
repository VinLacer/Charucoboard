# Charucoboard
A little code made to identify QR codes in python using Charucoboard, this was made to help in a project of my scientific initiation that I participate in at the university.

To run with your images follow the next steps:

## Settings 

First of all, type the following commands in terminal:
```
$ git clone https://github.com/VinLacer/Charucoboard
```




## Images
Separate your imagens into a folder, then change the imgs_path.

```
imgs_path = base_path / "your_folder_name"
```

To separate the images that contain a QR code create a folder named "detected" and another folder named "failed", to get images that not contains Qr codes.
Like this:

![image](https://user-images.githubusercontent.com/71742380/192044803-6be390da-f78f-40f4-b536-2ce633e54a0a.png)

-> ***Keep the detected and failed folders empty***

## Running the code

In Linux you can just open a terminal into the Charuco folder and type these commands:

```
$ python CharucoBoard.py
```

So in the detected folder, you will see the images with QR codes detected also with an ID and a markdown. 

## Note

In this case I use a 3x5 board, so you can change this in the source code to adjust to your board as well. To do that just change this line:

```
m, n = 3, 5
```
Also, you need to choose the dictionary you want to use according to your preferences and images. You can see the dictionaries in the documentation of the Charuco or in this link:
https://docs.opencv.org/3.4/d9/d6a/group__aruco.html#ggac84398a9ed9dd01306592dd616c2c975a6df6c3ad38ac44ea1546ef4f4841f310



See the Jupyter Notebook for previews.
