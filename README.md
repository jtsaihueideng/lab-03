# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Julie Deng
- Ellen Ko

## Lab Question Answers

Answer for Question 1: 

Restful APIs are scalable because REST optimizes client-server interactions. Statelessness removes server load because the server
doesn't have to retain past client request information. Caching also eliminates some server-client interactions. All these features
support scalability.

Answer for Question 2:

The mail server is provide the mail entries that the client requests based on the requests they made. For instance, when the 
client makes a request to get the inbox, the resources provided are the mail entries which includes information about the recipients,
senders, mail IDs, etc.


Answer for Question 3:

The PUT method is not used in the mail server. We can extend our mail server to use this method by allowing the functionality of
revising the body of the message that we already sent.

Answer for Question 4:

API keys are used for project authentication and project authorization. They're used to keep track of usage and identify invalid or malicious
requests. They also tell the API whether the requesting application has permission to use the API and which of the API's services it may access. 

Referred to this website: https://blog.hubspot.com/website/api-keys 

