### [◀](/SOSC-2018)

# Container orchestration with Mesos and Marathon

We are going to deploy a cluster of vms on cloud resources and to automatically configure a cluster resource manager (Mesos) that can be used by Marathon that is a container orchestrator using Mesos to manage the resource assignment for every container it has to deploy. 

__N.B. This setup is the base for the next Hands-on session, and will also deploy additional software on top of Mesos+Marathon__

## Mesos and Marathon deployment with PaaS Orchestrator

Proceed as in the previous exercise with PaaS Orchestrator, but passing a different template in order to automatically setup a cluster capable of orchestrate docker containers with Marathon:

``` bash
orchent depcreate  templates/hands-on-1/Marathon-Part1.yaml '{}'
```

### Exercise: deploy a webserver with Marathon


