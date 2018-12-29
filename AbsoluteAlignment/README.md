This is the code for positioning the robots according to a set of co-ordinates, with the robot-id 0 as the origin. The co-ordinates are mentioned in the coords dictionary in line number 10 of the .bzz file. Please note it is not necessary to assign (0, 0) to the robot-id 0. However, whatsoever it is assigned, it will be treated as the origin and all other robots will be positioned with respect to this bot.

This is done while avoiding obstacles.

#### ADDITIONAL CONSTANT(S): #####
RADIUS: Radius of the bot used. Its value is roughly 8.5 for footbot
