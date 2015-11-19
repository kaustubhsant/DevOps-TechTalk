# DevOps-TechTalk

#Tool
##IBM Bluemix

## TODO
###Show all servies bluemix provides

Assigned: Kaustubh Sant

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

4.monitoring and analytics. ->Kaustubh

5.track & plan. -> Kaustubh

6.blaze meter. -> Kaustubh

7.load impact. -> Kaustubh

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



