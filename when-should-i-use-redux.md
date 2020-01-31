---
description: This explanation seemed strange but think about the notifications
---

# When should i use Redux?

![](.gitbook/assets/image%20%285%29.png)

#### [From reduxjs/redux github page](https://github.com/reduxjs/redux#before-proceeding-further)

Here are some suggestions on when it makes sense to use Redux:

* You have reasonable amounts of data changing over time
* You need a single source of truth for your state
* You find that keeping all your state in a top-level component is no longer sufficient

#### From my expirience

* When the server sends messages to the client you would probably have some kind of message provider which could act as global reducer who updates the components.
* You have many state updates from different places and keeping state in parent component is no longer sufficient.
* You need money and want to extend your contract.

