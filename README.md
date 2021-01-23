# Backend (and some general) development topics

At the start, I tried to order things with a mix of complexity and importance, so somethings that might be more complex, might end up first on the list than simpler ones that I feel maybe less usual. Also, as time goes by, I can't guarantee the order will always be kept 😛.

My idea, besides just listing topics, is to eventually add some references for each in a sub-page.

It is also very dependent on tastes and choices, as not everyone will know everything, maybe focusing on some more specific stuff.

**Note:** keep in mind, this is based on my experience and the things I did/do. E.g. one topic I mention is working with containers, but maybe one wants to work on creating what supports containers - that’s more low level stuff I don’t know a lot about 🙂.

Also, this doesn't mean one should know all of it, maybe some things aren't needed in depth, but only knowing the concept and taking it into account when making decisions is useful (I for one don't know all of these things 😛).

## Topics

### "Basics"

Before all the other stuff, maybe just some "basics", or maybe just take them as general development advice:

- Try to become proficient in your stack of choice, but keep an open mind for other things
- Fundamental data types and their differences (array, list, map, hashset, …)
- It doesn’t hurt to have some clues on what’s going on in the frontend 😛
- Source control (mainly GIT)
- Know that there are different kinds of languages which may be better or worse depending on scenarios - people on the internet saying their language is better… meh!
- Try to follow your language’s idiomatic way of doing stuff
  - If a primarily object oriented language, actually write object oriented code
  - Functional language? Same idea
  - Mix and match where appropriate - e.g. C# is primarily an object oriented language, but also allows for some more functional constructs, which in some cases can give us the best of both worlds

### Big list of interesting topics

- HTTP (methods, headers, …)
- REST
- Try to make the most of the programming paradigm you use
- Know that there are different kinds of databases (Relational, document, key value, ...)
- ORMs
- Understand the different semantics of local vs remote calls
- Authentication/authorization
- Caching
- Common security threats and practices (XSS, CSRF, HSTS, CORS, ...)
- Logging
- Understanding the overall system architecture
- API authentication - e.g. OpenID Connect and OAuth 2.0
- SOLID
- Design patterns
- Dependency Injection
- TDD
- BDD
- ACID
- Continuous integration and continuous delivery
- Static code analysis tools
- Secret management (e.g. db passwords, API keys, ...)
- Async features of the language - at least the basic usage
- Have an understanding of the performance impacts - in terms of “local” code, but also when interacting with external systems (e.g. calling a service is not like calling a method)
- Feature flags/toggles
- Fallacies of distributed computing (https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
- Telemetry, tracing, observability
- Microservices
- Monoliths
- SOA
- Threading
- Concurrency
- Async features of the language - go deeper
- Communication patterns/technologies - synchronous (e.g. HTTP requests, RPC) and asynchronous (e.g. queues, event hubs)
- Idempotency
- Job scheduling
- [Synchronous interaction resiliency patterns (circuit breakers, retries, timeouts, bulkhead isolation)](/topic-resources/synchronous-interaction-resiliency-patterns.md)
- GraphQL (and probably other common REST alternatives)
- Containers
- Library packaging and sharing
- A/B testing
- Deployment
  - Blue/green deployment
  - Rolling deployment
  - Canary deployment
  - Others?
- DDD
- Onion architecture/ports and adapters/hexagonal architecture/clean architecture
- CQRS
- [Event sourcing](/topic-resources/event-sourcing.md)
- Actor model
- HATEOAS (part of REST, but people tend to ignore it)
- Sharding
- Load balancing
- Service discovery
- Active/passive replicas
- [CAP theorem](/topic-resources/cap-theorem.md)
- Back pressure
- Two-phase commit
- Distributed transactions
- [Saga](/topic-resources/saga.md)
- Process manager
- Be aware about what’s going on regarding garbage collection / memory management

## Curiosities for choosing languages/frameworks

- Performance - [TechEmpower Web Framework Benchmarks](https://www.techempower.com/benchmarks/)

## Random stuff

- [Falling Into The Pit of Success](https://blog.codinghorror.com/falling-into-the-pit-of-success/)
