---
description: The creation of Flux
---

# The Notification Bug

One really well known example for Flux was the notification bug.

Many updates from the client as well as from the server caused the notification counter to be incorrect.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZg7-aVRfctv-NUbESjrQJJDrn_GESCDvHByDpK-XPi_HyQ_Mr_w&s)

The Flux pattern was able to solve this issue with an unidirectional data flow.

![](.gitbook/assets/flux-simple-f8-diagram-1300w.png)

If there are many state updates for the same component from all over the application, the Flux pattern helps to track unwanted state manipulations. It gives you the ability to trace who dispatched the state change.

This approach requires a lot of boilerplate code which is considered as a big trade-off.

