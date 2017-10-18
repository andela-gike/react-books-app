When a component does not have state there is no need of making the component a class it can be a function

e.g
# As a function it can be
```
const App = () => (
  What ever the function does
  );
```
# When with a state
```
class App extends React.Component {
  state = {}

  render() {
    What should be rendered on the browser
   }
}
```
Redux is used to store state until it is changed
# Redux connect function parameter
 - MapStateToProps is a parameter passed into the connect function to allows us to pass some data from redux state into a component.
 - MapDispatchToProps is a parameter passed into the connect function that allows us to wrap our functions in dispatch, it is put in an object
