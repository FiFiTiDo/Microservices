# Gartner Report Blog

Assignment #1

CIS 4360-005

Evan Fiordeliso

* Agility
* Most don't need Scalability
* CD easier in a microservice codebase as it can be easier to find the faults
* MSA is flexible and independent, features easy to roll out quickly
* Agility increases with granularity
* Complexity decreases with granularity
* Need a healthy balance in the granularity
* Macroservice is to provide access
* Miniservice is to improve agility
* Microservice is for continuous delivery (CD)
* Benefits
    * Deploy features as quickly as they are developed
    * Each microservice is small and independent so there is less risk with deployment
    * Teams can work independently on their microservice/feature
    * Due to loose coupling, each microservice can use their own technology and languages
    * Each individual component can be scaled independently of the rest of the application
    * Well developed applications can continue running despite part of it being nonfunctional and can recover quickly
* Costs
    * Technical and cultural changes need to be navigated
    * Need proficiency in Agile and DevOps practices
    * Microservices change how data is managed
    * There needs to be a completely different organization which can include different funding
    * Teams must be able to work independently
    * The infrastructure is much more complex
* Risks
    * May perform poorly if not implemented properly
    * High costs
    * Project delays
    * Unmet expectations
    * New roles, responsibilities, and organizational structures
    * Microservices infrastructure is fractured, immature, and evolving quickly
* The best way to convert over to microservices is to slowly increase service granularity. Start with the api, making it a macroservice, and then break out some features into miniservices, and when necessary break them up into microservices.

For many companies and organization, the risks and costs of using a
microservice architecture might out way the benefits. Whether to use
microservices comes down to a case by case basis and requires some
considerations before committing to the newer technology. Probably the
biggest risk when implementing microservices is the major cultural and
technological changes that need to be made. With the new technology comes
new roles, responsibilities and organizational structure to allow for
teams to independently work on their designated feature.

The microservice architecture is not just all doom and gloom, it comes with
many benefits that make it worth dealing with the cultural shift. When well
implemented, microservices offer agility in both application performance as
well as development. It allows for features to be deployed as quickly as
they are developed as the process no longer requires the redeployment of the
entire code base, only the specific microservice where the feature resides.
This flexibility also makes debugging easier as you only need to understand
the specific microservice to be able to find the problem. Scalability is
another benefit of the flexibility as it allows for individual components
to be scaled independently of each other allowing you to provide more
resources to the components that really need them.

Some considerations that need to be made when working with a microservice
architecture is how granular to make the components. As you increase the
granularity, the agility of the application increases. This is because the
smaller the component, the less code you need to deploy in order to add a
new feature. However, when you increase the granularity it also increases
the complexity of the application as you need to integrate the individual
components and the infrastructure needs to be more complex to handle them.
With a healthy balance of granularity, the application can have the best of
both worlds of agility with the lowest possible complexity.

Once you have determined whether microservices is a good option for your
application, you have to consider how to implement it, mainly when you
are attempting to apply the microservice archtecture to an existing
monolithic application. The best way to handle this is to start large
with the granularity and then break out individual components into
miniservices as needed and then break them up into microservices as
needed. When done incorrectly the application can end up perfoming poorly
and not live up to your expectations and can lead to high costs and
project delays.