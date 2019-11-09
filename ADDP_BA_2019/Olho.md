# Planet

## How to creat a Planet
    
``` python
 
 
def setup():
    size(500, 500) # tamanho da área de desenho
    olho(200, 200, 50, color(255, 0, 0))
    olho(100, 100, 200, color(0, 200, 0))
    
def draw():
    rotateY(radians(frameCount*2))
    olho(mouseX, mouseY, 100, color(random(255),
                                    random(158),
                                    random(200)))
    
def olho(x, y, largura, cor):
    noStroke()
    fill(255)
    ellipse(x, y, largura, largura / 8)
    fill(cor)
    circle(x, y, largura / 10)
    fill(98)
    circle(x, y, largura / 2)
    
     ``` 


