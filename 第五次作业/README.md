boolean dj=false;

void setup(){
  background(0,0,0);
  size(2550,2550);
  
}
void draw(){
 if(dj==true){ 
  fill(mouseX/10,0,mouseY/10);
  rect(mouseX,mouseY,10,10);
  noStroke();
 } 
 if(dj==false){ 
  fill(0,0,0,0);
  rect(mouseX,mouseY,10,10);
  noStroke();
 } 
}
void mousePressed(){
  dj=true;
}
void mouseReleased(){
  dj=false; 
}
