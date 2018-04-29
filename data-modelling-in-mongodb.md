## Data modelling in NoSQL, in our case, MongoDb

### What led to the rise of NoSQL Databases?

    a. Rise in Internet traffic and need to handle huge amounts of data.
    b. Inability of Relational databases to scale horizontally.
    c. Need for ACID transactions
    d. Ease of modelling data based on use case.
    e. Need for high consistency
    f. a, b, c
    g. a, b, d, e
    *h. a, b, d
    e. a, b, c, d, e

### Which of the following characteristic(s) is NOT true about NoSQL Databases?

    a. Schemaless
    b. Non Relational
    c. Open Source
    d. Cluster Friendly
    *e. Consistency over Availability

### MongoDb falls under what category of NoSQL Dababase family?

    a. key-value
    b. column family
    *c. document database
    e. graph database

### Which of the below statement(s) is TRUE about CAP theorem?

    a. In case of a network partition, consistency can't be guaranteed but availability can.
    b. Consistency is always maintained regardless of a network partition.
    c. Availability takes precedence over consistency in case of a network partition.
    *d. Ony one out of the two, consistency or availability, can be guaranteed in case of network partition

### Who gets to decide which parameter, either consistency or availability, should be given more precendence over the other?

    a. Database Administrators
    b. Developers
    *c. Business people
    e. All of them

### Mark the statement(s) which is closest to being TRUE.

    a. Relational databases will be completely replaced by NoSQL databases in the future.
    b. NoSQL databases can't offer us ACID, hence not good for transaction based apps.
    c. Polyglot databases are the future of app development.
    d. All the statements are true.
    *e. b, c

### In which case, you'd choose a NoSQL database like MongoDb?

    a. You want a rapid time to market.
    b. Your app is heavy data heavy.
    c. You want a quick prototype, poc.
    *d. All of the above

### What is the closest analogy to a table in MongoDb?

    a. db
    *b. collection
    c. document
    d. column

### Which is NOT TRUE about Data modelling in MongoDb?

    a. Denormalization is preffered over normalization
    b. Normalization improves write performance
    *c. Normanilzation improves read performance
    d. Date modelling is done based on use case and nature of queries.
    

### NoSQL databases doesn't have any definite structure, schema.

    a. TRUE, because no schema is enforced.
    *b. FALSE, because there is still an implicit schema and order.
    