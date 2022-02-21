# FileGrunt
File Interrogation &amp; Processing Utility

This project is under development and is being used to help me learn C++, OpenCV and cross platform development.

# Development
I'm using the CLION IDE on Debian Bullseye and Gnome Desktop as my Development Environment

I'm using QT Framework 6.2.2, OpenCV 4.5.5 , SQLite 3 and C++ 

# How it works Now

1. Select a source folder
2. List of media files added to sqlite database
3. Duplicates identified by comparing file name and file size
4. Duplicate image files are then compared to each other using OpenCV bitwise XOR which results in all zeros if images match
5. The duplicates are recorded in the sqlite database

# TODO
Allow visual inspection of original and duplicate
Decide on which one should be classed as a duplicate e.g. earliest date?
Move the Duplicates to a location for archival/deletion
Remove the duplicates from the source
Improve README.md file as I go.

# Working Prototype
![image](https://user-images.githubusercontent.com/6379032/155019123-48916c28-0a87-4d0c-a83e-b799b8989361.png)

![image](https://user-images.githubusercontent.com/6379032/155020061-055f2def-3031-4c95-b59c-eb53857136e0.png)


# Does it Work
Initial inspection indicates duplicates are being identified correctly as expected.
