# Trabralho-e-Pens.-Computacional-Quadradol- 
function setup() {
  createCanvas(800, 800);
   background("white");
}

function draw() {


  stroke("black");
  fill("purple");

  //console.log(mouseIsPressed);

  if (mouseIsPressed) {
    rect(mouseX, mouseY, 26, 36);
  }
}
