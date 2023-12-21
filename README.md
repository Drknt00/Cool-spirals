# Cool-spirals
I have come across a different codes for cool looking spirals I replicated, mainly using turtle library

import turtle

t = turtle.Turtle()
s = turtle.Screen()
s.bgcolor("Black")
t.width(2)
t.speed(15)

col = ("white", "pink", "cyan")
for i in range (300):
    t.pencolor(col[i%3])
    t.forward(i*4)
    t.right(121)
