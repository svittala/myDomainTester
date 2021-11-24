myDomainTester
====================

A simple example to brand your Salesforce My Domain

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/svittala/myDomainTester)

The new design of https://login.salesforce.com requires that your My Domain page is responsive.   It will automatically scale up and down depending on the size of a user's browser.   This sample should aid with that.

The page itself will scale up on both veritical and horizontal dimensions indefinetely.   The minimum width is 511px;

to make changes -
1) make html changes
2) add changes git add changefile 
3) commit changes git commit -m 'i made changes'
4) deploy to heroku git push heroku main 
5) application updated - https://calm-hamlet-31447.herokuapp.com/
        svittala@svittal-ltmcfm9 myDomainTester % git remote -v                            
        heroku	https://git.heroku.com/calm-hamlet-31447.git (fetch)
        heroku	https://git.heroku.com/calm-hamlet-31447.git (push)
        heroku-calm	https://git.heroku.com/sunskymydomainsample01.git (fetch)
        heroku-calm	https://git.heroku.com/sunskymydomainsample01.git (push)
        origin	https://github.com/svittala/myDomainTester.git (fetch)
        origin	https://github.com/svittala/myDomainTester.git (push)
6) just push changes to regular git repositoru - git push - 
