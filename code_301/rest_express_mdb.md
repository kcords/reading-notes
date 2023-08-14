### REST API w/ Express & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

   * It reduces the chances of sensitive database credentials from being exposed in the code/repo
2. What is middleware?

   * Components that can handle various functions and sit between different parts of the Node application, running sequentially during an API call
3. What does app.use(express.json()) do?

   * Express middleware that parses JSON in a req body
4. What does the /:id mean in a route?

   * A placeholder in the route that will map the provided value to a param called `ID` that can be accessed in `params`
5. What is the difference between PUT and PATCH?

   * `PUT` - Update or replace an entire record
   * `PATCH` - Updates a portion of a record
6. How do you make a default value in a schema?

   ```
   mongoose.Schema({
     name: String,
     age: { type: Number, default: 18 }
   })
   ```

   With the `default: <value>` being the default value
7. What does a 500 error status code mean?

   * *Internal Server Error* - a generic error code expressing that an unexpected condition is preventing the request from being fulfilled
8. What is the difference between a status 200 and a status 201?

   * *200* - Request was successful, such as in a `GET`
   * *201* - Resource was successfully created, such as in a `POST` or `PUT`

### References

- [Express.js Docs](https://expressjs.com/en/5x/api.html#res.app)
- [Mongoose.js Docs](https://mongoosejs.com/docs/guide.html)
- [MDN HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
