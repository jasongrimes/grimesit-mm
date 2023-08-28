---
permalink: /services/
title: "Services"
toc: true
---

Grimes IT provides technical services to help web-based businesses grow.

## Full-stack web development

It can be useful to think of web applications as being composed of user interfaces, data, and business logic. 

### User interfaces

In modern web development, user interface often means **JavaScript**.

I use client-side JavaScript frameworks like React, Vue, and Angular to provide rich user experiences.
Additional "batteries included" frameworks like NextJS (for React) and NuxtJS (for Vue) can be helpful to add some server-side magic, and to simplify best practice and architecture decisions. 

For some user interfaces, a server-side rendered (SSR) HTML page is more suitable. I've done this with many PHP applications, including full-stack frameworks like Symfony, Zend/Laminas, and Laravel, microframeworks, home-grown frameworks, and third-party software like Wordpress and Moodle.

### Databases

Data is the molten core of a web business, and it needs to be stored and used in a secure and efficient way.
An RDBMS like Postgres or MySQL is often a good choice for the core databases,
though a NoSQL store like MongoDB can have its place.
I use other data technologies as needed for specialized purposes, like Redis, Elasticsearch, Memcache, and OpenAI.

### Business logic and APIs

Business logic is often distributed across a variety of applications and third-party services,
which all need to be integrated through various APIs.

REST is one of the most common API architectures, and I've built and consumed many REST APIs over the years.
More recently, I like GraphQL for solving some of the shortcomings of resource-based APIs.

## Web infrastructure

From bare metal to the cloud, servers to VMs, and containers to serverless, I've been scaling real-world web applications for decades. Before that, I was a network engineer in Silicon Valley. I know TCP/IP.

### Development environments

I run all my development environments in Docker containers.
That way I can closely reproduce production environments,
isolate my own computer from volatile development changes,
and take advantage of portable containerized environments.

Visual Studio Code and Docker Desktop make it easy to do development this way.

### Production infrastructure

The production infrastructure needeed for running a web application can be purchased on a scale roughly from "most expensive, least effort" to "least expense, most effort". 

For new or experimental applications, full-featured managed **platform** services like Vercel, Heroku, or Digital Ocean can be useful.
But they tend to become overly expensive beyond early stages.

**Managed services** can make sense for specialized management of particularly complex or important parts of the stack like databases. 

For everything else, **infrastructure services** like AWS tend to be the most practical and economical choice.

**Bare metal** servers can still be run in this day and age,
but it's only worth the trouble when an application's resource usage doesn't match the horizontally scalable models of the cloud providers.

### Deployment and dev-ops



<!-- 
![full](/assets/images/legacy-feature.png){: .full} -->

## Modernizing legacy applications

<!-- {% include feature_row id="service_legacy" type="right" %} -->

### Upgrading ancient LAMP stacks

Over 75% of websites use PHP, according to [surveys by W3Techs](https://w3techs.com/technologies/details/pl-php),
and 20% of those are still running PHP 5 (which is end-of-life and no longer receiving security updates).

Hard-earned experience has taught that sites don't stay on PHP 5 because they like it. 
It can be extremely challenging to upgrade an established legacy site to modern versions of PHP without disrupting the existing application--but it can be done. It takes a well-thought-out migration plan, 
practical automated testing, mentorship and training, and some patience.

### Getting the legacy codebase unstuck

Documentation.
Testing and monitoring.
Split architecture: the Strangler Fig pattern.
Encapsulation and API
Mentorship and training

### Enable and integrate new technologies



