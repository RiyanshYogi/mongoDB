# mongoDB
Learn mongoDB queries from basic to advance level, Ready for exciting journey of mongoDB.


# Setup mongoDB first
  follow the link :-
          https://www.mongodb.com/try/download/community
  Make sure you'll check install mongodb compass during installation process.
  After downloading , configuring and setup the application, go to Drive C -> program files -> mongoDB -> server -> 7.0 -> bin, now copy this address 
  Now open environment variables, in system variable, choose path, click edit then new and paste your copied address and finally ok and apply.

# Setup mongoDB shell
  follow the link :-
          https://www.mongodb.com/try/download/shell
  After installing it, open CMD and type mongod --version, You'll see the details of your mongoDB environment.
  now reopen the cmd, just type mongosh, you'll have mongodb shell to run queries.

# MongoDBCompass 
  We'll work in mongoDBCompass. Just follow the below steps to learn from my repository.

  # STEP 1 :
  Open MongoDBCompass, connect to the server, click mongosh just below the screen, where you can run your queries by typing.
  Create new database as per your choice of name. follow the query
    use yourDatabaseName
  now create new collection naming "restaurants". you must name the collection with the provided name only because all the queries are using this name

  # STEP 2 :
  Now download restaurants.json file from repository to your local computer.
  Now exit from mongosh, select the database you created in mongoDBCompass, select your collection which is restaurants in our case.
  You'll see a option of add data, click on it, now you will see the option import JSON or CSV file , click on this option, and select restaurants.json file you downloaded from repo.
  Now you successfully added restaurants.json data to your collection.

  # STEP 3 :
  now ready to explore all the queries. First prefer Queries.txt file and then go to AggregateQueries.txt .
  you can also see the provided png picture in repository for your reference that how a single document will look like




    
  
