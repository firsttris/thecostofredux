---
description: No it's not!
---

# Is Redux best practice?

## Seriously! Most apps are perfectly fine without Redux

Think about it, all this affort for a stateless protocol? If the user switches a route or reloads its browser everything is gone anyway. Means the only reliable way share information is in the URI. Because probably you need that some Id to fetch the data from the server.

![](.gitbook/assets/image%20%287%29.png)

One route is generally manageable even if you hold the state in the parent component. In most cases it's still more clean then a flux like architecture.

