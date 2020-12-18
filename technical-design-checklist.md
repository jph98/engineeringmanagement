## Operational 

How do we provision the infrastructure required for the service?

How do we deploy the service?

Network level deployment - cloud VPC, subnet etc...

How do we upgrade the service?

How do we handle versioning of the service in terms of the API and build?

How do we carry out configuration management (e.g. env vars or something else)?

How do we carry out configuration management for different environments?


## Structural

How do we manage dependencies of libraries, frameworks and other services?

How do we perform common build file (run, test, lint etc…) commands?

Does this service need to be included in other services?

Does the service have a repository or sit in a repository with other services?


## Data

How do we gather data from this service for reporting?

What is the data storage solution?

How do we store/query data in terms of solution?

Do we need connection pooling as part of the service? Have we considered multiple versions of the service scaling in terms of overall database capacity (connections, queries etc..)

How do we provide real-time querying/reporting without affecting transactional throughput?


## Monitoring

How do we monitor the service (up/down check, downtime)?

How do we monitor system events (e.g. throughput)

How do we monitor performance (e.g. latency)

How do we debug the service when failures occur?


## Communication

How do we handle synchronous messaging with other systems/services (via REST or other)?

How do we handle asynchronous messaging to other systems?

How do we orchestrate workflows involving multiple services (including downstream services)?

How do we expose an API for the service?

How do we document the API for the service?

Does this service need to be consumed by others or expose a web/mobile interface?


## Quality Management

How do we provide a continuous integration (deployment, run tests, report failures) for the service?

How do we perform local error checking (linting, common formatting, error checking) prior to repository check-in?


## Testing

How do we perform unit testing?

How do we perform integration testing?

How do we perform acceptance testing?

How do we run tests involving dependent services?


## Security

How do we audit events that occur within the system?

How do we handle authentication of the service (API endpoints or other)

What kind of networking level security needs to be in place?

How do we handle Authorisation within the service (API endpoints or other)


## Reliability

How do we handle failures within the service?

How do we handle failures for downstream services (as part of a workflow?)


## Performance

What are the latency requirements for the service in terms of response time?

How do we handle rate limiting if required for the service to prevent system outages?

How do we scale the service out? Vertical or horizontal scaling?

How many users do we need to support with the service?
