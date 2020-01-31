---
description: The creation of Flux
---

# The Notification Bug

One really well known example for Flux was the notification bug.

Many state updates from the client as well as from the server caused the notification counter to be incorrect.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZg7-aVRfctv-NUbESjrQJJDrn_GESCDvHByDpK-XPi_HyQ_Mr_w&s)

The Flux pattern was able to solve this issue with an unidirectional data flow.

![](.gitbook/assets/flux-simple-f8-diagram-1300w.png)

When you have many state updates from all over the application as well as from the server causing a re-render on the same component, the Flux pattern can help to track unwanted state manipulations. It gives you the ability to check who dispatched this action.

The downside of this pattern is it requires a lot of boilerplate code.

A big trade-off for a very special case.

