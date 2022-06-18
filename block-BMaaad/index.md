writeCode

Write command to

- List collections from a database.
    show collections
- create a new collection in your country database which you created recently.
db.createCollection('Gujrat',{capped:true,size:1024,max:3})

Write code to:-

- crate a database named `weather`
user wheather
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
db.createCollection('temperature',,{capped:true,size:1024,max:3})
- create a simple collection named `humidity`
db.createCollection('humidity')
- check whether `temperature` collection is capped or not ?
db.temperature.isCapped()
- Delete `humidity` collection and then the entire database(weather).

db.humidity.drop()
db.dropDatabase()
