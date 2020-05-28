# git terms

git has some terms that you'll need to learn in order to understand how everything works:

## Commit

Think of this as a "save point" of sorts. You make commits to mark a point in your code where you wish to track. Generally this is done after a sizable part of a feature youre working on has been completed so that you have that checkpoint to go back to if you need to.

## Staging

Before you commit something, you need to stage it. This is how you tell git what you want to keep a track of with the next commit.

## Branch

Branches are simply put a collection (or history) of commits. On larger collaborative projects you may have what we call "feature branches" which is a branch that a developer creates to work on individually so that they don't interfere with other developer's work.

## Merge

When you have two branches that you wish to combine the work of, you perform a merge. This unifies the code together in such a way that will hopefully not result in a...

## Merge conflict

For now you shouldn't need to worry *too* much about encountering a merge conflict, just know that they *generally* arise when the same area of code is modified by both branches. git tries to resolve these where it can if it can unambigiously figure out how to fit them both in, but if it can't figure it out then it rests on the developer to manually look at the changes being requested and fix them. We will be covering these much later on because working with other people (especially those who aren't good at listening to instructions) can cause these to pop up and you'll find yourself needing to fix them.

## Repository

You need somewhere to store these branches and other bits of information related to your project, and that is what the repository is. Generally speaking you will have a repository (or repo for short) per project, mixing and matching may cause headaches for you though as you get more proficient in git you'll learn when this is and isn't appropriate.

## Remote server

You can store repos locally on your machine, but this can make it harder for others to collaborate with you and also doesn't provide you with a backup if your repo decides to break or corrupt. The solution to this is remote servers where you can upload your repo. There are currently a lot of free options if you wish to store your projects online remotely (GitHub, GitLab, Bitbucket, etc) each with their own pros and cons, but they work the same way for the most part.

## Push

When you upload your changes to a repo to the remote server it is called a push.

## Pull

When you download the changes on the remote server to your local machine it is called a pull.

If you've understood all of these terms, then great! If not, then don't worry it can take some getting used to. git is a pretty abstract concept in of itself, but if you keep at it you'll get it in no time. Also, I can already hear the git ninjas out there screaming "oh but you forgot `x` term! It's super important!". While I get that there's a lot to git that is SUPER helpful and SUPER important (trust me, I know), for just the basics this will do for now.
