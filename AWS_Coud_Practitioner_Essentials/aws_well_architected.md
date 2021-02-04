# AWS Well-Architected and the Five Pillars
**link**: https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.
sort-order=desc 

## Framework Overview

The AWS Well-Architected Framework describes the key concepts, design principles, and architectural best practices for designing and running workloads in the cloud. By answering a set of foundational question you learn how well your architecture aligns with cloud best practices and are provided guidance for making improvements. 

## Operational Excellence Pillar

- Focuses on running and monitoring systems to deliver business value, and continually improve processes and procedures. 
- Operational excellence is challenging to achieve in environments where operations is perceived as a function isolated and distinct from the lines of business and development teams that it supports.

### Design Principles

1. **Perform operations as code**
With cloud technologies, you can use the same engineering discipline that you use for application code, for your entire environment. Your entire workload (applications, infrastructure, etc) can be defined with code, and updated with code. 

Procedures can be scripted and have automated execution by triggering them in response to events. By performing operations as code, you can limit human error, and enable consistent responses to events. 

2. **Make frequent, small, reversible changes**
Design workloads to allow components to be updated regularly to increase the flow of beneficial changes into your workload. Changes to you workloads can be incremental, and reversed if they fail to aid in the identification and resolution of issues introduced to your environment. 
`
3. **Refine operations procedures frequently**
As operations procedures are used, look for opportunities to improve them. As your workload evolves, evolve your procedures accordingly. Set up regularly game days to review and validate that all procedures are effective and that teams are familiar with them.

4. **Anticipate failure**
Perform "pre-mortem" exercises to identify potential sources of failure so that they can be removed or mitigated. Test your failure scenarios and validate your understanding of their impact. 

Tets your response procedures to ensure that they are effective and that teams are familiar with their execution. Setup regular game days to test workload and team response to simulated events.

5. **Learn from all operations failures**
Drive improvement through lessons learned from all operational events and failures. *Share what is learned* across teams and through the entire organization. 

### Definition

Operational excellence in the cloud is composed of four areas:

- Organization
- Prepare
- Operate
- Evolve

The organizations leadership defined business objectives, your organization must understand requirements and priorities and use these to organize and conduct work to support the achievement of business outcomes. The workload must emit the information necessary to support it. 

Implementing services to enable integration, deployment and delivery of your workload will enable an increased flow of beneficial changes into production by automating repetitive processes. 

Risks may be inherent with your workload, and they should be understood to make informed decision to enter production. Your teams must also be able to support your workloads. 

Priorities will change as your business needs change, use this feedback loop to continuously improve the operation of your workload. 

## Organization Pillar

You need to understand your organization's priorities, your organization structure, and how your organization supports your team members, so that they can support your business outcomes. 

