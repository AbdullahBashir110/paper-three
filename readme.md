# On the Shoulders of Giants: A New Dataset for Pull-based Development Research

## Authors 
Xunhui Zhang
National University of Defense
Technology, Changsha, China.

### Published on :

year June 2020
## Link
 https://www.researchgate.net/publication/342529857_On_the_Shoulders_of_Giants_A_New_Dataset_for_Pull-based_Development_Research.

## Description
 Pull-based development is a widely adopted paradigm for collaboration in distributed software development, attracting eyeballs from both academic and industry. To better study pull-based development model, this paper presents a new dataset containing 96 features collected from 11,230 projects and 3,347,937 pull requests. We describe the creation process and explain the features in details. To the best of our knowledge, our dataset is the most comprehensive and largest one toward a complete picture for pull-based development research.

## Introduction
The pull-based development model [7] has changed the traditional
way of code contribution [31], code review [28] and process automation
[27]. Since Gousios et al. [8] proposed a firsthand dataset
of pull request, plenty of valuable studies have been designed based
on it, to better understand the essence of modern software development,
e.g, human aspect of SE, DevOps and collaborative environment.


### Feature Selection:
The feature selection is based on Gousios et. al’s dataset [8] as
well as studies on pull request development from 2009 until 2019.
By combining “pull-based development”, “pull-request”, “Github”,
“open source” with zero or more of the following sub-terms: “model”,
“software”, “accepted”, “rejected”, “review”, “merged”, we searched

 Contibutors Charactersitics
Contributor characteristics relate to submitters (or developer) and
integrator (or committer). Some of the factors relate to individuals


### Pull request characteristics
Size of change is measured at commit-level (number of commits),
file-level (files added, deleted, modified and changed)
aswell as type of files changed (source, document and others).
### Dataset
Similar to the previous study by Gousios et al. [8], the new dataset
for pull-based development research builds on the publicly available
datasets hosted on GHTorrent5. We use the latest version of
Mysql data dump 6 (created on 1 June 2019) and complement it
with additional information (e.g. issue comments) provided in the
comparable version of MongoDB dump 7.
To create a large dataset of active and representative software
repositories, we applied several inclusion and exclusion criteria.


## Research 
The pull-based model provides a synthesized paradigm for distributed
collaboration, which has attracted global attentions in recent
years. In this paper, we create a comprehensive and large-scale
dataset collected from 11K+ representative OSS projects in GitHub,
and describe the creation process and explain all features in details.
Our dataset, in addition to supporting research on pull-based
development, provides new opportunities to the related research