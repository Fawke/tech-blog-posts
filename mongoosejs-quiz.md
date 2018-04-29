## Data Modelling and Schema Definition in Mongodb using mongoose.js

### What major problem is solved by using an ORM or an ODM?

    a. It makes execution of our Database queries faster compared to native queries.
    *b. It provides a standard and easy interface to interact with the database.
    c. It helps in scaling and sharding of our data in the database.
    d. It adds an extra security layer to our database to protect against cyber attacks.

### What is the Active Record Pattern? Select the statement(s) that are TRUE.

    a. It's a Plain Old JSON object with key-value pairs and few methods.
    b. It wraps raw data with methods to perform CRUD on it.
    c. Process of copying values from query to object is called Hydration.
    *d. All the statements are true.

### What is the major benefit of having a DAO (Data Access Layer)?

    a. Decoupling of busicess logic code from date query language code.
    b. Code modularity to facilitate unit test cases for DAO methods and functions.
    c. Easy replacement of underlying persistent data storage without changing business logic code.
    *d. a, b and c are all benefits of having a DAO Layer.

### What's the ideal scenario(s) to use an ODM like mongoose.js?

    a. You're coming from a SQL background, schema definition will make your life easy.
    b. You want data validation built in.
    c. You want to rapidly prototype an app but data flow may change later.
    d. You want to abstract away most of your mongodb code.
    e. All scenarios are ideal for using mongoose.js
    *f. Only a, b and d.

### Write a query to find the people with last name `Ghost` and aged between `17` and `20`.

    *a. Person.find({'name.last': 'Ghost'}).where('age').gt(17).lt(20)
    b. Person.findOne({'name.last': 'Ghost'}).where('age').gt(17).lt(20)
    c. Person.find({'name': 'Ghost'}).where('age').gt(17).lt(20)
    d. Person.find({'name.last': 'Ghost'}).where('age').gt(17)

### What's the maximum allowed size of a single document in MongoDB?

    a. 2mb
    b. 20mb
    *c. 16mb
    d. there's no upper limit, it depends on your RAM capacity

### Spot the incorrect way to open a Mongoose connection with MongoDB database.

    a. db = mongoose.createConnection('mongodb://@localhost:port/database');
    b. var opts = { db: { native_parser: true }}
       db = mongoose.createConnection('mongodb://user:pass@localhost:port/database', opts);
    c. db = mongoose.createConnection('mongodb://user:pass@localhost:port,anotherhost:port, yetanother:port/database');
    *d. all are correct

### 

###

###