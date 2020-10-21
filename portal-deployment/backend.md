## Deploy backend

Clone github repo

`git clone https://AKcessLabs@bitbucket.org/akcessapi/cbk_server.git`{{execute}}

Go to backend project 

`cd cbk_server`{{execute}}

Install dependencies 
`npm i`{{execute}}

Install pm2 
`npm i -g pm2`{{execute}}

Run API
`pm2 start --name portal-api "node index.js"`{{execute}}