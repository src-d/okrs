# OKRs 2018 Q3

## Bring 'Code as Data' to market with enterprises

### gitbase & engine

- [ ] Improve gitbase performance
- [ ] Release a more stable gitbase version
    - [ ] Make regression test
- [ ] Engine using gitbase as backend
    - [ ] Change engine schema to match gitbase's
    - [ ] Replace actual JGit implementation with a query builder and calls to gitbase
- [ ] [P1] gitbase interoperability with 3rd party tools

### Babelfish

- [ ] Client/Library improvements, packaging, and stability
- [ ] Iterate the higher level UAST abstractions to fix and maintain
- [ ] C# driver
- [ ] C/C++ driver

### Gemini

- [ ] Release a new version with the integration of function similarity

## Being a better company to work at

- [ ] Conduct an engineering survey to improve development practices for Q3 and Q4
- [ ] Conduct empathy sessions for cross-team documentation validation
- [ ] Regression Test, Benchmarks and Deploy platform (CD?)
- [ ] Improve Logs, CLI, and other guides.
- [ ] Make it easy to update and maintain PGA.

## Bring 'Assisted Code Review' to developers in the open-source community

### Launch source{d} lookout alpha at GopherCon

- [ ] Release a production ready analyzer SDK
  * Build alpha/beta versions of an analyser SDK
  * Build a simple reference example of analyzer
  * Any developer is able to understand how to create a new analyzer
  * Testing an analyzer locally is easy: streamlined to 1-2 shell commands
  * Release a production ready SDK with API stability guarantees

- [ ] Release a production ready service
  * Use the lookout service internally
    - build alpha/beta versions of the service (learning from PoC)
    - automated CI/CD pipeline to staging
    - service deployed on a staging environment
    - 2 source{d} projects enable lookout from staging

  * Any OSS project on Github is able to add lookout service (through 'Github Apps' flow)
    - automated CI/CD pipeline for production environment
    - private 'status page' of the service health
    - service deployed on a production environment
    - 2 OSS projects besides source{d} enable lookout

- [ ] Release a beta of the style analyzer[s]

## Store the world's source code

### Stable fetch pipeline

- [ ] Stable and performant borges/rovers
    - [ ] Improve regression tests with more use cases
    - [ ] Keep improving go-git performance
- [ ] go-borges library, to reuse borges logic in other projects (lookout)
    - [ ] borges states diagram
    - [ ] Define a public API for that library studying actual use cases
    - [ ] Integration tests and regression tests for that library
- [ ] borges cleanup, documentation and release
    - [ ] Define documentation summary
    - [ ] Gitbook integration

### Production Kubernetes Cluster

- [ ] Release of the production cluster, and run borges, lookout, on it
- [ ] HA of databases and other persistent services.

## Advance ML-on-Code awareness

