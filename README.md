## Elevation profiles of trails in Bryce Canyon National Park

For this 3D map, I interpolated shapefiles of trails with a digital elevation model of the area. I split the trails into each named segment, generated a stack profile for each, and then displayed each elevation profile as a separate chart, as shown in the picture below. I wrote [some code](https://github.com/jbelian/bryce/blob/main/find_min_max.ipynb) in Python that loops through each trail's attribute table and finds the minimum and maximum height of each. Additionally, ran I an EC2 server through Amazon Web Services and deployed the resulting [CSV file](https://github.com/jbelian/bryce/blob/main/trails_min_max_elev.csv) to it.

![Image of a 3D model of trails and terrain in Bryce Canyon, as well as a chart of one trail section's elevation profile](https://user-images.githubusercontent.com/33590262/203166897-d851ec23-004f-490d-8da5-5c7ac47b8673.png)
