---
title : Packages 
id    : packages
wip   : true
---

Before writing a ton of code, check that it hasn't already been done before. NuGet is the place to go to find libraries and tools built by the .NET community.

Always favour packages built by the authors of the library. If you're not sure, write a proof of concept app with the package and if it suits the purpose you've just saved yourself the time of writing it yourself!

## Internal packages

When writing common libraries, the CI for those projects should be configured to output a NuGet package. These packages will be hosted within TeamCity's own NuGet feed. You can add that feed on your machine with the following command:

	nuget sources add -Name TeamCity -Source [url]
