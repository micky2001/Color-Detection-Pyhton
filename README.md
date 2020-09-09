# Color-Detection-Pyhton
Libraries Used: Pandas, OpenCV, Numpy and argparse 

Description:
An application which can automatically get the name of the color by clicking on them.  So for this The data file of the project contains the color name and it value in RGB. We will get the RGB value of the input color. Then we will calculate the distance from each color and find the shortest one. Colors are made up 3 primary color: Red, Green & Blue. In computer we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16.5million different ways to represent a color. In our dataset we need to map each color’s value with their corresponding name. 
My dataset contains RGB values, hexadecimal values with the corresponding color name. It includes 865 color names along with RGB & hex values.
STEPS:
1.	Taking image from user:
2.	Read the csv file with pandas:
3.	Set a mouse call back event on a window:
4.	Create a draw function:
5.	Calculate The Distance to get the Color name:
6.	Display the image on the window:
7.	Run the Python file:
 Go to the directory of the file saved and then write following command:
                      Python color_detection.py -I colorpic.jpg
