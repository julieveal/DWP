# DWP
<<<<<<< HEAD
DEPLOYMENT PLAN FOR DWP Portfolio site

Merge branch into master branch
  $ git checkout master
    Get the most recent version of the project
  $ git pull github master
    github is the remote name for the github repository
  Merge the feature(s) to be tested with the master branch
    $ git merge
    Resolve any conflicts from the merge
  Test application
    Failures must be fixed before proceding
    Push new working version to github
    $ git push github master

Push new version to server
  $ git push JulieJulieLive master
    JulieJulieLive is the server name
  Test again
    Failures must be fixed before proceding
    Push new working version to github
    $ git push github master
  Announce server is working
    If not working start all over
=======

DEPLOYMENT PLAN FOR DWP Portfolio site

Merge branch into master branch
	$ git checkout master
	
    Get the most recent version of the project
    
  $ git pull github master
  
    github is the remote name for the github repository
    
  Merge the feature(s) to be tested with the master branch
  
    $ git merge
    
    Resolve any conflicts from the merge
    
  Test application
  
    Failures must be fixed before proceding
    
    Push new working version to github
    
    $ git push github master
    

Push new version to server

  $ git push JulieJulieLive master
  
    JulieJulieLive is the server name
    
  Test again
  
    Failures must be fixed before proceding
    
    Push new working version to github
    
    $ git push github master
    
  Announce server is working
  
    If not working start all over
    
>>>>>>> origin/master
