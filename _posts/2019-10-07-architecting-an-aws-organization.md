---
title: Architecting An AWS Organization
tags:
  - aws
  - nerd
---
## Introduction

When setting up an AWS Organization it's important to take a pragmatic approach. The key concept most strategies go for
is to make full use of the fact that AWS accounts are free - make as many accounts as you need to separate by major
billing or application use.

Using AWS accounts for distinct purposes gives huge advantages in both cost management and security. Isolating by work
load will in broad terms mean:

* Splash damage on a comprimised account is limited.
* Role and access management is simpler.
* Cost reporting is easier with an account being the top-tier for filtering.
* When a product or platform is terminated the tear-down process can be as simple as closing the account.

In this series of articles I'll focus on setting up and structuring an organization to allow you to take full advantage
of free accounts. 


## Further Reading

Enabling AWS Organizations on your account ([AWS Docs](https://aws.amazon.com/premiumsupport/knowledge-center/get-started-organizations/))

AWS Multiple Account Billing Strategy ([AWS Docs](https://aws.amazon.com/answers/account-management/aws-multi-account-billing-strategy/))

