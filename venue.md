---
layout: page
permalink: /venue/
title: Where are we going ?
modified: 2014-02-20
---

# The schedule

* 15:00 at the city council
* 18:00 at the reception

# The city council

<script type="text/javascript">
    function initialize() {
        // City council map
        var cityCouncilLatlng = new google.maps.LatLng(43.103341, 5.879964);
        var mapCityCouncilOptions = {
            center: cityCouncilLatlng,
            zoom: 16
        };
        var mapCityCouncil = new google.maps.Map(document.getElementById("map-city-council"),
            mapCityCouncilOptions);
        
        // To add the marker to the map, use the 'map' property
        var marker = new google.maps.Marker({
                position: cityCouncilLatlng,
                map: mapCityCouncil,
                title:"Salle des mariages de La Seyne sur mer"
        });

        // Reception Map
        var receptionLatlng = new google.maps.LatLng(43.1890367,6.1277288);
        var receptionMapOptions = {
            center: receptionLatlng,
            zoom: 10
        };
        var receptionMap = new google.maps.Map(document.getElementById("map-reception"),
            receptionMapOptions);
        
        // To add the marker to the map, use the 'map' property
        var receptionMarker = new google.maps.Marker({
                position: receptionLatlng,
                map: receptionMap,
                title:"Magnanerie de Saint Isidore"
        });
    }
google.maps.event.addDomListener(window, 'load', initialize);
</script>

<figure class="half">
  <div id="map-city-council" class="map elem" style="height:0;padding-bottom: 40.25%;"></div>
  <p class="elem"><a href="https://www.google.com/maps/place/43%C2%B006'11.4%22N+5%C2%B052'48.2%22E/@43.103176,5.88007,14z/data=!3m1!4b1!4m2!3m1!1s0x0:0x0"><strong>Salle des mariages de La Seyne sur mer</strong><br />13-15 Rue Ambroise Croizat, 83500 La Seyne-sur-Mer, Francei</a></p> 
  <figcaption></figcaption>
</figure>


# The reception

<figure class="half">
  <div id="map-reception" class="map elem" style="height:0;padding-bottom: 40.25%;"></div>
  <p class="elem"><a href="https://www.google.co.jp/maps/place/La+Magnanerie+de+Saint+Isidore/@43.1890367,6.1277288,17z/data=!3m1!4b1!4m2!3m1!1s0x0:0xac93425c69b72207"><strong>La Magnanerie de Saint Isidore</strong><br />9074 Route de Pierrefeu, 83400 Hyères, France</a></p> 
  <figcaption></figcaption>
</figure>
