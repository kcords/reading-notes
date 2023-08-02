Understanding good API design will be important as we build out our APIs to interface between our frontend as well as implementation in upcoming projects.

### Rest API Design

1. What does REST stand for?
   * Representational State Transfer
2. REST APIs are designed around a **__** **__** .
   * resource representation
3. What is an identifier of a resource? Give an example.
   * https://www.something.com/product/123
4. What are the most common HTTP verbs?
   * Get, put, post, patch, delete
5. What should the URIs be based on?
   * Nouns -- the resource
6. Give an example of a good URI.
   * https://www.something.com/product/123
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
   * APIs that expose a large number of small resources.
   * It's generally bad, but should be blanced as to not create larger overhead of data that the client doesn't need.
8. What status code does a successful `GET` request return?
   * 200
9. What status code does an unsuccessful `GET` request return?
   * 404
10. What status code does a successful `POST` request return?
    * 201
11. What status code does a successful `DELETE` request return?
    * 204

### References

* [API design best practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

### Things I want to know more about
*