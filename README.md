![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Remote API

### Author: Brent Woodward

### Links and Resources

* [Assignment](https://codesandbox.io/s/pymmznnoy7)


### Modules

#### `Assignment`
###### `index.js`
Renders app.js to the DOM, and wraps/serves app with Provider (giving it access to Store)
###### `app.js`
Renders Components, handles local state, and exicutes actions based on interaction
###### `store/index.js`
Defines reducer using Combined Reducer and creates/exports store
###### `store/players-actions.js`
Exports actions for player route behavior
###### `store/people-reducer.js`
Defines reducer functions when action dispatched from app to get all people from swapi.
###### `store/person-reducer.js`
Defines reducer functions when action dispatched from app to get a single person from swapi.
###### `Player.js`
Component that renders content provided by state and gives interactable components to users.


#### UML
Link to an image of the UML for your application and response to events