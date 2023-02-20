---
title: Force Reconfigure a MongoDB Replicaset if majority of nodes fail
---

You can force kick out failed nodes from a MongoDB replicaset in case of emergencies...

[instructions](https://www.mongodb.com/docs/manual/tutorial/reconfigure-replica-set-with-unavailable-members/)

Ensure that you store off the prior configuration and think through the risk of human error in the
operations.

But if you're in the dire situation of wondering if you should do this... it worked in my cluster in
a dire situation.
