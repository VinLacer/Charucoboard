# Charucoboard
A little code made to identify QR codes in python using Charucoboard, this was made to help in a project of my scientific initiation that I participate in at the university.

To run with your images follow the next steps:

## Running the code

First of all, type the following commands in terminal:
```
$ git clone https://github.com/VinLacer/Charucoboard
```

Separate your imagens into a folder named images.

The script will create 2 folders named failed and detected to separate the images.

-> ***Keep the detected and failed folders empty***

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
Also, you need to choose the dictionary you want to use according to your preferences and images. You can see the dictionaries in the documentation of the Charuco or in the [Documentation](https://docs.opencv.org/3.4/d9/d6a/group__aruco.html#ggac84398a9ed9dd01306592dd616c2c975a6df6c3ad38ac44ea1546ef4f4841f310).

## Before script
<img src = "https://user-images.githubusercontent.com/71742380/192060555-f05a3ff6-f4c3-4e0e-80bd-94d248b784d2.png">

## After script

<img src = "https://user-images.githubusercontent.com/71742380/192060777-91845008-93f7-49fb-ae99-96ce89b624a4.png">

The result varies depending on the image quality. 


See the Jupyter Notebook for previews.
