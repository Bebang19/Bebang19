import turtle

turtle.bgcolor("black")
pen = turtle.turtle()
pen.hideturtle()
pen.pencolor("red")
pen.fillcolor('red')
pen.begin_fill()
pen.left(140)
pen.forward(113)
for i in range(200):
    pen.rigth(1)
    pen.forward(1)
pen.left(120)
for i in range(200):
    pen.rigth(1)
    pen.forward(1)
pen.forward(112)
pen.end_fill()

turtle.done()
