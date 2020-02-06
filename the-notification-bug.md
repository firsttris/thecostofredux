---
description: The Notification Bug
---

# How did we get Redux

One really well known example for Flux was the notification bug.

Countless updates from the client as well as from the server caused the notification counter to be always incorrect.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZg7-aVRfctv-NUbESjrQJJDrn_GESCDvHByDpK-XPi_HyQ_Mr_w&s)

The Flux pattern was able to solve this issue with an one way data flow.

For a state change you have to dispatch an action which updates the global store that re-renders the corresponding view.

![](.gitbook/assets/flux-simple-f8-diagram-1300w.png)

It sounds rather complex, but if there are many state updates for the same component from all over the application, the Flux pattern helps to keep track of state manipulations. It also has the advantage that you don't have to pass props down the component tree. It's a dearly bought advantage that requires a lot of boilerplate code.

Redux is a implementation of the Flux API. [Dan Abramov](https://github.com/gaearon) created Redux to cut some complexity and to enable [hot module replacement](https://webpack.js.org/concepts/hot-module-replacement/) and [time-travel](https://medium.com/the-web-tub/time-travel-in-react-redux-apps-using-the-redux-devtools-5e94eba5e7c0).



