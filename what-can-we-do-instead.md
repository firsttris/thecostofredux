---
description: Build micro frontends instead of monolithic frontends
---

# What can we do instead?

### On the Backend Side

* Put as much business logic in your backend as possible.
* Put as much transformation and mapping logic in your backend as possible.
* You could implement [projection](https://jsonapi.org/format/#fetching-sparse-fieldsets) in your REST services.

### On the Client Side

* Always start without Redux or any other state management solution.
* Create one class which contains your API calls.
* Do your API calls in componentDidMount\(\) or UseEffect\(\) and hold the state in the component \(Smart Component\).
* Try to use [Component Composition](https://reactjs.org/docs/composition-vs-inheritance.html) to reverse the flow of control whenever needed.
* You can persist information in the URI, and it will always be the better way, simply because http is stateless.
* For Security you can use [ProtectedRoutes](https://reacttraining.com/react-router/native/example/auth-workflow).



And if there really is no way around it you could still use

* React Context
* useReducer\(\) hook

