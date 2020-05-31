# Phyio-App-API
Physiotherapy Application API Source Code


Git Branching Startegy:
----------------------


Commands
-------------

git checkout -b AIT-4

git push origin AIT-4

git branch -a

git remote add AIT-4

git status


Notes
-------------

<feature> => d0322948

d  => Development / q => QA / h => Hotfix

03 => Month

22 => Day

9  => Hours

48 => Minutes


Flow Diagram
----------------

master 

      => develop-ready 
  
		    => <Jira Ticket like AIT-4>

master (Deploy in Prod)

develop-ready (Deploy in QA/Dev)


Every month there will be new branch from develop-ready.

// delete branch locally

git branch -d localBranchName

// delete branch remotely

git push origin --delete remoteBranchName


Travis-CI
-------------

tavis.yml 
  
  => Every pull request and merge CI should run on all branch.



Docker
-------

docker-compose build







