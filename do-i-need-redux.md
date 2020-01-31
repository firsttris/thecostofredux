---
description: 'No, you don''t!'
---

# Do I need Redux?

## Seriously! Most apps are perfectly fine without Redux

Think about it, all this effort for a stateless protocol? If the user switches a route or reloads the browser everything is gone. The only reliable way to share information is in the URI. Because you probably need the Id to fetch the data from the server on the next page.

![](.gitbook/assets/image%20%287%29.png)

One route is generally manageable, even if you hold the state in the parent component. In most cases it's still more clean than a Flux like architecture.

