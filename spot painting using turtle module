# import colorgram
# colors = colorgram.extract("image.jpg", 30)
# color_list = []
# for color in colors:
#     r = color.rgb.r
#     g = color.rgb.g
#     b = color.rgb.b
#     new_color = (r, g, b)
#     color_list.append(new_color)
import turtle
import random

turtle.colormode(255)
color_list = [(202, 164, 110), (240, 245, 241), (236, 239, 243), (149, 75, 50), (222, 201, 136), (53, 93, 123),
              (170, 154, 41), (138, 31, 20), (134, 163, 184), (197, 92, 73), (47, 121, 86), (73, 43, 35),
              (145, 178, 149), (14, 98, 70), (232, 176, 165), (160, 142, 158), (54, 45, 50), (101, 75, 77),
              (183, 205, 171), (36, 60, 74), (19, 86, 89), (82, 148, 129), (147, 17, 19), (27, 68, 102),
              (12, 70, 64), (107, 127, 153), (176, 192, 208), (168, 99, 102)]
tim = turtle.Turtle()
i = 10
while i > 0:
        if tim.pos()[0] == 450:
            tim.left(90)
            tim.dot(20, random.choice(color_list))
            tim.penup()
            tim.forward(50)
            tim.pendown()
            tim.left(90)
            i -= 1
        if tim.pos()[0] == 0 and tim.pos()[1] != 0:
            tim.right(90)
            tim.dot(20, random.choice(color_list))
            tim.penup()
            tim.forward(50)
            tim.pendown()
            tim.right(90)
            i -= 1
        if i > 0:
            for moves in range(9):
               tim.dot(20, random.choice(color_list))
               tim.penup()
               tim.forward(50)
               tim.pendown()
               print(tim.pos())
       

screen = turtle.Screen()
screen.exitonclick()

