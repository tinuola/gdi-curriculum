# DevOps Practices, Tools, and Skills

DevOps ≠ Tools

<img src="dist/img/devops-tools.png" alt="DevOps Tools" class="noborder"/>

<small>Image from https://www.osolabs.com/blog/devops-tools-of-the-trade/</small>

===

## DevOps Practices

<img src="dist/img/devops-practices.jpg" alt="DevOps Practices" class="noborder"/>

<small>Image from https://www.bmc.com/blogs/continuous-delivery-continuous-deployment-continuous-integration-whats-difference/</small>


===

## Code ⟺ Build (Agile Development)

- Predates DevOps
- Iterative development of code
- Scrum teams, sprints, etc.
- Launch often
- Counter to "waterfall development"

<img src="dist/img/agile.jpg" alt="Agile Methodology" class="noborder"/>

<small>Image from https://www.initio.eu/blog/2020/1/22/change-management-in-agile-methodology</small>

===

## Code ⟺ Test (Continuous Integration)

Practice of automating integration of code changes reliably

- Code, Build, Integrate, Test
- Relies heavily on automated testing
- Integrate or merge code only if tests pass
- Tools: Jenkins, Travis CI, CircleCI, TeamCity, AWS CodeBuild

<img src="dist/img/continuous-integration.png" alt="Continuous Integration with Jenkins" class="noborder"/>

<small>Image from https://medium.com/faun/github-enterprise-ci-cd-integration-with-jenkins-fcd9ba1b4eb</small>

===

## Code ⟺ Release (Continuous Delivery)

Practice of automating releases so that they are *ready* to be deployed to production

- Requires Continuous Integration
- Often abbreviated to CI/CD
- Often involves deploying to non-production environments
- Tools: Spinnaker, Jenkins X, Helm, Harness

<img src="dist/img/spinnaker-deployment.png" alt="Spinnaker Deployment Pipeline" class="noborder"/>

<small>Image from https://spinnaker.io</small>

===

## Code ⟺ Deploy (Continuous Deployment)

Practice of automating deployment of release *to production*

- Tooling the same as Continuous Delivery
- Biggest change is cultural
- More test coverage / confidence in prior CI/CD
- Dependent on better operations and real-time monitoring
- Rollback and recover automatically

<img src="dist/img/sdlc-devops.png" alt="Software Development Life Cycle for DevOps" class="noborder"/>

<small>Image from https://www.netsparker.com/devops-security-tools/</small>

===

## Operating and Monitoring

- Operating environment (AWS, Azure, GCP)
- Virtualization Inception: Docker containers, Kubernetes for container orchestration
- Monitoring and Dashboard tools: Prometheus, Nagios, Grafana, DataDog, Splunk, PagerDuty

<img src="dist/img/kubernetes.png" alt="Kubernetes Graphic" class="noborder"/>

<small>Image from https://stablekernel.com/an-introduction-to-kubernetes/</small>

===

## DevOps

It's not just tooling, practices or a role

It's also culture and philosophy and fundamentally changes how an organization operates

===

## DevOps Skill Tree

Sample skill tree for a "DevOps Engineer"

You learn as you go - nobody knows everything

- Foundation
    - Linux
    - Python (some scripting language)
    - Amazon Web Services (Cloud Provider)
- Tools
    - Configuration
        - Terraform
    - Source Code Management
        - Git
    - Packaging
        - Docker
    - CI/CD
        - Jenkins
    - Operating
        - AWS ECS (just an example)
        - Kubernetes
    - Monitoring
        - ELK Stack (just an example)

===

# General Q&A ❓
