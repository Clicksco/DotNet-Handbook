---
title  : Getting started
id     : getting-started
---

Before you dive in there's a few things you're going to need. There are also some bits and pieces that aren't necessary but are going to make your life a lot easier.

* **Visual Studio** *(required)*{.label .label-info}

	No brainer&hellip;
	
* [**Resharper**](http://jetbrains.com/resharper) *(highly recommended)*{.label .label-info}

	The one stop shop for code analysis, refactoring, and code completion. Comes with a built in test runner, live templates, and introduces a ton of useful keyboard shortcuts for navigation. If you want a copy we'll furnish you with a license.
	
* [**chocolatey**](http://chocolatey.org/) *(highly recommended)*{.label .label-info}

	This is a package manager for machine level applications. With a wave of your console you can install most of your favourite apps including the tools mentioned below.
	
	For example, `chocolatey install skype` (or `cinst skype` for short), will - you've guessed it - install skype.

* [**git**](http://git-scm.com) *(required)*{.label .label-info}

	We use git for [version control](#vcs) which means you're going need this to grab the source code.
	
	With chocolatey installed simple type `cinst git`

*	[**TortoiseGit**](https://code.google.com/p/tortoisegit/) /
	[**SourceTree**](http://www.sourcetreeapp.com/)
	*(recommended)*{.label .label-info}

	A GUI for managing git repositories. Although you can use the command line, they make working with git significantly easier. Each have their merits. Choose one, or both or neither.

		cinst tortoisegit
		cinst sourcetree

* **KDiff3** *(recommended)*{.label .label-info}

	A 3-way merge and diff tool. Miles better than many other similar tools out there.

* **NHProfiler** *(recommended)*{.label .label-info}

	If the project you're working on uses NHibernate you'll want to checkout NHProfiler

* [**nCurnch**](http://nchrunch.net) *(recommended)*{.label .label-info}

	Test as you type! WAT? Yes that's right. It compiles your code and runs your tests as you type. It displays indicators next to your code so you can see what code is covered by passing\failing tests and how long each line took to execute.
	
* [**TeamCity**](http://jetbrains.com/teamcity) *(recommended)*{.label .label-info}

	We use TeamCity for [continuous integration](#ci). Although it's not necessary to run TeamCity on your local machine doing so would allow you to monitor your local repositories and be confident when pushing your changes.
