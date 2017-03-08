int pantalla=0;
int seleccion=0;
int turno=0;

PImage fondo1;
PImage title1;
PImage fondo2;
PImage title2;
PImage fondo3;
PImage golpe1;
PImage golpe2;
PImage golpe3;
PImage golpe4;
int[] jugador1=new int[4];
int[] jugador2=new int[4];

int[] m1=new int[4];
int[] m2=new int[4];
int[] m3=new int[4];
int[] m4=new int[4];
int[] m5=new int[4];
int[] m6=new int[4];

void  monster1()
{
  //Dibujo
  noStroke();
  fill(255, 0, 0);
  rect(70, 0, 30, 10); 
  rect(60, 10, 50, 10);
  rect(50, 20, 20, 10);
  rect(100, 20, 20, 10);
  rect(40, 30, 30, 10);
  fill(255, 150, 30);
  rect(80, 30, 10, 10);//ojo
  fill(255, 0, 0);
  rect(100, 30, 30, 10);
  rect(30, 40, 40, 10);
  rect(100, 40, 40, 10);
  rect(20, 50, 30, 10);
  rect(60, 50, 50, 10);

  rect(120, 50, 30, 10);
  rect(20, 60, 30, 10);
  rect(70, 60, 30, 10);
  rect(120, 60, 30, 10);
  rect(10, 70, 150, 10);
  rect(10, 80, 10, 10);
  rect(30, 80, 110, 10);
  rect(150, 80, 10, 10);
  rect(10, 90, 10, 10);
  rect(40, 90, 40, 10);
  rect(90, 90, 40, 10);
  rect(150, 90, 10, 10);

  rect(20, 100, 10, 10);
  rect(50, 100, 70, 10);
  rect(140, 100, 10, 10);
  rect(60, 110, 10, 10);
  rect(100, 110, 10, 10);
  rect(60, 120, 10, 10);
  rect(100, 120, 10, 10);
  rect(50, 130, 10, 10);
  rect(70, 130, 10, 10);
  rect(90, 130, 10, 10);
  rect(110, 130, 10, 10);
}

//size(170,160); 
//background(255);
void monster2()
{
  

  noStroke();
  fill(0, 200, 200);
  rect(60, 10, 10, 10); 
  rect(110, 10, 10, 10);
  rect(40, 20, 80, 10);
  rect(30, 30, 20, 10);
  rect(70, 30, 10, 10);
  rect(100, 30, 20, 10);
  rect(30, 40, 90, 10);
  rect(30, 50, 90, 10);
  rect(30, 60, 20, 10);
  rect(60, 60, 10, 10);
  rect(80, 60, 10, 10);
  rect(100, 60, 20, 10);
  rect(40, 70, 10, 10);
  rect(100, 70, 20, 10);
  rect(10, 80, 50, 10);
  rect(70, 80, 10, 10);
  rect(90, 80, 30, 10);
  rect(10, 90, 10, 10);
  rect(30, 90, 90, 10);
  rect(30, 100, 90, 10);
  rect(40, 110, 80, 10);
  rect(50, 120, 20, 10);
  rect(90, 120, 20, 10);
  rect(50, 130, 20, 10);
  rect(90, 130, 20, 10);
}

void monster3() {

  noStroke();
  fill(100, 200, 100);
  rect(40, 10, 10, 10);
  rect(70, 10, 10, 10);
  rect(30, 20, 60, 10);
  rect(30, 30, 10, 10);
  rect(50, 30, 10, 10);
  rect(70, 30, 20, 10);
  rect(20, 40, 70, 10);
  rect(110, 40, 10, 10);
  rect(80, 50, 10, 10);
  rect(100, 50, 10, 10);
  rect(20, 60, 10, 10);
  rect(40, 60, 10, 10);
  rect(60, 60, 10, 10);
  rect(80, 60, 40, 10);
  rect(30, 70, 60, 10);
  rect(100, 70, 10, 10);
  rect(30, 80, 60, 10);
  rect(110, 80, 10, 10);
  rect(30, 90, 50, 10);
  rect(40, 100, 10, 10);
  rect(60, 100, 10, 10);
  rect(30, 110, 20, 10);
  rect(60, 110, 20, 10);
}


void monster4() {

  noStroke();
  fill(255, 50, 50);
  rect(20, 10, 10, 10);
  rect(80, 10, 10, 10);
  rect(20, 20, 20, 10);
  rect(80, 20, 20, 10);
  rect(20, 30, 80, 10);
  rect(20, 40, 90, 10);
  rect(10, 50, 100, 10);
  rect(40, 50, 20, 10);
  rect(70, 50, 50, 10);
  rect(10, 60, 20, 10);
  rect(50, 60, 10, 10);
  rect(80, 60, 50, 10);
  rect(20, 70, 100, 10);
  rect(20, 80, 20, 10);
  rect(80, 80, 30, 10);
  rect(20, 90, 10, 10);
  rect(40, 90, 40, 10);
  rect(90, 90, 10, 10);
  rect(20, 100, 70, 10);
  rect(40, 110, 30, 10);
  rect(10, 120, 10, 10);
  rect(30, 120, 50, 10);
  rect(90, 120, 10, 10);
  rect(20, 130, 10, 10);
  rect(40, 130, 30, 10);
  rect(80, 130, 20, 10);
  rect(40, 140, 10, 10);
  rect(60, 140, 10, 10);
  rect(30, 150, 20, 10);
  rect(60, 150, 20, 10);
}

