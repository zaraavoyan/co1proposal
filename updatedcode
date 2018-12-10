var bg;

var S1P = false;
var S2P = false;
var S3P = false;
var S4P = false;
var S5P = false;
var S6P = false;
var S7P = false;
var S8P = false;
var S9P = false;
var S10P = false;
var S11P = false;
var S12P = false;
var S13P = false;
var S14P = false;




var isPlaying = false;

function preload() {
  bg = loadImage("assets/zaraUI1.jpg");
  S1 = loadSound("assets/01Intro.mp3");
  S2 = loadSound("assets/02Light.mp3");
  S3 = loadSound("assets/03BounceBack.mp3");
  S4 = loadSound("assets/04NoFavors.mp3");
  S5 = loadSound("assets/05JOTW.mp3");
  S6 = loadSound("assets/06Moves.mp3");
  S7 = loadSound("assets/07SameTime.mp3");
  S8 = loadSound("assets/08OweMe.mp3");
  S9 = loadSound("assets/09HWOTB.mp3");
  S10 = loadSound("assets/10VIMH.mp3");
  S11 = loadSound("assets/11SundayMorning.mp3");
  S12 = loadSound("assets/12InspireMe.mp3");
  S13 = loadSound("assets/13Sacrifices.mp3");
  S14 = loadSound("assets/14BiggerThanMe.mp3");
}

function setup() {
  createCanvas(1800, 1391);

}


function draw() {
  background(bg);
  if (mouseIsPressed) {
    playMusic();
  }
  displayCircle();
  if (isPlaying) {
    fill(0);
    noStroke();
    rect(1050, 1195, 100, 100);
    fill(255);
    rect(1050, 1195, 15, 65);
    rect(1090, 1195, 15, 65);
  }

  displayPause();
  analyzeMusic();




}

function displayPause() {
  if ((mouseX > 1050) && (mouseX < 1120) && (mouseY > 1195) && (mouseY < 1260) && (mouseIsPressed) && (isPlaying)) {
    isPlaying = false;
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S1.stop();
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if (keyIsPressed) {
    if (keyCode === 32) {
      isPlaying = false;
      S2.stop();
      S3.stop();
      S4.stop();
      S5.stop();
      S6.stop();
      S7.stop();
      S8.stop();
      S9.stop();
      S10.stop();
      S11.stop();
      S12.stop();
      S13.stop();
      S14.stop();
      S1.stop();
      S1P = false;
      S2P = false;
      S3P = false;
      S4P = false;
      S5P = false;
      S6P = false;
      S7P = false;
      S8P = false;
      S9P = false;
      S10P = false;
      S11P = false;
      S12P = false;
      S13P = false;
      S14P = false;
    }
  }
}




function playMusic() {
  if ((mouseX > 650) && (mouseX < 730) && (mouseY > 760) && (mouseY < 785)) {
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop(); 
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S1.play();
    isPlaying = true;
    S1P = true;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 650) && (mouseX < 730) && (mouseY > 805) && (mouseY < 845)) {
    S1.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S2.play();
    isPlaying = true;
    S1P = false;
    S2P = true;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 650) && (mouseX < 820) && (mouseY > 855) && (mouseY < 880)) {
    S1.stop();
    S2.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S3.play();
    S1P = false;
    S2P = false;
    S3P = true;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 650) && (mouseX < 820) && (mouseY > 900) && (mouseY < 930)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S4.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = true;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 650) && (mouseX < 940) && (mouseY > 945) && (mouseY < 975)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S5.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = true;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 650) && (mouseX < 730) && (mouseY > 995) && (mouseY < 1020)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S6.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = true;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;

  }
  if ((mouseX > 650) && (mouseX < 855) && (mouseY > 1040) && (mouseY < 1065)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S7.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = true;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1250) && (mouseY > 760) && (mouseY < 785)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S8.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = true;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1425) && (mouseY > 805) && (mouseY < 845)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();

    S9.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = true;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1560) && (mouseY > 855) && (mouseY < 880)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S10.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = true;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1425) && (mouseY > 900) && (mouseY < 930)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S12.stop();
    S13.stop();
    S14.stop();
    S11.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = true;
    S12P = false;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1280) && (mouseY > 945) && (mouseY < 975)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S13.stop();
    S14.stop();
    S12.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = true;
    S13P = false;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1270) && (mouseY > 995) && (mouseY < 1020)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S14.stop();
    S13.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = true;
    S14P = false;
  }
  if ((mouseX > 1120) && (mouseX < 1340) && (mouseY > 1040) && (mouseY < 1065)) {
    S1.stop();
    S2.stop();
    S3.stop();
    S4.stop();
    S5.stop();
    S6.stop();
    S7.stop();
    S8.stop();
    S9.stop();
    S10.stop();
    S11.stop();
    S12.stop();
    S13.stop();
    S14.play();
    isPlaying = true;
    S1P = false;
    S2P = false;
    S3P = false;
    S4P = false;
    S5P = false;
    S6P = false;
    S7P = false;
    S8P = false;
    S9P = false;
    S10P = false;
    S11P = false;
    S12P = false;
    S13P = false;
    S14P = true;
  }
}

