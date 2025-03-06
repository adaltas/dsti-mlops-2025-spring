
# MLOps

## Introduction

According to DSTI Scientific Advisory Board policy for ever-evolving programmes, this syllabus may be
subject to adaptations and changes when the class will be delivered by the selected Professor(s).
Applied MSc in Data Science & AI
MLOps with Adaltas
Combining development and operations (DevOps) is an approach to shorten the
development life cycle and improve software quality while delivering features,
fixes, and updates frequently in close alignment with business objectives. We will
learn its most important building blocks, before extending it to the usage in data
science (MLOps). A machine learning model is only valuable once it can be used
togenerate business value. We will go through the steps of the ML lifecycle
from developmentto production. We will learn how versioning and testing help
us achieve reproducible data science, and how to leverage automation to speed up
the delivery of the pipelines.

## Educational goals

- Discover the DevOps culture and its tooling ecosystem.
- Gain and share confidence in your code and operated systems.
- Maximize time-to-market, productivity and security.
- Build robust and evolving applications and infrastructures.
- Integration of ML and DevOps principles
- Building End-to-End Machine Learning pipelines
- Learn about the challenge of going to production
- Monitoring and maintenance of ML Systems

## Prerequisites

Common computer skills, Linux basic knowledge, and basic Python programming skills.

## Modules

### Module 1: DevOps introduction

- Definition
- The reason to DevOps
- DevOps life cycle
- Site Reliability Engineering (SRE) implements DevOps
- SRE service levels
- SRE tools
- Devops' history
- Agile vs Waterfall
- The Agile Manifesto
- Agile Principles
- Scrum
- Version management with SemVer
- Naming

### Module 2: Source Control Management (SCM)

- Objectives
- Definition
- VCS motivations
- VCS Usages
- Semantic Versioning (SemVer)
- Centralized vs Distributed VCS
- Git: introduction
- Git: motivations
- Git: ecosystem
- Git: basic concepts
- Git: repository
- Git: common usage scenario
- Git: branching
- Git: branches merging
- Git: conflicts resolution
- Git: lab praticing
- Git: `.gitignore`
- Git: tagging
- Git best practices: use rebase instead of merge
- Git best practices: Conventional Commits
- Where can you use Git?
- Open-source project management

### Module 3: Continuous testing

- Benefits
- Types of tests
- Example
- Test coverage
- Test-driven development (TDD)
- TDD benefits
- Test automation
- Test writing best practices

### Module 4: Continuous Integration & Continuous Delivery (CI/CD)

- Simple deployment illustration
- Definitions
- Benefits
- CI/CD fundamentals
- CI/CD pipeline
- CI/CD platforms
- Registry deliveries

### Module 5: Containers with Docker

- The problems for developers
- Container definition
- Docker container
- Docker
- Container vs Virtual Machines vs Bare metal
- Docker architecture
- Docker components
- Example of a Docker workflow
- CLI commands
- Building Docker images
- Storage on Docker
- Running multi-container applications with Docker Compose
- Use cases
- Using Docker Compose
- Docker Compose example
- Docker Compose commands

### Module 6: Introduction to MLOps, MLOps vs DevOps

Course:

- Motivations
- What does it do?
- Why is it important?
- Data science landscape
- ML in research vs. production
- Challenges of deploying ML
- DevOps Principles
- MLOps Principles
- DevOps vs MLOps
- Different tasks (and definitions) of MLOps
- ML Lifecycle and Roles
- Tools
- Maturity levels of MLOps systems (according to Google)
- Real life applications

### Module 7: Data versioning

Course:

- Git recap
- Data versioning
- Roadmap
- Problem definition
- Data versioning use cases
- Data is in the heart of any ML project
- Common data versioning solutions and their downsides
- What is DVC?
- Version extraction
- Practical example

Lab: Data versioning with DVC

- Version data using DVC
- Access the data in DVC using python api
- Access a specific version of the dataset

### Module 8: Data and model testing, integration with CML

Course: 

- Extension of 'Garbage in, garbage out' to ML systems
- Roadmap
- Tests everywhere
- ML pipeline testing
- Model testing
- Model evaluation
- Model validation
- Data testing
- Training-serving skew
- Tools
- PyTest

Lab: Testing

- Learn how to define a test function and how to write an assertion
- Learn the approach to data testing
- Learn the approach to feature engineering testing

Lab: CML

- Learn how to automate testing with Git and [CML](https://cml.dev/)
- Understand the processes that run after the Git Action workflow is triggered

### Module 9: Experiment tracking

Course:

- Motivations
- Roadmap
- Objectives
- Definition
- Basic concepts
- Practical example

Lab:

- Demonstrate how experiment tracking helps with linking the code, the results and the environment details
- Note how this increases the reproducibility

### Module 10: Model deployment

Course: 

- Motivations
- Roadmap
- Vocabulary
- Deployment targets
- Latency constraints
- Deployment strategies
- Tests after deployment

Lab:

- Understand the steps of a model deployment
- Prepare and test the app locally
- Create a Docker container image
- Deploying the container to Azure Web Services

### Module 11: Monitoring of deployed model

Course: 

- Motivations
- Roadmap
- Quick recap
- Extra layer of complexity
- System monitoring
- Data monitoring
- Model decay
- Stale models handling

Lab: Data drift detection and model degradation

- See a concrete example of data drift
- Learn how to detect and evaluate it

### Module 12: End-to-end ML platforms

Course:

- Architectural complexitiy
- Solution
- Platform comparison
- TensorFlow Extended (TFX)
- Comparison of the initial pipeline and TFX

Lab: TFX introduction

- Try out an example of end-to-end platform
- Deepen the notion of the pipeline and metadata
this is a dev branch
