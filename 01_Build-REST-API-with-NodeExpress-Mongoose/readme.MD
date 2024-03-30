 #### Build REST API with Node Express Mongo & Mongoose in 2024

 - step1  ==>  npm init -y
 - step2  ==> npm i express
 - step3 ==> create app.js file and make connection to port 5000
 - step4 ==> make routes and controllers folder
 - step5 ==> create products.js file in routes folder and product.js file in controllers folder as well
 - step6 ==> npm i dotenv
 - step7 ==> npm i mongoose
 - step8 ==> create Schema of your data in model folder 
 - step9 ==> RUN node productDB.js to insert data into mongoose database
 - step10 ==> npm run start
 - step-11 ===> check api in localhost     http://localhost:5000/api/products/testing  http://localhost:5000/api/products/

 - step-12 ==> it will show only iphone in API  http://localhost:5000/api/products/?name=iphone
 - step-13 ==> it will show sorting with price,name  in API  http://localhost:5000/api/products/?sort=-name,-price
 - step-14 ==> it will show only selected name and company in API  http://localhost:5000/api/products/?select=name,company
-  step-15 ==> it will show page no 2  in API  http://localhost:5000/api/products/?page=2&limit=10





###### Reference Video:  https://www.youtube.com/watch?v=0T6e8aJkG2c&t=40s&ab_channel=ThapaTechnical


