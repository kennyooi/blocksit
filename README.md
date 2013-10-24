blocksit
========

BlocksIt.js is a jQuery plugin for creating dynamic grid layout. It manages to convert HTML elements into 'blocks' and position them in well-arranged grid layout like Pinterest. How? Well, simply specific the number of columns you wish to have and BlocksIt.js will do the rest for you. Also, you can even combine the 'blocks' and make a huge block! 

Demo Page
=========

http://www.inwebson.com/demo/blocksit-js/

How It Works
============

BlocksIt.js will re-position the selected elements using CSS absolute position property. It has the capability to calculate the top and left positions for an element based on certain criteria, like below:

- Start the new block from left to right, and
- Place the new block under shortest block.

Configuration
=============

	.BlocksIt( [Options] )
	
Options
-------

- **numOfCol** - The number of columns to be created. *(Default:5)*
- **offsetX** -	Margin left and right for each block. *(Default:5)*
- **offsetY**	- Margin top and bottom for each block. *(Default:5)*
- **blockElement** - Targeted child element, which will converted into blocks. *(Default:div)*

For more set up and configuration details, do visit http://www.inwebson.com/jquery/blocksit-js-dynamic-grid-layout-jquery-plugin/
