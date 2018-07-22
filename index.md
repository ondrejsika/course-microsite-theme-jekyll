---
layout: default
---

{% capture actual_courses %}
## Actual courses

{% include table.html table=site.data.actual_courses %}
{% endcapture %}
{% include section.html content=actual_courses %}



{% capture about %}
## About Docker

Docker is container platfor which provide strictly defined and separated enviroment for run your application. Docker has many advantages, you have full control of environment of every part of your application. You can use somewhere Debian, otherwhere Cent OS, and host it on one server. Docker also provide security level to separate every application from one large system to many microservices on one host. Containers will se just what you grant them.
{% endcapture %}
{% include section.html content=about %}

{% capture clients %}
## My Clients

{% include clients-logos.html clients=site.data.clients_logos %}
{% include clients-recommendations.html recommendations=site.data.clients_recommendations %}
{% endcapture %}
{% include section.html content=clients %}

{% capture agenda %}
## Course Agenda

- What Docker is, why use Docker and it’s advanages & disadvanages
- How to install Docker and basic terminology
- Docker registry and running containers
- Building own images
- Multi-container aplications and Docker Compose
- Docker Machine - Docker host manager
- Docker Swarm - Docker’s native cluser
- Deployment into the Swarm
- Production setting of Docker
- Container monitoring a management in production
- Basic usage in CI (Continues Itegration)
{% endcapture %}
{% include section.html content=agenda %}
