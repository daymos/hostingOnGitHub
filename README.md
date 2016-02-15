# hostingOnGitHub

This tutorial explains how to host static pages on github. At the end of this you will be able to host for free you pages on github and to assign **customs URLs to them**.

The service is called Github Pages, and is very easy to use from your current github account.
You can find their official tutorials here: https://pages.github.com/.
Their tutorial is very well done, but I try to put all the useful extra info that I didn't find right away on their guide.

## Setup a repository

Create a new repository: ![pic1](https://github.com/daymos/hostingOnGitHub/blob/gh-pages/img/pic1.png)
The name of the repo must follow this standard: _yourUsername_.github.io.
This is the URL you will be using to access your website from a browser.  
This is according to the github guide. However I found that if you plan to use a custom domain, you can call this anything and don't need to follow the standard.  
The repo can be public or private, but be aware that the even if you set it on private the page will be available at _username_.github.io

## Clone the repo in your local machine

`$ git clone https://github.com/username/username.github.io`

## Add your website to the repo. 
Copy paste all your website files inside the repo folder. If you want to try yourself [here]() you can find a generic landing page.

`git add --all`  
`~$git commit -m "Initial commit"`  
`~$git push -u origin master`  


