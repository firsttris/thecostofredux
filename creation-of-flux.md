---
description: Web development was okay till the notification bug
---

# Notification bug and the creation of Flux

One really well known example for Flux was the notification bug.

Many state updates from the client as well as from the server caused the notification counter to be incorrect for a long time...

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZg7-aVRfctv-NUbESjrQJJDrn_GESCDvHByDpK-XPi_HyQ_Mr_w&s)

The Flux pattern solved this issue with its unidirectional data flow

![](.gitbook/assets/flux-simple-f8-diagram-1300w.png)

The downside of this pattern was it required a lot of boilerplate code.

But remember, this was a very special case

And everything comes at a price

