# Phyio-App-API
Physiotherapy Application API Source Code


Git Branching Startegy:
----------------------


Commands
-------------

git checkout -b feature-d0322948

git push origin feature-1

git branch -a

git remote add develop-d0114032020 feature-1

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
	     
		    => develop-d0114032020 
			 
			          => <feature>

master (Deploy in Prod)

develop-ready (Deploy in QA/Dev)


Every month there will be new branch from develop-ready.


Travis-CI
-------------

tavis.yml 
  
  => Every pull request and merge CI should run on all branch.



Docker
-------

docker-compose build







