---
description: 'No, you don''t!'
---

# Do I need Redux?

## Seriously! Most apps are perfectly fine without Redux

Think about it, all this effort for a stateless protocol? If the user switches a route or reloads the browser everything is gone. Don't build something unnecessarily complex if you don't have to. 

![](.gitbook/assets/image%20%288%29.png)

In general one route should be manageable, even if you hold the state in the parent component. In most cases it's more clean than a Flux like architecture.

Apps have all kinds of strange requirements but in most cases its not about Flux. 

Let's take the following example

You have created a store to persist the filters for a dashboard. In the next sprint meeting, the customer suddenly asks that he would like to save the filters as bookmarks.

In this case its required to persist the information in the URI, a store is now actually superfluous.

