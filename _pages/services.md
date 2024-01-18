---
permalink: /services/
title: "Services"
toc: true
toc_sticky: true
author_profile: true
---

Grimes IT provides technical services to solve business problems.

## Full stack web development

![full](/assets/images/feature-development.webp){: .full}

Grimes IT specializes in building custom web applications---software applications that run on the World Wide Web.

Full stack development is more than a buzzword. It means supporting every technology layer used by the application,
including user interfaces, databases, business logic, server-side APIs, infrastructure, development and deployment.

### User interfaces

In modern web development, user interface often means **JavaScript**.

I use modern JavaScript frameworks to provide rich user experiences and rapid backend development,
along with Go as needed for high performance backend services,
and old-school server-side workhorses like PHP and Ruby for tried-and-true applications.

I enjoy working with modern technologies, but I'm not too cool to roll up my sleeves and dig into old PHP codebases and third-party ecosystems like WordPress.

A good user interface needs a good designer,
and I know more than a few,
but I'm also experienced at working productively with unfamiliar outside teams.

### Databases

Data is the core of a web business, and it needs to be stored and used in a practical, secure and efficient way.

Relational data stores like Postgres and MySQL are often a good choice for the core databases.
NoSQL options like MongoDB and Redis also have their place.
I spent many years pushing MySQL and Postgres to their early limits to scale growing web applications.
ORM libraries can be great for basic database interactions,
but I'm well-experienced with complex and performant SQL for making the most of valuable business data.

### Business logic and APIs

Business logic tends to be distributed across a variety of applications and third-party services,
and they all need to be integrated to some degree.

Often fundamental business logic is embedded in older systems,
and needs to be leveraged by newer applications.
This typically means APIs.

I have many years of experience building and consuming RESTful API architectures,
and GraphQL and RPC have also proven valuable for working around some of the shortcomings of resource-based APIs.

## Web infrastructure

![full](/assets/images/feature-infrastructure.webp){: .full}

From bare metal to cloud,
from server to VM to container to serverless, I've scaled real-world systems for decades.
Before that, I was a network engineer in Silicon Valley.
For me, the "full stack" includes the network protocols.

### Development environments

I like to run development environments in Docker containers now,
so developers can install whatever mad dependency a project might require without messing up their own computers.
Containers allow developers to closely reproduce entire production environments
(databases, caches, cloud services, and all)
and can simplify deployment, infrastructure, and operations.

Tools like VSCode and Docker Desktop have made it vastly easier to do development in this way.

For new projects and quick changes, web-based development environments like GitHub Codespaces, StackBlitz, and CodeSandbox can be an easy way for developers to get up and running almost instantly and to make quick changes on the fly.

### Production infrastructure

Production infrastructure for web apps is sold á la carte in a range of service levels, with
the general idea being the more it costs, the less work you have to do yourself,
and vice versa.
Every business has to find its own sweet spot for its own needs and budget.

For new or experimental applications, full-featured managed platform providers like Vercel, Heroku, or Digital Ocean can be useful.
But they tend to become overly expensive beyond early stages.

Managed service providers can be valuable for specializing in particularly complex or important parts of the stack,
like databases and network services.
Just beware of vendor lock-in.

As a business scales, infrastructure services like Amazon AWS, Microsoft Azure, and Google Cloud tend to become more economical choices.

Bare metal servers can still be run in this day and age,
and can save a business a lot of money compared to cloud infrastructure services,
if you have people who can manage them.

### Deployment and DevOps

Deploying changes from development to production should be fast, easy and safe.
Pre-release testing and post-release monitoring are two sides of the same coin,
and both should be configured to happen automatically.

I'm experienced with a variety of build environments and CI/CD toolchains.

## Modernizing legacy applications

![full](/assets/images/feature-legacy.webp){: .full}

Grimes IT respects the legacy.
Software only survives to become old and messy because it's been providing genuine value to the business for a long time.

Successful applications endure, and technical debt accumulates.

### Getting the legacy codebase unstuck

Legacy codebases are often poorly understood by the team that inherited them.
Often the best way to approach them is by creating some good documentation.
This gets everyone literally on the same page about important parts of the software and the business,
and it's a valuable work product to deliver a client early in a project.

Since legacy codebases can be fragile and risky to change,
basic testing and monitoring are needed to make changes safer,
detecting problems before and after deployment,
and making it easier to revert when needed.

When new architectures are required, it's often most practical to run them in parallel with the legacy application,
keeping them both running for as long as needed.
This requires the architecture to be split somehow,
to allow simultaneous work on both the old and new.
(The ["Strangler Fig" design pattern](https://martinfowler.com/bliki/StranglerFigApplication.html) can be a useful way to think about this challenge.)

Code review and training keeps the legacy codebase gradually improving, along with the team that maintains it.
Grimes IT provides code review as a service and customized training.

### Integrating new technologies

Having an established legacy application doesn't mean you can't have shiny new applications, too.

To integrate new technologies while keeping all the useful features of legacy services,
it can help to encapsulate the legacy system into a "black box" with convenient APIs,
to abstract away the internal complexity of the legacy codebase from other projects.

The legacy API can then be exposed using a variety of transports and architectures (HTTP, Websockets, REST, GraphQL, etc.), as newer technologies require.

### Upgrading ancient LAMP stacks

According to [2023 surveys by W3Techs](https://w3techs.com/technologies/details/pl-php),
around 75% of websites use PHP,
and around 20% of those are still running PHP 5.
PHP 5 has long been officially dead ("end of life"),
and is well known to be more than _twice as slow_ as newer versions.
Companies don't stay on PHP 5 because they like it.

Upgrading a core technology like PHP, MySQL, or Linux that has been powering a real business for a long time
can be challenging and disruptive.
But it can be done. It takes a well-thought-out migration plan,
practical testing and monitoring, mentorship and training, and a bit of patience.

## Estimate your project

Does your business need help with technical challenges like this? [Contact Grimes IT](/contact/) today to learn how we can help.
