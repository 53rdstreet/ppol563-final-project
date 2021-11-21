## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/53rdstreet/projectpage/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/53rdstreet/projectpage/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

### Folium 

<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_357f6819d1a44b1c857da43709052bb3 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
             <h3 align="center" style="font-size:16px"><b>MSBA HotSpots</b></h3>
             
    
            <div class="folium-map" id="map_357f6819d1a44b1c857da43709052bb3" ></div>
        
    

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>jQuery UI Draggable - Default functionality</title>
  <link rel="stylesheet" href="//code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">

  <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
  <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
  
  <script>
  $( function() {
    $( "#maplegend" ).draggable({
                    start: function (event, ui) {
                        $(this).css({
                            right: "auto",
                            top: "auto",
                            bottom: "auto"
                        });
                    }
                });
});

  </script>
</head>
<body>

 
<div id='maplegend' class='maplegend' 
    style='position: absolute; z-index:9999; border:2px solid grey; background-color:rgba(255, 255, 255, 0.8);
     border-radius:6px; padding: 10px; font-size:17px; left: 30px; bottom: 30px;'>
     
<div class='legend-title'>Legend (draggable)</div>
<div class='legend-scale'>
  <ul class='legend-labels'>
    <li><span style='background:orange;opacity:0.7;'></span>MSBA Fall 2022</li>
    <li><span style='background:blue;opacity:0.7;'></span>MSBA Spring 2022</li>

  </ul>
</div>
</div>
 
</body>
</html>

<style type='text/css'>
  .maplegend .legend-title {
    text-align: left;
    margin-bottom: 5px;
    font-weight: bold;
    font-size: 90%;
    }
  .maplegend .legend-scale ul {
    margin: 0;
    margin-bottom: 5px;
    padding: 0;
    float: left;
    list-style: none;
    }
  .maplegend .legend-scale ul li {
    font-size: 80%;
    list-style: none;
    margin-left: 0;
    line-height: 18px;
    margin-bottom: 2px;
    }
  .maplegend ul.legend-labels li span {
    display: block;
    float: left;
    height: 16px;
    width: 30px;
    margin-right: 5px;
    margin-left: 0;
    border: 1px solid #999;
    }
  .maplegend .legend-source {
    font-size: 80%;
    color: #777;
    clear: both;
    }
  .maplegend a {
    color: #777;
    }
