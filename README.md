# JavaScript-Mapping-From-URL
Built to take a url with addresses as query strings and create a Google Map with markers

Our company is using a Filemaker Pro database.  Filemaker has a built in web browser that I wanted to utilize to place our daily customer locations on a map. In order to do so I created a script in Filemaker in order to compile all service locations into a URL.  

I built this Javascript program to run locally in order to parse the url into addresses, turn those addresses into Long/Lat and then plot them on a map. Then the script opens the file file:///C:/Users/sean/Downloads/GoogleMap.html?address1="AddressListedHere" and replaces the "AddressListedHere" with the appropriate address.

# Future Plans
This method does not allow me to embed service descriptions as the tag headers. I would also like to color code the markers based on the service description to correspond to what I have on file.
