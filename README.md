# 2D-Art-Crafting-Using-STM32-LINEAR-LINES-ONLY

![IMG_20220217_104317](https://user-images.githubusercontent.com/52085750/166915003-6920d180-9b23-4d47-a0d1-5096f986da39.jpg)

2d Art Crafting machine using stm32 black pill. Only linear lines can be made. 


The code consists of only the main source file. 
You will have to manually configure the pins using mxcube before.

there is a 50 x 50 matrix. In order to create a shape, change the matrix values to 1.

        
       0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 0 0 0
       0 0 0 0 0 0 0 1 0 0 0 0 0 0 1 0 0 0
       0 0 0 0 0 0 0 1 0 0 0 0 0 0 1 0 0 0
       0 0 0 0 0 0 0 1 0 0 0 0 0 0 1 0 0 0
       0 0 0 0 0 0 0 1 0 0 0 0 0 0 1 0 0 0
       0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 0 0 0

suppose the matrix is like that.
so lines would now be constructed 

    ________________
    |              |
    |              |
    |              |
    ________________
    
    THERE WOULD BE NO SPACE. THIS IS JUST A DEMONSTATION.
    
    
  You would need 3 stepper motors.
   
  1 for x axis
  1 for y axis
  1 for up and down for the pen. you can use any other device too for this purpose.
  
 
![IMG_20220217_104317](https://user-images.githubusercontent.com/52085750/166915003-6920d180-9b23-4d47-a0d1-5096f986da39.jpg)
