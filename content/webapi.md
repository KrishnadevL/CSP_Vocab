{% include navigation.html %}

# Web API, REST, FETCH, Async, Request, Response
## Web API
An application programming interface, a service that allows applications and websites to directly communicate data to one another.  It is often used to host live data on servers that clients would want to see in live time, such as weather reports, social media posts, and COVID-19 statistics.

## REST
Parameters that allow functions to accept as many arguments as they want.  This may be useful to specific functions, such as one that takes in a string and counts how many words it contains (it would be best for this function to be able to take a variable amount of letters as any amount of words could be inputted).

## FETCH
Javascript method used to retrieve data from a remote server, often within the context of an API.  It is used in many web APIs (eg. if they update themselves live), as described above.  It is the opposite of async (described below) since the client first contacts the server.

## Async
Javascript keyword that enables a function to operate "asynchronously" and anticipate the arrival of data from a server.  It is the opposite of FETCH (described above) since the server contacts the client.

## Request
A part of network communication that requests data, generally in the context of client-to-server communication.

## Response
The resulting data transported from the server to the client as a result of a request.
