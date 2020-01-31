---
description: No it doesn't!
---

# But does it need to be this complex?

## Seriously! Most apps are perfectly fine without Redux

Think about it, all this affort for a stateless protocol? If the user switches a route or reloads its browser the store is gone anyway. Means the only way to really persist information is in the URI. 

![](.gitbook/assets/image%20%287%29.png)

One route is generally manageable even if you hold the state in the parent component. In most cases its still more clean then a flux like architecture.

