import turtle as t
import time


def draw(x, y):
    t.up()
    t.goto(x, y)
    t.down()


def h():
    draw(-250, 80)
    t.goto(-250, 0)
    draw(-250, 20)
    t.left(90)
    t.circle(-20, 180)
    t.goto(-210, 0)


def e():
    draw(-190, 20)
    t.goto(-160, 20)
    t.left(180)
    t.circle(20, 300)


def l(count):
    if count == 1:
        draw(-150, 80)
        t.goto(-150, 25)
        t.left(240)
        t.circle(25, 90)
    elif count == 2:
        draw(-125, 80)
        t.goto(-125, 25)
        t.left(270)
        t.circle(25, 90)
    elif count == 3:
        draw(125, 80)
        t.goto(125, 20)
        t.right(80)
        t.circle(25, 80)


def o(c):
    if c == 1:
        draw(-60, 35)
        t.left(140)
        t.circle(20, 360, 50)
    elif c == 2:
        draw(65, 35)
        t.circle(20, 360, 50)


def r():
    draw(85, 40)
    t.goto(85, 0)
    draw(85, 15)
    t.right(50)
    t.circle(-25, 90)


def d():
    draw(195, 80)
    t.goto(195, 15)
    draw(195, 20)
    t.left(90)
    t.circle(20, 360, 50)
    t.left(160)
    t.circle(20, 80)


def w():
    draw(-15, 40)
    t.goto(-5, 0)
    t.goto(5, 40)
    t.goto(15, 0)
    t.goto(25, 40)


def bg():
    t.screensize(1000, 1000, "black")
    t.pensize(10)
    t.pencolor("white")


def zm():
    h()
    e()
    l(1)
    l(2)
    o(1)
    w()
    o(2)
    r()
    l(3)
    d()
    draw(240, 80)
    t.goto(240, 20)
    draw(240, 0)
    t.dot(15)


def hello_world():
    bg()
    zm()
    draw(1000, 1000)


hello_world()
time.sleep(1)
