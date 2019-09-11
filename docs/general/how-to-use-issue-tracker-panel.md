---
id: how-to-use-issue-tracker-panel
title: How to use “Issue Tracker” panel
sidebar_label: How to use “Issue Tracker” panel
---

“Issue Tracker” counts lines of code in each issue. Sleeek links each commit to an issue number by reading the commit log. That’s why an issue number must be described in commitment logs at GitLab or GitHub repository management.

Here are examples:
```
$ git commit -m “Fix typos reported by issue #4”
$ git commit -m “#8 Add build script”
$ git commit -m “#35 Add asserts for properties”
```
