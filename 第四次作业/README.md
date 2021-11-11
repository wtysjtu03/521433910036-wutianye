
String txt ="happyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappyhappy";
void setup() {
  size(800, 800);
  for (int j=0; j<8; j++) {
    for (int i=0; i<8; i++) {
      char c= txt.charAt(i+1+j*8);
      int x=int(c);
      fill(x, 100, 100);
      rect(i*100, j*100, 100, 100);
    }
  }
}
