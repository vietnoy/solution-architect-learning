# Solution Architect Learning

A living knowledge base for learning system design and solution architecture from first principles.

## Goal

Build broad, practical foundations across computing, networking, backend systems, data systems, distributed systems, cloud, DevOps, security, observability, reliability, cost, and system design.

## Learning loop

1. Learn the concept.
2. Explain it back in your own words.
3. Correct the mental model.
4. Build a small implementation.
5. Break it intentionally.
6. Redesign it.
7. Record the final notes here.

## Curriculum

### 01 — Computing fundamentals
- [x] Client and server
- [x] Program vs process
- [x] CPU, RAM, and persistent storage
- [x] IP, port, HTTP, and DNS overview
- [ ] Threads and concurrency
- [ ] Filesystems and processes in more depth

### 02 — Networking
- [ ] IPv4
- [ ] Private vs public IP
- [ ] localhost and 0.0.0.0
- [ ] CIDR
- [ ] Subnets
- [ ] Routing
- [ ] Firewalls
- [ ] NAT
- [ ] DNS
- [ ] Load balancing
- [ ] VPN
- [ ] VPC peering
- [ ] PrivateLink / Private Service Connect

### 03 — Backend systems
- [ ] HTTP in depth
- [ ] REST APIs
- [ ] Stateless services
- [ ] Authentication and authorization
- [ ] Sessions and JWT
- [ ] Webhooks
- [ ] Caching
- [ ] Rate limiting
- [ ] Connection pooling

### 04 — Data systems
- [ ] Relational databases
- [ ] Document databases
- [ ] Key-value stores
- [ ] Object storage
- [ ] OLTP vs OLAP
- [ ] Warehouses and lakehouses

### 05 — Distributed systems
- [ ] Synchronous vs asynchronous
- [ ] Queues, topics, and events
- [ ] Retries and backoff
- [ ] Idempotency
- [ ] Ordering
- [ ] Dead-letter queues
- [ ] Transactions
- [ ] Race conditions
- [ ] Consistency and replication
- [ ] Backpressure

### 06 — Cloud
- [ ] Compute
- [ ] Storage
- [ ] Databases
- [ ] IAM
- [ ] Managed services
- [ ] GCP resource hierarchy
- [ ] Multi-project architecture

### 07 — DevOps
- [ ] Git
- [ ] Docker
- [ ] Artifact registries
- [ ] CI/CD
- [ ] Terraform
- [ ] Environments
- [ ] Deployment and rollback strategies

### 08 — Security
- [ ] IAM and least privilege
- [ ] OAuth / OIDC
- [ ] TLS
- [ ] Secrets
- [ ] KMS
- [ ] Trust boundaries
- [ ] Audit logs

### 09 — Observability
- [ ] Logs
- [ ] Metrics
- [ ] Traces
- [ ] Alerting
- [ ] SLI / SLO / SLA

### 10 — Reliability
- [ ] High availability
- [ ] Backups
- [ ] PITR
- [ ] RPO / RTO
- [ ] Failover
- [ ] Disaster recovery

### 11 — Cost and scaling
- [ ] Vertical vs horizontal scaling
- [ ] Bottlenecks
- [ ] Cost drivers
- [ ] Capacity estimation

### 12 — System design
- [ ] Requirements
- [ ] Assumptions
- [ ] Capacity estimates
- [ ] Architecture diagrams
- [ ] Security model
- [ ] Failure handling
- [ ] Cost model
- [ ] Alternatives and trade-offs

## Start here

- [Computing Fundamentals — Client, Server, Process, CPU, Memory, Storage](01-computing-fundamentals/01-client-server-processes.md)

## Standard topic template

Each topic should answer:

- What is it?
- Why does it exist?
- How does it work?
- What are the important components?
- When should I use it?
- When should I not use it?
- What can fail?
- How is it secured?
- What does it cost?
- How does it connect to the rest of the system?
