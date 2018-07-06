# OKRs 2018 Q3

## Bring 'Code as Data' to market with enterprises

### Get gitbase enterprise ready
- [ ] Release a stable gitbase version
  - [ ] Add regression testing
- [ ] Ensure gitbase interoperability with 3rd party tools

#### Improve gitbase performance to single second responses on most queries 
- [ ] **Key results pending an internal engineering meeting**
- [ ] Switch Engine to use gitbase as a backend
  - [ ] Change engine schema to match gitbase's
  - [ ] Replace actual JGit implementation with a query builder and calls to gitbase

#### Announce gitbase publicly
  - [ ] Figure out date for Gitbase announcement and see what we can do
  - [ ] Announcement talk at GitHub Universe
  - [ ] If not possible for Github Universe define alternative

### Formally map 'Code as Data' enterprise needs
- [ ] Do 8 user research interviews
- [ ] Map formal user personas
- [ ] Map key use cases
  - [ ] Map features missing & priorities

### Update website to match current reality and needs
- [ ] Deliver updated landing content
  - [ ] Product pages
  - [ ] General content
- [ ] Add salesforce integration
  - [ ] Deliver actionable conversion funnel metrics
- [ ] Update visual style
- [ ] Map content managing responsibilities

#### Define & design hosted Playground experiences
- [ ] Babelfish
- [ ] Gitbase
- [ ] Engine

### Setup a stable 'Code As Data' deployment in our cluster for BigCompanyG

### Release necessary language support for enterprise
- [ ] C# driver
- [ ] C/C++ driver

### Ensure stability of Babelfish in a production environment
- [ ] Client/Library improvements, packaging, and stability

### [P1] Get gemini enterprise ready
- [ ] Release a new version with the integration of function similarity
- [ ] Announce gemini publicly
  - [P1] Deliver gemini product page

#### Formally map gemini enterprise needs
- [ ] Do 3 user research interviews
- [ ] Map formal user personas
- [ ] Map key use cases
  - [ ] Map features missing & priorities

## Being a better company to work at

### Successfully hire for each open Role
- [ ] Hire a VP of Engineering
- [ ] Develop a candidate pipeline for VP of Sales
- [ ] Improve candidate pipeline on Infrastructure Role
- [ ] Attract relevant profiles of applicants through our community
- [ ] Improve the speed of the hiring process from our side
- [ ] Increase candidate’s motivation and engagement at every interviewing step
  - [ ] Implement candidate feedback surveys
  - [ ] Deliver dashboard with actionable metrics

#### Having a more diverse funnel in terms of gender and race
- [ ] Explicit developer community promotion via social media
- [ ] Proactively reaching out to diverse communities
- [ ] Proper updates to the website & guide to promote multi-national and cultural environment

#### Make our interview process more remote friendly
- [ ] Identify bottlenecks in the hiring process that makes it less remote-friendly and solve them

### Improve general happiness and communication
- [ ] Implement periodic employee happiness surveys
  - [ ] Deliver dashboard with actionable metrics
  - [ ] Map key problems and successes
- [ ] Conduct an engineering survey to improve development practices for Q3 and Q4
- [ ] Conduct empathy sessions for cross-team documentation validation
- [ ] Improve internal communication for events happening at source{d}
- [ ] Improve the formal process of speaking at a conference
- [ ] Resolve connectivity problems at the Madrid office

#### Setup GPU production cluster for ML
- [ ] Research and install Kubeflow (or alternatives) to the production cluster

#### Improve engineering workflows
- [ ] Regression Test, Benchmarks and Deploy platform
- [ ] Improve Logs, CLI, and other guides.
- [ ] Make it easy to update and maintain PGA.

### Improve financial analysis and reporting
- [ ] Finish financials processes refactoring
  - [ ] Deliver financial insights dashboard

## Bring 'Assisted Code Review' to developers in the open-source community

### Launch source{d} lookout alpha at GopherCon

#### Release a production ready analyzer SDK
- [ ] Build alpha/beta versions of an analyser SDK
- [ ] Build a simple reference example of analyzer
- [ ] Any developer is able to understand how to create a new analyzer
- [ ] Testing an analyzer locally is easy: streamlined to 1-2 shell commands
- [ ] Release a production ready SDK with API stability guarantees

#### Release a production ready service

#### Define key product features
- [ ] Deliver formal user research
  - [ ] Do 5 internal user research interviews
  - [ ] Do 10 external user research interviews
  - [ ] Do a large-scale community survey
  - [ ] Estimate quant prevalence of pain points from code reviews/PRs
- [ ] Map formal user personas
- [ ] Map key use cases
  - [ ] Map features & priorities
- [ ] Design the user experience
  - [ ] Have over 2/3 of key users report a positive experience

##### Release a beta of the style analyzer[s]
- [ ] General code style rules mining under UAST
- [ ] General code style rules mining over UAST
  - [ ] Iterate the higher level UAST abstractions to fix and maintain
