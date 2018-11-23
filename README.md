# trabajoenclases
int Diametro = 50;
int n;
void setup() {
  size(300, 300);
  noStroke();
  rectMode(CENTER);
  rect(100, 100, 250, 250);
}
void draw() {
  if (mousePressed) {
    n = int(random(0, 6));
    print(n);
  }

  switch(n) {
  case 0:
    uno();
    break;

  case 1:
    dos();
    break;

  case 2:
    tres();
    break;

  case 3: 
    cuatro();
    break;

  case 4:
    cinco();
    break;

  case 5:
    seis();
    break;
  }
}

void uno() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(100, 100, Diametro, Diametro);
}
void dos() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(50, 50, Diametro, Diametro);
  fill(0);
  ellipse(150, 150, Diametro, Diametro);
}
void tres() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(50, 50, Diametro, Diametro);
  ellipse(100, 100, Diametro, Diametro);
  ellipse(150, 150, Diametro, Diametro);
}
void cuatro() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(50, 50, Diametro, Diametro);
  ellipse(50, 150, Diametro, Diametro);
  ellipse(150, 50, Diametro, Diametro);
  ellipse(150, 150, Diametro, Diametro);
}
void cinco() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(50, 50, Diametro, Diametro);
  ellipse(50, 150, Diametro, Diametro);
  ellipse(100, 100, Diametro, Diametro);
  ellipse(150, 50, Diametro, Diametro);
  ellipse(150, 150, Diametro, Diametro);
}
void seis() {
  fill(255);
  rect(100, 100, 250, 250);
  fill(0);
  ellipse(50, 50, Diametro, Diametro);
  ellipse(50, 150, Diametro, Diametro);
  ellipse(50, 100, Diametro, Diametro);
  ellipse(150, 100, Diametro, Diametro);
  ellipse(150, 50, Diametro, Diametro);
  ellipse(150, 150, Diametro, Diametro);
}
