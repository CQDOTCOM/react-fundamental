## React Recap


Don't worry - while there is a lot to see at first, React is a pretty straightforward framework to use. You can create user interface components that extend from `React.Component`. These have a built-in lifecycle that accepts data and can trigger automatic re-rendering whenever that data is updating. In a React Component, an update in either the State or Props will trigger the method cascade that can lead to a `render()`.

#### Best Practices

- Each component should be in a file unto itself. Don't put multiple components into one Javascript file.
- Do not automatically render elements on the DOM *inside* its own component class definition. If you look through your files, you'll see in your component classes, you define a `render()` method for that component, which is great. That class then is called by `ReactDOM.render()` in **a different place, outside that class definition** (likely index.js). In some tutorials or older code, you may find examples of `ReactDOM.render()` inside a component, but you should avoid this at all cost; this was an older technique in past versions of React.
- Remember that `state` represents the _state_ of your user interface component.
- State can trigger changes in `props` or `props` can come from parent components.
- Don't ever let yourself think that State and Props are the same thing. They aren't.

#### Check Yourself: Component Lifecyle

- What method inside of a component is called first?
- Which returns JSX to be displayed?
- When `setState()` is called, what methods are called prior to `render()` being called?

#### Tips for Newbies

- Write code. Use `create-react-app` so you focus on writing React from the get go! Learning Webpack and the tooling for the ecosystem is cool but that is another topic unto itself. Keep that in mind and focus on React.

#### Last thoughts before the project... a video.

<video width="640" height="480" controls="controls" type="video/mp4">
<source src="https://embed-ssl.wistia.com/deliveries/bfae96f54dbe068256aa5f0e5fc44696c7179f57.bin">
Your browser does not support the video tag.
</video>
