# AWS Exploration Blog

Assignment #1

CIS 4360-005

Evan Fiordeliso

---

### Instructiuons
1. Create a AWS Free Trial Account at https://aws.amazon.com/free
2. Spin up free compute and run some ordinary program - this may require you to install software or write a program
3. You are to write about the cloud experience and show snapshots of what you have done
4. You are to write a few paragraphs on how cloud would aid microservices
5. this writeup is to go in your github like a blog and you are to post your URL in this assignment.  You may be asked in class to bring up your blog and cover it in class next Thursday February 18.

---

## Exploration

Exploration section

## Cloud Platforms and Microservices

The benefits of using a cloud platform to implement a
microservice architecture are clear when considering the
properties of the architecture. One of the main properties
is scalability, the ability for the application to grow or
shrink depending on the needs of the client. By using a
cloud platform, it would be rather easy to obtain more
resources required to scale the application up. Also with
many platforms you only pay for what you use so allocating
resources to the more important parts of the system makes
it more cost effective to run.

There are also cloud platforms that come with specific
features designed to make implementing a microservice
architecture easier. AWS has such a feature that they call
AWS Lambda. With these features being designed specifically
for microservices it makes implementing the architecture
far easier as you don't have to put together the part that
will host the microservice as it is handled for you. Also
this feature is designed to integrate well with their other
features allowing for easy and seamless communication with
the parts of the system as needed.

Even if the cloud platform of choice does not have a specific
feature designed around microservices, there often is a way
to implement it using containerization. Containerization is
the process of bundling an application with all of the 
configuration files, libraries, and dependencies needed to
have the application run. The most popular containerization
ecosystems, Docker and Kubernetes, are well supported by many
cloud platforms. This allows for easily deploying a
microservice with all of the things it needs to run.

As you can see, cloud platforms offer many benefits when it
comes to a microservice architecture and it seems like an 
obvious choice when choosing to implement it.