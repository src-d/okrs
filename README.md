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
   * [P0] function-level hashing runs on a single machine
   * [P0] function-level hashing runs on Apache Spark cluster & fraction of PGA
   * [P1] function-level hashing runs on Apache Spark cluster & full PGA

## Being a better company to work at

- [ ] Setup the ML cluster environment
- [ ] Conduct an engineering survey to improve development practices for Q3 and Q4
- [ ] Conduct empathy sessions for cross-team documentation validation
- [ ] Regression Test, Benchmarks and Deploy platform (CD?)
    - For which projects? Are any of ML included? - Vadim
- [ ] Improve Logs, CLI, and other guides.
    - Logs for Go or for Python too? CLI guide - do we have one?
- [ ] Make it easy to update and maintain PGA.
- [ ] Conduct a happiness survey and react to the unveiled issues
- [ ] Improve the formal process of speaking at a conference
    - We have nothing currently. Even a simple checklist would save us much time and nerves, especially to poor Esther who really struggled with my conferencing season. It starts with notifying her once the approval registered in src-d/conferences and ends with submitting the expenses report. It also includes what to check in the booking confirmation because I had to buy tickets at the airport one hour before the flight two times already and that sucked very much. It also includes the Visa knowledge database, e.g. British visas are tricky.
- [ ] Increase the transparency of the events happening at source{d}
    - Rationale: there are meetups, get togethers, holidays, beaconfellows, etc. at source{d} Many, MANY times people missed them in the calendar. Even if there are calendar records, it is so easy to forget about them. How about creating a Slack bot which will post event notifications a few (1) days before?
- [ ] Resolve the wifi connectivity problems in Madrid office
    - I walk with my laptop from the kitchen to my work place and it just hangs. It is not only because of Ubuntu :trollface: Anna and Esther confessed that they had the same problems. And of course MEETING ROOMS CONNECTION QUALITY ISSUES.

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

### Code review study across GitHub

- [ ] Conduct the study how people do code reviews on GitHub
    - We need the numbers. E.g. what is the ratio of stupid style fixes compared to the overall? Clever fixes?

### ML approach to source code style check

- [ ] General code style rules mining under AST
- [ ] General code style rules mining over AST
    - What does this mean? Read https://github.com/src-d/minutes/blob/673545e3c9d2bc12a2f112f725cccec6d8054ff4/machine-learning/2018-06-22-Lookout-discussion.md
- [ ] Naming style suggestion
- [ ] Bad names detection
- [ ] Typos correction in names
- [ ] One-line best practices mining

### ML support objectives

- [ ] Maintain the sourced-ml stack
- [ ] Incorporate the identifier splitter inside sourced-ml extraction pipeline
    - Yes, Máximo, it is really needed for the upstream tasks suchs as typos, naming style and bad names detection
- [ ] Internal ML research meetups once per month

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

- Is it supposed to be MLonCode instead of ML-on-Code? - Vadim

### ML team activities

- [ ] Speak on two conferences
    - This is an "ambitious goal" because ML team would like to focus on the intelligent code review. The one conference being ML4P in mid-July.
- [ ] Write 5 ML blog posts
    - Ambitious!
- [ ] Let's not forget about our MSR interviews - Francesc & Victor
- [ ] Help the community with MLonCode
    - E.g. https://src-d.slack.com/services/BBACXFVD1
- [ ] Support awesome-mloncode
