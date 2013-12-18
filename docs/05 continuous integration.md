---
title : Continuous Integration 
id    : ci
wip   : true
---

One of the first things to do on a project should be to setup continuous integration for it. Once you've got a Git repository and a solution with some projects, it's incredibly easy to create a new project on TeamCity which will build the solution, and run the tests every time you commit to the repository.

A continuous integration server can do a lot more, like notify you when the build breaks, publish the build artefacts, host NuGet packages, even run custom scripts.

Once the continuous integration server has done its job, there should only be one step left. Deploy.