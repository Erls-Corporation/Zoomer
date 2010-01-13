Zoomer
=====
Zoomer is simple and nice image zoom class. It's shows zoomed image inside original.

![Screenshot](http://mifjs.net/assets/images/queen.jpg)

How to use
----------
Example 1:
html:
	<img src="gomer-small.jpg" id="homer" big="gomer.jpg"/>
js:
	new Zoomer('homer');
	
big attribute - big image src.

Example 2:
html:
	<img src="girl-thumb.jpg" id="girl"/>
js:
	new Zoomer('girl', {
		big: 'girl.jpg',
		smooth: 10
	});
	
options:
- *big* - big image src
- *smooth*(integer) - smooth 