void monster5() {


  noStroke();
  fill(110, 50, 250);
  rect(30, 30, 10, 10);
  rect(110, 30, 10, 10);
  rect(20, 40, 20, 10);
  rect(110, 40, 20, 10);
  rect(40, 50, 10, 10);
  rect(70, 50, 10, 10);
  rect(100, 50, 10, 10);
  rect(50, 60, 50, 10);
  rect(40, 70, 70, 10);
  rect(20, 80, 110, 10);
  rect(20, 90, 10, 10);
  rect(40, 90, 10, 10);
  rect(70, 90, 10, 10);
  rect(100, 90, 10, 10);
  rect(120, 90, 10, 10);
  rect(10, 100, 20, 10);
  rect(40, 100, 70, 10);
  rect(120, 100, 20, 10);
  fill(255, 255, 0);
  rect(40, 110, 70, 10);
  rect(40, 120, 70, 10);
  rect(40, 130, 70, 10);
  rect(40, 140, 10, 10);
  rect(60, 140, 10, 10);
  rect(80, 140, 10, 10);
  rect(100, 140, 10, 10);
  rect(30, 150, 20, 10);
  rect(100, 150, 20, 10);
}


void monster6() {

  noStroke();
  fill(80, 250, 120);
  rect(30, 10, 10, 10);
  rect(60, 10, 30, 10);
  rect(110, 10, 10, 10);
  rect(40, 20, 70, 10);
  rect(30, 30, 20, 10);
  rect(70, 30, 10, 10);
  rect(110, 30, 10, 10);
  rect(30, 40, 20, 10);
  rect(70, 40, 10, 10);
  rect(110, 40, 10, 10);
  rect(30, 50, 50, 10);
  rect(110, 50, 10, 10);
  rect(40, 60, 10, 10);
  rect(60, 60, 60, 10);
  rect(70, 70, 50, 10);
  rect(10, 80, 10, 10);
  rect(30, 80, 10, 10);
  rect(50, 80, 10, 10);
  rect(70, 80, 50, 10);
  rect(20, 90, 100, 10);
  rect(30, 100, 90, 10);
  rect(40, 110, 70, 10);
  rect(30, 120, 10, 10);
  rect(50, 120, 50, 10);
  rect(110, 120, 10, 10);
  rect(50, 130, 10, 10);
  rect(90, 130, 10, 10);
  rect(40, 140, 20, 10);
  rect(80, 140, 20, 10);
}

void setup()
{


  m1[0]=3;
  m1[1]=3;
  m1[2]=15;
  m1[3]=1;

  m2[0]=3;
  m2[1]=3;
  m2[2]=15;
  m2[3]=2;

  m3[0]=3;
  m3[1]=4;
  m3[2]=15;
  m3[3]=1;

  m4[0]=4;
  m4[1]=3;
  m4[2]=15;
  m4[3]=2;

  m5[0]=3;
  m5[1]=2;
  m5[2]=15;
  m5[3]=1;

  m6[0]=3;
  m6[1]=2;
  m6[2]=15;
  m6[3]=2;

  size(600, 400); 
  //background(255);
  textSize(40);
  

  fondo1 = loadImage("galaxy1.png");
  title1 = loadImage("TITLE1.png");
  fondo2 = loadImage("galaxia.png");
  title2 = loadImage("TITLE2.png");
  fondo3 = loadImage("pelea.png");
  golpe1 = loadImage("golpe1.png");
  golpe2 = loadImage("golpe2.png");
  golpe3 = loadImage("golpe3.png");
  golpe4 = loadImage("golpe4.png");
}

