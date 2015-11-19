# DevOps-TechTalk

#Team

Kaustubh Sant - ksant
Nikhil Chinthapalli - nchinth
Vamshi Vikas - 
Rishi Vardhi -

##IBM Bluemix
---------------

[IBM Bluemix](https://console.ng.bluemix.net/) is an open-standards, cloud platform for building, running, and managing applications. With Bluemix, developers can focus on building excellent user experiences with flexible compute options, choice of DevOps tooling, and a powerful set of IBM and third-party APIs and services. It provides mobile and web developers access to IBM software for integration, security, transaction, and other key functions, as well as software from business partners. 

Built on Cloud Foundry open source technology, Bluemix makes application development easier with Platform as a Service (PaaS). Bluemix also provides pre-built Mobile Backend as a Service (MBaaS) capabilities. Bluemix also has cloud deployments that fit your needs. It has different *services, runtimes, containers, virtual machines, starters, boilerplates, and buildpacks*. With the broad set of services and runtimes in Bluemix, the developer gains control and flexibility, and has access to various data options, from predictive analytics to big data.

Bluemix provides the following features:

* A range of services that enable you to build and extend web and mobile apps fast.
* Processing power for you to deliver application changes continuously.
* Fit-for-purpose programming models and services.
* Manageability of services and apps.
* Optimized and elastic workloads.
* Continuous availability.

Bluemix abstracts and hides most of the complexities that are associated with hosting and managing cloud-based apps. The [catalog](https://console.ng.bluemix.net/catalog/) shows the different services that IBM Bluemix provides.


###Concentrating on services related to DevOps:

**1.Active deploy**:

This feature is still in BETA phase. With Active Deploy, the latest changes to our application can be deployed without any downtime. There are four phases during the active deploy.
* Original Version: This is the initial phase where the original version is still active and new version is yet to be rolled out.
* Rampup Phase: During this phase the rolling out of new version is began. The new version is deployed on new instances and the original version will not
be effected.
* Test Phase: The Rollout has been done. During this phase, we can test the latest changes and that too in a production environment. If tests fail, we can stop rolling out the new features.
* Rampdown Phase: By this phase we will have confidence on the new version as the testing has already been done. We can now stop the original version and
route all the traffic to new version.

**2.Auto Scaling**:
  
With AutoScaling feature, IBM Bluemix allows us to manage the compute capacity of our application. Whenever the load on our application increases,more instances are spawned and traffic will be directed to new instances as well. In this feature, we have the option to specify parameters like 
  * 'Scale-out' : The number of new instances to be spawned in case load increases.
  * 'Scale-in' : The number of instances to be removed when we need to scale down.
  * 'Allowable Maximum Instance Count': The maximum number of instances can be started. Scaling does not happen beyond this limit.

**3.Delivery Pipeline**:

This feature allows you to build your application, run tests and deploy the application to servers. This is extremely helpful as all this would on cloud and you would not need to maintain seperate build infrastructure. In delivery pipeline, you are needed the option to provide the build script and this script will be run to procure the build artifacts. Currently pipeline works with either git or cloudfarm source code repositories. Deployments can be done across the regions and to multiple instances. The advantage it holds over Jenkins is that it is entirely in Cloud and is easy to configure.

**4.Monitoring and Analytics**

The Monitoring and Analytics service allows to gain the visibility and control you need over your application. You can determine the response time your users see, understand the performance and availability of the application components, leverage analytics to keep your application up and performing well, and get automatically notified if application problems occur.
The main advantages of using Monitoring and Analytics are:

  * Effortless visibility: It lets you get the visibility you need without taking time and effort to learn and deploy another monitoring tool.
  * Diagnose problems faster: It helps to quickly identify the root cause of application problems with line of code diagnostics.
  * Keep your app running: It helps to keep the app up and reduce maintainence costs while improving availability.
  * Resolve problems with embedded analytics: Intelligently searches through logs and metric data to find the answers to your application problems.

**5.Track & Plan**

The Track & Plan service makes it easier to maintain the agile development process. It can be used to create stories, tasks, and defects to describe and track project work, and use agile planning tools for the product backlog, releases, and sprints. The Track & Plan service links plans and code so that plans stay in sync with the development team's progress. On the Bluemix Dashboard, you can see your DevOps Services projects and their member counts, visibility, and whether they have the Track & Plan service enabled. You can create work items for any of your DevOps Services projects or go to your planning tools.

**6.Blaze Meter**

BlazeMeter is a third party service that can be integrated with your project. It is a self-service, web and mobile load testing platform (PaaS) providing developers an enterprise grade, out-of-the-box load testing solution that’s 100% compatible with Apache JMeter™.

**7.Load Impact**

Load Impact is a third party service that can be integrated with your project. It is the leading load testing tool. It provides unlimited testing, on-demand from multiple geographic locations. You can create sophisticated tests using simple GUI or connect directly to its platform via API.

**8.New Relic**:

This is a third party tool which can be integrated into IBM Bluemix Devops services. New Relic is web app performance analysis tool which provides features
like:
* Code level visibilty: See which functions/code segments are consuming CPU the most.
* Database Call reponse times.
* Alerts: Sends alerts to the team when performance goes down.

###Show how bluemix works for build, test and deplyment

Screencast of demo -> Vamshi

show how auto-scaling parameters are set

###Pros and Cons and ppt -> Vamshi,Rishi

jenkins CI vs Bluemix CI



