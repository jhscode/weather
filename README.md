This is a 5 day Weather App using React and Redux using the openweather api.

This was my attempt at making a Weather app using Redux. Also, insteading of using react-create-app, I used a boilerplate to give me a different perspective in development. 

My Lessons Learned:
1. Redux is the application state, not the component state. React is the views. Redux separates state away from React.
2. Componenets are upgraded to Containers
3. Containers is where you connect redux and react.
4. Reducers hold the piece of the application state and are combined to one object (the application state)
5. Action and action creators are functions that pass along data. Action creator returns and action and it's primarily made of    an action and a payload.

To do:
1. Add react-google-maps to show where the city is located
