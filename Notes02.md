# Notes 02


### PUT Vs PATCH

** PUT and PATCH update a resource at a location, but they do it differently.

PUT: is a method of modifying resource where the client sends data that updates the entire resource. 
It is used to set an entity’s information completely. 
PUT is similar to POST in that it can create resources, but it does so when there is a defined URI. 
PUT overwrites the entire entity if it already exists, and creates a new resource if it doesn’t exist.

PATCH: Unlike PUT, PATCH applies a partial update to the resource.
This means that you are only required to send the data that you want to update, and it won’t affect or change anything else.
So if you want to update the first name on a database, you will only be required to send the first parameter; the first name.


### Mock API Tools

**[Postman](https://www.postman.com/features/mock-api/): Build higher-quality APIs faster with Postman mock API servers.**

**[Mockoon](https://mockoon.com/): Mockoon is the easiest and quickest way to run mock API servers locally.
No remote deployment, no account required, free, open source and cross-platform.**

**[SoapUI](https://www.soapui.org/downloads/soapui/): The Most Advanced API Testing Tool on the Market
With an improved interface and feature set, you can immediately switch to ReadyAPI and pick up right where you left off in SoapUI. 
It's as seamless as it can get.**

### Swagger and APIDoc.js

**Swagger:** *Excerpt from Swagger website* Swagger is a powerful yet easy-to-use suite of API developer tools for teams and individuals, 
enabling development across the entire API lifecycle, from design and documentation, to test and deployment.

Swagger consists of a mix of open source, free and commercially available tools that allow anyone, 
from technical engineers to street smart product managers to build amazing APIs that everyone loves.

Swagger is built by SmartBear Software, the leader in software quality tools for teams. 
SmartBear is behind some of the biggest names in the software space, including Swagger, SoapUI and QAComplete.

**APIDoc.js:** apiDoc creates a documentation from API annotations in your source code.

Unsuccessful API Call should be sent with an error code in the 5xxs Status.


### SOAP Vs. REST:

**KEY DIFFERENCES:**

- SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.

- SOAP is a protocol whereas REST is an architectural pattern.

- SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the   components on the hardware device.

- SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.

- SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.

- SOAP cannot make use of REST whereas REST can make use of SOAP.




References:

https://www.guru99.com/comparison-between-web-services.html#:~:text=SOAP%20stands%20for%20Simple%20Object%20Access%20Protocol%20whereas,access%20to%20the%20components%20on%20the%20hardware%20device.

https://techbeacon.com/app-dev-testing/11-top-open-source-api-testing-tools-what-your-team-needs-know

https://www.soapui.org/downloads/soapui/

https://mockoon.com/

https://www.postman.com/features/mock-api/

https://apidocjs.com/#getting-started

https://swagger.io/about/

https://moz.com/learn/seo/http-status-codes#:~:text=An%20HTTP%20status%20code%20is%20a%20server%20response,a%20conversation%20between%20your%20browser%20and%20the%20server.





