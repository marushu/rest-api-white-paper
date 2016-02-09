# What is a REST API?
*We look at what the REST architectural style is, explore the elements that make an API RESTful, and consider some of the ways in which open APIs are changing the internet.*
**Representational State Transfer (REST)** is a software architectural style for Application Programming Interfaces (APIs) that consists of guidelines and best practices for creating scalable web services. REST uses simple HTTP to make calls between machines.

This happens via a request/response mechanism between the server and the client. For example, a client, let’s say an Android application, makes a request for the most recent posts from the website. The server knows how to interpret this request, through REST, and satisfies the response by providing the most recent posts in a format understood by the client.

REST requests interact with the resources in your application (e.g. a Post or Page). These interactions are typically Reading, Creating, Updating, or Deleting. Combined with HTTP, REST requests are formed using four verbs:

- ```POST```: Create a resource

The data retrieved is supplied in a machine-readable format, often JSON in modern web applications.
> REST was proposed by Roy Fielding in his 2000 dissertation [Architectural Styles and the Design of Network- based Software Architectures](http://www.ics.uci.edu/~fielding/pubs/dissertation/abstract.htm).

## What makes an API RESTful?

An API must have the following architectural features to be considered RESTful:

A separate, but closely-related concept is hypermedia. Hypermedia allows a client to more fully discover a REST API without needing to know anything about the structure of the API. It’s similar to hyperlinks on the human-readable web (which enable discovering new sites and content). The server provides the information the client needs to interact with it. This means that the client can interact with the server in complex ways without knowing anything beforehand about it.

![a graph showing the growth of web APIs from 1 in June 2005 to 10,302 in October 2013](images/web api chart.001.png)
*Source: Programmable Web*

Open APIs are publicly available APIs that give developers access to proprietary software information that they can make use of in their own software and applications. REST is the ideal architecture for creating an Open API for the web because, by using HTTP, it is built on the principles of the open web. To leverage an open REST API a developer just needs to make a HTTP request.


This aggregation of public data across different platforms enables the creation of feature-rich, powerful applications that do more than any individual product or service could do on its own.