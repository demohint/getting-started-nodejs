
$ git clone https://github.com/demohint/getting-started-nodejs.git

$ cd node-js-sample

$ git remote add dokku dokku@dokku.tk:getting-started-nodejs.git

$ git push dokku master


Counting objects: 296, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (254/254), done.
Writing objects: 100% (296/296), 193.59 KiB, done.
Total 296 (delta 25), reused 276 (delta 13)
-----> Building getting-started-nodejs ...
       Node.js app detected
-----> Resolving engine versions

... blah blah blah ...

-----> Application deployed:
       http://getting-started-nodejs.dokku.tk



$ git clone git@github.com:demohint/getting-started-nodejs.git


Cloning into 'getting-started-nodejs'...
remote: Counting objects: 24, done.
remote: Compressing objects: 100% (19/19), done.
remote: Total 24 (delta 5), reused 17 (delta 1)
Receiving objects: 100% (24/24), done.
Resolving deltas: 100% (5/5), done.
Checking connectivity... done


$ cd getting-started-nodejs

$ wercker create

$ git add wercker.yml

$ git commit -m 'wercker.yml added'

$ git push origin master



[![wercker status](https://app.wercker.com/status/b6deef93f27ddd5da1f84d1849d2caa7/m "wercker status")](https://app.wercker.com/project/bykey/b6deef93f27ddd5da1f84d1849d2caa7)
