# locationdemo

**Purpose:**

This is a demo single page application for Webster University Web Engineer position demonstration.

**Requirement:**
1. Query the location by ip/domain.
2. Display the location in the map.

**Implementation**
1. Applied the account on the ipify website to get the API key and get familiar with the API spec. 
   The url is: https://geo.ipify.org/docs
2. Use the leafletjs to create map view.   
3. Created the html elements to diplay the title, label, button and map.
4. The demo will query the current user's ip and then display the address on the map when the page is loading. 
5. The ip/domain's detail info display in the popup of the map.
6. Use ajax to send the query request to ipify server to query the ip/domain location information.
7. This Application will check the user's input. The program will invoke the API by passing the ip paramter if the user's input is a valid IP format, otherwise it will invoke the API by passing the domain paramter.
8. The search button text will become to "Searching..." and disabled after user pressed the search to indicates the searching is ongoing.
9. The search button will return to normal after the ajax return the query result.

