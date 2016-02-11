void setup() {
  size(700,600);
}

void draw() {
  if(mousePressed){
  background(0);
  
  stroke(0);
  fill(0, 0, 255);
  ellipse(mouseX, mouseY, 500, 500);

  stroke(255);
  fill(255);
  ellipse(mouseX, mouseY, 400, 400);
  
  stroke(255, 0, 0);
  fill(255, 0, 0);
  rect(mouseX-125, mouseY-125, 250, 250);
  
  stroke(255);
  fill(255);
  ellipse(mouseX, mouseY, 200, 200);
  
  stroke(0, 0, 255);
  fill(0, 0, 255);
  rect(mouseX-25, mouseY-75, 50, 150);
  
  stroke(0, 0, 255);
  fill(0, 0, 255);
  rect(mouseX-75, mouseY-25, 150, 50);
  } else{
    background(255);
  }
}
