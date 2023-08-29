---
permalink: /services/
title: "Services"
toc: true
---

Grimes IT provides technical services to grow web-based businesses.

## Full-stack web development

Grimes IT develops web applications. 
Converting ideas into products through code,
creating something from nothing in a sense. 
That's the main value proposition.

So what is the "full stack"?
Think of a web app as being stacked together
like bricks or a card deck, 
from a variety of technology choices.
A full-stack developer can work on all the technologies up and down the stack.

A web application stack generally includes user interfaces, data, business logic, and APIs.

### User interfaces

In modern web development, user interface often means **JavaScript**.

I use client-side JavaScript frameworks like React, Vue, and Angular to provide rich user experiences.
Additional "batteries included" frameworks like NextJS (for React) and NuxtJS (for Vue) can be helpful to add some server-side magic, and to simplify best practice and architecture decisions. 

Some cases still call for old school SSR (server-side rendered) PHP applications.
I've built a generation of PHP apps with a variety of architectures, including full-stack frameworks like Symfony, Zend/Laminas, and Laravel; microframeworks like Slim and Silex; home-grown frameworks; and third-party ecosystems like Wordpress and Moodle.

Regardless of the underlying architecture, good user interfaces need good designers,
who are often outside specialists unfamiliar with the application's underlying technology.
It should be as convenient as possible for outside designers to contribute to the user interface.

### Databases

Data is the molten core of a web business, and it needs to be stored and used in a secure and efficient way.

An RDBMS like Postgres or MySQL is often a good choice for the core data store,
though NoSQL options like MongoDB can have their place.
I spent many years pushing MySQL and Postgres to their early limits to scale web apps.
I like common ORM libraries for basic database interactions,
and I'm experienced using complex (yet performant) SQL to work with the more interesting cross-sections of data.

Atop the core business data, many other technologies can be stacked in various combinations,
to leverage or compile data for a variety of specialized purposes.
Some common ones I've used include Redis, Elasticsearch, Memcache, OpenAI, etc.

### Business logic and APIs

Business logic is often distributed across a variety of applications and third-party services,
which all need to be integrated.

Often fundamental business logic is embedded in an original web application,
and it needs to be extracted in order to be more easily shared, tested, and refined.
This means APIs.

REST has become one of the most common API architectures, and I've built and consumed many REST APIs over the years.
I also like GraphQL for solving some of the shortcomings of resource-based APIs.

## Web infrastructure

From bare metal to cloud, servers to VMs, containers to serverless, I've been scaling real-world web applications for decades. Before that, I was a network engineer in Silicon Valley. I know the web all the way down to TCP/IP.

### Development environments

I run all my development environments in Docker containers now,
so I can install whatever mad dependency a project might need without messing up my own computer.
Containers are also useful because they can closely reproduce entire production environments
(databases, caches, cloud services, and all)
and even simplify deployment, infrastructure, and operations.

Visual Studio Code and Docker Desktop make it easy to do development this way.

For new projects and quick changes, GitHub Codespaces can be an easy way to get a simple dev environment up and running, and to make quick changes on the fly, without having to hassle with creating a local dev environment first.

### Production infrastructure

Production infrastructure for web apps is sold in a range of service levels, 
where the general idea is the more it costs, the less work you have to do yourself,
and vice versa.
Every business has to find its own sweet spot for its own needs and budget.

For new or experimental applications, full-featured **managed platform** providers like Vercel, Heroku, or Digital Ocean can be useful.
But they tend to become overly expensive beyond early stages.

**Managed service** providers can make sense for specialized management of particularly complex or important parts of the stack, like databases. But beware of vendor lock-in.

For everything else, **infrastructure services** like AWS tend to be the most practical and economical choice.
Consider that most managed service providers are probably using AWS or something comparable themselves,
so you'll pay them whatever you'd pay AWS anyway,
plus the additional markup for their services.
Some will be worth it. Some will not.

**Bare metal** servers can still be run in this day and age,
especially if you enjoy that sort of thing. 
But for me bare metal is
only worth the trouble when an application's resource usage doesn't match the horizontally scalable models of the cloud providers.

### Deployment and dev-ops

Deploying a change from development to production should be easy and safe.
Pre-release testing and post-release monitoring are two sides of the same coin,
and both should happen automatically.

I like GitHub Actions for automating deployment workflows
and I've used a variety of build environments and CI/CD toolchains.

## Modernizing legacy applications

### Upgrading ancient LAMP stacks

According to [2023 surveys by W3Techs](https://w3techs.com/technologies/details/pl-php),
around 75% of websites use PHP,
and around 20% of those are still running PHP 5.

PHP 5 has long been officially dead ("end of life"), 
and is well known to be at least *twice as slow* as newer versions.
Sites don't stay on PHP 5 because they like it. 
Upgrading a core technology like PHP, MySQL, or Linux, 
which has been running a real business for a long time,
can be extremely challenging without causing major disruptions. 

But it can be done. It takes a well-thought-out migration plan, 
practical testing and monitoring, mentorship and training, and some patience.

### Getting the legacy codebase unstuck

A poorly documented legacy codebase is best approached by creating some good documentation.
That lets everyone reach the same understanding about important parts of the application and the business,
and it delivers a valuable artifact to the client early in a project.

Since legacy codebases can be fragile and risky to change,
basic testing and monitoring can make changes safer,
detecting problems before or after deployment,
and making it easy to revert if needed.

With the legacy codebase documented and changeable,
it becomes practical to decide what changes should be made to improve it, and where it should reside in the overall architecture.

To keep the legacy application intact while making improvements, it becomes necessary to split the architecture somehow, to allow simultaneous work on both the old and new. The ["Strangler Fig" design pattern](https://martinfowler.com/bliki/StranglerFigApplication.html) is a common way to think about it.

Code review and training keeps the legacy codebase gradually improving, along with the team that maintains it.
Grimes IT can provide code review as a service or dedicated training sessions.

### Integrating new technologies

Having an established legacy application doesn't have to stop you from having shiny new applications, too.

To integrate new technologies, while keeping all the useful features of legacy services, 
it can be useful to encapsulate the legacy system into a "black box" with a convenient API,
to abstract away the internal complexity of the legacy codebase.

The legacy API can then be exposed using a variety of transports and architectures (HTTP, Websockets, REST, GraphQL, etc.), as newer technologies require.

## Contact

Does your business need help with something like this? [Contact me.](/contact/)