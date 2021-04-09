# Create your map geojson html5
 - How to use leaflet js to create map
 - Map of world countries vectors created from GeoJSON objects
 
        var map = L.map('map').setView([31.74739, 31], 2);
        var statesStyle = {


                //"stroke": true,
                //"fill": true,
                "radius": 8,
                "fillColor": "#0078A8",
                "color": "#0078A8",
                "weight": 1,
                "opacity": 1,
                "fillOpacity": 1
            };
        L.geoJSON(states, {
                style: nilesStyle
            }).addTo(map);



# Extending Leaflet: Multi Layers  (lakes and rivers lake)
        L.geoJSON(niles, {
                style: myStyle
            }).addTo(map);


            L.geoJSON(lakes, {
                style: myStyle
            }).addTo(map);

# Tutorial Quick Start Guide
 - Markers With Custom Icons and Label
               
       L.marker([31.2, 31.2], { icon: new icon({ labelText: "marker 1" }), description: "Description 1" }).addTo(map).on('click', click);

 - Rotated Marker Label
       
        L.marker([24.452, 36.784], {
            icon: new icon_19s({ labelText: " Red Sea" }), rotationAngle: 60
        }).addTo(map);

# OpenPopup
 - Button Click
       
       L.marker([31.2, 31.2]).addTo(map)
       .bindPopup('Description 1')
        .openPopup();
  
 
# Zoom levels
 - Button zooom in
       
       function zooomin() 
                 {
        map.setZoom(map.getZoom() + 1)
                }
                
 - Button zooom Out
  
       function zooomout() {
                    map.setZoom(map.getZoom() - 1)
                }      
                
 - With marker click

       function zooomd() {
                    map.setView([26.47, 30.784], 7);
                }
##  Web Augmented reality
Https://Webxr.edafait.com

##  Free Short URL (Shortner) 
https://shorturl.edafait.com/

##  Blog
Https://blog.edafait.com

## Good Company hosting and low price VPN 
https://shorturl.edafait.com/?hosting 


## YouTube Channel Wonder developer To Subscribe 
https://shorturl.edafait.com/?Subscribe
