build-lists: true
theme: Letters from Sweden, 3

[.footer: #### Igor Karpovich]

## Go, Swarm and DevOps
### vs
## The Mighty Monolith

---

![](servers.jpg)

# 2013:

- Secure in-house infrastructure
- Cloud for customer facing products
- Monitoring by looking into server rooms
- Log analysis by *grep*
- Jenkins for tests, *manual* deployments
- 4 products

---

# 2018

- Multi cluster AWS environment
- Container orchestration for *all* products
- Logging, monitoring, tracing
- CI/CD for products and infrastructure
- 50+ products

---

![](enterprise.jpg)

# It's been a long road...

- Culture
- Architecture
- Platform
- Legacy

<!--
Deployments were automated by the beginning of 2015.
First microservice launched in July 2015.
Docker for CI launched in March 2016.


Full timeline:
Core product started October 2009
--- First micro service started July 2015
Swarm 1.0 November 3 2015
Helm February 23 2016
—- Docker launched for CI March 2016
K8s 1.2 March 16 2016
—- legacy swarm live June 2016
K8s 1.3 July 1 2016
Minikube July 11 2016
Swarm Mode July 28 2016
Kops September 8 2016
K8s 1.4 September 26 2016
—- swarm live December 2016
​
-->

---

![](swarm.jpg)

# Swarm?

Out of the box (*2016*):

- Service discovery
- Networking, i.e. mesh routing
- Volumes (EBS/EFS in AWS)
- Orchestration with Compose
- Quick start, less maintenance

Missing:
- Scheduler
- Job runner
- Configs, secrets (*2016*)

---

![right](goblin.png)

# Goblin

## Microservice framework
