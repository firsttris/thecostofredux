---
description: 'This explanation seemed strange, but think about the notifications'
---

# When should I use Redux?

![](.gitbook/assets/image%20%286%29.png)

#### [From reduxjs/redux github page](https://github.com/reduxjs/redux#before-proceeding-further)

Here are some suggestions on when it makes sense to use Redux:

* You have reasonable amounts of data changing over time
* You need a single source of truth for your state
* You find that keeping all your state in a top-level component is no longer sufficient

#### From my experience

* When the server sends messages to the client, you would probably have some kind of message provider, which could act as global reducer, that updates the components.
* You have many state updates from multiple places and keeping state in parent component becomes unclear.
* You need money and want to extend your contract.



[Question: How to choose between Redux's store and React's state? \#1287](https://github.com/reduxjs/redux/issues/1287)

