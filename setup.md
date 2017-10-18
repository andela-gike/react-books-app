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
