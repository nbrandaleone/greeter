# greeter

This code is based upon a simple microservice app created by [Nathan Peck](https://github.com/nathanpeck/greeter-cdk).
I have updated it by adding in the AWS X-Ray library, so that the http requests can be traced. While instrumented your code can be tedious, it pays huge dividends in terms of troubleshooting and visibility.

Sample code for three microservices that construct a greeting.

You can find working, published Docker images for these three microservices at:

* [nbrandaleone/greeter](https://hub.docker.com/r/nbrandaleone/greeter/) - Constructs a random greeting phrase from a greeting and a name.
* [nbrandaleone/greeting](https://hub.docker.com/r/nbrandaleone/greeting/) - Returns a random greeting
* [nbrandaleone/name](https://hub.docker.com/r/nbrandaleone/name/) - Returns a random name

You can find an infrastructure as code sample that deploys the microservice stack automatically on AWS here:

https://github.com/nathanpeck/greeter-cdk
