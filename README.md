# Case-Study-1

1. For this case study I'm suggesting Zendrix Softwares to use standard Git Workflow 
architecture. It would consist of the following branches:
master
f1
f2
hotfix

2. All changes must be done befor 25th of every month, particularly any changes to 
hotfix must be ready and tested by 24th. This way, the product releases can happen 
on 25th only.

3. WorkFlow:
   merge f2 --> f1 --> master.
   create hotfix branch, and add urgent.txt file (stage & commit the file, stash it, then unstash it by 24th).
   then merge hotfix --> master.
