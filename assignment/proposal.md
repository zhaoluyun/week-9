##Problem / Question
The application can help users find housing in Beijing. Users can get information about available secondhand housing, such as price, nearby school, year of construction, distance to subway station, etc.

##The data
The datasets I plan to use are secondhand housing data and key primary and secondary schools of Beijing. They are now CSV files and can be converted to geojson data.

##Technologies used
I will use underscore, jQuery, turf, leaflet draw, and bootstrap.
Underscore & jQuery: Users can search such as housing within certain price at sidebar and the related housing will be shown on the map. When click a specific point, the information about that housing will be shown at the sidebar.
Turf & Bootstrap: When click the point of school, the surrounded housing will be highlighted and be shown at the sidebar. When click the housing at sidebar, the information will popup as bootstrap modal.
Leaflet draw: Users can draw point or polygon on the map. The housing within the polygon or the housing within certain distance of the point will be shown at sidebar. When click the housing at sidebar, the information will popup as bootstrap modal.

##Design spec
####User experience
The users are the people who want to find housing in Beijing. They can get the information such as price, nearby school, year of construction, distance to subway station of available secondhand housing.
####Layouts and visual design
The application has a sidebar on the left. At the main page, users can search what they want. There are three buttons: “school district housing”, “personal drawing”, and “back to main page”. The “school district housing” button will direct to the page that has schools on the map. (When click the point of school, the surrounded housing will be highlighted and be shown at the sidebar. When click the housing at sidebar, the information will popup as bootstrap modal.) The “personal drawing” button will direct to the page that users can draw points or polygon on the map. (The housing within the polygon or the housing within certain distance of the point will be shown at sidebar. When click the housing at sidebar, the information will popup as bootstrap modal.)
