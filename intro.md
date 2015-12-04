# Introduction

## Motivation

I have taken a long journey developing a brand new cloud infrastructure from the ground up.  
Now that we are 6 months into that journey, I decided to chronicle my adventures.  
I will do my best to refrain from synthesis in an attempt to allow free movement for the audience to gain insight.

Before I begin, I want to lay out some fundamental constraints, priorities, and assumptions.

## Constraints

We are trying to bring the agility of a startup into the enterprise.  
This does not immunize us from risk, governance, and compliance.
Therefore, we have to take precautions to prevent breaches, secure data, enable rescue operations, and store forensics. 
While cost is always an issue, our audience pays a premium due to the massive liabilities from negligence. 

## Priorities

Based on our constraints, we prioritize a set of core philosophies.
- secure
- isolated
- traceable
- microservices
- automated
- immutable

Secure, isolated, and traceable are obvious philosophies based on our constraints.
We believe we can take the energies from automated, immutable microservices to the infrastructure world.
We strive to build pieces of infrastructure that are highly disposable.  This relies on us
managing persistence independent of appliances.

## Assumptions

Amazon Web Services (AWS) provided the best value proposition to attain our objective given our constraints and priorities.
Our initial infrastructure relies on AWS; however, our concepts could be translated other cloud infrastructures.