function displayCircle() {
  fill(20, 22, 228);
  noStroke();
  if ((isPlaying) && (S1P)) {
    ellipse(750, 775, 10);
  }
  if ((isPlaying) && (S2P)) {
    ellipse(750, 820, 10);
  }
  if ((isPlaying) && (S3P)) {
    ellipse(845, 870, 10);
  }
  if ((isPlaying) && (S4P)) {
    ellipse(820, 910, 10);
  }
  if ((isPlaying) && (S5P)) {
    ellipse(950, 960, 10);
  }
  if ((isPlaying) && (S6P)) {
    ellipse(770, 1010, 10);
  }
  if ((isPlaying) && (S7P)) {
    ellipse(870, 1050, 10);
  }
  if ((isPlaying) && (S8P)) {
    ellipse(1270, 775, 10);
  }
  if ((isPlaying) && (S9P)) {
    ellipse(1435, 820, 10);
  }
  if ((isPlaying) && (S10P)) {
    ellipse(1600, 870, 10);
  }
  if ((isPlaying) && (S11P)) {
    ellipse(1440, 915, 10);
  }

  if ((isPlaying) && (S12P)) {
    ellipse(1300, 960, 10);
  }

  if ((isPlaying) && (S13P)) {
    ellipse(1280, 1010, 10);
  }

  if ((isPlaying) && (S14P)) {
    ellipse(1350, 1050, 10);

  }
}


function analyzeMusic() {
  t1 = S1.currentTime() / S1.duration();
  t2 = S2.currentTime() / S2.duration();
  t3 = S3.currentTime() / S3.duration();
  t4 = S4.currentTime() / S4.duration();
  t5 = S5.currentTime() / S5.duration();
  t6 = S6.currentTime() / S6.duration();
  t7 = S7.currentTime() / S7.duration();
  t8 = S8.currentTime() / S8.duration();
  t9 = S9.currentTime() / S9.duration();
  t10 = S10.currentTime() / S10.duration();
  t11 = S11.currentTime() / S11.duration();
  t12 = S12.currentTime() / S12.duration();
  t13 = S13.currentTime() / S13.duration();
  t14 = S14.currentTime() / S14.duration();
  stroke(20, 22, 228);
  strokeWeight(10);


  strokeCap(SQUARE);

  if ((S1P) && (isPlaying)) {

    line(535, 1160, 535 + t1 * 1140, 1160);
  }
  if ((S2P) && (isPlaying)) {
    line(535, 1160, 535 + t2 * 1140, 1160);
  }
  if ((S3P) && (isPlaying)) {
    line(535, 1160, 535 + t3 * 1140, 1160);
  }
  if ((S4P) && (isPlaying)) {
    line(535, 1160, 535 + t4 * 1140, 1160);
  } 
  if ((S5P) && (isPlaying)) {
    line(535, 1160, 535 + t5 * 1140, 1160);
  }

  if ((S6P) && (isPlaying)) {
    line(535, 1160, 535 + t6 * 1140, 1160);
  }
  if ((S7P) && (isPlaying)) {
    line(535, 1160, 535 + t7 * 1140, 1160);
  }
  if ((S8P) && (isPlaying)) {
    line(535, 1160, 535 + t8 * 1140, 1160);
  }
  if ((S9P) && (isPlaying)) {
    line(535, 1160, 535 + t9 * 1140, 1160);
  }
  if ((S10P) && (isPlaying)) {
    line(535, 1160, 535 + t10 * 1140, 1160);
  }
  if ((S11P) && (isPlaying)) {
    line(535, 1160, 535 + t11 * 1140, 1160);
  }
  if ((S12P) && (isPlaying)) {
    line(535, 1160, 535 + t12 * 1140, 1160);
  }
  if ((S13P) && (isPlaying)) {
    line(535, 1160, 535 + t13 * 1140, 1160);
  }
  if ((S14P) && (isPlaying)) {
    line(535, 1160, 535 + t14 * 1440, 1160);
  }

}

