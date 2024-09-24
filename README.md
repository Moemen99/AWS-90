# AWS DevOps Course Introduction

## Course Overview

This course focuses on DevOps activities specifically within the AWS ecosystem. It covers:

- AWS services relevant to DevOps practices
- Hands-on experience with the AWS console
- Script writing and resource management
- Real-world applications used by companies in the market

The goal is to provide practical knowledge that aligns with industry practices, preparing you for work in AWS-focused DevOps roles.

## Course Scope

- Covers approximately 90% of common AWS DevOps activities
- Emphasizes hands-on learning over theoretical concepts
- Focuses on AWS-specific DevOps practices, not general DevOps principles

## Prerequisites

To get the most out of this course, you should have:

1. Basic understanding of IT concepts (hardware, software, networking)
2. Familiarity with virtual machines
3. Comfort with Linux operating systems
4. Experience with command-line interfaces (CLI)
5. Basic scripting knowledge (shell or bash)
6. Previous experience setting up development environments

## Target Audience

This course is suitable for:

- Aspiring DevOps engineers
- Software developers looking to incorporate DevOps practices
- IT professionals seeking AWS-specific DevOps skills

## Course Structure

- Utilizes an AWS account for hands-on practice
- Focuses on cost-effective resource usage
- Includes practical exercises and real-world scenarios

## Note

This course is part of a broader DevOps curriculum and specifically targets AWS DevOps practices.


# Introduction to Cloud Computing

## Traditional IT Infrastructure

### Hardware and Software Basics
- Computers and networking devices form the hardware base
- Software applications drive business efficiency and productivity

### Common Business Applications
- Enterprise Resource Planning (ERP)
- Customer Relationship Management (CRM)
- Asset Management
- Business Intelligence
- Marketing Automation
- Communication Management
- Human Resources
- Mobility Management
- Content Management Systems (CMS)

### Varying IT Needs
- Small companies: Minimal server requirements
- Larger companies: Dedicated IT rooms or data centers
  - Multiple racks, servers, networking devices
  - Complex cabling and cooling systems

## Evolution to Data Centers
- Large-scale facilities designed for IT infrastructure
- Specialized construction and layout
- Efficient cooling and cable management
- Various server rack configurations (1U, 2U, 3U)
- Specialized storage servers (HDDs, SSDs)
- Storage Area Network (SAN) technology

## Cloud Computing Concept

### Definition
Cloud computing offers IT resources through the internet, eliminating the need for on-premises infrastructure.

### Key Features
1. Flexible resource allocation
   - Scale from 1 to 10,000+ servers
   - Rent partial or multiple "virtual IT rooms"
2. On-demand networking devices
3. Pay-as-you-go model
4. Access to both hardware and software services

### Cloud vs. Web Hosting
- Cloud: Scalable, flexible IT resources
- Web Hosting: Limited to predefined server packages

### Types of Cloud Services
1. Foundation Services (Hardware)
2. Application Services (Software)
3. Deployment and Management Services

## Summary
Cloud computing provides scalable IT services over the internet, offering businesses flexibility in hardware and software resources without the need for physical infrastructure management.



# Cloud Delivery Models and IT Stack

## IT Delivery Stack

The IT delivery stack consists of several layers, each with its own components. Understanding this stack is crucial for grasping cloud delivery models.

### Stack Layers (from bottom to top):

1. Network
2. Storage
3. Servers (Processor, RAM)
4. Virtualization
5. Operating Systems
6. Runtime
7. Data
8. Applications

Each layer in this stack has its own set of components and complexities.

## On-Premises Model

In the on-premises model:

- The entire IT stack is located at the client's site
- The client is responsible for managing the entire stack
- This includes all aspects of maintenance and operation

**Note**: Some cloud providers, like AWS, can provide a physical rack to the client, but the management responsibility remains with the client.


### 2. Infrastructure as a Service (IaaS)

In the IaaS model:

- The cloud provider manages:
  - Networking
  - Storage
  - Servers
  - Virtualization
  - Operating Systems
- The client is responsible for:
  - Runtime
  - Data
  - Applications

Key points:
- Clients rent resources from the provider's data center
- Provider manages physical infrastructure (cables, networking devices, servers, storage)
- Clients can choose virtual servers and operating systems
- Clients are not responsible for physical hardware management

### 3. Platform as a Service (PaaS)

In the PaaS model:

- The cloud provider manages everything up to and including the runtime environment
- The client is only responsible for:
  - Data
  - Applications

Key points:
- Provider prepares servers with necessary runtimes (e.g., Java)
- Clients only need to specify their application and data
- Provider deploys the application on appropriate machines
- Clients have no direct server management responsibilities


### 4. Software as a Service (SaaS)

In the SaaS model:

- The cloud provider manages the entire stack, including the application
- The client only uses the application, with no management responsibilities

Key points:
- SaaS is not limited to cloud providers; many mobile and web applications are SaaS
- Examples include CRM systems, where companies subscribe to a service rather than hosting it themselves
- SaaS applications are ready to use, with no infrastructure management required by the client

## Practical Application of Cloud Delivery Models

In real-world scenarios, organizations typically use a combination of these models rather than choosing just one:

1. **Hybrid Approach**: Companies often divide their IT solutions across different models based on specific needs.

2. **Examples of mixed usage**:
   - SaaS: For ready-to-use applications like monitoring systems
   - PaaS: When runtime management is not desired
   - IaaS: For scenarios requiring more control over the server environment
   - On-premises: For systems that need to remain in-house, connected to cloud services

3. **Flexibility**: This mixed approach allows organizations to optimize their IT infrastructure based on security, control, and management preferences.

4. **Integration**: Different models can be integrated, allowing for connections between on-premises systems and various cloud services.

Remember, the choice of model(s) depends on specific business needs, security requirements, and desired levels of control and management.

## Cloud Delivery Models

Cloud delivery models determine how the IT stack is divided between the client and the service provider (cloud provider). The division of responsibilities varies depending on the chosen model.
