# MWA Homework05 - Expressjs 01
## Exercise  
* Create a new Express project: 
  1. `npm init`
  2. Download the necessary dependencies: `npm i express superagent`.
* When you receive a `GET` request to `/users`, fetch and return 10 users from `https://randomuser.me/api/?results=10`, use `superagent` and `async/await`.
* Map the results and send the users firstname and lastname only. (Optional: use child process to map the results).
## Express configurations
* Your API should hide the framework name from clients.
* Your route should be case sensitive and strict.
## HTTP headers configurations
* Send standard pagination headers in the response for the next and previous results pages (check the [pagination docs](https://randomuser.me/documentation#pagination) and [Express docs](https://expressjs.com/en/5x/api.html#res.links)).
* Your server will have header details for Proxy servers not to cache the response, but allow the response to be cached at the client only for 1 minute.

**Note: Add `node_modules` folder to your `.gitignore` file. You should only push your code along with `package.json` and `package-lock.json`**
