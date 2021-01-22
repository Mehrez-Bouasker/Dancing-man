# Dancing-man
AR Foundation is a framework purpose-built for augmented reality development that allows you to build rich experiences once, then deploy across multiple mobile and wearable AR devices.
This is a first dive-in project aiming to explore this framework making an AR mobile application using Unity 3D.
## Setting up the project
first we create a new empty 3D unity project and switch our platform to Android under **File -> Build Settings**
![alt text](./ScreenShots/3d.png)

![alt text](./ScreenShots/Android.png)

In the package manager (**Window -> Package Manager**) we should install 
-ARFoundation
-AR Subsystems
-ARCore XR Plugin
make sure to also install and import **XR Plugin Management** into your project
![alt text](./ScreenShots/Plugin.png)


Lastly we need to set up the player under **Edit -> Project Settings**
-remove multhithread rendering
-activate autographics API
-change minimum API level to 24
-enabele auto graphics API
-change company name
you can follow this link for a demo of this aprt [demo](https://youtu.be/0mpsiO2lCx0)

After setting up we can now add an **ARSession origin** and an **ARSession** and run our application

## Setting up dancing man application
Now let us first add 
-AR plane manager (only leaving the horizontal detection mode)
-AR raycast manager
to **AR Session origin** as new components 

![alt text](./ScreenShots/Components.png)


### Creating a placement indicator

 