# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > where you can implement custom logic that initializes your application
  and sets up the FVC

02. What is the difference between a vue `component` and `page`?

  > pages are what opens when you go to a specific route. Components are used when you want to reuse code in several places.

  pages are the parent, components are the child!

03. What is ***Component-Based Architecture***?

  > a framework for building software based on reusable components

04. What are the three tags that make up a Vue component?

  > template, styles, and javascript

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > allow you to know when your component is created, added to the DOM, updated, or destroyed. makes certain things have a certain time before actions are rendered.

06. Which component in Vue does the vue-router use to mount pages onto?

  > mounted() or router-link

07. What is the difference between the `AppState` and the state object within a component?

  > appstate is global, while state object is local

08. What is the responsibility of `Services` in our Vue projects?

  > to create a JavaScript file that will export something for you to use in your application

09. What are ***props*** and how are they used? Provide an example

  > passing data from the parent component, to it's child.

  export default {
  props: {
    carProp: {type: Car, required: true}

NOW GO TO CARSPAGE - (TO PASS DOWN THE DATA)

<CarCard :carProp="car"/>


10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > computed() or created?
