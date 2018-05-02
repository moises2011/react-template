# persistent-react-template


```
- scenes/
  -- Dashboard/
    --- index.js
    --- components/
      ---- someComponent.js
  -- About/
    --- index.js
    --- components/
      --- someOtherComponent.js
```   

```
  import { Route, Router } from "react-router";
  import createBrowserHistory from "history/createBrowserHistory";
  
  export const history = createBrowserHistory();
```
 
```
<Router history={history}>
  <div>
    <Route exact path="/home" component={Home} />
    <Route exact path="/about" component={About} />
  </div>
</Router>
```

 
 
 
