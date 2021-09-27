# White Box Testing

## what is white box testing ?

White-box testing (also known as clear box testing, glass box testing, transparent box testing, and structural testing) is a software testing method that examines an application's internal structures or workings rather than its functionality (i.e. black-box testing). In white-box testing, test cases are created using an internal perspective of the system as well as programming skills. The tester selects inputs from which to exercise code routes and identify expected outputs. Testing nodes in a circuit, such as in-circuit testing, is equivalent to this (ICT).
In the software testing process, white-box testing can be used at the unit, integration, and system levels. Although conventional testers thought of white-box testing as being done at the unit level, it is now more commonly utilized for integration and system testing. During a system–level test, it can test paths within a unit, paths between units during integration, and paths between subsystems. Though this technique of test design can find numerous faults or problems, it has the ability to overlook elements of the specification that have not been implemented or criteria that have not been met. When it comes to white-box testing, it's all about the design.

now before we get to testing, in my web app i used a few libraries wich are:

axios , dotenv , cors , express.
but what are these libraries? glad you asked!!

-------------------------------------------------------

## lets start with axios

Axios: Axios is a Javascript library that implements the Promise API, which is native to JS ES6 and is used to make HTTP requests from node.js or XMLHttpRequests from the browser. It can be used to intercept HTTP requests and answers, as well as provide client-side XSRF prevention. It's also capable of canceling requests.

why did i choose it ? simple!! because of these reasons:

+ it has URL in request object
+ it  is a stand-alone third party package that can be easily installed. and in my knowledge in game development and moding , stand-alone is an amazing word, it basically means it does not rely on other packages to work properly.

+ Axios enjoys built-in XSRF protection.
+ Axios uses the data property.
+ Axios’ data contains the object.

## now lets move to next one which is dotenv

Dotenv is a zero-dependency module that loads process.env with environment variables from a.env file. The Twelve-Factor App technique recommends storing settings in the environment distinct from code.

Why should I use dotenv? also glad you asked !!!!

Dotenv is a tool that allows you to keep secrets separate from your source code. This is handy in a collaborative context (e.g., work or open source) where you don't want to reveal your database login details. Instead, you can distribute the source code and let others to generate their own.env files.

It can also be used to dynamically adjust your app without having to modify the original code. For local development, for example, you can set DB URL to a dev database. Alternatively, if you wish to print logs to the console for local development but not in production, use the following command.
Using dotenv (or other similar tech) for real-world applications that are deployed to hundreds or even thousands of instances allows all instances to share the same source code while having their own.env file to allow them to use different configurations, such as connecting to different databases or writing logs to different endpoints.

## Cross-Origin Resource Sharing (CORS)

CORS (Cross-Origin Resource Sharing) is an HTTP header-based system that allows a server to specify any additional origins (domain, scheme, or port) from which a browser should allow resource loading. CORS also uses a system in which browsers send a "preflight" request to the server hosting the cross-origin resource to ensure that it will allow the actual request. The browser transmits headers indicating the HTTP method and headers that will be used in the real request during this preflight.
A cross-origin request is when the front-end JavaScript code from <https://domain-a.com> makes a request to <https://domain-b.com/data.json> using XMLHttpRequest.

Browsers block cross-origin HTTP queries launched by scripts for security concerns. The same-origin policy is followed by XMLHttpRequest and the Fetch API, for example. This means that a web application using those APIs can only request resources from the same origin as the one from which the application was loaded, unless the answer from other origins includes the appropriate CORS headers.

-------------------------------------------------------

testing :

testing bootstarp library :

![test1](img/test1.png)

![test2](img/test2.png)

after installing the library and checking if there are any errors in the implementation

now lets test the new libraries in my app (axios , dotenv , cors , express)

here is what we get for using the libraries commands without the libraries when we run our backend app:

![test3](img/Screenshot(1313).png)
![test4](img/Screenshot(1314).png)
![test5](img/Screenshot(1315).png)

and now after installing the libraries needed for my app, we can use the commands we need for the API:
we can run it , work with it, and then pushing it to our github repo.

![test6](img/Screenshot(1316).png)

now lets move to the local host for our frontend app and our heroku app for backend:

![test7](img/Screenshot(1317).png)
![test8](img/Screenshot(1318).png)

with installing the right libraries and using correct commands we see that there are no errors in our console!!

now this here is our .env file, here we stash data that we dont want anyone to see:

![test9](img/Screenshot(1319).png)

we hide our key for accessing the locationIQ here, also the link for heroku app.

next up is my front end app, here we see using the axios and importing it and also testing the variables in our .env file

![test10](img/Screenshot(1320).png)
![test11](img/Screenshot(1321).png)
![test12](img/Screenshot(1322).png)

-------------------------------------------------------

### references

<https://en.wikipedia.org/wiki/White-box_testing>

<https://www.geeksforgeeks.org/difference-between-fetch-and-axios-js-for-making-http-requests/>

<https://github.com/motdotla/dotenv>

<https://dev.to/getd/how-to-manage-secrets-and-configs-using-dotenv-in-node-js-and-docker-2214>

<https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS>

<https://www.coursereport.com/blog/what-is-express>
