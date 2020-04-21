# FarmEasy

This is barebone skeleton for building your MERN stack Web App 

## SetUp Instructions : 

1. Open Git Bash in your local computer from the folder location where you want to set up the project
2. In Git Command prompt run : <br/>
`git clone https://github.com/microdegree/FarmEasy.git`
      
3. Git will automatically download the code into your local folder
4. Now , run <br/>
`cd FarmEasy`

## Frontend Setup 
1. Run below command in git bash <br/>
`cd my-app`
<br/>This will take you inside the front end code

2. Next step , run <br/>
`npm install`
3. You'll see the project downloading required dependencies
4. After this step is run successfully, run <br/>
`npm run start`

This step should start your server and automagically open browser with (If not , paste the below url in chrome and enter)
<br/> localhost:3000

and you should be able to see the farmeasy homepage.
This is the end of setup for frontend setup

## Backend setup : 

If you are continuing from above , run below command to come out of that folder<br/>
`cd ..`

1. Next run<br/>`cd backend`
2. Now run<br/> `npm install`<br/>
3. Next step run <br/>`npm run start`

Now go to a browser and hit below API url
[http://localhost:5000/api/v1/products](http://localhost:5000/api/v1/products "http://localhost:5000/api/v1/products")

<br/>This should fetch some data and display success as a json
##### Example : 
{"success":true,"count":0,"pagination":{},"data":[]}

## Database Setup : 

Currently the data is fetched from a dummy profile configured at Mongo Db Atlas.

Now, we need to setup our own Database by going to below url<br/>
[`https://www.mongodb.com/cloud/atlas`](https://www.mongodb.com/cloud/atlas "`https://www.mongodb.com/cloud/atlas`")

We have already done the same in MongoDb class, but we'll walk you through again in our Team Discussion Call

## **Credits : ** <br/>

Madhura from MicroDegree [Github Link](https://github.com/MadhuKS-MKS/FarmEasy "Github Link")

