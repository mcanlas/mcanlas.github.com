---
title: git instaweb
---
If you're on a Mac and you get a 404 when running `git instaweb`, make sure you have Xcode installed properly.

Without Xcode, `instaweb` will refer to a location where its CGI service does not exist.

Alternatively, this can be solved by using a different installation of `git` (provided via [`brew`](http://brew.sh/) for example).
