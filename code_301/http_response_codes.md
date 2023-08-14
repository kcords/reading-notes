### HTTP status response codes

1. In your own words, describe what each group of status code represents:
   *100’s* = Communicates connection status / req progress before completing requested action & sending a final response
   *200’s* = Request was received and accepted as valid
   *300’s* = The requested resource has been moved/removed from the location it was previously requested at
   *400’s* = An invalid request has been sent by the client, such as, unauthenticated/unauthorized, invalid input, etc.
   *500’s* = An error has occurred on the server itself and the request was unable to be completed
2. What is a status code 202?
   * The request has been received but not yet acted upon
3. What is a status code 308?
   * The resource is now permanently located at another URI
4. What code would you use if an update didn’t return data to a client?
   * 204 - often used for a resource updated
5. What code would you use if a resource used to exist but no longer does?
   * 410
6. What is the ‘Forbidden’ status code?
   * 403

### References

* [Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
* [HTTP response status codes - MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
* [Specifications](https://httpwg.org/specs/rfc9110.html#overview.of.status.codes)
