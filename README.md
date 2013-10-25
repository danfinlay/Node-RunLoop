#RunLoop

A Node.js module for easily using RequestAnimationFrame cross-browser.  Based on a snippet of code from a Stack Overflow post I read which has served me well.

Wraps all cross-browser touching of requestAnimationFrame() or cancelAnimationFrame() into these two simple methods:

##draw()

For example:

		var runLoop = require('runLoop');

		runLoop.draw(function(){
		    //Draw some stuff here.
		})

##stop()

For example:

		//To stop the loop from running:
		runLoop.stop();

Created for Andy Leeper's WiiU presentation at JS.Everywhere by Dan Finlay while working at MochaLeaf Inc.