function mousePressed() {
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S13P)) {
      
      S13.stop();
      S14.play();
      S13P = false;
      S14P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S12P)) {
      
      S12.stop();
      S13.play();
      S12P = false;
      S13P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S11P)) {
      
      S11.stop();
      S12.play();
      S11P = false;
      S12P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S10P)) {
      
      S10.stop();
      S11.play();
      S10P = false;
      S11P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S9P)) {
      
      S9.stop();
      S10.play();
      S9P = false;
      S10P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S8P)) {
      
      S8.stop();
      S9.play();
      S8P = false;
      S9P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S7P)) {
      
      S7.stop();
      S8.play();
      S7P = false;
      S8P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S6P)) {
      
      S6.stop();
      S7.play();
      S6P = false;
      S7P = true;
 
    
}
  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S5P)) {
      
      S5.stop();
      S6.play();
      S5P = false;
      S6P = true;
 
    
}

  
      if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S4P)) {
      
      S4.stop();
      S5.play();
      S4P = false;
      S5P = true;
 
    
}
  
        if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S3P)) {
      
      S3.stop();
      S4.play();
      S3P = false;
      S4P = true;
 
    
}
    if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S2P)) {
      
      S2.stop();
      S3.play();
      S2P = false;
      S3P = true;
 
    
}
    if ((mouseX > 1150) && (mouseX < 1225) && (mouseY > 1200) && (mouseY < 1255) && (S1P)) {
      S1.stop();
      S2.play();
      S1P = false;
      S2P = true;
      
}
  
  //Backwards
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S2P)) {
   S2.stop();
   S1.play();
   S2P = false;
   S1P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S3P)) {
   S3.stop();
   S2.play();
   S3P = false;
   S2P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S4P)) {
   S4.stop();
   S3.play();
   S4P = false;
   S3P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S5P)) {
   S5.stop();
   S4.play();
   S5P = false;
   S4P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S6P)) {
   S6.stop();
   S5.play();
   S6P = false;
   S5P = true;}
  
    
   if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S7P)) {
   S7.stop();
   S6.play();
   S7P = false;
   S6P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S8P)) {
   S8.stop();
   S7.play();
   S8P = false;
   S7P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S9P)) {
   S9.stop();
   S8.play();
   S9P = false;
   S8P = true;}
  
    
   if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S10P)) {
   S10.stop();
   S9.play();
   S10P = false;
   S9P = true;}
  
  if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S11P)) {
   S11.stop();
   S10.play();
   S11P = false;
   S10P = true;}

     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S12P)) {
   S12.stop();
   S11.play();
   S12P = false;
   S11P = true;}
  
     if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S13P)) {
   S13.stop();
   S12.play();
   S13P = false;
   S12P = true;}

 if ((mouseX > 940) && (mouseX < 1000) && (mouseY > 1200) && (mouseY < 1255) && (S14P)) {
   S14.stop();
   S13.play();
   S14P = false;
   S13P = true;}
  
}
  

