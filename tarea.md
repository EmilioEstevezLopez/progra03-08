void setup(){
  size(560,560);
  
}

void draw(){
  background(204);
/*
// invertido
  for(int i=1; i<=5; i=i+1){
    for (int j=1; j<=i; j=j+1){
    ellipse(i*100,j*100,50,50);
    */
    for(int i=1; i<=5; i=i+1){
    for (int j=1; j<=i; j=j+1){
    ellipse(j*100,i*100,50,50);
    }
   }
  }
