# NEXRAD
NEXRAD Weather Radar Widget for CMV.
Inspired by the Iowa State University of Science and Technology - Flex widget https://www.arcgis.com/home/item.html?id=75d3bf48976c44ef986a70e0dcad0f75.
Radar map services:
https://mesonet.agron.iastate.edu/ogc/

Widget configuration:
```
nexred: {
			    include: true,
			    id: 'Nexrad',
			    type: 'titlePane',
			    canFloat: true,
			    position: 16,
			    path: 'gis/dijit/Nexrad',
			    title: 'Nexrad',
			    options: {
			        map: true
	}
},
```

Demo:
![alt tag](https://cloud.githubusercontent.com/assets/8904086/11914624/6bfb2646-a653-11e5-8daa-114621a387ce.PNG)
