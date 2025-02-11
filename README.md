
## D280 – JAVASCRIPT PROGRAMMING
<!-- Welcome to JavaScript Programming! 
For specific task instructions and requirements for this assessment, please refer to the course page. -->

<!-- 
1.   Create a README file that contains the configuration details of the project, including both of the following items student Id and angular version: -->
## Project with student Id AND 
**Student ID**:012251427 
**Angular CLI Version**: 19.0.6  
**Node Version**: 20.14.0  
**Package Manager**: npm 10.8.2  
**Operating System**: darwin arm64  
**Angular Version**: 19.0.6 

 **What the project does**
This project uses the World Bank API to dynamically to fetch and display information about countries by using an SVG. For example, When a user clicks on a country, the id of the clicked path is captured in the getCountryData method and then The id from the clicked country is sent to the API service which fetches detailed information about that country

**How you implemented the requirements**
-Create an HTML layout with two columns 
The SVG map is displayed in one column by using the event binding to make the map interactive
The country information panel is displayed in the other column by using a div element with CSS is a way to create two side-by-side columns

### Routing Configuration
Angular's routing 

- When users visit the root URL local/host4200, they are automatically redirected to /map.
- The /map route renders the main component the app component, which contains the SVG map and displays country data.


### API Integration 
- A service  is implemented to make HTTP requests using Angular's  provideHttpClient() for API calls
- The method (getcountrydata) then accepts a two-letter country code and retrieves detailed information about the selected country when the user clicks on the map



# map
