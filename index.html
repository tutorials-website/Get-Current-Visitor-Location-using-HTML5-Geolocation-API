<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
    </head>
<body>

<p>Click the button to get your coordinates.</p>

<button onclick="getLocation()">Get My Location</button>

<p id="demo"></p>
<h3>Your Current Location:</h3>
<p id="location"></p>
<p id="mapurl"></p>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
 
<script>
var x = document.getElementById("demo");

function getLocation() {
     x.innerHTML = "Please Wait.. We are loading your location";
  if (navigator.geolocation) {
    navigator.geolocation.watchPosition(showPosition);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}
    
function showPosition(position) {
    x.innerHTML="Latitude: " + position.coords.latitude + 
    "<br>Longitude: " + position.coords.longitude;
	
	jQuery.ajax({
                    type:'POST',
                    url:'geocoordinates.php',
                    data:'lat='+position.coords.latitude+'&lng='+position.coords.longitude,
                    success:function(address){
                        if(address){
                            var encodedUrl = encodeURIComponent(address);
                          	jQuery("#location").html(address);
                          		jQuery("#mapurl").html('<a href="http://maps.google.com/maps?z=12&t=m&q=loc:'+encodedUrl+'">Map Url</a>');
                        }else{
                            	jQuery("#location").html('Not Available');
                        }
                    }
                });
	
}
</script>

</body>
</html>
