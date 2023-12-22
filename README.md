# JunkCash API for Bangkit Capstone Project 2023

Welcome to JunkCash API. JunkCash is the waste buying and selling application that revolutionizes the recycling experience. This app allows users to buy and sell recyclable materials efficiently while contributing to a cleaner environment.

## Add Order
#### URL
```URL
/orders
```
#### Method
```
POST
```
#### Data Params
```
username, email, wasteType, quantity, collectorLoc, userLoc, notes
```

#### Success Response
```
code : 200
{
    "message": "Insert Successful"
}
```
## Get All Orders
#### URL
```
/orders
```

#### Method
```
GET
```

### Data Params
```
username, email, wasteType, quantity, price, collectorLoc, userLoc, notes, imgUrl, date, status
```

## Get Orders by Id
#### URL
```
/orders/{id}
```

#### Method
```
GET
```

#### Data Params
```
username, email, wasteType, quantity, price, collectorLoc, userLoc, notes, imgUrl, date, status
```


## Get Total Price
#### URL
```
/orders/{username}/totalprice
```

#### Method
```
GET
```

#### Data Params
```
total_price
```

## Update Order Status
#### URL
```
/orders/{id}/completed
```

#### Method
```
PUT
```

#### Data Params
```

```

#### Success Response
```
{
    "fieldCount": 0,
    "affectedRows": 1,
    "insertId": 0,
    "serverStatus": 2,
    "warningCount": 1,
    "message": "(Rows matched: 1  Changed: 1  Warnings: 1",
    "protocol41": true,
    "changedRows": 1
}
```
