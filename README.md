oneday-conf-template
====================

base repo for one day conferences

To create the website for a new conference
==========================================
1. create a new empty repository
2. add this repo as a remote
3. create a "gh-pages" branch; checkout it
4. pull this repo's master branch to the new repo's gh-pages branch
5. set the upstream branch on origin: git push --set-upstream origin gh-pages
6. remove the README.md file
7. write the DNS cname record in the CNAME file: 201x.newconfday.it
8. push to origin
9. set the CNAME record on DNS
