# Code401 Pre-work Deployment Workshop

### Author: Holly Davis

### Links and Resources
* [submission PR](https://github.com/hollydavis-401d3/deployment-workshop/pull/1)
* [travis](https://travis-ci.com/hollydavis-401d3/deployment-workshop/builds/141709610)
* [front-end](https://hollydavis-prework-deployment.herokuapp.com/)

#### Documentation
* [jsdoc](https://hollydavis-prework-deployment.herokuapp.com/docs/)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * placeholder for notes to TAs about tests I haven't written yet

#### UML

![UML Diagram (image from CodeFellows Tutorial)](whiteboard.jpg)
