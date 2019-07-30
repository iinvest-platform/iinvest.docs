## iinvest Platform Development Plan
---

## Time Line
---
The iivest group estimates the development timeline for the main backend services (user, social network, financial data, learn, podcast, and email) will be around __12 months__ to
__18 months__. Fundamental points taken into consideration when providing this rough estimate include timeline of complete feature implementations, testing (unit, regression, and integration tests),
deployment, and additional unaccounted overhead costs.

## Development Plan
---
#### August - November
##### August 1st - September 30th
- System Architecture (User Microservice) [1 Week]
  - Architect Backend User Microservice & Define Its Communication Protocol (REST, GRPC, ...etc)
- Service Development [6 weeks]
  - Go backend service implementation
  - Docker Workflow Definition
  - Continuous Integration & Kubernetes deployment
  - Testing (Unit test, regression test, integration tests, performance tests, ...etc)
  - Tracing
- Service Documentation [1 week]
  - Swagger Service Documentation

#### October 1st - November 30th
- System Architecture (Social Network Microservice) [1 week]
    - Architect Social Network Microservice
    - Define Database Schema (GraphDB or vitess.io)
    - Architect communication protocols
    - Enforce Best Practices
- Service Development [6 weeks]
  - Go backend service implementation
  - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
  - Complete Testing of service & constituent parts
  - Tracing
- Service Documentation [1 week]
  - Swagger Service Documentation

#### December 1st - January 30th (2020)
- System Architecture & Requirements (Learn Microservice) [1 week]
    - Architect Social Network Microservice
    - Define Database Schema (vitess.io)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[6 weeks]
    - Go backend service implementation
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- Service Documentation [1 week]
    - Swagger Service Documentation
- Functionalities
  - Khan Academy + Bank Of America Service Set + Youtube Channels

#### February 1st - March 30th
Frontend Development & UI/UX implementation
- Frontend Requirements Specification & Wireframe Templating [1 week]
  - Template all application/web page views
  - Define page level requirements for each view
  - Define necessary functionalities to the utmost level of granularity (As Detailed As Possible)
- Frontend Development [6 weeks]
  - React.js to develop entire frontend application (Privacy Focused Social network + Learning functionalities)
  - Implement all necessary tests suites & enforce required optimizations
- Service Documentation [1 week]
  - Swagger Documentation of service/frontend

#### April 1st - May 1st (Deployment V1.0)
Initial Release (Primary Iteration)
- Testing [3 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Deployment [1 week]
  - Deploy V1.0 of the iinvest platform

#### May 2nd - July 1st
Financial Data Microservice Development
- System Architecture & Requirements (Financial Data Microservice) [1 week]
    - Architect Financial Data Microservice
    - Define Database Schema (vitess.io + object store)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[6 weeks]
    - Go backend service implementation
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- Service Documentation [1 week]
    - Swagger Service Documentation

##### July 2nd - July 30th (Deployment V1.1)
Release V1.1 Of iinvest platform (Financial Data Microservice)
- Testing [2 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Front End Update [2 weeks]
- Deployment [1 week]
  - Deploy V1.1 of iinvest platform

#### August 1st - September 30th
Podcast Microservice & News letter Microservice & Email Microservice Development
- System Architecture & Requirements (Newsletter & Podcast & Email Microservice) [1 week]
    - Architect Both Microservices
    - Define Database Schema (vitess.io + object store)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[6 weeks]
    - Go backend service implementation (Podcast Microservice) & NodeJS backend implementation (Email & Newsletter Microservice)
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- Service Documentation [1 week]
    - Swagger Service Documentation

##### October 1st - October 30th (Deployment V1.2)
Release V1.2 of iinvest platform (Newsletter & Podcast & Email Microservice)
- Testing [2 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Front End Update [2 weeks]
- Deployment [1 week]
  - Deploy V1.2 of iinvest platform

#### November 1st - December 30th
News Microservice Development
- System Architecture & Requirements (News Microservice) [1 week]
    - Architect Both Microservices
    - Define Database Schema (vitess.io + object store)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[6 weeks]
    - Go backend service implementation (News Microservice)
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- Service Documentation [1 week]
    - Swagger Service Documentation


#### January 1st - January 30th (Deployment V1.3) (2021)
Release V1.2 of iinvest platform (News)
- Testing [2 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Front End Update [2 weeks]
- Deployment [1 week]
  - Deploy V1.3 of iinvest platform

#### February 1st - August 30th
Chat Microservice & Publishing Microservice
- System Architecture & Requirements (Chat & Publishing Microservice) [1 month]
    - Architect Both Microservices
    - Define Database Schema (vitess.io + object store)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[3 months]
    - Go backend service implementation (News Microservice)
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- UI/Frontend Definition [2 months]
    - Implement Front End Functionalities/Features Associated With Each Microservice
- Service Documentation [1 week]
    - Swagger Service Documentation

#### September 1st - September 30th (Deployment V1.4)
Release V1.4 of iinvest platform (Chat & Publishing Microservice)
- Testing [2 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Front End Update [2 weeks]
- Deployment [1 week]
  - Deploy V1.4 of iinvest platform

#### October 1st - January 30th (2022)
Brokerage Microservice & Portfolio Microservice
- System Architecture & Requirements (Brokerage & Portfolio Microservice) [1 month]
    - Architect Both Microservices
    - Define Database Schema (vitess.io + object store)
    - Architect communication protocols
    - Define service requirements
    - Enforce Best Practices
- Service Development[2 months]
    - Go/C++ backend service implementation (News Microservice)
    - Docker Workflow Orchestration, Continious Integration, & Kubernetes deployment
    - Complete Testing of service & constituent parts
    - Tracing (Service Level & Infra. Level)
- UI/Frontend Definition [2 months]
    - Implement Front End Functionalities/Features Associated With Each Microservice
- Service Documentation [1 week]
    - Swagger Service Documentation

#### September 1st - September 30th (Deployment V1.5)
Release V1.5 of iinvest platform (Brokerage & Portfolio Microservice)
- Testing [2 weeks]
  - Stress Testing Microservices & Cost Estimations
  - Code Optimizations & Reliability Testing
- Front End Update [2 weeks]
- Deployment [1 week]
  - Deploy V1.5 of iinvest platform

Summer 2019 Goals
1. Read
    - 5 Technical Books (Golang, Microservices, ..etc)
    - 2 Business Books (Startups)
    - 2 Life Books
    - Build iinvest company site (HUGO golang framework) Through Use Of Markdown
2. Complete iinvest Company Site
3. Surveys
   - Dish Out 5 Different Surveys To Test Hypothesis
    - Privacy Focused Social Network
    - Financial Analytics
    - Content Control
    - Education
    - User Goals
4. Complete the Following Services
    - Podcast Service
    - News Service
    - Learn Service
    - Research Service
    - News-Letter & Email Service

