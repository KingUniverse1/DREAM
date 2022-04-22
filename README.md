# DREAM
doors to infinite realities and universes with a side of teal floating "clouds"

//variable(s)
let x = 100;

// Only runs once
function setup() {
  createCanvas(1000, 800);
  smooth();
  
}

// Runs over and over in a loop
function draw() {
  // Set the background
  background(red(43),green(45),blue(66));
 
 /*doors*/
  //cinnamon satin
  noStroke();
  fill(red(181),green(101),blue(118));
  circle(200,200,300);
  //tumble weed
  noStroke();
  fill(red(222),green(170),blue(136));
  rect((50,30),500,200);
  //candy pink
  noStroke();
  fill(red(229),green(107),blue(111));
  circle(650,400,500); 
   //tumble weed
  noStroke();
  fill(red(222),green(170),blue(136));
  rect((300,1000),600,500);
 
 /*text*/
 fill(red(152),green(193),blue(217));
 text('DREAM', 300,400);
 textSize(100)
 
  /*floating "clouds"*/
  noStroke();
  fill(red(102),green(221),blue(170));
  circle(x,35,25)
  noStroke();
  fill(red(102),green(221),blue(170)); 
  ellipse(x,155,85,70)
  noStroke();
  fill(red(102),green(221),blue(170));
  circle(x,400,200)
  noStroke();
  fill(red(102),green(221),blue(170));
  circle(x,250,55)
  noStroke();
  fill(red(102),green(221),blue(170));
  ellipse(x,650,195,150)
    x = x+1;
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
}
