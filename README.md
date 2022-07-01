# GitHub Glossary

## Base branch

> The [branch](#branch) into which changes are combined when you [merge](#merge) a pull request. When you create a pull request, you can change the base branch from the repository's default branch to another branch if required.

## Branch

> A branch is a parallel version of a [repository](#repository). It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can [merge](#merge) your branch back into the main branch to publish your changes.

## Clone

> A clone is a copy of a [repository](#repository) that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

## Commit

> A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

## Default branch

> The [base branch](#base-branch) for new pull requests and code commits in a repository. Each repository has at least one branch, which Git creates when you initialize the repository. The first branch is usually called main, and is often the default branch.

## Merge

> Merging takes the changes from one [branch](#branch) (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

## Merge conflict

> A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

## Pull request

> Pull requests are proposed changes to a [repository](#repository) submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.

## Push

> To push means to send your [committed](#commit) changes to a remote [repository](#repository) on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

## Remote

> This is the version of a [repository](#repository) or [branch](#branch) that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

## Repository: 

> A repository is the most basic element of GitHub. They're easiest to imagine as **a project's folder**. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


