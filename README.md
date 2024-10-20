# CIS 5660 HW03 Procedural Building

# Demo

https://github.com/user-attachments/assets/210ce985-a7b0-4c1f-b1ed-f3d2cca6994d

# Description

For this project, I developed a procedural multi-floor building generator in Houdini following Simon Houdini's tutorial: [Click here for tutorial.](https://www.youtube.com/watch?v=uIe97023sDk).
The core of the project involved creating a custom Houdini Digital Asset (HDA) that stacks boxes to form the basic structure of the building.

![image.png](image.png)

I extended the setup by adding detailed elements, each with customizable parameters like height, width, and additional features.

![image.png](image%201.png)

These elements are seamlessly integrated into the building, allowing for flexible customization based on the chosen architectural style.

![image.png](image%202.png)

I also incorporated features like pillars, borders, and supports for overhanging floors. The user interface includes adjustable parameters to modify building dimensions and details dynamically.

![image.png](image%203.png)

There is a node used to control the the height and width of the windows, and you can switch the style of the building accordingly.

![image](https://github.com/user-attachments/assets/756cf3e4-4731-465e-8221-ccd45bf93009)

Also, you can control the window to be single or double in this node:
| Single Window | Double Window |
| ---- | ---- | 
|![image](https://github.com/user-attachments/assets/4565a571-4b7e-4906-ad9f-2419cebde230)|![Double](https://github.com/user-attachments/assets/086b6b66-1f74-46c3-ab1a-f942f542df4f)|

The style defines the following pattern of the outside style:
| Style 0 | Style 1 |
| ---- | ---- | 
|![image](https://github.com/user-attachments/assets/3181a7bd-7ef3-4917-9a5f-36f536173536)|![image](https://github.com/user-attachments/assets/d27dcbb3-590a-4a74-9ce2-80a8c531a4ac)|

# Reference
I used these models for windows:  
[Window1](https://sketchfab.com/3d-models/window-e826c513779149d7ab3bde944647573f)  
[Window2](https://sketchfab.com/3d-models/residential-window-ae11104237314463a61251fd46ded4b4)  
[Window3](https://sketchfab.com/3d-models/picture-window-5c7987af188c4b7087003fd76385fade)  
