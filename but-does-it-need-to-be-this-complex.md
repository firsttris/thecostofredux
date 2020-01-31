---
description: No it doesn't!
---

# But does it need to be this complex?

## Seriously! Most apps would be perfectly fine without Redux

All this affort for a stateless protocol? If the user switches a route or reloads its browser its gone.

Means the only way to really persist information is in the URI. 

![](.gitbook/assets/image%20%287%29.png)

One route is generally manageable even if you hold the state in the parent component. 

Believe me, in most cases its still more clean then a flux like architecture.

