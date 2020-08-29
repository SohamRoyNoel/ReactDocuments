# ReactDocuments
# `React Component LifeCycle`
![github-small](https://github.com/SohamRoyNoel/ReactDocuments/blob/master/Lifecycle.PNG?raw=true)
# `Why To Use Or How To Use`
### Best Practice
  -- Load Data from API in ```componentDidMount(){}```
  -- ```componentDidUpdate()``` method is used to render new component in any certain changes; Remember setState is mandatory where initial state can be defined in ```constructor``` or simply under ```React.Component``` method <br />
  EX:<br />
  ```
  state = { lat: null, errorMessage: '' };
  ```
  EX:<br />
  ```
  this.setState({ lat: position.coords.latitude }),
  ```
![github-small](https://github.com/SohamRoyNoel/ReactDocuments/blob/master/DescriptionLifeCycle.PNG?raw=true)

### Concatinating A String, inside a className : 
```
<i className={`icon-left massive ${iconName} icon`} />
```
### HOOKS
![github-small](https://github.com/SohamRoyNoel/ReactDocuments/blob/master/Hooks.PNG?raw=true)
