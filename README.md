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

3.delivery pipeline. -> Nikhil

4.monitoring and analytics. ->Kaustubh

5.track & plan. -> Kaustubh

6.blaze meter. -> Kaustubh

7.load impact. -> Kaustubh

8.new relic. -> Nikhil

###Show how bluemix works for build, test and deplyment

Screencast of demo -> Vamshi

show how auto-scaling parameters are set

###Pros and Cons and ppt -> Vamshi,Rishi

jenkins CI vs Bluemix CI



