Description
===========

This is a simple git sub-command that can be used to create a remote copy of your Git repository.
Note that _all the local branches_ are pushed.

Especially useful when publishing a repo to GitHub.

Installation
============

Copy the git-share to a directory included in your PATH, e.g. /usr/local/bin:

    $ sudo install -m 755 ./git-share /usr/local/bin

Examples
========

GitHub:

    $ git share git@github.com:myuser/myrepo.git

Any repository managed using Gitosis:

    $ git share git@server.com:path/to/myrepo.git
