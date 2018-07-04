# Restaurant API Gateway server

This creates the API Gateway server for the Restaurant services.

### Running

Following URLs are equivalent(first one is directly calling the service and the second one is calling via API Gateway):

#### Directly calling the service
```
http://localhost:10000/items/1002/type/restaurant
http://localhost:11000/orders/type/takeaway
```

#### Calling using API Gateway
```
http://localhost:8765/item-service/items/1002/type/restaurant
http://localhost:8765/order-service/orders/type/takeaway
```