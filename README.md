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

### source{d} Engine add-ons (applications) [DevRel]

#### Get Gemini enterprise ready [DevRel]

- [ ] Find a better name for Gemini
- [ ] Define messaging around gemini
- [ ] Deliver gemini product page

#### Get source{d} engine on Spark enterprise ready [DevRel]

- [ ] Find a better name
- [ ] Define messaging around Spark connector
- [ ] Deliver Spark integration product page

### Get web interfaces enterprise ready [APPS]

- [ ] gitbase-web SSO (protocol compatible with Google)
- [ ] bblfsh-web SSO (protocol compatible with Google)

### Gitbase research [DR]

- [ ] Initial research on supporting updates in backing data (indexes, etc)
- [ ] Use precomputed UASTs

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

- [x] Release a new version with the integration of function similarity

## Improve the 'Code as Data' individual user experience

- [ ] Move engine maintainership to apps, review code [APPS]

### Launch Unified Engine Playground [DevRel]

- [ ] Define Engine Playground experience (sandbox for srcd)
- [ ] Launch new Engine Playground Alpha Version
- [ ] Add metrics from playground to main dashboard
- [ ] Define main use cases and personas for the engine

### source{d} Engine awareness & use cases [DevRel]

- [ ] Define roadmap + timeline of Engine releases
- [ ] Identify at least 3 companies effectively using the Engine 
- [ ] Publish at least 1 case study
- [ ] Press announcement for Engine releases 0.2 & power users
- [ ] Define "Give me your end of year budget" campaign
- [ ] Create enterprise workshop on Code as Data and run it at least once
- [ ] Offer 6 companies our CodeAsData workshop and schedule at least one

### Promote current source{d} stack [DevRel]

- [ ] Develop strategy & app for the "What's in your code?" campaign
- [ ] Develop strategy & app for the "Analyzing most popular OSS Projects" campaign
- [ ] Write and promote blog series for each feature in the engine
- [ ] source{d} Engine featured at 3 conferences
- [ ] source{d} Engine featured at 3 meetups

#### Run beta program on source{d} Engine [DevRel]

- [ ] Identify at least 3 users of source{d} Engine with different personas/use cases
- [ ] Meet regularly (biweekly) with users and gather feedback

### Defined unified web client [DevRel]

- [ ] Write specifications and draft design for a unified web client (instead of gitbase + bblfsh, etc)

## Improve quality across all products [INFRA][DR]

- [ ] Regression test platform [INFRA]
- [ ] Automated regression tests for borges [DR]
- [ ] Automated regression tests for gitbase [DR]
- [ ] Conduct two empathy sessions for cross-team documentation and user experience improvements [ENG][QA]

## ~~Release a new version of PGA [INFRA][APPS]~~

- [ ] ~~Incremental PGA updates [APPS]~~
- [ ] ~~Automate PGA generation [APPS][INFRA]~~
- [ ] ~~Release PGA v2 [APPS]~~

## Bring 'Assisted Code Review' to developers in the open-source community

### Get lookout production ready [APPS]

- [ ] Extend lookout end user documentation in gitbook
- [ ] Extend lookout developer documentation in gitbook
- [ ] Stable Python SDK
- [ ] Stable Go SDK

### Promote 'Assisted Code Review' to developers in the open-source community [DevRel]

- [ ] Prepare beta announcement with top 3 analyzers
- [ ] Update Product webpage with description, videos, and instructions on how to use it
- [ ] Write press release, blog post, etc
- [ ] Plan social media strategy (twitter, reddit, hackernews ...)
- [ ] Schedule an online meetup demoing Analyzers & show how people can build one
- [ ] Define a strategy for analyzers promotion / Registry ?
- [ ] Identify users after launch and partner with them

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

## Define DevRel Strategy/Tools [DevRel]

- [ ] Define DevRel strategy/tools
- [ ] Hire one more team member (Tech Writer / Advocate)
- [ ] Hire social media intern
- [ ] Define DevRel budget
- [ ] Execute sponsorships / attendance strategies for Q4 & 2019
- [ ] Decide and document responsibilities for Website content updates
- [ ] Find & Onboard Swag vendor
- [ ] Define a schedule of integrated campaigns for Q4 and 2019Q1
- [ ] Improve metrics dashboard to show actionable data (MoM, YoY, QoQ)

### Define PR & BD Strategy [DevRel]

- [ ] Pitch the "What's in your code?" campaign to the press and get publication in at least 2 publications
- [ ] Get Eiso bylines published in at least 2 publications
- [ ] Secure at least 3 analysts briefings or demos
- [ ] Qualify at least 1 BD led opportunity for joint announcement i.e Microsoft,  GitHub / GitLab etc

### Manage Read/Write Community [DevRel]

- [ ] Decide on new blogging platform
- [ ] Decide on new forum platform
- [ ] Define metrics of success per social platform and decide which ones matter

### Define & Setup Email Marketing strategy [DevRel]

- [ ] Curate content and send newsletter bi-weekly
- [ ] Newsletter reaches 300 (+100% growth) subscribers
- [ ] Set up master drip campaign for leads
- [ ] Write report on email performance with hindsights and recommendations

### Define and Manage a Community / Sales Funnel [DevRel]

- [ ] Refine Salesforce + Pardot MQL and SQL rules
- [ ] GDPR compliance 
- [ ] Map and report on conversion funnel with hindsights and recommendations

## Advance MLonCode awareness [DevRel]

### Make source{d} the face of MLonCode [DevRel]

- [ ] Create two lookout analyzer demos
- [ ] Get at least 6 collaborators (talk/blog/...) from engineering team
- [ ] Lookout featured at 3 conferences
- [ ] Lookout featured at 3 meetups

### Create an "source{d} friends" program [DevRel]

- [ ] Define "source{d} friends" program goals & value proposition & final name
- [ ] Identify potential members and invite them officially, get 20 to join
- [ ] Welcome each member personally and provide some swag
- [ ] Classify members by profile (speakers, researchers, industry/academia, event organizers, etc)
- [ ] Create dedicated slack channel for MLonCode friends
- [ ] Organize private briefings with members pre-launch giving them opportunity to give us feedback on prez + product and help promote the message

### Make source{d} a friend of MLonCode academia [DevRel]

- [ ] Plan participation for academic events relevant to MLonCode until 1st half of 2019
- [ ] Decide level of involvement (attending, presenting, sponsoring, etc)
- [ ] Organize a Lookout Analyzer Hackathon and invite researchers
- [ ] 3 citations of source{d} datasets / tech in academia endorsed documents

### Increase social engagement with MLonCode [DevRel]

- [ ] Support and promote 3 Paper Reading Clubs 
- [ ] Make Paper Reading Club summaries publicly available (forum?)
- [ ] Identify 20 blog posts / papers on the topic written by others, propose cross-posting to our blog/medium (awesome ml on code)
- [ ] Identify 10 speakers at conferences talking about MLonCode, invite them for collaboration / tweet about their talks / partner with them

