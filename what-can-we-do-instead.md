---
description: Alot
---

# What can we do instead?

### On the Backend Side

* Put as much business logic in your backend.
* Put as much transformation and mapping logic on your backend.
* If possible your could implement [projection](https://jsonapi.org/format/#fetching-sparse-fieldsets) and [selection](https://jsonapi.org/format/#fetching-filtering) in your REST services.

### On the Client Side

* Always start without Redux or any other state management solution.
* Use the [Fetch](https://reactjs.org/docs/faq-ajax.html) API in componentDidMount\(\) or UseEffect\(\) to load you data and hold the state in the component \(Smart Component\).
* Try to use [Component Composition](https://reactjs.org/docs/composition-vs-inheritance.html) to reverse the flow of control if needed.
* You can persist information in the URI, and it will always be the better way, simply because http is stateless.
* You can use Singletons \(HoC‘s\) which are on the Router level or above \(e.g. for Security ProtectedRoutes\).
* You could still use React Context
* You could still use useReducer\(\)

