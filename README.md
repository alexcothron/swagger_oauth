# swagger_oauth
Test application to integrate swagger documentation with identityserver4

https://stackoverflow.com/questions/47164862/is-it-possible-to-explicitly-define-a-swagger-method-upfront-using-swashbuckle-f

Is it possible to explicitly define a swagger method upfront using swashbuckle for aspnetcore?

I am currently using identityserver middleware in my project to implement an oauth service. I would like to use swagger to define some of the methods available in this middleware such as /Connect/Token which is used to acquire and access token.

Unfortunately since this is middleware I do not have implementations of controllers that handle the http requests - since the requests are handled in the middleware.

Is it possible to explicitly define upfront a swaggerdoc with all the endpoint information (such as url, params etc) if you are using a middleware that handles all http requests?



