# 6-Key Terminology

Get to grips with these key concepts to better understand how Onum works and use it to its full potential.

### **Action**

A unit of work performing a given operation on an event.

***

### **API**

Application Programming Interface. A set of defined methods of communication among various components.&#x20;

***

### **Cluster**

Various distributors and workers can be grouped and contained within a cluster. You can have as many clusters as required per Tenant.

***

### **Data Sink**

Where the data is routed after being processed by Onum.

***

### **Data source**

Where the data is generated before ingesting it into Onum, e.g. application server logs, firewall logs, S3 bucket, Kafka Topic, etc.

***

### **Distributor**

This service receives and processes the Listener data before sending it on to workers within a cluster.&#x20;

***

### **Event**

An event represents semi-structured data such as a log entry. Events can be parsed so that structured data can be generated and eventually processed by the engine. Events are composed of fields, which are referred to as **Field**. An action that produces a new field will be referred to as **outputField.**

***

### **Label**

Used to sort events coming from Listeners into categories or sets that meet given filters to be used in a Pipeline.

***

### **Listener**

A Listener retrieves events in a given IP address and a port, routing the data to the Pipelines so that it can be processed.

***

### **Lookup**

A **lookup** refers to searching for and retrieving information from a specific source or dataset, typically based on a key or reference.&#x20;

***

### **Multitenancy**

Multitenancy is an architecture in which tenants share the same underlying infrastructure, including databases and application code, but their data and configurations are kept separate to ensure privacy and security.

***

### **Pipeline**

A sequence of Actions connected through inputs/outputs to process a stream of data. Data comes from the Listener and eventually is routed to a Datasink.

***

### **Role**

A role is assigned to a user in order to control the access they have to certain or all Onum features. This way, we can personalise the experience for each user.

***

### **Tag**

Tags can be assigned to Listeners, Pipelines or Data sinks in order to classify them or make them easier to find. This is particularly useful if you have a wide database and want to avoid lengthy searching for the resources you wish to use.

***

### **Tenant**

A Tenant is a domain that contains a set of data in your organization. You can use one or various tenants and grant access to as many as required. &#x20;

***

### **Worker**

This service runs the Pipelines, receiving data from its distributor and contained within a Cluster.\
<br>
