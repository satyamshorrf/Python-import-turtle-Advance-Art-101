# Python-import-turtle-Advance-Art-101
Create python use import turtle graphics code
from turtle import*
import colorsys as P
bgcolor("black")
tracer(100)
h=0.1

for i in range(2000):
    c=P.hsv_to_rgb(h,1,1)
    fillcolor(c)
    h+=0.003
    begin_fill()
    circle(170,72)
    right(18)
    end_fill()

done()   
 
