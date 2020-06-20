Music Thoughts


Link to Project: https://music-thoughts-client.vercel.app/

API Documentation: https://dashboard.heroku.com/apps/secret-lowlands-06468

ONLY ENDPOINTS USED IN APP

GET

REQUEST: /api/thoughts
Retrieves the the thoughts posted on the page
RESPONSE: 200

POST

REQUEST: /api/thoughts/:thoughts.id
Posts a thought to the page
RESPONSE: 201 OK

POST

REQUEST: /api/thoughts/:thoughtsid/:comment.id/comments
Posts a thought to the page
RESPONSE: 201 OK    



Summary: 
- The API allows users to GET the users thoughts on the main page and also allows the user to post a thought to the page. The API also allows users to post comments under a specific thought.

Screenshots: 
![Image of Landing Page](https://puu.sh/FWy17/7eed5ca273.png)
![Image of Website](https://puu.sh/FWy0U/9e538740ea.png)

Tech Stack: 

Client:
ReactJS
HTML
JavaScript
CSS
Vercel

Server:
NodeJs
Express
Knex
PostgreSQL
Heroku
Screenshots