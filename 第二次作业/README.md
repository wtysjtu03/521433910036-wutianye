Eye s1, s2;

void setup() {
  size(340, 360);
  noStroke();
  s1 = new Eye( 250,  16, 120);
  s2 = new Eye( 164, 185,  80);  

}

void draw() {
  background(102);
  
  s1.update(mouseX, mouseY);
  s2.update(mouseX, mouseY);

  s1.display();
  s2.display();
}