- [ ] Naming style suggestion
  - [ ] Incorporate the identifier splitter inside sourced-ml extraction pipeline
- [ ] Typos correction in names
- [ ] One-line best practices mining
- [ ] Release UAST diffing

##### Build alpha/beta versions of the service (learning from PoC)
- [ ] Automated CI/CD pipeline to staging
- [ ] Service deployed on a staging environment
- [ ] 2 source{d} projects enable lookout from staging
- [ ] Implement the lookout service internally

##### Any OSS project on Github is able to add lookout service (through 'Github Apps' flow)
- [ ] Automated CI/CD pipeline for production environment
- [ ] Private 'status page' of the service health
- [ ] Service deployed on a production environment
- [ ] 2 OSS projects besides source{d} enable lookout

##### Announce Lookout to the world
- [ ] Prepare talk and announcement at GopherCon
- [ ] Product webpage with description, videos, and instructions on how to use it
- [ ] Write press release, blog post, etc
- [ ] Plan social media strategy (twitter, reddit, hackernews ...)
- [ ] Schedule an online meetup with technical details about the bot
- [ ] Find alpha testers for bot and work with them closely until launch
- [ ] Identify users after launch and partner with them

## Store the world's source code

### Reach a stable version on borges & rovers

#### Stable and performant borges & rovers
- [ ] Improve regression tests with more use cases
- [ ] Keep improving go-git performance

#### Refactor to go-borges library, to reuse borges logic in other projects (i.e. lookout)
- [ ] Borges states diagram
- [ ] Define a public API for that library studying actual use cases
- [ ] Integration tests and regression tests for that library

#### Improve borges documentation
- [ ] Define documentation summary
- [ ] Gitbook integration

### Release the production kubernetes cluster
- [ ] Release of the production cluster, and run rovers, borges and lookout, on it
- [ ] HA of databases and other persistent services.

## Advance MLonCode awareness

### Make source{d} the face of #MLonCode
- [ ] Run that workshop at least once at a meetup / conference
- [ ] Create two demos showing the power of our stack solving a “real problem”
- [ ] Get at least 6 more collaborators (talk/blog/...) with engineering
- [ ] Improve the formal process of our internal speaker program in collaboration with Esther and get buyin from Engineering

### Create an "MLonCode friends" program
- [ ] Define "MLonCode friends" program goals & value proposition
- [ ] Identify potential members and invite them officially, get 20 to join
- [ ] Welcome each member personally and provide some swag
- [ ] Classify members by profile (speakers, researchers, industry/academia, event organizers, etc)
- [ ] Engage with members and enable them to grow their influence and our message

### Make source{d} a friend of MLonCode academia  
- [ ] Create a list of all academic events relevant to MLonCode until end of 2019
  - [ ] Decide level of involvement (attending, presenting, sponsoring, etc)
- [ ] Release CodeNet with one challenge on top of PGA
- [ ] Consider and plan/reject creation of competition on Kaggle
- [ ] 3 citations of source{d} datasets / tech in academia endorsed documents
- [ ] Develop and organize at least 3 Enterprise workshops in Q3

### Promote current source{d} stack
- [ ] Write and promote 1 blog post for each project in the stack and how it came to be
- [ ] Gather list of users of each project and classify them according to their profiles
- [ ] source{d} Engine and/or Lookout featured at minimum 5 conferences
- [ ] source{d} Engine and/or Lookout featured at minimum 5 meetups
- [ ] Develop the MlonCode documentation/walkthrough  

### Define PR & BD Strategy
- [ ] Develop & pitch source{d}'s unique Open Source Philosophy / Culture to the press and get publication in at least 2 publications
- [ ] Onboard a PR agency to support product annoucements
- [ ] Identify at least 1 BD led opportunity for joint announcement i.e GitHub / GitLab integration, etc

### Define Social Media Strategy
- [ ] Define infrastructure for this (Buffer, etc)
- [ ] Slack: figure out strategy and onboarding process
- [ ] Increase followers on Twitter / Facebook /  Linkedin ...
- [ ] Provide an alternate method to Slack for communication: forum?

### Create a weekly newsletter for announcements, events, curated content, etc
- [ ] Create the newsletter
- [ ] Curate content and send newsletter weekly
- [ ] Reach 100 subscribers
- [ ] Map and measure the conversion funnel
  - [ ] Deliver actionable metrics dashboard

### Increase social engagement with #MLonCode #49
- [ ] Increase hashtag usage on social media channels by X% (tbd)
- [ ] Identify 20 blog posts / papers on the topic written by others, propose cross-posting to our blog/medium
- [ ] Identify 10 speakers at conferences talking about #MLonCode, invite them for collaboration / tweet about their talks / partner with them
- [ ] Post 10 times a week in our multiple social media accounts about #MLonCode
- [ ] Create a strategy to manage our online communities (slack, etc) and corresponding online marketing
- [ ] Get periodic & actionable insights from our data
  - [ ] Automate data collection & storage
  - [ ] Map DevRel dashboard needs and future direction
