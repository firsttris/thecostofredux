---
description: 'No, you don''t!'
---

# Do I need Redux?

## Seriously! Most apps are perfectly fine without Redux

Think about it, all this effort for a stateless protocol? If the user switches a route or reloads the browser all state which is not persistent in the url is gone. My advice is don't build something unnecessarily complex if you don't have to. 

![](.gitbook/assets/image%20%288%29.png)

In general one route should be manageable, if you hold the state in the parent component. In most cases it's more clean and simpler to understand than a Flux like architecture.

Apps have all kinds of strange requirements but in most cases not about Redux. 

Imagine the following case:

You are a big fan of Redux and build a store to hold the state of some filters from a dashboard. But in the next sprint meeting, the customer suddenly asks that he would like to save the filters as bookmark in the browser.

Now it is inevitable to persist the information in the URI. Does it still make sense to use Redux for this case?

