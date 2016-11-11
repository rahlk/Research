Skip to content
This repository
Search
Pull requests
Issues
Gist
 @rahlk
 Unwatch 4
  Star 0
 Fork 0 ai-se/XTREE_IST Private
 Code  Issues 3  Pull requests 0  Projects 0  Wiki  Pulse  Graphs  Settings
XTREE_IST/ 
Reviewers_comments.md
   or cancel
    
 Edit file    Preview changes
1
# Comments from the editors and reviewers
2
​
3
![image](https://cloud.githubusercontent.com/assets/1433964/20149973/8902ced6-a681-11e6-8ad2-3f796cb1807c.png)
4
​
5
### Editor
6
​
7
Dear Authors, 
8
The reviewers have finished evaluating your work. As you can observe, they raised some concerns that deserve your attention. It is important that you take into account their comments and evolve the paper accordingly. Please,  evolve the paper to make clear the defect model, hypothesis, limitations and readability and prepare a letter of changes explaining all modifications made. 
9
​
10
​
11
### Reviewer 1
12
​
13
- This paper presents the results of a case study regarding the likelihood that a code reorganization to address bad code smells will yield improvement in the defect proneness of the code. Five research questions were investigated and results pointed out that code modules that are changed in response to XTREE’s recommendations contain significantly fewer defects than recommendations from previous studies. Further, XTREE endorses changes to very few code metrics and the bad smell recommendations are not universal to all software projects.
14
​
15
This work provides useful insights to support the hard task to decide where to put efforts to reorganize code in software projects. This is an old problem in the software evolution area but that requires continuous investigation due to the new scenarios we face when developing software projects.
16
​
17
In overall, I enjoyed to read the paper and I think it is well structured. Despite this, some suggestions that I´d like to see incorporated in the paper are:
18
​
19
1- I missed a section discussing possible implications for researchers and practitioners. How the results of this work contribute to future research activities in the area? How can practitioners benefit from the results achieved in the paper?
20
​
21
2- I also missed a section presenting the main limitations of the work. Although some words have been said about it, I believe it is important to have a more structured discussion on a specific section.
22
​
23
3- It would be interesting to have further discussion at the end indicating how this work complements the body of knowledge about code smells (specifically, on the elimination of them in software projects). Do reached results indicate a similar direction? contradictory? Does This work somehow confirm the results of other studies or points to new directions?
24
​
25
Another point is: this work evaluated XTREE , a framework to evaluate whether a code reorganization is likely to have a perceivable benefit in terms of defect-proneness. It is fine to have this scope (defect-proneness) in terms of evaluation. However, it would be nice to have a discussion on why this characteristic (defect-proneness) is good to support the decision on code reorganization and/or how it could complement other characteristics. For instance, nowadays we are seeing a growing discussion on technical debt, that brings financial aspects (interest, principal, debt…) to the decision-making process on development activities. Could we use XTREE as a strategy to prioritize the payment of technical debt items?
26
​
27
Finally, I have one last question: is there any reason for do not use the GQM template to state the goal of the study and also to define null and alternative hypotheses for the research questions? 
28
​
29
​
30
- Reviewer 2
31
​
32
- This paper is about a tool that investigates a log of historical defects to suggest changes that will reorganize code to reduce the defect-proneness of the code. The motivation is that often code reorganization (refactoring) is carried out to remove code bad smells even though such smells do no increase the likelihood of defects in a given setting. That kind of reorganization would then be wasted effort. 
33
​
34
I sympathize with this approach. Software development is certainly dependent on many context factors. So learning the effect of various smells in a given context as input to how to deal with the smells is “intelligent”, as the title of the paper indicates.
 
@rahlk
Commit changes


Update 

Add an optional extended description…
  Commit directly to the master branch.
  Create a new branch for this commit and start a pull request. Learn more about pull requests.
Commit changes  Cancel
Contact GitHub API Training Shop Blog About
© 2016 GitHub, Inc. Terms Privacy Security Status Help
