We will be using the gitflow workflow for our branching strategy. This page provides a high level description of gitflow.  Here are some background links explaining gitflow in more detail:
* [Gitflow Workflow Tutorial from Atlassian](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
* [Gitflow blog from Axosoft](https://blog.axosoft.com/gitflow/)

With gitflow we use two long-lived branches:
* master
* develop

The develop branch is a fork of master. **Developers should never check code directly into the master or develop branches.**   We only modify master and develop by merges.

Branch naming: gitflow enforces branch naming by the type of change desired, e.g.
* feature
* bugfix

**The name of your branch should start with your MSID**, so that at any given time it is easy to tell who owns what branches. Here are a few example branch names:
* feature/kkinder2_ivr_pa_enhancement
* bugfix/kkinder2_alm1234

For any given task (e.g. feature or bug fix) developers will:
1. Create their own short-lived branch, usually from develop. 
1. Make and test changes in that branch, committing and pushing changes to that short-lived branch as desired.
1. When completed, merge the short-lived branch back into its parent, usually this is the develop branch.

To create a release, we will:
1. Create a tag against the develop branch.
1. Create a release branch from the develop branch tag.
1. Merge develop into master.
