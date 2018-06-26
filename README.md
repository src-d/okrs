# OKRs 2018 Q3

## Bring 'Code as Data' to market with enterprises

### gitbase & engine

- [ ] Improve gitbase performance
- [ ] Release a more stable gitbase version
- [ ] Engine using gitbase as backend
- [ ] Change engine schema to match gitbase's
- [ ] [P1] gitbase interoperability with 3rd party tools

### Babelfish

- [ ] Client/Library improvements, packaging, and stability
- [ ] Iterate the higher level UAST abstractions to fix and maintain
- [ ] C# driver
- [ ] C/C++ driver

### Gemini

- [ ] Release a new version with the integration of function similarity

## Being a better company to work at

- [ ] Setup the ML cluster environment
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
- [ ] Release a production ready service
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

- [ ] Stable and performat borges/rovers
- [ ] go-borges library, to reuse borges logic in other projects (lookout)
- [ ] borges cleanup, documentation and release

### Production Kubernetes Cluster

- [ ] Release of the production cluster, and run borges, lookout, on it
- [ ] HA of databases and other persistent services.

## Advance ML-on-Code awareness

