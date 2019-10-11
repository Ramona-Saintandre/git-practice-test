**10/4/2019** Links

Today I am learning how to add an image to a readme file in github.
I am also working on linking in Github.
Here is a link to some [Resources](gitresources.md) that I used to help me with this. 
Give it a try, when your done don't forget to do a PR. 
[GitHub Readme Images Tutorial ](https://www.youtube.com/watch?v=hHbWF1Bvgf4)

**10/7/2019** 

Adding images 

Having issues with my repo on Github, so I am a little late with getting the image. 
I did put an image on the git-journey page.
It works fine, but when I try this way as per the video, I an not get it to render. 
I did do a gitmerge on this repo, now I just need to figure out how to merge my branch. 
gray folder issue <img src= "./git-practice-test/images/github-gray-folder.png">

 **10/10/2019**  

I have two pull requests that I need to figure out how to merge. 
So my goal today is to merge, and close these pull request. 
Still have not figured out how to fix the grayed out folders in GIThub. 

**10/11/2019**

All right having some real issues now. 
Trying to fix an issue via Github's instruction. 

Conflicting files
Checklist.md
git-practice-test/gitlearn.md
git-practice-test/monas-git-journey.md
 You can also open this in GitHub Desktop or view .
Checkout via command line
If you cannot merge a pull request automatically here, you have the option of checking it out via command line to resolve conflicts and perform a manual merge.

HTTPS
Git
Patch
https://github.com/thenewmona/Monas-Hacktoberfest2019.git
Step 1: From your project repository, bring in the changes and test.

git fetch origin
git checkout -b monas-algorithms origin/monas-algorithms
git merge master
Step 2: Merge the changes and update on GitHub.

git checkout master
git merge --no-ff monas-algorithms
git push origin master
I got this. 


ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (master)
$ git fetch origin

ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (master)
$ git checkout -b monas-algorithms origin/monas-algorithms
Switched to a new branch 'monas-algorithms'
Branch 'monas-algorithms' set up to track remote branch 'monas-algorithms' from 'origin'.

ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (monas-algorithms)
$ git merge master
Unlink of file 'cutter' failed. Should I try again? (y/n) y
Unlink of file 'cutter' failed. Should I try again? (y/n) n
Auto-merging git-practice-test/monas-git-journey.md
CONFLICT (content): Merge conflict in git-practice-test/monas-git-journey.md
Auto-merging git-practice-test/gitlearn.md
CONFLICT (content): Merge conflict in git-practice-test/gitlearn.md
Removing cutter
Automatic merge failed; fix conflicts and then commit the result.



ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (monas-algorithms|MERGING)
$ git checkout master
error: you need to resolve your current index first
git-practice-test/gitlearn.md: needs merge
git-practice-test/monas-git-journey.md: needs merge

ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (monas-algorithms|MERGING)
$ git merge --no-ff monas-algorithms
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

ramonas@ISops31 MINGW64 /c/source/Monas-Hacktoberfest-2019 (monas-algorithms|MERGING)
$ git push origin master

Looks like I am going to have a fun day with this.
Then I will really need to clean up and format this readme, to make it legalable.  

Not sure if I have fixed my grayed out folders or not. 
Opening up folder's in VSC , I noticed that there was nothing in them. 
So I went into file explorer and verified that all the folders were in deed empty. 
So I have deleted all of the empty folders. 
I have cloned a new repo that I have never cloned before. 
[Hacktoberfrest-2019-Angular](https://github.com/thenewmona/hacktoberfest-2019-angular.git)  
I am now going to commit these changes and see what happens on Github. 

Ok so I had no errors this time doing the commit or the push.
All the folders Repo's are gone.  
Except for the Cutter and Angular folder.   
I have verified that they are not empty, but they are still grayed out in github. 