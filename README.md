# bresenham-logisim
Implementation of Bresenham's line algorithm using logisim

## Requirements
* [Logisim](http://www.cburch.com/logisim/index.html) (known to work on 2.7.1)

## Files
* `skeleton.circ`: skeleton code provided before Project 1
* `bresenham.circ`: implement Bresenham's line drawing algorithm

## Usage
1. Open `bresenham.circ` with Logisim. 
2. Set "Simulate -> Tick Frequency" (128 Hz or higher recommended). 
3. Select "Simulate -> Ticks Enabled" (Ctrl-K). 
4. Select the hand shaped tool ("Change values within circuit", Ctrl-1). 
5. Modify the values of x1, y1, x2, y2 in circuit. 
6. The LED Matrix on the screen should change in respond to the changes, by
	drawing a line from (x1, y1) to (x2, y2) using the Bresenham's line
	algorithm. 

## Lisence
* This project is published under GNU AFFERO GENERAL PUBLIC LICENSE Version 3.

## Demo
![](demo.gif)

