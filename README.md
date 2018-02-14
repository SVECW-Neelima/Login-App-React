# Login-App-React


## Steps

 Go to package.json path and type npm install
 npm start to start the server
 Open http://localhost:3000

## Code Flow

Login Component is used to show the login form inside App.js

Used onChange event to trigger state change for username and password

this.setState - it sets/updates the state of  username and password

On submit, getting values from the state of the component as this.state.username

Using fetch to make a POST service call with username and pwd as params to it

Due to CORS issue in the setup , made a mock POST service  url which returns isSuccess as true

Even added code for the POST call with given service url 

## CSS

Added a login container which will be centered to the page and z-index as 1 to overlap the 4 rectangles as shown 

Used transform style to align the container to the center of the page based on the container height and width

Used percentage margins to the 4 rectangles to make it responsive
