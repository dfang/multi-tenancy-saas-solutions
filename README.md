# Multi-Tenant Saas Solutions

记录下最近的研究下的multi-tenancy saas方案.

## What is multi-tenancy ?
Multi-tenancy is a single instance of software that serves multiple customers privately.

## Examples of multi-tenancy apps:
Slack, Salesforce, G Suite, Heroku

## Why would you use multi-tenancy ?

* Cost-savings
* Single Deployment point
* Easier maintenance

## Database Strategies

* Solution 1: One Database per tenant
* Solution 2: One Schema in a db for per tenant
* Solution 3: Shared tables architecture(tenant_id or organization_id)

[Building Multi-Tenant Applications - Speaker Deck](https://speakerdeck.com/tomschlick/building-multi-tenant-applications)

K8S Multi-Tenancy 

[GitHub - kubernetes-sigs/multi-tenancy: A working place for multi-tenancy related proposals and prototypes.](https://github.com/kubernetes-sigs/multi-tenancy)

[k8s multi-tenancy proposals and design docs](https://github.com/kubernetes-sigs/multi-tenancy/blob/master/docs/links.md)


[**Multi-tenant SaaS database tenancy patterns**](https://docs.microsoft.com/en-us/azure/sql-database/saas-tenancy-app-design-patterns)
[Database Multi-Tenancy in the Cloud & Beyond Best Practices - MemSQL Blog](https://www.memsql.com/blog/database-multi-tenancy-in-the-cloud-and-beyond/)


[multi-tenancy-in-kubernetes-sharing-a-cluster-with-hundreds-of-users from hasura cto shahidhk](https://speakerdeck.com/shahidhk/multi-tenancy-in-kubernetes-sharing-a-cluster-with-hundreds-of-users) 


### Multi-Tenancy In Rails

原理是通过增加一个外键字段 tenant_id 或者 customer_id 来区分租户

[https://github.com/citusdata/activerecord-multi-tenant](https://github.com/citusdata/activerecord-multi-tenant) 
[https://www.citusdata.com/blog/2017/01/05/easily-scale-out-multi-tenant-apps/](https://www.citusdata.com/blog/2017/01/05/easily-scale-out-multi-tenant-apps/) 
[https://www.allerin.com/blog/multi-tenancy-in-rails](https://www.allerin.com/blog/multi-tenancy-in-rails) 
[GitHub - influitive/apartment: Database multi-tenancy for Rack (and Rails) applications](https://github.com/influitive/apartment)


### Multi-Tenancy with spring-boot
[Multi-Tenancy with Spring Boot - Speaker Deck](https://speakerdeck.com/stormpath/multi-tenancy-with-spring-boot)
