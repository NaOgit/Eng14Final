# Eng14Final

## Mongo Replica-set
Our 2 tier architecture currently has a serious Single Point of Failure; the database tier.
We currently only run a single instance in a single availability zone. If this were to fail we would not only have down time but we would also have a serious loss of data.
Investigate how to create a replica set using mongo that allows three machines to replicate data and balance the load across three availability zones.

## Multi AZ Project
Using Terraform and AWS create a load balanced and autoscaled 2 tier architecture for the node example application.
The Architecture should be a "Highly Available" application. Meaning that it has redundancies across all three availabililty zones.
The application should connect to a single database instance.

## ELK STACK
Immutable architectures are notoriously difficult to debug because we no longer have access to the instances and thus do not have access to the logs for those machines.
Log consolidation allows us to have logs files broadcast to a central repository by the instances themselves which allows us to more easily view them.
The ELK stack is a commonly used system for this purpose.
Research the setup of the elk stack and create a cookbook for provisioning the required machines.
