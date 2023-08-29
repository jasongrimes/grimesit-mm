---
permalink: /services/
title: "Services"
toc: true
---

Grimes IT provides technical services to grow web-based businesses.

## Full-stack web development

Grimes IT develops web applications. 
Literally creating something out of nothing, 
in a certain sense. 
That's the main value proposition.

What's the "full stack"?
Think of a web app as being "stacked together",
like bricks or cards, 
from a variety of technology choices.

### User interfaces

In modern web development, user interface often means **JavaScript**.

I use client-side JavaScript frameworks like React, Vue, and Angular to provide rich user experiences.
Additional "batteries included" frameworks like NextJS (for React) and NuxtJS (for Vue) can be helpful to add some server-side magic, and to simplify best practice and architecture decisions. 

For some user interfaces, a server-side rendered (SSR) HTML page is more suitable. I've done this with many PHP applications, including full-stack frameworks like Symfony, Zend/Laminas, and Laravel, microframeworks, home-grown frameworks, and third-party software like Wordpress and Moodle.

### Databases

Data is the molten core of a web business, and it needs to be stored and used in a secure and efficient way.

An RDBMS like Postgres or MySQL is often a good choice for the core data store.
though a NoSQL store like MongoDB can have its place.
I spent many years pushing MySQL to its limits (and Postgres, to a lesser extent) to scale web applications.
ORM libraries are useful for the majority of basic database interactions,
Raw SQL is also needed to work with the more interesting cross-sections of data.

Many other technologies can leverage or compile the core business data for a variety of specialized purposes,
like Redis, Elasticsearch, Memcache, or OpenAI.

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

For new or experimental applications, full-featured **managed platform** providers like Vercel, Heroku, or Digital Ocean can be useful.
But they tend to become overly expensive beyond early stages.

**Managed service** providers can make sense for specialized management of particularly complex or important parts of the stack, like databases. But beware of vendor lock-in.
I know first hand how hard it is to manage production databases for a long time,
so I really appreciate how much work the managed service providers can take on, 
and why they cost so much.

For everything else, **infrastructure services** like AWS tend to be the most practical and economical choice.
Consider that most managed service providers are probably using AWS or something comparable themselves,
so you'll pay them whatever you'd pay AWS anyway,
plus the additional markup for their services.
Some are worth it,
some are not.

**Bare metal** servers can still be run in this day and age,
especially if you enjoy that sort of thing. 
But personally, I'm over it and I think bare metal is
only worth the trouble when an application's *resource usage doesn't match the horizontally scalable models* of the cloud providers.

### Deployment and dev-ops

Getting finished changes from development into production should be easy and reliable.

I like GitHub Actions for automating deployment workflows.

Pre-release testing and post-release monitoring are two sides of the same coin,
and both should happen automatically. 

## Modernizing legacy applications

### Upgrading ancient LAMP stacks

Over 75% of websites use PHP, according to [surveys by W3Techs](https://w3techs.com/technologies/details/pl-php),
and 20% of those are still running PHP 5 (which is end-of-life and no longer receiving security updates).

Hard-earned experience has taught that sites don't stay on PHP 5 because they like it. 
It can be extremely challenging to upgrade an established legacy site to modern versions of PHP without disrupting the existing application--but it can be done. It takes a well-thought-out migration plan, 
practical testing and monitoring, mentorship and training, and some patience.

### Getting the legacy codebase unstuck

- I start by documenting the existing system at a high level,
to validate my understanong and create a useful artifact right away.  .
- Gain confidence to make changes by setting up basic end-to-end testing and monitoring.
- Decide on an architectural direction. Re-invigorate, or gradually replace?
- Split the architecture, to allow simultaneous work on both the old and new. c.f. the "Strangler Fig" design pattern.
- Ongoing code review and mentorship

### Integrating new technologies

- Encapsulate the legacy system so it can be treated as a black box by new development projects.
- Create a clean and reliable API to interface with new technologies. 



