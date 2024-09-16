n the bustling city of Techville, a new startup called RoboFleet has revolutionized the food delivery industry with autonomous delivery robots. However, the city is huge, and traffic conditions change frequently, causing delays for some robots while others zip through the streets with ease.

You’ve just been hired as a Python intern to help RoboFleet optimize their delivery system. Your job is to write a program that can track how long each robot takes to complete its delivery based on distance and speed, and determine the fastest robot for any given race.

The Challenge:

Each delivery robot has two attributes:

Distance (in kilometers) – The total distance it needs to cover.
Speed (in kilometers per hour) – The average speed at which the robot travels.
Your task is to:

Write a function that calculates the delivery time for each robot.
Write a second function that determines which robot is the fastest.
Requirements:

Create a Python class called Robot with:

An __init__ method that accepts distance and speed as parameters.
A method calculate_time() that returns the time taken by the robot to complete the delivery (time = distance / speed).
Write a function called find_fastest_robot() that accepts a list of Robot objects and returns the robot that takes the least time to complete its delivery.

Create 3 different robot instances with varying distances and speeds, then print the time taken by each robot and the fastest robot.
