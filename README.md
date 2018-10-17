# jj-draw
var length2;
var points;
var radius;
var circ;
var sides;
var repeat;

function draw_a_house(length2) {
  for (var count = 0; count < 3; count++) {
      moveForward(length2);
    turnLeft(120);
  }
  for (var count2 = 0; count2 < 4; count2++) {
      moveForward(length2);
    turnRight(90);
  }
}

penPattern("rainbowLine");
jumpForward(100);
draw_a_house(22);
penPattern("ropeLine");
jumpBackward(100);
draw_a_pinwheel(10, 20, 50);
jumpBackward(150);
penPattern("squigglyLine");
draw_a_star(5, 20);
penPattern("swirlyLine");
turnRight(52);
jumpForward(160);
draw_a_shape(20, 10);
penPattern("squigglyLine");
turnLeft(70);
jumpForward(150);
draw_a_circle(10);
penPattern("rainbowLine");
jumpForward(100);
draw_a_square(10);
penPattern("swirlyLine");
turnLeft(93);
jumpForward(100);
draw_a_triangle(50);
jumpForward(150);
penPattern("squigglyLine");
