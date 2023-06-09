# Installing MongoDb on Local machine

## Link to download Community version 
### https://www.mongodb.com/try/download/community-edition

## Follow the steps given below
### Step1 - Click on the next button
<img width="355" alt="1" src="https://user-images.githubusercontent.com/129230735/228676150-6c6bf30a-2efa-47b9-898a-517419a32167.png">

### Step2- Accept the terms in the License Agreement
<img width="356" alt="2" src="https://user-images.githubusercontent.com/129230735/228676519-e582927b-9adf-4bfa-86b7-a585fc7512c8.png">

### Step3- Select the Complete option
<img width="357" alt="3" src="https://user-images.githubusercontent.com/129230735/228676860-b73f0b44-ce30-4274-8384-a4e45a6bc1a8.png">

### Step4- Check on Install MongoDB as a service and run service as Network Service user
<img width="354" alt="4" src="https://user-images.githubusercontent.com/129230735/228677090-165abb8b-0596-4148-9d46-909167f7bb6a.png">

### Step5- Click on Install MongoDB Compass and enter next
<img width="358" alt="5" src="https://user-images.githubusercontent.com/129230735/228677464-765a11a1-0d2a-4be9-8bf2-ac59cace2f9c.png">

### Step6- Click on Install
<img width="354" alt="6" src="https://user-images.githubusercontent.com/129230735/228677743-ee6458bd-7dc7-4f03-84f3-fe8932b98e72.png">

## Now download mongoDB shell from the link given below
https://www.mongodb.com/try/download/shell

### Follow the instructions
<img width="355" alt="1" src="https://user-images.githubusercontent.com/129230735/228679438-2ba32413-e78a-4cf7-940b-d9509aeef706.png">

<img width="358" alt="2" src="https://user-images.githubusercontent.com/129230735/228679523-16f2e3ba-7dc1-4d68-93e9-91117d315f6a.png">

<img width="358" alt="3" src="https://user-images.githubusercontent.com/129230735/228679697-37cf2793-147f-4280-990e-4df569209927.png">


## Now open mongoDB compass
### Click on connect 
<img width="960" alt="1" src="https://user-images.githubusercontent.com/129230735/228681103-d115bae6-d161-4116-b543-acdcebe107af.png">

### Also go to service and check if mongoDB server running.
<img width="605" alt="Screenshot 2023-03-30 035652" src="https://user-images.githubusercontent.com/129230735/228681732-1aa20171-db08-4dee-ac5e-1c0424a1caaf.png">

### To create a database click on create database or '+' sign on the left.
### To delete a database or collection, click on the trash icon
<img width="195" alt="delete" src="https://user-images.githubusercontent.com/129230735/228683007-58f97d68-effd-4344-bc39-f72af29d4e05.png">

## use mongo shell in compass.
Click on MONGOSH on the bottom of the compass.

## Some shell Commands
### 1-> show dbs or show databases - To show all the database, it will also return the database in which we are working.

### 2-> use DATABASE_NAME - to switch between databases even if doesn't exist.

### In the terminal type mongosh to start interactive mongo shell.

### 3- cls - to clear screen.

### show collections - to show all the collection inside that database.
### help - to get list of commands.
### exit - to exit from the shell.

## To add document inside collection 
### db.COLLECTION_NAME.insertOne({})
### db.COLLECTION_NAME.insertMany([{}])

## 
## To Find in the database
### db.COLLECTION_NAME.find() - Gives the list of all the record
### db.COLLECTION_NAME.find({key1:value1, key2:value2}) - gives the list specific record
### db.COLLECTION_NAME.find({}, {key1:1, key2:1}) - return all the record with specific field. 
### db.COLLECTION_NAME.find({key1:value1, key2:value2}, {key:1}) - To have specific part of selected record. 1 to show and 0 to hide.


