# FOR-FOR-YOU
composición utilizando iteración "For"

void setup(){
  
  size (700,450);
  
}

void draw(){
  
background(0,0,60);


 for(int blue=20; blue<300; blue=blue + 5){
   for(int black=0; black<750; black=black+50){
     
    //Sun
    strokeWeight(3);
     stroke(255,255,0,blue/16);
     ellipse(600,50,blue*2,blue*2);
     
     
    //forest
    strokeWeight(1);
     noFill();
     stroke(0,blue,150);
     
     ellipse(black,blue*2,blue,blue);
  
     }
   }  
 }
