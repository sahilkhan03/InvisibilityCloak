# Invisibility Cloak
Invisibility Cloak to make yourself invisible .


# Steps


First :
Choose the camera (either using webcam or mobilecam)

Second :
According to the lighting condition of your room , find upper and lower HSV values of the color you want to make disappear

To use webcam run find_hsv_webcam.py
To use mobile cam , download IP webcam App in your mobile and on its camera and change the IP accordingly to start and
then find upper and lower HSV values of the color you want to make disappear.

Adjust the upper and lower HSV values until the color disappears.

NOTE : Make sure while testing keep some other shades of that color with it , so to find the HSV value of that particular
shade correctly.

Some of the tested HSV values : 
lower_light_Red = [0,120,70]        upper_light_red = [10,255,255]
lower_green = [45,100,60]        upper_green = [95,255,255]
lower_purple = [100,90,50]        upper_purple = [130,255,255]


