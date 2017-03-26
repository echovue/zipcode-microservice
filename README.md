# zipcode-microservice
A Spring based microservice which determines the distance for a specific zip code.

To build the project, download it into a local directory.
 
You will need to update the apiKey variable in ZipcodeDistanceService with your own from
https://www.zipcodeapi.com/API

To run the program, execute the following from the commandline:

`./gradlew clean build bootRun`

An example request which you can submit is:

`http://localhost:8080/distance?zipCode1=97035&zipCode2=97001`

And the response should be:

`107 miles`

An incorrect request, such as one which includes an invalid zip code should result in:

`Unable to calculate distance`





