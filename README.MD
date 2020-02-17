What code draws the blades of grass?

function draw() {
  stroke(random(70,80), 155, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();
  
  What code makes the "lawnmower" come by? How often does it come by?
  
  
  
What's the point of the h variable?
hight of the grass.



What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
when the grass reaches the border it stops and starts from left again.