</style>
</body>
<script>    
    
            var map_357f6819d1a44b1c857da43709052bb3 = L.map(
                "map_357f6819d1a44b1c857da43709052bb3",
                {
                    center: [42.3959296, -95.1786655],
                    crs: L.CRS.EPSG3857,
                    zoom: 3,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_f2ac1ae0bb8541318cd5be918784e472 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            map_357f6819d1a44b1c857da43709052bb3.fitBounds(
                [[52.193636, -112.221575], [42.3959296, -71.1786655]],
                {}
            );
        
    
            var circle_marker_9c0f488ac24e479db9b9b337cad4c56a = L.circleMarker(
                [40.6526006, -73.94972109999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_9c0f488ac24e479db9b9b337cad4c56a.bindTooltip(
                `<div>
                     Andrea  Aleman<br>City:Brooklyn<br>State:NY<br>Email:aa2519@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7dd261036f6045a1ac315ddf1d211af0 = L.circleMarker(
                [38.952944200000005, -76.9408647],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_7dd261036f6045a1ac315ddf1d211af0.bindTooltip(
                `<div>
                     Kristina  Amaral-Salas<br>City:Hyattsville<br>State:MD<br>Email:kna23@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d53ed86ec022434e9669215e32ad2561 = L.circleMarker(
                [38.969531599999996, -77.3859479],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_d53ed86ec022434e9669215e32ad2561.bindTooltip(
                `<div>
                     Daniel Dan Behrns<br>City:Herndon<br>State:VA<br>Email:db1507@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7d3e1ae697e242d8adc85762fbb05820 = L.circleMarker(
                [38.896729, -77.29869697995694],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_7d3e1ae697e242d8adc85762fbb05820.bindTooltip(
                `<div>
                     Carly  Bren<br>City:Oakton<br>State:VA<br>Email:clb309@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fdf2805c1bdc4d83a5ad0f636e3b8962 = L.circleMarker(
                [37.779026200000004, -122.41990600000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_fdf2805c1bdc4d83a5ad0f636e3b8962.bindTooltip(
                `<div>
                     Rachel  Burgess<br>City:San Francisco<br>State:CA<br>Email:rmb307@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6eae0ab487e94db09649cef080399592 = L.circleMarker(
                [42.4853125, -83.3771553],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_6eae0ab487e94db09649cef080399592.bindTooltip(
                `<div>
                     Adriana  Cailao<br>City:Farmington Hills<br>State:MI<br>Email:ac2304@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_086059523f0d4d988490a41206f6ac11 = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_086059523f0d4d988490a41206f6ac11.bindTooltip(
                `<div>
                     Aurora Castillo<br>City:washington<br>State:DC<br>Email:ac2039@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1f6a535ae8874ab7836b214d38e32b0b = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1f6a535ae8874ab7836b214d38e32b0b.bindTooltip(
                `<div>
                     Jordan Dantzler<br>City:Washington<br>State:DC<br>Email:jd1965@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_42e8cf8cd18c436dbe1c04fb0d153d23 = L.circleMarker(
                [40.1742759, -75.0437814],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_42e8cf8cd18c436dbe1c04fb0d153d23.bindTooltip(
                `<div>
                     Seth Dennis<br>City:Southampton<br>State:PA<br>Email:swd38@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e25672f656174b61aefa6cb44a82996d = L.circleMarker(
                [40.518681, -78.394736],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e25672f656174b61aefa6cb44a82996d.bindTooltip(
                `<div>
                     James  DeNofrio<br>City:Altoona<br>State:PA<br>Email:jmd427@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4c851579577244e7b01a5ec7dd27a45f = L.circleMarker(
                [43.0481221, -76.1474244],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_4c851579577244e7b01a5ec7dd27a45f.bindTooltip(
                `<div>
                     James  DePaul<br>City:Syracuse<br>State:NY<br>Email:jtd78@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bbcc24891e39459398d40388b57e4aa1 = L.circleMarker(
                [29.7589382, -95.36769740000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_bbcc24891e39459398d40388b57e4aa1.bindTooltip(
                `<div>
                     Larry  Edwards<br>City:Houston<br>State:TX<br>Email:le255@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_8e9286f3368443b79554a54fc8302753 = L.circleMarker(
                [40.6526006, -73.94972109999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_8e9286f3368443b79554a54fc8302753.bindTooltip(
                `<div>
                     James Jay Egger<br>City:Brooklyn<br>State:NY<br>Email:jce60@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_df12d4180f0b4c519771b0fbfddab38a = L.circleMarker(
                [42.3959296, -71.17866550000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_df12d4180f0b4c519771b0fbfddab38a.bindTooltip(
                `<div>
                     Lloyd  Ellison<br>City:Belmont<br>State:MA<br>Email:lme58@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a513cf98db574e098927d97e5c908313 = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a513cf98db574e098927d97e5c908313.bindTooltip(
                `<div>
                     Wenhui  Fang<br>City:Arlington<br>State:VA<br>Email:wf219@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5f471913669b49e0bbc4b3d5f38ada5c = L.circleMarker(
                [38.8788355, -77.40221718011088],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_5f471913669b49e0bbc4b3d5f38ada5c.bindTooltip(
                `<div>
                     Mariam  Fazal<br>City:Chantilly<br>State:VA<br>Email:mf1350@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f5c256e1fcb940829a8923e1a2885c8a = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f5c256e1fcb940829a8923e1a2885c8a.bindTooltip(
                `<div>
                     Xue  Feng<br>City:Arlington<br>State:VA<br>Email:xf74@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_258ed2d7d23e49ff9fbcc874ee61ada1 = L.circleMarker(
                [39.21980050000001, -77.2969909421444],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_258ed2d7d23e49ff9fbcc874ee61ada1.bindTooltip(
                `<div>
                     Sihui Rainie Feng<br>City:Clarksburg<br>State:MD<br>Email:sf985@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b5a65839748846248f5918527f807b62 = L.circleMarker(
                [38.8462236, -77.3063733],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b5a65839748846248f5918527f807b62.bindTooltip(
                `<div>
                     Juancarlos  Figueroa Quintana<br>City:Fairfax<br>State:VA<br>Email:jrf135@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_44205fadd65b4cacb0a0525d0990e5b4 = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_44205fadd65b4cacb0a0525d0990e5b4.bindTooltip(
                `<div>
                     Amber  Fording<br>City:Washington<br>State:DC<br>Email:agf55@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a246bbdd642b4c6cab994f891e78f726 = L.circleMarker(
                [38.99203005, -76.94610290199051],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a246bbdd642b4c6cab994f891e78f726.bindTooltip(
                `<div>
                     Kristoffer Kris Garringer<br>City:College Park<br>State:MD<br>Email:kcg51@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6457287b345f41cfbb982f96a477fd74 = L.circleMarker(
                [39.0180508, -77.1956331355745],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_6457287b345f41cfbb982f96a477fd74.bindTooltip(
                `<div>
                     Maegan  George<br>City:Potomac<br>State:MD<br>Email:mg2041@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d1439d53223641e38becd4e58becb111 = L.circleMarker(
                [38.98127255, -77.12335871396549],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_d1439d53223641e38becd4e58becb111.bindTooltip(
                `<div>
                     Alexander  Gerstenfield<br>City:Bethesda<br>State:MD<br>Email:abg84@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1f0078cbb52741e8a32d4e8ea5a0f250 = L.circleMarker(
                [39.9622601, -83.00070649999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1f0078cbb52741e8a32d4e8ea5a0f250.bindTooltip(
                `<div>
                     Kyle  Gullette<br>City:Columbus<br>State:OH<br>Email:kdg61@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6bace378a4044775bfc130ce50c8b56f = L.circleMarker(
                [37.779026200000004, -122.41990600000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_6bace378a4044775bfc130ce50c8b56f.bindTooltip(
                `<div>
                     GENEVIEVE  HEIDKAMP<br>City:San Francisco<br>State:CA<br>Email:gmh65@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d3365df729404f6d9fd78380fbe49727 = L.circleMarker(
                [37.53850870000001, -77.43428],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_d3365df729404f6d9fd78380fbe49727.bindTooltip(
                `<div>
                     David  Henry<br>City:Richmond<br>State:VA<br>Email:dh1101@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3e6cbe86c88a42b0a759fe4a97d06365 = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_3e6cbe86c88a42b0a759fe4a97d06365.bindTooltip(
                `<div>
                     Lauren Holec<br>City:Washington<br>State:DC<br>Email:lmh168@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_81e4fa2221ea4cf3bbb82fe6bceb3687 = L.circleMarker(
                [35.7803977, -78.63909890000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_81e4fa2221ea4cf3bbb82fe6bceb3687.bindTooltip(
                `<div>
                     Than  Htay<br>City:Raleigh<br>State:NC<br>Email:tth43@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f05d09dcc32a49a08e34d13e44fb74e1 = L.circleMarker(
                [37.3361905, -121.890583],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f05d09dcc32a49a08e34d13e44fb74e1.bindTooltip(
                `<div>
                     Yingyi Huang<br>City:San Jose<br>State:CA<br>Email:yh737@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5155d338dd0640b2944e1fbf8162a42e = L.circleMarker(
                [38.882334, -77.17109140000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_5155d338dd0640b2944e1fbf8162a42e.bindTooltip(
                `<div>
                     Sean  Huie<br>City:Falls Church<br>State:VA<br>Email:seh160@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_cebd36c0a30b42f5990eb615ed3ca82e = L.circleMarker(
                [29.424600199999997, -98.4951405],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_cebd36c0a30b42f5990eb615ed3ca82e.bindTooltip(
                `<div>
                     Johann Idsellis<br>City:San Antonio<br>State:TX<br>Email:ji198@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_19b2cfb534634aa984f3dc3b3f2362bc = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_19b2cfb534634aa984f3dc3b3f2362bc.bindTooltip(
                `<div>
                     Manuel Manny Jean<br>City:Arlington<br>State:VA<br>Email:mj750@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_8a2f2575ecf44b65812909741d6603cc = L.circleMarker(
                [38.9317403, -77.16706245352789],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_8a2f2575ecf44b65812909741d6603cc.bindTooltip(
                `<div>
                     Yusuke Yus Johnson<br>City:McLean<br>State:VA<br>Email:yj249@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_612122cbbeef4e00a6567d3482b95d79 = L.circleMarker(
                [30.323572600000002, -81.6745406],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_612122cbbeef4e00a6567d3482b95d79.bindTooltip(
                `<div>
                     Ruth  Kaplan<br>City:Brooklyn<br>State:FL<br>Email:rok12@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0049ecdf4058475b921b6116cc818bba = L.circleMarker(
                [42.268156899999994, -83.7312291],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_0049ecdf4058475b921b6116cc818bba.bindTooltip(
                `<div>
                     Yunwon Tom Kim<br>City:Ann Arbor<br>State:MI<br>Email:yk698@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e922047f8fb64f8da3121f01171d6bfe = L.circleMarker(
                [41.0573188, -74.1409771],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e922047f8fb64f8da3121f01171d6bfe.bindTooltip(
                `<div>
                     Zachary Zach Klein<br>City:Ramsey<br>State:NJ<br>Email:zek8@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e94ee138c48041bf8eefc87bfc3d273f = L.circleMarker(
                [38.84487, -77.43540260778344],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e94ee138c48041bf8eefc87bfc3d273f.bindTooltip(
                `<div>
                     Lauren  Kwon<br>City:Centreville<br>State:VA<br>Email:lk569@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c06dbe2412c34e80a27c7df66333d6e8 = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_c06dbe2412c34e80a27c7df66333d6e8.bindTooltip(
                `<div>
                     Meghan  McDonald<br>City:Arlington<br>State:VA<br>Email:mm4885@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a7e0ea6beedf4c73ba73fb505c785ece = L.circleMarker(
                [39.00380985, -77.40832792370676],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a7e0ea6beedf4c73ba73fb505c785ece.bindTooltip(
                `<div>
                     Zaib Naveed<br>City:Sterling<br>State:VA<br>Email:zn76@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_23c5fa28456a4a08a36c086ce56f9db9 = L.circleMarker(
                [38.4493315, -78.8688833],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_23c5fa28456a4a08a36c086ce56f9db9.bindTooltip(
                `<div>
                     Hiep  Nguyen<br>City:Harrisonburg<br>State:VA<br>Email:hnn9@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f37ae4abd798401ea50baf3daa995f8e = L.circleMarker(
                [38.7459482, -78.6422377],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f37ae4abd798401ea50baf3daa995f8e.bindTooltip(
                `<div>
                     Matthew Matt Nicoletta<br>City:Mount Jackson<br>State:VA<br>Email:mjn84@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b09edea5ce6c4981a3e9f48a461690f1 = L.circleMarker(
                [39.1399187, -77.1929215],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b09edea5ce6c4981a3e9f48a461690f1.bindTooltip(
                `<div>
                     Yaw  Opoku<br>City:Gaithersburg<br>State:MD<br>Email:yo123@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e51382ca0309438183a62ad0b4656c2c = L.circleMarker(
                [39.1399187, -77.1929215],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e51382ca0309438183a62ad0b4656c2c.bindTooltip(
                `<div>
                     David  Osuch<br>City:Gaithersburg<br>State:MD<br>Email:do318@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e7dce52b4673471fb3383f4901d3f48d = L.circleMarker(
                [39.9348351, -75.0307264],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e7dce52b4673471fb3383f4901d3f48d.bindTooltip(
                `<div>
                     Adrian Ott<br>City:Cherry Hill<br>State:NJ<br>Email:ajo78@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_84024040c81049c6a256eca6ad09275b = L.circleMarker(
                [47.3075369, -122.2301808],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_84024040c81049c6a256eca6ad09275b.bindTooltip(
                `<div>
                     Jackson  Payan<br>City:Auburn<br>State:WA<br>Email:jp1962@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_92093b9a997046b98cb963dfe31fc259 = L.circleMarker(
                [33.9597677, -83.376398],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_92093b9a997046b98cb963dfe31fc259.bindTooltip(
                `<div>
                     Conor  Powell<br>City:Athens<br>State:GA<br>Email:cp1128@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e5dd39e926714140b2e99849cae7a809 = L.circleMarker(
                [40.5382375, -74.39451734508772],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e5dd39e926714140b2e99849cae7a809.bindTooltip(
                `<div>
                     Anirudh Ramesh<br>City:Edison<br>State:NJ<br>Email:asr124@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c21668af1e914df1bb3b7bc95a6bfd62 = L.circleMarker(
                [47.4873895, -117.57576759999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_c21668af1e914df1bb3b7bc95a6bfd62.bindTooltip(
                `<div>
                     Jed Raynes<br>City:Cheney<br>State:WA<br>Email:jrr134@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f79e42a0ecef4222b836281e35d6facb = L.circleMarker(
                [36.032568700000006, -86.7825235],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f79e42a0ecef4222b836281e35d6facb.bindTooltip(
                `<div>
                     Bryson Sadama<br>City:Brentwood<br>State:TN<br>Email:bss84@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4f1303d2a22d483db3c6856b72d0cf6b = L.circleMarker(
                [44.0505054, -123.09505060000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_4f1303d2a22d483db3c6856b72d0cf6b.bindTooltip(
                `<div>
                     Megan  Schaub<br>City:Eugene<br>State:OR<br>Email:mjs530@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e49730eb532d43958b609247e3a91709 = L.circleMarker(
                [38.955696, -77.34188283719988],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e49730eb532d43958b609247e3a91709.bindTooltip(
                `<div>
                     Theodore Ted Skowronski<br>City:Reston<br>State:VA<br>Email:tes102@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_2789ed9eb61340a1a2de235593fe1048 = L.circleMarker(
                [40.7970382, -74.4809868],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_2789ed9eb61340a1a2de235593fe1048.bindTooltip(
                `<div>
                     Karalyn Jeannie Springle<br>City:Morristown<br>State:NJ<br>Email:kjs170@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e3c2a849f70843ef97fb9be3fa16ccd3 = L.circleMarker(
                [40.72676920000001, -73.7415208],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e3c2a849f70843ef97fb9be3fa16ccd3.bindTooltip(
                `<div>
                     Cassi  Sullivan<br>City:Queens Village<br>State:NY<br>Email:cs1665@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_123688dfab1043cfb06aa7a4c530bed3 = L.circleMarker(
                [39.7459468, -75.546589],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_123688dfab1043cfb06aa7a4c530bed3.bindTooltip(
                `<div>
                     Marc  Torchio<br>City:Wilmington<br>State:DE<br>Email:mt1435@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_db20231681ad42fe969616ede6f30898 = L.circleMarker(
                [43.157284999999995, -77.615214],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_db20231681ad42fe969616ede6f30898.bindTooltip(
                `<div>
                     Connor  Upchurch<br>City:Rochester<br>State:NY<br>Email:cju7@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ae0fc22e079b447a98736c5cc60c2b00 = L.circleMarker(
                [33.448436699999995, -112.07414170000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_ae0fc22e079b447a98736c5cc60c2b00.bindTooltip(
                `<div>
                     Peter  Vail<br>City:Phoenix<br>State:AZ<br>Email:prv3@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_22153787121a43828e8635e47dd763be = L.circleMarker(
                [38.029306, -78.4766781],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_22153787121a43828e8635e47dd763be.bindTooltip(
                `<div>
                     Angela  Zhang<br>City:Charlottesville<br>State:VA<br>Email:angela.zhang@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b5734e6405ce499eb6c824df2c5a679f = L.circleMarker(
                [38.8462236, -77.3063733],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b5734e6405ce499eb6c824df2c5a679f.bindTooltip(
                `<div>
                     Xinran Blair Zuo<br>City:Fairfax<br>State:VA<br>Email:xz555@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d01cd073044e43c9935c5e3c31c91719 = L.circleMarker(
                [39.8006685, -75.45964040000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_d01cd073044e43c9935c5e3c31c91719.bindTooltip(
                `<div>
                     Stephen  Algeo<br>City:Claymont<br>State:DE<br>Email:spa46@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ab0ccd8877714bb99261dc02b34b7227 = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_ab0ccd8877714bb99261dc02b34b7227.bindTooltip(
                `<div>
                     Christopher  Antwi<br>City:Arlington<br>State:VA<br>Email:ca896@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1296d6d305cf4c97bf1b96d6edd3d3b4 = L.circleMarker(
                [41.875561600000005, -87.6244212],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1296d6d305cf4c97bf1b96d6edd3d3b4.bindTooltip(
                `<div>
                     Fiona  Baenziger<br>City:Chicago<br>State:IL<br>Email:fb581@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5aced1d4017d412d9c0d4ebe0c2c27c8 = L.circleMarker(
                [35.996653, -78.90180529999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_5aced1d4017d412d9c0d4ebe0c2c27c8.bindTooltip(
                `<div>
                     Breanna  Barton<br>City:Durham<br>State:NC<br>Email:bb1114@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_40debd0ef3d84d1c8d788632c5f26fcd = L.circleMarker(
                [45.5202471, -122.6741949],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_40debd0ef3d84d1c8d788632c5f26fcd.bindTooltip(
                `<div>
                     Aaron  Beverly<br>City:Portland<br>State:OR<br>Email:alb393@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7b263a9d8dea4e2a97208c3dfcfe88fd = L.circleMarker(
                [41.762044700000004, -72.74203990000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_7b263a9d8dea4e2a97208c3dfcfe88fd.bindTooltip(
                `<div>
                     Marialena  Bevilacqua<br>City:West Hartford<br>State:CT<br>Email:mcb271@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a00ea9a7231d4bbcbc12b90e03454868 = L.circleMarker(
                [35.227208600000004, -80.84308270000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a00ea9a7231d4bbcbc12b90e03454868.bindTooltip(
                `<div>
                     Nicholas Nick Boyd<br>City:Charlotte<br>State:NC<br>Email:nb834@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3caa19fa38444fd989528f7c0212607a = L.circleMarker(
                [40.7127281, -74.0060152],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_3caa19fa38444fd989528f7c0212607a.bindTooltip(
                `<div>
                     Megan  Byrnes<br>City:New York<br>State:NY<br>Email:mb2541@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ddaa584cfbe24878b46158b14d52802d = L.circleMarker(
                [40.6526006, -73.94972109999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_ddaa584cfbe24878b46158b14d52802d.bindTooltip(
                `<div>
                     Samia  Cabezas<br>City:Brooklyn<br>State:NY<br>Email:sc2044@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4454b106a4d64305ba88dfb0cf0bb9bf = L.circleMarker(
                [42.599813899999994, -71.3672838],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_4454b106a4d64305ba88dfb0cf0bb9bf.bindTooltip(
                `<div>
                     Andrew Drew Carbone<br>City:Chelmsford<br>State:MA<br>Email:amc470@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f97abc247c254ef0943d2a9561219801 = L.circleMarker(
                [39.1938429, -76.86460919353361],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f97abc247c254ef0943d2a9561219801.bindTooltip(
                `<div>
                     Xiangqian Carter Che<br>City:Columbia<br>State:MD<br>Email:xc192@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_07904e378f254b1a9529417d287f8906 = L.circleMarker(
                [40.6526006, -73.94972109999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_07904e378f254b1a9529417d287f8906.bindTooltip(
                `<div>
                     Chloe  Clements<br>City:Brooklyn<br>State:NY<br>Email:cvc29@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bbcaa24af13744719b99f26dc594d6fe = L.circleMarker(
                [39.9527237, -75.16352619999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_bbcaa24af13744719b99f26dc594d6fe.bindTooltip(
                `<div>
                     Pranathi  Divi<br>City:Philadelphia<br>State:PA<br>Email:PD695@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f29579f06c6e49018c570ab628825158 = L.circleMarker(
                [29.7589382, -95.36769740000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_f29579f06c6e49018c570ab628825158.bindTooltip(
                `<div>
                     Brendan  Griffin<br>City:Houston<br>State:TX<br>Email:bgg4@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b2f1b2402cd14c09b062f6f08028b268 = L.circleMarker(
                [40.019833500000004, -75.30462990000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b2f1b2402cd14c09b062f6f08028b268.bindTooltip(
                `<div>
                     Nicholas Nick Gutierrez<br>City:Bryn Mawr<br>State:PA<br>Email:ng668@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0b65166a51474517aa09e81c36c21479 = L.circleMarker(
                [33.4942189, -111.92601840000002],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_0b65166a51474517aa09e81c36c21479.bindTooltip(
                `<div>
                     Chet  Hammer<br>City:Scottsdale<br>State:AZ<br>Email:cdh106@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fa6033d3aa7748d4b10cc1facf012b87 = L.circleMarker(
                [36.16227670000001, -86.7742984],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_fa6033d3aa7748d4b10cc1facf012b87.bindTooltip(
                `<div>
                     Benjamin Ben Hammons<br>City:Nashville<br>State:TN<br>Email:bch60@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c23bf8f835284411ae9b6231e21d5407 = L.circleMarker(
                [38.8051095, -77.0470229],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_c23bf8f835284411ae9b6231e21d5407.bindTooltip(
                `<div>
                     William Will Sam<br>City:Alexandria<br>State:VA<br>Email:wmh45@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_97f115dff4ed4840ba61219e3b93eb5a = L.circleMarker(
                [38.029306, -78.4766781],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_97f115dff4ed4840ba61219e3b93eb5a.bindTooltip(
                `<div>
                     Danielle Dani Herzberg<br>City:Charlottesville<br>State:VA<br>Email:dh1087@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0e6c9deaf9704963b951b0f647548b29 = L.circleMarker(
                [40.7127281, -74.0060152],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_0e6c9deaf9704963b951b0f647548b29.bindTooltip(
                `<div>
                     Jacqueline Jackie Hiner<br>City:New York<br>State:NY<br>Email:jeh320@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4d93692c76404803875534971aee0f2d = L.circleMarker(
                [32.845786499999996, -97.0667142473263],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_4d93692c76404803875534971aee0f2d.bindTooltip(
                `<div>
                     Samuel  Idakwo<br>City:Euless<br>State:TX<br>Email:si375@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_350f1809f61c4c738d9566111a4ec899 = L.circleMarker(
                [39.2908816, -76.610759],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_350f1809f61c4c738d9566111a4ec899.bindTooltip(
                `<div>
                     Zachary Zach Kaplove<br>City:Baltimore<br>State:MD<br>Email:zlk3@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e6a791eeb0b649e59b2d313a62da195a = L.circleMarker(
                [40.5462553, -74.46604079999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e6a791eeb0b649e59b2d313a62da195a.bindTooltip(
                `<div>
                     Nicole Kuker<br>City:Piscataway<br>State:NJ<br>Email:nk845@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fc44134ef8c7412fa13ea2769e72e13c = L.circleMarker(
                [39.9622601, -83.00070649999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_fc44134ef8c7412fa13ea2769e72e13c.bindTooltip(
                `<div>
                     Anthony  Long<br>City:Columbus<br>State:OH<br>Email:asl93@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0850581165324a9f84ebfa877b9e33e4 = L.circleMarker(
                [38.999762100000005, -77.02403709829767],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_0850581165324a9f84ebfa877b9e33e4.bindTooltip(
                `<div>
                     Samuel Sam Lopez<br>City:Silver Spring<br>State:MD<br>Email:SL1200@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a798c9ee67e54d82849138163987f924 = L.circleMarker(
                [40.7215682, -74.047455],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a798c9ee67e54d82849138163987f924.bindTooltip(
                `<div>
                     Daria  Lorenzo<br>City:Jersey City<br>State:NJ<br>Email:dl1116@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_78386251120443cab23994d945600cc2 = L.circleMarker(
                [40.0992294, -83.11407709999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_78386251120443cab23994d945600cc2.bindTooltip(
                `<div>
                     Connor  Loughead<br>City:Dublin<br>State:OH<br>Email:crl89@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ef525756e1be4584b5d956859d55e25b = L.circleMarker(
                [39.38685220000001, -76.55086176363942],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_ef525756e1be4584b5d956859d55e25b.bindTooltip(
                `<div>
                     Parker  Main<br>City:Parkville<br>State:MD<br>Email:pm1170@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a19bcb40c70f422bb336053019801901 = L.circleMarker(
                [40.7287274, -73.21360733221161],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a19bcb40c70f422bb336053019801901.bindTooltip(
                `<div>
                     Bryce  Nevola<br>City:Islip<br>State:NY<br>Email:bgn8@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e372675fdb7f460396e18a71546fdc03 = L.circleMarker(
                [42.3602534, -71.0582912],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_e372675fdb7f460396e18a71546fdc03.bindTooltip(
                `<div>
                     Olivia Liv Ng<br>City:Boston<br>State:MA<br>Email:okn5@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ba953fc5582f453a9cc8a0c044271f29 = L.circleMarker(
                [38.449015100000004, -77.65526700000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_ba953fc5582f453a9cc8a0c044271f29.bindTooltip(
                `<div>
                     Martin  Ngoh<br>City:Goldvein<br>State:VA<br>Email:mn884@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_43b771795b234fe882a07812bf9d6cac = L.circleMarker(
                [33.6469261, -117.6859213],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_43b771795b234fe882a07812bf9d6cac.bindTooltip(
                `<div>
                     Oliver  Pan<br>City:Lake Forest<br>State:CA<br>Email:oyp3@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_02cb02af57bf49b6a029bb0626e408c7 = L.circleMarker(
                [43.18345789999999, -89.21343590000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_02cb02af57bf49b6a029bb0626e408c7.bindTooltip(
                `<div>
                     Amanda  Parker<br>City:Sun Prairie<br>State:WI<br>Email:ap1751@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1df194f1c01e443a967beb4e6edbf582 = L.circleMarker(
                [29.6196787, -95.6349463],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1df194f1c01e443a967beb4e6edbf582.bindTooltip(
                `<div>
                     Karan Patel<br>City:Sugar Land<br>State:TX<br>Email:kp766@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_31e26e524de6419cae80a955a686aebb = L.circleMarker(
                [39.7940026, -75.1721232],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_31e26e524de6419cae80a955a686aebb.bindTooltip(
                `<div>
                     Haley  Petrarca<br>City:Mantua<br>State:NJ<br>Email:
hap52@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a31e72ecf50346d08beb14b0d1c4ecf5 = L.circleMarker(
                [19.4326296, -99.1331785],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_a31e72ecf50346d08beb14b0d1c4ecf5.bindTooltip(
                `<div>
                     Marcela Rivero Perkins<br>City:Mexico City<br>State:Mexico<br>Email:mr1723@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_53e4d850457c4cb9b19f2740d8100b35 = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_53e4d850457c4cb9b19f2740d8100b35.bindTooltip(
                `<div>
                     Luke  Robb<br>City:Washington<br>State:DC<br>Email:lwr17@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b5906f49137a4994bb35f7bab5feb0ce = L.circleMarker(
                [42.67774685000001, -71.00127464149776],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b5906f49137a4994bb35f7bab5feb0ce.bindTooltip(
                `<div>
                     Nicholas Nick Schena<br>City:Boxford<br>State:MA<br>Email:ns1266@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_134f2e39c2dd49089bea9d2e8ea436dd = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_134f2e39c2dd49089bea9d2e8ea436dd.bindTooltip(
                `<div>
                     Austin  Schwoegl<br>City:Washington<br>State:DC<br>Email:as4731@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1083122b66b64a5ebd51a6c492812a6d = L.circleMarker(
                [33.942215000000004, -118.1235646],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1083122b66b64a5ebd51a6c492812a6d.bindTooltip(
                `<div>
                     Yoon Jae Jason Shin<br>City:Downey<br>State:CA<br>Email:ys864@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_16d682d822a54d11912673f210216785 = L.circleMarker(
                [32.0809263, -81.09117679999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_16d682d822a54d11912673f210216785.bindTooltip(
                `<div>
                     Peter  Shoemaker<br>City:Savannah<br>State:GA<br>Email:ps1233@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3ae88b98c9ac47538101710119c39c35 = L.circleMarker(
                [38.89503679999999, -77.0365427],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_3ae88b98c9ac47538101710119c39c35.bindTooltip(
                `<div>
                     Amelia Simpson<br>City:Washington<br>State:DC<br>Email:als413@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4c8abb2968c94e029414342fcbb2ba5c = L.circleMarker(
                [33.7489924, -84.3902644],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_4c8abb2968c94e029414342fcbb2ba5c.bindTooltip(
                `<div>
                     Charles Alec Snipes<br>City:Atlanta<br>State:GA<br>Email:cas494@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b048d4a7b8614bbfbed9ed7de3f79155 = L.circleMarker(
                [29.5639758, -95.28642990000002],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_b048d4a7b8614bbfbed9ed7de3f79155.bindTooltip(
                `<div>
                     Emily  Strohm<br>City:Pearland<br>State:TX<br>Email:els118@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5ada354363d647e19fcca43ab9eb7848 = L.circleMarker(
                [35.227208600000004, -80.84308270000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_5ada354363d647e19fcca43ab9eb7848.bindTooltip(
                `<div>
                     Ryan  Taylor<br>City:Charlotte<br>State:NC<br>Email:rkt34@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1651116f4edf40f3b341283e483edb8c = L.circleMarker(
                [38.890396100000004, -77.0841585],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_1651116f4edf40f3b341283e483edb8c.bindTooltip(
                `<div>
                     Carl  Thomas<br>City:Arlington<br>State:VA<br>Email:cat94@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d779b2530b98451e86d19e3e4ccdc93c = L.circleMarker(
                [18.4801972, -69.942111],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_d779b2530b98451e86d19e3e4ccdc93c.bindTooltip(
                `<div>
                     Rosa  Villabrille Coss<br>City:Santo Domingo<br>State:Dominican Republic<br>Email:rnv7@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_519b03456d70454fade1d9c010022020 = L.circleMarker(
                [26.3586885, -80.08309840000001],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_519b03456d70454fade1d9c010022020.bindTooltip(
                `<div>
                     Pedro  Voyer<br>City:Boca Raton<br>State:FL<br>Email:plv13@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_648c32aab884458ab2b8c88757a865c7 = L.circleMarker(
                [40.7492678, -73.64068449999999],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_648c32aab884458ab2b8c88757a865c7.bindTooltip(
                `<div>
                     Yohanes  Wahyudi<br>City:Mineola<br>State:NY<br>Email:yw806@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bed9960034b6452eb92e92698902f277 = L.circleMarker(
                [25.72149, -80.2683838],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_bed9960034b6452eb92e92698902f277.bindTooltip(
                `<div>
                     Mitchell  Weiser<br>City:Coral Gables<br>State:FL<br>Email:mw1292@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_56d5472e46884ba9b869b113bdca62ec = L.circleMarker(
                [40.3909023, -79.8100473],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_56d5472e46884ba9b869b113bdca62ec.bindTooltip(
                `<div>
                     Ahmad  Wilson<br>City:Wilmerding<br>State:PA<br>Email:asw99@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_2938c7bc3e9a4dc794e060be9289f80d = L.circleMarker(
                [38.9317403, -77.16706245352789],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_2938c7bc3e9a4dc794e060be9289f80d.bindTooltip(
                `<div>
                     Andrew  Yang<br>City:McLean<br>State:VA<br>Email:aly21@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_696937f5e89b44b9a5dae36b8d694878 = L.circleMarker(
                [38.969531599999996, -77.3859479],
                {"bubblingMouseEvents": true, "color": "white", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_357f6819d1a44b1c857da43709052bb3);
        
    
            circle_marker_696937f5e89b44b9a5dae36b8d694878.bindTooltip(
                `<div>
                     Reyisha  Yiliyasi<br>City:Herndon<br>State:VA<br>Email:ry197@georgetown.edu
                 </div>`,
                {"sticky": true}
            );
        
    
            map_357f6819d1a44b1c857da43709052bb3.fitBounds(
                [[18.4801972, -123.09505060000001], [47.4873895, -69.942111]],
                {}
            );
        
</script>
