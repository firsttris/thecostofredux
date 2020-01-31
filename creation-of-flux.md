---
description: Web development was okay till the notification bug was introduced
---

# Notification bug and the creation of Flux

One really well known example for Flux was the notification bug.

Many state updates from the client as well as from the server caused the notification counter to be incorrect.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZg7-aVRfctv-NUbESjrQJJDrn_GESCDvHByDpK-XPi_HyQ_Mr_w&s)

The Flux pattern was able to solved this issue with an unidirectional data flow

![](.gitbook/assets/flux-simple-f8-diagram-1300w.png)

When you have many state updates from all over the application as well as from the server causing a re-render on the same component, the flux pattern can help track unwanted state manipulations. It gives you the ability to check who was the one who dispatched this action. Assuming the correct action was dispatched.

The downside of this pattern is it requires a lot of boilerplate code.

A big trade-off for a very special case.

