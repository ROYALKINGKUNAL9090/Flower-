import turtle as t
import math
import random

screen = t.Screen()
screen.setup(width=800, height=800)
screen.bgcolor("#11020f")
screen.tracer(0)

t.speed(0)
t.hideturtle()
t.penup()

WORD = "My Love"
FONT = ("Arial", 8, "bold")


def draw_petal(base, base_angle, length, width, color, points=20):
    t.color(color)
    bx, by = base
    cos_a, sin_a = math.cos(base_angle), math.sin(base_angle)
    for i in range(points + 1):
        theta = 2 * math.pi * i / points
        rad = length * math.sin(theta)
        side = width * math.cos(theta) * math.cos(theta)
        rx = rad * cos_a + side * sin_a
        ry = rad * sin_a + side * cos_a
        t.goto(bx + rx, by + ry)
        t.write(WORD, align="center", font=FONT)


def draw_leaf(base, angle_deg, length, width):
    draw_petal(base, math.radians(angle_deg), length, width, "#14a83c", points=15)


rings = [
    {"radius": 4, "count": 4, "length": 35, "width": 15, "color": "#f1abcf", "offset": 0},
    {"radius": 15, "count": 5, "length": 55, "width": 22, "color": "#f17ebb", "offset": 15},
    {"radius": 30, "count": 7, "length": 75, "width": 30, "color": "#f159a2", "offset": 30},
    {"radius": 45, "count": 9, "length": 95, "width": 40, "color": "#f13289", "offset": 15},
    {"radius": 60, "count": 11, "length": 115, "width": 48, "color": "#f11378", "offset": 45},
    {"radius": 75, "count": 12, "length": 135, "width": 55, "color": "#e7176d", "offset": 0},
]

# Draw Stem and Leaves
t.goto(0, -90)
t.setheading(160)
t.pendown()

t.color("#14a83c")
t.circle(250, 25)
pos1, head1 = t.position(), t.heading()
t.penup()
draw_leaf(base=pos1, angle_deg=160, length=50, width=25)
t.goto(pos1)
t.setheading(head1)
t.pendown()

t.circle(250, 25)
pos2, head2 = t.position(), t.heading()
t.penup()
draw_leaf(base=pos2, angle_deg=-30, length=55, width=28)
t.goto(pos2)
t.setheading(head2)
t.pendown()

t.circle(250, 20)
t.penup()

# Draw Flower Petals
for ring in rings:
    for i in range(ring["count"]):
        angle = (360 / ring["count"]) * i + ring["offset"]
        base_x = ring["radius"] * math.cos(math.radians(angle))
        base_y = ring["radius"] * math.sin(math.radians(angle))

        draw_petal(
            base=(base_x, base_y),
            base_angle=math.radians(angle),
            length=ring["length"],
            width=ring["width"],
            color=ring["color"]
        )

# Background Stars
t.color("#ff72a1")
for i in range(12):
    x = random.randint(-250, 250)
    y = random.randint(-250, 250)
    if math.hypot(x, y) > 120:
        t.goto(x, y)
        t.write("✦", align="center", font=("Courier", 14, "bold"))

# Footer
t.goto(0, -320)
t.color("white")
t.write("Click anywhere to close", align="center", font=("Arial", 10, "italic"))
screen.exitonclick()
