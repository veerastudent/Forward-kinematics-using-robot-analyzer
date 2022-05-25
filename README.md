# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1.open the roboanalyzer software.

2.select the robot and its degrees of freedom.

3.change the values with the link lenght wherever necessary.

4.simulate the model for forward kinematics.

5.plot the graph between the link and the joints.

6.update the DH parameters of the link configuration and end effector configuration.



### SIMULATION 

6 DOF

 ![Screenshot 2022-05-25 094025](https://user-images.githubusercontent.com/75234790/170178957-ad81ba67-acda-4da3-b6f8-c88c61b11246.png)

4 DOF

 
 ![Screenshot 2022-05-25 093917](https://user-images.githubusercontent.com/75234790/170178967-e1999ba5-c6f4-49da-bfe0-4115ceb1ae65.png)

 
 
 
 
 ### PLOT 
 
 4 DOF
 
 ![Screenshot 2022-05-25 094538](https://user-images.githubusercontent.com/75234790/170178985-286bbb45-7abc-451a-91ad-41cf5df63303.png)

 
 ![Screenshot 2022-05-25 094430](https://user-images.githubusercontent.com/75234790/170178992-55da913a-94be-43fd-8b9c-f1aa008612d3.png)

 
 
 
 ![Screenshot 2022-05-25 094204](https://user-images.githubusercontent.com/75234790/170178999-e067ad8a-2727-4843-a099-a09085b5a6b2.png)

 
 
 6 DOF
 
 
 ![Screenshot 2022-05-25 094111](https://user-images.githubusercontent.com/75234790/170179084-a3a2dbbd-b69e-46af-9da0-2921f59b7772.png)


 
 

![Screenshot 2022-05-25 095240](https://user-images.githubusercontent.com/75234790/170179337-5e744a11-6a77-4462-95bf-675bacba7181.png)




![Screenshot 2022-05-25 095313](https://user-images.githubusercontent.com/75234790/170179358-3ad6316a-8357-49c4-a445-d36246c571bc.png)









### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
