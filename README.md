# endpoint-explorer

## Eric Tran A11484008 eqtran.edu

### Description of Code
For the styling I used twitter bootstrap. In order to use bootstrap I had to import the jquery script and the bootstrap.min.js files. 
All of the buttons and menu lists use bootstrap for style and implementation. I decided to implement three HTTP request methods: GET, POST, and HEAD. I created a fillable textbox for the Request URL and the Payload to be desired. I do have error checking for the url field that covers most forms of possible urls. For the Preview Request, Header Selection, Response, and Header Response I put them all within a group of navigatable tabs. To create the actual request I used the XMLHTTPRequest object and depending on which request method was chosen I would xhr.open() the corresponding method type along wit the payload to be sent. To get the Response headers I used the getAllResponseHeaders() method. For the response body I used the responseText field in the XMLHttpRequest object. For local storage I used the localStorage api. One problem I had was not being able to populate the url field when a saved request is selected. I was able however to populate the saved requests on window load that contains the URL and corresponsonding "friendly name". When a request is successfully sent I used animations and keyframes to show the toast message. 
