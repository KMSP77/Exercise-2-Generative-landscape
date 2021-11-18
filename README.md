size(500,500);
background(255,255,255);

float a  = random(0,500);
float b  = random(0,500);

fill(225,255,255);
rect(0,0,a,b);

fill(255,255,255);
rect(a + (500-a)/2,0,(500-a)/2, b);
