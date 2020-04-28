# remedy-ar-sapi
Remedy Action Request MuleSoft System API


Connecting with Remedy AR System

As organizations use Remedy AR for business critical workflow it is necessary to synchronize or flow the information in Remedy to other applications like Salesforce and in other cases expose for partner consumption. MuleSoft provides a BMC Remedy AR Connector that is built using the Remedy AR Java API for accessing various Remedy modules and forms. 

While the out-of-the-box connector uses Remedy Java API there are situations where connecting through REST API is preferred. In this article we will explore how to use Remedy REST APIs to perform CRUD operations on Incident, Task, and WorkInfo forms; in other words build a System API for Remedy AR by defining endpoints in RAML API specification and implementing the API in a Mule application.

See this [blog post](https://blogs.mulesoft.com/dev/howto/connect-to-remedy-action-request-rest-api) for step-by-step process to build MuleSoft Remedy System API

