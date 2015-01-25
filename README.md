# JQPlot Custom Image Renderer

A Custom Image Renderer jqplot plugin graphing library.
Using this plugin, you can plot your own image as a data point. Include the plugin source in your javascript file and enable the jqplot plugins by this code `$.jqplot.config.enablePlugins = true;`

Usage:
In series object, use this:
```javascript
markerRenderer:$.jqplot.ImageMarkerRenderer,
			markerOptions: {
				show:true,
				imageElement:customImg,
				xOffset:-5,
				yOffset:-5				
			}
			
			//custom image object creation:
			var customImg = new Image();
			customImg.src = '<PATH TO IMAGE FILE>';
```

xOffset and yOffset is to align the image horizontally and vertically to the center. Modify these to suit your needs
			
		
