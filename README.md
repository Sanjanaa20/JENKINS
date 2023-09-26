# JENKINS
Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration, and continuous delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat. 

## History
Jenkins is the father of DevOps developed in 2005 by sun microsystem bought by Oracle in 2010. Jenkins was called as Hudson in the past.
### Features
- Open source, Integration tool
- Written in java
- server based system running in a servlet container such as Apache Tomcat.
##### Why Jenkins?
- Highly configurable system by itself and known for its flexibility.
##### Uses
- Generate test reports 
- Integrate with many different version control systems.
- Notify stakeholders with build status and deploys directly to production or test environments.

#### Installation 
Default installation in /var/lib/jenkins and to login get the password by /secrets/initialAdminPassword to unlock within the browser. Then install the add on Extensions to use the plugins.

#### Procedure 
1. After creating ==> freestyle project.
2. Go to build ==> execute shell , command , build and save.

| S | Weather | Name | Last success | Last failure | Duration |
| :---         |     :---:      |          ---: | ---: | ---:| ---:|
| ✔ |☀︎ |Sanju |3.6 seconds | | Run
| ✔| ☀︎|Krish |4.2 seconds | | Run

Top five run rate indicates the weather like S F F S S ==> indicates 60% success 3/5

## Queuing of Job : Creating job by sequence 
1. Upstream 
2. Downstream 

Dev→Test→Prod where - Dev's downstream is test and Test downstream is prod and upstream is Dev etc depending upon jobs created by users or root.

### Triggers
All trigger are executable manually where it means by running of execution.
- Automatic trigger
1. Periodic trigger : build using cron job by scheduling the time.
2. Remote trigger: building trigger remotely by using authentication token.




