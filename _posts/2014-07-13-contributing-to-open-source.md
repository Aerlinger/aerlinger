---
layout: post
title:  "How to contribute to open source"
date:   2014-03-03
tags: open_source
comments: true
---


# How to get started contributing to Open Source projects

Open source software (OSS) is competitive. As such, developers of all ability levels
generally have a "mental block" when it comes to submitting a contribution.
Having been involved in various projects, I wanted to share some things I've
learned that I wish I would have known sooner.


### Before you start
*Most of these seem obvious, but it's always good to make sure you've got
your bases covered.*

  1. **Familiarize yourself with the codebase.** This doesn't mean being an
expert (there's no such thing). However, all codebases have a general
organization and structure, you should know every top-level folder.
Pareto's law states that 80% of the effects come from 20% of the causes.
Software is no exception. As such, you should know the most commonly
used classes/modules/namespaces/files and so on...
  2. **Familliarize yourself with the community.**: Again, you don't
  3. **Read the Readme and the document on contributing, if any** Almost all large projects have
a document like this that outlines the requirements for a contribution
to even be considered. Usually, these are basically guidelines for
things like conventions, style, testing, documentation, and so on.
  4. **Read and know the license** If the project doesn't have one, it's best to
submit an issue or contact the author if possible. In general a software
project may use one of several standard licenses.
  5. Read up on the recent Issues, Pull requests. In a large project
there can literally be thousands of these. Obviously, you don't have to
know all of them, but it's good to know the general direction of
development.


### Getting your feet wet

  1. Familiarize yourself with the projects git history.
  1. **Identify low-risk changes you can make:** If you're making your first
pull-request to a repository, try to introduce a change that's
relatively low risk. Look at it from the perspective of the project owner. If you're not a familiar face, it's going to be much
harder to get a pull request merged. Thus, you'll initially want to make small merges,
preferably on non "mission critical" parts of the system. Some example may include:
    - Improving documentation (this includes inline comments)
    - Adding tests
    - Improve the wording of logging messages such as warnings, errors,
etc...
  2. Post on community challenges to get feedback on what you're planning on doing _before_ you start.
  Like I said, OSS is very competitive so it's likely that what you're proposing may have already been done or is in the process of being done.
  3. **Always add tests and proper documentation:**
  4. **Rebase key branches constantly** This means constantly running `git pull -r` on the master/development branches.


Again, these are just a few quick pointers.

##Additional Resources

  1.
