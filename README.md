# OKRs 2019 Q1

## Bring 'Code as Data' to market with enterprises

### Enable engine integration with 3rd parties

- [ ] gitbase-spark-connector SQL 3rd party interop (Spark Thrift Server) [P0][DP]

### Increase number of algorithms we can run

- [ ] Support for git diff tree [P0][DP]
- [ ] Support for diff [P0][DP]
- [ ] Research options for UDFs (gitbase or gitbase-spark-connector) [P1][DP]
- [ ] Research options for gitbase plugins [P2][DP]
- [ ] Gitbase support for low-level git UDFs [P2][DP]

### Increase variety of data we can analyze

- [ ] Provide specs for external data sources [P1][DP][PRODUCT]
- [ ] Provide specs to expose dependency analysis [P2][LA]

### Analyze current performance limits and improve them

- [ ] Gitbase to expose only reachable objects [P0][DP]
- [ ] Parallelized index creation [P1][DP]
- [ ] Parallelized queries inside of a repository [P2][DP]
- [ ] Make performance dashboard available to product team [P1][DP][PRODUCT]
- [ ] Provide specs for distributed version (gitbase-spark-connector-enterprise) [P2][DP][INFRA]

### Make enterprise friendly

- [ ] gitbase-web SSO and RBAC [P1][APPS][PRODUCT]
- [ ] bblfsh-web SSO and RBAC [P1][APPS][PRODUCT]
- [ ] document gitbase audit logs and RBAC [P1][DP]

### Simplify usage

- [ ] Provide installers [P2][APPS][PRODUCT]
- [ ] Provide specs for new Engine architecture (stand-alone server + config file) [PRODUCT]

### Improve stability

- [ ] Ensure gitbase works when dataset and indexes do not match [P0][DP]
- [ ] Provide a single, default, performant and stable regex implementation for gitbase and enry [P2][DP][LA]
- [ ] Stabilize Babelfish in production (support large-scale use from gitbase) and ML tasks [P0][LA]
- [ ] Add engine cli integration tests [P0][APPS]

### Online updates

- [ ] Gitbase to support online updates [P1][DP]

### Release necessary language support for enterprise

- [ ] C# driver [P0][LA]

### Get bblfsh ready for wide language support of our use cases

- [ ] Make UAST v2 the standard interface for Babelfish [P0][LA]
- [ ] Compact diffs of UAST trees [P1][LA]
- [ ] Plan for a language-independent style-analyzer (bblfsh-side support) [P2][LA]
- [ ] Provide an efficient storage format for large UASTs collections [P3][LA]

## Improve the 'Code as Data' individual user experience

## Improve quality across all products

- [ ] Conduct two empathy sessions for cross-team documentation and user experience improvements [P1][ENG]

## Release a new version of PGA

- [ ] Release a new version, updated, fixed, including #stars [P1][DR]

## Bring 'Assisted Code Review' to developers in the open-source community

### Improve current lookout analyzers

- Style Analyzer in one more language (possibly Java) [P0][ML]
- Release Typo Analyzer [P0][ML]

### Create new lookout analyzers

- [ ] Analyzers for most common linters / traditional static tools [P?][APPS][PRODUCT]
- [ ] Collect a structured dataset of diffs for best-practices-analyzer [P2][ML]
- [ ] Research what ML team can deliver for best-practices-analyzer [P1][ML]

### Lookout Platform

- [ ] Collect GitHub reactions as feedback to comments [P1][APPS]
- [ ] Provide metrics on usage [P0][APPS]
- [ ] Live Demo Repository with all available analyzers set-up [P1][APPS][INFRA]

## Store the world's source code

### Refactor to go-borges library, to reuse borges logic in other projects

- [ ] Library for access to a collection of git repositories (go-borges) [P0][DR]
- [ ] go-borges-based borges [P0][DR]
- [ ] siva backend for go-borges [P1][DR]

### Improve borges storage

- [ ] Inspect storage efficiency (review siva usage, siva compaction, git gc, etc) [P1][DR]
- [ ] Research distributed storage alternatives [P2][INFRA][DR]

## Improve infrastructure

### Release the production kubernetes pipeline cluster

- [ ] Release of the production cluster [P0][INFRA]
- [ ] Run rovers and borges on it [P0][INFRA]
- [ ] Deploy services with HA: PostgreSQL, RabbitMQ, etcd [P0][INFRA]
- [ ] Add monitoring to the pipeline (rovers, borges and associated services) [P0][INFRA]
- [ ] Migrate staging cluster to the new deployment method [P0][INFRA]
- [ ] Improve Helm Terraform Provider [P1][INFRA]
- [ ] New staging cluster with latest Code as Data stack [P1][INFRA]

### Improve local-gpu cluster usability

- [ ] Migrate to the new ML cluster [P0][ML][INFRA]

## Being a better company to work at

## Advance MLonCode awareness

- [ ] Publish the final id2vec model [P2][ML]

## Hiring

- Hiring: Test (1 Senior) [P0][TALENT]
- Hiring: ML (1 Intern + 1 Senior) [P0][TALENT]
- Hiring: Apps (1 Senior, 1 Lead) [P0][TALENT]
- Hiring: LA (1 Senior + 1) [P0][TALENT]
- Hiring: DR (1 Senior) [P1][TALENT]
- Hiring: DP (1 Senior) [P1][TALENT]
- Hiring: Infra (1 Senior) [P1][TALENT]
