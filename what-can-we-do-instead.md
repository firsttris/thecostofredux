---
description: Build micro frontends instead of monolithic frontends
---

# What can we do instead?

### In General

1. Keep your application clean and simple at all costs.
2. Minimize 3rd party dependencies.
3. Don't create your own soup, stick to the documentation.

### Backend

* Put as much business logic in your backend as possible.
* Put as much transformation and mapping logic in your backend as possible.
* You could implement [projection](https://jsonapi.org/format/#fetching-sparse-fieldsets) in your REST services.

### Client

* Start as simple as possible and go from there... 
  * Always start without Redux or any other state management solution
  * Don't start with any other premature optimization.
* Do your API calls in componentDidMount\(\) or UseEffect\(\) and hold the state in the Component \(Smart Component\).
* Try to use [Component Composition](https://reactjs.org/docs/composition-vs-inheritance.html) to reverse the flow of control.
* You can persist information in the URI, and it will always be the better way, simply because http is stateless.
* For Security you can use [ProtectedRoutes](https://reacttraining.com/react-router/native/example/auth-workflow).

### There is no way around global state

* React Context
* useReducer\(\) hook

