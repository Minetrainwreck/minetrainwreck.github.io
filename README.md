# minetrainwreck.github.io
game thing 
var y1= 200;
var y2=200;
var snowmanleft = ellipse(50,y1,50,50);
var snowmanright = ellipse(350,y2,50,50);
var draw = function() {
    background(255, 255, 255);
    
    if (key.toString() === 'w') {
            y1--;
    } else
    {snowmanleft=ellipse(50,y1,50,50); ellipse(50,y1,25,25);
    }
    if (key.toString() === 's') {
            y1++;
    } else
    {snowmanleft=ellipse(50,y1,50,50);ellipse(50,y1,25,25);
    }
    if (keyIsPressed && keyCode === UP) {
            y2--;
    } else
    {snowmanright=ellipse(350,y2,50,50); ellipse(350,y2,25,25);
    }
    if (keyIsPressed && keyCode === DOWN)
    {
        y2++; 
    {
            y2++;
    }
    {snowmanright=ellipse(350,y2,50,50);ellipse(350,y2,25,25);
}

}

};
