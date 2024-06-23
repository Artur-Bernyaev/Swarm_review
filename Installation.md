Short Description: The installation process of the controller depend on Webots version, which you are using. For my case, I am using the Webots R2020b, since it is most frendly version for improt 3D models, from different sources.

Setting the environment:
1. First, open the Webots
2. Next, press "Wizards" --> "New Project Directory"
3. The programm will open the window, in which you will see the following sentense "New project creation" & "This wizard will help you creating a new project", click "Next"
4. Next, you must choose the part for the project directory and then name the project. Example - "C:\Users\User\Documents\my_project2", where "my_project2" is tha name of the project, then click "Next"
5. Then, you must choose the name for new world and select the features which you want to add. I recomend to put tick on all features. Click "Next"
6. The last window you will see is the list of files, which will be added, click "Finish"
7. You will see the rectangle arena, and the following files - WorldInfo, Viewpoint, TexturedBackground, TexturedBackgroundLight, RectangleArena

Adding the e-puck model:
1. Using left mouse button, click on RectangleArena
2. Click on plus icon in the header of the programm (Add a new object or import an object.), or simply use Ctrl+Shift+A keyboard shortcut
3. Here is the location of the e-puck model - PROTO nodes (Webots Project)/robots/gctronic/e-puck/E-puck
4. Click on E-puck, using LMB, then click "Add"
5. Here it is, the E-puck model will appear on rectangle area

Creating a new controller:
1. Click on "Wizards" --> "New Robot Controller"
2. The programm will open the window, in which you will see the following sentense "New controller creation" & "This wizard will help you creating a new controller", click "Next"
3. Next, you need to choose a programming language for the controller. In our case its C++. Click on "C++" and the click "Next"
4. Then, there is and IDE selection, for the controller. In our case it is Webots. Click on "Webots(gcc /Makefile)", click "Next"
5. In the next window you need to choose name for the controller. Choose name, for example "my_controller_2", then click "Next"
6. Choose name carefully, so you will be able to find you controller from the list. There to many default controllers in Webots, beside the one you are creating
7. The last window you will see is the list of directory and files, which will be added, out tick on "Open "my_controller_2" in TextEditor", (so, you dpn't need to search the created controller to open) then click "Finish"
8. Copy to code from any of my controllers and paste it into the text file, you've just created

Implenemting the controller:
1. Click on "E-puck"
2. Select "controller "e-puck_avoid_obstacles" "
3. By default, e-puck model has the obstacles avoding controller
4. Click "Select..."
5. Form the list, choose the controller which you've created, press "OK"
6. Press Ctrl+2, to run the simulation, or the Run button in the header (Run the simulation in real-time.)

