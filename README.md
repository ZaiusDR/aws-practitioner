# AWS Cloud Practitioner

## Introduction to AWS Cloud

One of the benefits of using a Cloud platform, is that is easy to scale using the Cloud
interfaces. On a traditional infrastructure, it's harder to correctly dimension the resources
needed for a customer platform. Usually driven into low (and not easy to scale) or over
dimensioned infrastructure, incurring in an excess of costs.

It's possible to reduce risks, auto-scale, access resources such as servers, dbs, etc... and
consider them as temporary and secure data.

AWS provide a way to scale the resources at the need pace, so it's possible to be Agile on
infrastructure requirement changes.

Agility is based on:
* Increased speed.
* Favour experiments.
* Cultivate a culture of innovation.

Since AWS has infrastructure all over the world, is easy to provide services to customers
in any place.

With Cloudformation, it's possible to define stacks for different environments using it's DSL.

Also it's easy to have a reliable infrastructure, since AWS provides ways to detect errors
and self healing infrastructure. This is in part achieved thanks to the AWS regions and 
availability zones with redundant, current, network, etc... which are physically independent 
infrastructure locations, providing fault tolerance and high availability.

Regarding Security, the customers are owners of their data, how encryption is handled. It's
possible to spy on resources and respond to any unexpected changes. AWS Takes care of the security
of their physical resources, with video vigilance, control access, etc... So there is a mixed
security responsibility between AWS and its customers.


## Introduction to AWS Interfaces

### AWS Management Console

Easy-to-use GUI that supports majority of AWS. There is a mobile App as well. Supports
having access to billing, setup users and permissions, etc... It's possible to create
shortcuts using the "pin" functionality. You can also create Resource Groups in the
AWS Systems Manager to have an overview of the resources of one or several types or filtering
by Tags. They are personal and shareable to other users on the same account using a URL.

There is a section called "Build a solution" with typical setups which can be used as a
base for the needed infrastructure using wizards.

There is also a lot of material to learn how to build infrastructure through courses and
tutorials called "Learn to build".

### Command Line Interface

Access to service via discrete command. It's useful to automate tasks in a programming
language agnostic way.

### SDKs

Incorporate the connectivity and functionality of the wide range of AWS Services into
your code. This provides a high customization of AWS features and task automation.