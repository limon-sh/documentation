# 1. Introduction
### 1.1 Backgroud
All products that are available in the Internet are hosted on servers. Such products may be used by large organisations or by private users on the internet. Because nesessity to provide permanent access to products it's needed to keep the server where this product is hosted available and understand if it's needed to pay attention to server work to prevent crashes, slowness and predict nesessity in enhancements.

### 1.2 Users
|User | Aim | Scenario|
|------- |:---:|:-------:|
|DevOps Engineer| To monitor server and be ready to adjustments to keep the good quality of the product | The DevOps Engineer is responsible for all operations with server. They set up Agent to the server, manage metricks, applies changes to server
|BE Developers|Apply load testing, understand the quality of the code|The BE developer verify if the code may be supported by the server load
|Project Managers|Keep clear information about server condition quickly without deep knowloge about the servers|Set up team who will be responsible for all operations and management of the server. The person review servers condition and may trigger required actions regarding server enhancement 
|QA Engineer|Need to conduct loading testing to understand if it meet non-functional requirements|The QA Engineer initiate load testing and get results to compare them with planned ones
|Product Owners|Need to understand loading of the servers to plan its usage in depence on plans about users|The Product Owner gets main information about the server and may calculate the server loading in depence on the planned amount of users

### 1.3 Risks

|Risk| Description|Resolution|
|-------|:---:|:-------:|
|Payback Period|Storage of the data is highly cost operation and there are some efficient featyres that require this operation|- Need to analyze traffic and volume of the data that should be stored   - Need to determine which features will be free and their volume - Need to determine duration of data storage for different |
|Accesability of the server|AWS will be used as a server provider, the AWS allows several minutes per month of unavailability|Agent should have local data base and then send them to server and clear data base. The clients should be notified about local DB to be able plan their storage|
|Huge technical support|There is a technical issue with BE/FE|7 days to resolve a technical issues, during this period all data will be collected and stored on the client side|
|Market analysis|No confidence in |Make market analysis, conduct market research|
|Absence of time|There is no enought time to support project after launch|Be ready to spend a lot of time by ourselves|

### 1.2 Scope
The solution is a web - application and agent. Agent is a programm that aim is to collect information about server to vizualize it in the web application. Web - application is a way to agregate information that is gotten from Agent and allow users apply action regarding server monitoring. Web - application will be presented as a responsive one.
