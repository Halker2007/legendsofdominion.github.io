# halker2007.github.io
This is a game that is made with code.org Gamelab.

I put this game on a website so I can have a website to host the map images

Here is some javascript code of how this works:

-------------------------

var url = "https://halker2007.github.io/legendsofdominion.github.io/mapimages/00.jpg";
var Image = loadImage(url);

// Create a sprite for the image
var Sprite = createSprite(200, 200);
Sprite.addImage(Image);

function draw() {
  background(220);
  
  // Display the sprite
  drawSprites();
  
  // Check if the mouse is pressed over the sprite
  if (mousePressedOver(Sprite)) {
    console.log("it worked");
  }
}

---------------------------

If I got rid of this website, the code would no longer work. 

How it works:

In this game that I am making, it is a turn - based combination of Risk and Age of Empires.
Every turn, the current player gets a number of troops.
Based on where the troops are, (if the troops are on the tiles) part of the map (tiles) will be visible.
So in the begginning of the game, you won't know where you are, and where your oponent is.
You can keep troops in tiles to keep the tiles visible (to know where the oponent is), like the game Risk.
You can build buildings, get resources, ect. like the game Age of Empires.
The goal of the game is to completely eliminate the oponent.
