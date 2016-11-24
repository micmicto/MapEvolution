## My question on StackExchange!

I'm making a map [(you can see here)](https://micmicto.github.io/mapplugins)  with different markers and layers to group these markers. I added polygons in another layer (Poligono layer), and I want to know if exist a way to add different information on each polygons that after can be show on a popup. 

I can add different information on each marker using this

    		L.marker ([21.017697, -89.641353], {icon:hospitalIcon}).bindPopup('Info info info').addTo(hospitales),

Exist a way to add information for each polygon using something like .bindPopup for the polygons I am using?

    L.polygon ([
			[20.6894, -88.2017],
			[20.572997, -88.730264],
			[20.3457, -88.1677], 
		]).addTo(polygon),

Something like the image. When you click, show information, I need to show different information for each polygon.

![](https://micmicto.github.io/mapplugins/icons/PolygonPopupExample.png)

Thanks! :D and you can see [the complete code](https://github.com/micmicto/mapplugins)
