Display the coordinates, heading, and interior ID on the screen

configure with INI file:

```
[mszcoord]
enable = 1 // 1 to enable, 0 to disable

right = 1  // 0 to left-align the text, 1 to right-align the text

coords = 1  // you can choose
heading = 1 // which ones
area = 1    // to display

x = 620.0 // where to place the text, but I don't know exactly how the 'screen' values work
y = 380.0 // below is an example of how I chose these numbers
// take a screenshot of the game and resize it to 640x440 (but the height 
// might be slightly wrong I'm not sure), then put the mouse where you want the 
// top-left or top-right of the text to be (620,380 in my example), 
// then write the left number in X, and the right one in Y. for some reason, 
// the numbers have to be floats, so also put a decimal
// Or you can just set these to 0.0 or remove them and the text will be 
// displayed somewhere, I can't remember at the moment
```

Fun fact: I wrote this script to demonstrate that CJ is moving during the 
credits where the camera slides across the cities. I also did one with the 
camera coordinates, but that one may not be as useful, because you can _see_ 
that the camera moves, so I didn't keep it