void draw()
{
 
  
  

  switch (pantalla)
  {
  case 0:
    background(255);
    pushMatrix();
    textSize(20);
    fill(50);
    text("PRESIONE FLECHA ARRIBA PARA SELECCIONAR",100,100);
    popMatrix();
    //image(fondo1,0,0);
    //image(title1,0,0);
    
    
    break;
  case 1:
    background(155);
     pushMatrix();
    textSize(20); 
    text("CON EL CURSOR SELECCIONE J1 Y J2",100,200);
    popMatrix();
    //image(fondo2,0,0);
    //image(title2,0,0);

    monster1();

    pushMatrix();
    translate(200, 0);
    monster2();
    popMatrix();

    pushMatrix();
    translate(400, 0);
    monster3();
    popMatrix();

    pushMatrix();
    translate(0, 200);
    monster4();
    popMatrix();

    pushMatrix();
    translate(200, 200);
    monster5();
    popMatrix();

    pushMatrix();
    translate(400, 200);
    monster6();
    popMatrix();

    break;
  case 2:
   
    //image(fondo3,0,0);
    background(255,200,200);
      fill(0,255,0);
      textSize(24);
      text("J1 GLP1= A GLP2= S     J2 GLP1= L GLP2= K", 50, 370);
    
    pushMatrix();
    fill(255,0,0);
    rect(100,100,jugador1[2],30);
    popMatrix();
    
    pushMatrix();
    fill(255,0,0);
    rect(300,100,jugador2[2],30);
    popMatrix();
    
    pushMatrix();
    translate(100, 100);
    if (jugador1==m1)
    {
      monster1();
    } else if (jugador1==m2)
    {
      monster2();
    } else if (jugador1==m3)
    {
      monster3();
    } else if (jugador1==m4)
    {
      monster4();
    } else if (jugador1==m5)
    {
      monster5();
    } else if (jugador1==m6)
    {
      monster6();
    }
    popMatrix();

    pushMatrix();
    translate(400, 100);
    if (jugador2==m1)
    {
      monster1();
    } else if (jugador2==m2)
    {
      monster2();
    } else if (jugador2==m3)
    {
      monster3();
    } else if (jugador2==m4)
    {
      monster4();
    } else if (jugador2==m5)
    {
      monster5();
    } else if (jugador2==m6)
    {
      monster6();
    }
    popMatrix();


    if (jugador1[2]<=0)
    {
      fill(255);
      text("YOU WIN PRESS BAR", 220, 50);
    } else if (jugador2[2]<=0)
    {
      fill(255);
      text("YOU WIN PRESS BAR", 50, 50);
    }
  }
}

void keyPressed()
{
  if (keyCode==UP)
  {
    pantalla=1;
  }

  if (turno==0&&pantalla==2)
  {
    if (key=='a'||key=='A')
    {
      
      //image (golpe3,0,-150);
      jugador2[2]=jugador2[2]-(jugador1[0]-jugador2[3]);
      println(jugador2[2]);
      turno=1;
    }
    if (key=='s'||key=='S')
    {
      //image (golpe4,0,-150);
      jugador2[2]=jugador2[2]-(jugador1[1]-jugador2[3]);
      println(jugador2[2]);
      turno=1;
    }
  }
  if (turno==1&&pantalla==2)
  {
    if (key=='l'||key=='L')
    {
      //image (golpe1,0,-100);
      jugador1[2]=jugador1[2]-(jugador2[0]-jugador1[3]);
      println(jugador1[2]);
      turno=0;
    } 
    if (key=='k'||key=='K')
    {
      //image (golpe2,0,-100);
      jugador1[2]=jugador1[2]-(jugador2[1]-jugador1[3]);
      println(jugador2[2]);
      turno=0;
    }
  }

  if (jugador1[2]<=0||jugador2[2]<=0)
  {
    if (key==' ') {
      pantalla=0;
    }
  }
}

void mouseClicked()
{
  if (pantalla==1)
  {
    //Monster1
    if (mouseX>0&&mouseX<200&&mouseY>0&&mouseY<200)
    {
      if (seleccion==0)
      {
        jugador1=m1;
        seleccion=1;
        //println(jugador1);
        //println(seleccion);
      } else if (seleccion==1)
      {
        //P2
        jugador2=m1;
        //println(jugador2);
        pantalla=2;
      }
    }

    //Monster2
    if (mouseX>200&&mouseX<400&&mouseY>0&&mouseY<200)
    {
      if (seleccion==0)
      {
        jugador1=m2;
        seleccion=1;
        //println(jugador1);
      } else if (seleccion==1)
      {
        //P2
        jugador2=m2;
        //println(jugador2);
        pantalla=2;
      }
    }

    //Monster3
    if (mouseX>400&&mouseX<600&&mouseY>0&&mouseY<200)
    {
      if (seleccion==0)
      {
        jugador1=m3;
        seleccion=1;
        //println(jugador1);
        //println(seleccion);
      } else if (seleccion==1)
      {
        //P2
        jugador2=m3;
        //println(jugador2);
        pantalla=2;
      }
    }

    //Monster4
    if (mouseX>0&&mouseX<200&&mouseY>200&&mouseY<400)
    {
      if (seleccion==0)
      {
        jugador1=m4;
        seleccion=1;
      } else if (seleccion==1)
      {
        //P2
        jugador2=m4;
        pantalla=2;
      }
    }

    //Monster5
    if (mouseX>200&&mouseX<400&&mouseY>200&&mouseY<400)
    {
      if (seleccion==0)
      {
        jugador1=m5;
        seleccion=1;
      } else if (seleccion==1)
      {
        //P2
        jugador2=m5;
        pantalla=2;
      }
    }

    //Monster6
    if (mouseX>400&&mouseX<600&&mouseY>200&&mouseY<400)
    {
      if (seleccion==0)
      {
        jugador1=m6;
        seleccion=1;
      } else if (seleccion==1)
      {
        //P2
        jugador2=m6;
        pantalla=2;
      }
    }
  }
}
