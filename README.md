[![CircleCI](https://circleci.com/gh/shanepeckham/eventhublistenerack.svg?style=svg)](https://circleci.com/gh/shanepeckham/eventhublistenerack)

### FulfillOrder - TACK

A containerised Go swagger API to fulfill orders and commit them to MongoDB

The following environment variables need to be passed to the container:

### ACK Logging
```
ENV TEAMNAME=[YourTeamName]
```
### For Mongo
```
ENV MONGOHOST="mongodb://[mongoinstance].[namespace]"
```
### File mount
```
/orders
```
