# MWA Homework05 - Expressjs 01
## Exercise
Create an Express application that will accept a `GET` request from route `/users` and send a `JSON` response with users data.  
  
* Create a new project: `npm init`, and then download the necessary dependencies: `npm i express rxjs axios`
* JSON data to be fetched from `https://randomuser.me/api/?results=10`
* Use `axios` module to fetch the data.
* Create a custom `Observable` object, once a subscription is made to it, it will fetch the data and cache the response using `shareReplay` operator.
* When you receive `GET` request to `/users`, subscribe to your `Observable` and send the appropriate `JSON` response.
* Your application should run fluently behind any proxy without revealing the framework name to clients, proxy should not cache the response.
* Your route should be case sensitive and strict.
* Send standard pagination options in the response headers.
* Allow the response to be cached at the client for one day if no change occur at the server.
