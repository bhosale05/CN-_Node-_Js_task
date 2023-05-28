<h3 align="center">Assessment Test</h3>

## Instruction

Follow below procedure to run application

## 🏁 node server

Run below command to install node modules
 npm install

Command to start server
    node server.js

## Notes:
For POST, PUT, PATCH API Payload should be in JSON format
e.g. {"Type": "buy"}

API URL 
POST    
    -> http://localhost:8080/api/trades
GET
    -> http://localhost:8080/api/trades
    -> http://localhost:8080/api/trades?Type=buy&User_id=23 ( By Query )
    -> http://localhost:8080/api/trades/6473346ca2139d2adc8a9f8e ( By Id )

PUT
    -> http://localhost:8080/api/trades/6473346ca2139d2adc8a9f8e

PATCH
    -> http://localhost:8080/api/trades/6473346ca2139d2adc8a9f8e

DELETE
    -> http://localhost:8080/api/trades/6473346ca2139d2adc8a9f8e