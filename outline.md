# Abstract:
This skill-up session is targeted towards novice contributors to the Carpentries lessons.
You should already have some experience using Git --- attending a Software Carpentry workshop
is sufficient.

By the end of the session you will:
- be able to make a pull request
- know what makes a good PR
- how to edit/update your PR

# Outline
## How the carpentries lessons are organised
- Lessons all use the same [structure](http://carpentries.github.io/lesson-example/03-organization/index.html)
- Content written as markdown files in `_episodes` directory
- Markdown files formatted with [special blockquotes](http://carpentries.github.io/lesson-example/04-formatting/index.html)
- Syntax highlighting available
- Local preview of site available using Jekyll

## How to make a PR:
- fork repo
- create new branch
- make changes
- push to origin
- make PR

## How to update a PR:
- maintainer requests changes
- check out your branch and make changes
    - another commit
    - reset
    - rebase
- (force) push your branch to origin
- PR automatically updates

## How to rebase your PR:
- you submitted a PR, but there have been new commits since, and your PR can't be merged due to conflicts
- check out your branch
- pull -rebase
- fix conflicts
- (force) push again

## What makes a good PR:
- Maybe discuss in issues first
    - get approval before committing your time
    - don't duplicate anything which already exists
- Does one thing only
- Title indicates what the PR is about
	- Include episode number, link to section, quote of text being discussed
- Uses good commit messages


