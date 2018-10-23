# OKRs 2018 Q4

## Bring 'Code as Data' to market with enterprises

### Ensure gitbase interoperability with 3rd party tools [DR]

- [ ] Drivers for in-house languages (Python, Go, Java).
- [ ] mysqldump
- [ ] grafana
- [ ] Tableau
- [ ] Drivers for other popular languages (JavaScript, Ruby, .NET, PHP).

### Get gitbase enterprise ready [DR]

- [ ] Authentication and authorization abstractions prepared for future integration with LDAP and Kerberos
- [ ] Basic MySQL auth implementation
- [ ] Audit logs (connections, queries)

### Get web interfaces enterprise ready [APPS]

- [ ] gitbase-web SSO (protocol TBD)
- [ ] bblfsh-web SSO (protocol TBD)

### Gitbase research [DR]

- [ ] Initial research on supporting updates in backing data (indexes, etc)
- [ ] Usage of caches for UAST and others, precalculated in packfiles

### Launch gitbase-spark-connector [DR]

- [ ] Launch gitbase-spark-connector community beta version.
- [ ] Launch gitbase-spark-connector enterprise beta version.

### Release necessary language support for enterprise [LA]

- [ ] C# driver
- [ ] C/C++ driver

### Get bblfsh ready for wide language support of our use cases [LA]

- Finish migration to v2 for all supported client languages (JVM, Python, Go)
- Deprecate v1
- Fix positions in all alpha+ drivers

### Have an available demo cluster [INFRA]

- [ ] Deploy a demo cluster for 'Code as Data' that we can use for demos and 3rd parties

### Define a delivery strategy for the enterprise

- [ ] Test deployment for faux-customer [INFRA][ENG]

### Get Gemini production ready [APPS]

- [ ] Release a new version with the integration of function similarity

## Improve the 'Code as Data' individual user experience

- [ ] Move engine maintainership to apps, review code [APPS]

## Improve quality across all products [INFRA][DR]

- [ ] Regression test platform [INFRA]
- [ ] Automated regression tests for borges [DR]
- [ ] Automated regression tests for gitbase [DR]
- [ ] Conduct two empathy sessions for cross-team documentation and user experience improvements [ENG][QA]

## Release a new version of PGA [INFRA][APPS]

- [ ] Incremental PGA updates [APPS]
- [ ] Automate PGA generation [APPS][INFRA]
- [ ] Release PGA v2 [APPS]

## Bring 'Assisted Code Review' to developers in the open-source community

### Get lookout production ready [APPS]

- [ ] Extend lookout end user documentation in gitbook
- [ ] Extend lookout developer documentation in gitbook
- [ ] Stable Python SDK (training-aware? DD)
- [ ] Stable Go SDK (training-aware? DD)

### Release a production ready service

#### Release style analyzers [ML]

- [ ] Launch beta formatting analyzer
- [ ] Launch beta typos analyzer
- [ ] Add Java or Go formatting support
- [ ] Collect the structured diff dataset
- [ ] Best practices analyzer PoC
- [ ] Finalize id2vec
- [ ] Deployment to Google Cloud [INFRA]
- [ ] Setup monitoring [INFRA]

#### Any OSS project on Github is able to add lookout service (through 'Github Apps' flow) [APPS]

- [ ] Private 'status page' of the service health
- [ ] Automated CI/CD pipeline for production environment
- [ ] Service deployed on a production environment
- [ ] 2 OSS projects besides source{d} enable lookout

## Store the world's source code

### Improve borges archiving performance [DR]

- [ ] Improve borges archiving average throughput by 5x

### Refactor to go-borges library, to reuse borges logic in other projects (i.e. Lookout) [DR]

- [ ] Define a public API for that library studying actual use cases

### Release the production kubernetes cluster [INFRA]

- [ ] Release of the production cluster
- [ ] Run rovers and borges on it
- [ ] Deploy services with HA: PostgreSQL, RabbitMQ, etcd
- [ ] Add monitoring to the pipeline (rovers, borges and associated services)
- [ ] Migrate staging cluster to the new deployment method

## Improve local-gpu cluster usability [INFRA]

- [ ] Improve local-gpu usability for the ML team so that it can be adopted as the main ML platform instead of science-3

## Being a better company to work at

### Successfully hire for each open role

- [ ] Hire a Lead engineer for the Applications team 
- [ ] Hire a Senior test engineer 
- [ ] Hire two interns in Q4 for Q1-2 for ML team
- [ ] Attract relevant profiles through our community

### Scale the hiring process

- [ ] Use of scheduling tools for efficient communication by all interviewers
- [ ] Each team responsible for candidates in last steps when the Talent Manager is unavailable 

### Increase candidate’s motivation and engagement at every interviewing step

- [ ] Applicants reviewing time fall to 5 days in average 
- [ ] Analyse candidate's survey answers to identify bottlenecks in the process 
