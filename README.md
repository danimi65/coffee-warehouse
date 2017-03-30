# coffee-warehouse


## Tables

Coffee
1. id
2. name
3. location (origin bean )
4. caffiene level

| HTTP Method   | Body          | Response                | Action           |
| ------------- |:-------------:| :----------------------:|------------------|
| GET /         | empty         | render HTML index.html | serves index.html |
| GET /coffee   | empty         | { "coffee: [...]"} A JSON response containing a list of all the coffee | Retrieves all coffee|
| zebra stripes | are neat      |    $1 |


Order
1. FK Coffee
2. FK customer
3. tag (pending, shipped, voided)


Customer 
1. First name
2. last name
3. id
4. order
