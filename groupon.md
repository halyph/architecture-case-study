## Groupon

### References
 
 - [I-Tier: Dismantling the Monolith](https://engineering.groupon.com/2013/misc/i-tier-dismantling-the-monoliths/) actual case study of migration



### Case Study

We recently completed a year-long project to migrate Groupon’s U.S. web traffic from a **monolithic Ruby on Rails** application to a new **Node.js** stack with substantial results.

#### The original Rails architecture
![](images/groupon/arch.png)

#### Extended Architecture
![](images/groupon/arch2.png)

#### Going Global
![](images/groupon/arch3b.png)

#### Mobile
![](images/groupon/arch4.png)

### Split each major feature of the website into a separate web application
![](images/groupon/arch52.png)

### Routing layer
![](images/groupon/arch6.png)

### Single federated API layer that serves both our web and mobile apps
![](images/groupon/arch7a.png)

### Still need to support two backends
![](images/groupon/arch9b.png)
