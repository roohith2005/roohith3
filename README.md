# roohith3
from turtle import *

bgcolor('pink')
speed(0)
hideturtle()
for i in range(120):
    color('red')
    circle(i)
    color('black')
    circle(i*0.8)
    right(3)
    forward(3)
done()    
