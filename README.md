android-app
===========

FIU ACM Android application

# Environment
Android Studio (IntelliJ)

# Committing code
Do not commit .idea files
Always pull before pushing

# Deployment Flow

## Main branches

### Dev - *develop* branch
Use  [git branch](http://git-scm.com/book/ch3-2.html) to create a *develop* branch of the codebase rather than making edits directly to the *master* branch
> 
>

### Staging
Once there's a realease candidate all all the code will be merged into a *staging* branch.
Use [git tag](http://git-scm.com/book/en/Git-Basics-Tagging) to tag a release candidate.
If last minute code/commits or code changes need to be made, do so in the *develop* branch.

### Production - *master* branch
The last train stop
Once testing has been performed in *staging*, and we have not been able to break the application, merge the code from *staging* into *master*.

## Supporting branches
These are the limited-life time branches, that will be removed

### Feature branches
### Release branches
### Hotfix branches

At the beginning each member will choose a feature to develop.
The feature branch will exitst as long as the feature is in development.
Once the feature has been completed, the code will be merged back into *develop*

A feature branch will exist in your local repo, not in *origin*

To start working on a new feature, branch off from the *develop* branch.

`git checkout -b myfeature develop`

# Code Style Guidelines

[Android](http://source.android.com/source/code-style.html)
[Java](https://google-styleguide.googlecode.com/svn/trunk/javaguide.html)

# Design Decisions
