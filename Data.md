# Data

## Notes

This is all of the products and services that the fictitious company "DevHosts" has available. It will be your job to structure this data in a way that's easy to work with. You can change property names like `eventsPerMonth` if needed but all of the values and product names must be preserved.

A user should be able to add any of the servers or services to their cart and order.

The user account itself should contain all of the servers and services that they are subscribed to. For example, if a user has a `Lynx VPS`, a `Perpetuate Yellow` service and the `Telescope Cosmos` service, they should all be listed in the user's account. You should also be tracking the total cost per month for each user.

Treat this like a real-world application. The user is buying and subscribing to these services and there is a ton of information that can be tracked.

Good Luck~!


All prices in USD

## VPS - Standard Servers

> These are our standard choices for the regular user or your average website

### Lynx

memory: 1 GB
cpu: 1
storage: 25 GB
transfer: 1 TB
price:  $15/month

### Puma

memory: 2 GB
cpu: 1
storage: 50 GB
transfer: 2 TB
price:  $25/month

### Panther

memory: 4 GB
cpu: 2
storage: 100 GB
transfer: 4 TB
price:  $25/month

### Tiger

memory: 8 GB
cpu: 4
storage: 100 GB
transfer: 10 TB
price:  $50/month

### Lion

memory: 16 GB
cpu: 6
storage: 250 GB
transfer: 25 TB
price:  $75/month

### Goat

memory: 64 GB
cpu: 16
storage: 1 TB
transfer: 100 TB
price:  $350/month

## Data Storage

> We also have dedicated JSON storage

### Blue Store

storage: 250 GB
transfer: 1 TB
price: $25/month

### Red Store

storage: 500 GB
transfer: 5 TB
price: $75/month

### Black Store

storage: 5 TB
transfer: 100 TB
price: $500/month

## Services

### Load Balancer

> Automatically distributes incoming traffic across a collection of servers

price: $25/month

### Continuous integration

> Automatically build and test code every time you push to Github. This will connect your server directly to a repo on Github

### Perpetuate Yellow

price: $100/month
builds: 50/day
concurrentBuilds: 1
> 1 build at a time

### Perpetuate Green

price: $150/month
builds: 100/day
concurrentBuilds: 2
> 2 builds at a time

### Perpetuate Silver

price: $300/month
builds: unlimited
concurrentBuilds: 5
> 5 builds at a time

### Error Logging / Monitoring

> Monitor your server/projects/code. Measure preformance, track errors as well as server info

### Telescope Andromeda

price: $25/month
eventsPerMonth: 100,000
history: 90 days
users: 2

### Telescope Cosmos

price: $50/month
eventsPerMonth: 250,000
history: 180 days
users: 5

### Telescope Virgo Stellar

price: $150/month
eventsPerMonth: 750,000
history: 365 days
users: 25


----