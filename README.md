# OpenGenus-Internship

Published articles during my intern @OpenGenus at [link](https://iq.opengenus.org/author/nishkarsh)

[1. HTML Elements: Tables](https://iq.opengenus.org/p/00a9c8b3-56c0-4478-a3cb-bd3463ca824d/)

[2. HTML Features: Drag and Drop](https://iq.opengenus.org/p/ff80ce9a-cafd-498f-a13f-9d42b64e2382/)

[GitHub link](https://github.com/OpenGenus/drag_and_drop)

[3. HTML Elements: Lists](https://iq.opengenus.org/p/76be2c6a-dfa5-4309-a943-b3cf6c9159e4/)

[GitHub link](https://github.com/OpenGenus/html_lists)

[4. HTML Elements: Class and Id attribute](https://iq.opengenus.org/p/381f01f6-ffb8-42d2-9749-2cf17e37c1c1/)

[5. HTML Links with targets](https://iq.opengenus.org/p/5c000ffb-2543-4d08-b164-bb7425080b60/)

[6. CSS Elements: Border](https://iq.opengenus.org/p/37cb4569-ddb5-42df-a037-4eaa0467f9a1/)

[GitHub link](https://github.com/OpenGenus/cosmos/tree/master/code/html)

[7. CSS Elements: Margin](https://iq.opengenus.org/p/3d903d6a-9078-4e1a-919b-bd4545f92d19/)

[GitHub link](https://github.com/OpenGenus/cosmos/tree/master/code/html/css/Margin)

[8. CSS Elements: Padding](https://iq.opengenus.org/p/28def0b3-dffb-487f-9533-8b31999f903f/)

[GitHub Link](https://github.com/OpenGenus/cosmos/tree/master/code/html/css/Padding)

[9. CSS Positioning: Z-index](https://iq.opengenus.org/p/b0438af0-9030-4674-84b9-b41535e9405b/)

[10. CSS Positioning](https://iq.opengenus.org/p/09ad1629-d6b8-44f3-a67d-786aa0d8af90/)

[11. Apache Maven=> Create a Java project using Command line](https://iq.opengenus.org/p/269eac7c-0d17-49f0-885f-4a60eeeebb89/)

[12. Sidebar implementation in HTML](https://iq.opengenus.org/p/ffcc4c42-2a26-4734-a9d8-8c46872f1e96/)

[13. Shell Scripting Basics](https://iq.opengenus.org/p/6243f090-8ebe-408b-9f33-862c6cd34a92/)

[GitHub](https://github.com/NishkarshRaj/Automation-using-Shell-Scripts)

[14. Shell Scripting Looping Structures](https://iq.opengenus.org/p/46b0da11-d18c-4207-b7c0-1846c491ead0/)

[15. Shell Scripting Control Structures](https://iq.opengenus.org/p/d001de93-adda-47bd-be09-bcfb4eea165e/)

[16. Functions in Shell Scripts](https://iq.opengenus.org/p/366ad415-f632-409b-a0bb-d381d4826ebb/)

[17. Full Stack Calculator Project using DevOps tools](https://iq.opengenus.org/p/e028bbde-153d-460f-bc27-32bdbf723bd2/)

[GitHub Link](https://github.com/OpenGenus/calculator_devops)

[18. Automated Backup in Linux](https://iq.opengenus.org/p/92fcff89-71d7-4f53-b62d-2aba4648b7af/)

[19. Crontab Scheduler](https://iq.opengenus.org/p/a74916c8-143f-445f-91cf-073d4af49e5a/)

[20. GNU Tape Archiver Compression tool for Unix like systems](https://iq.opengenus.org/p/d909afac-8f3a-4784-9755-b892f565cd32/)

[21. SonarQube for Code coverage and Analysis](https://iq.opengenus.org/p/64ed0039-cbd7-47db-8506-291e83bf3b37/)

[22. GitHub Actions](https://iq.opengenus.org/p/d16feff6-8a76-43e1-bc5b-d70048eb046a/)

[GitHub Link](https://github.com/NishkarshRaj/GitHub-Actions-Tutorial)

[23. Introduction to Containerization using Docker](https://iq.opengenus.org/p/862c8581-19a9-48e1-8d87-47a34235c1be/)

[GitHub Link](https://github.com/NishkarshRaj/Dockerfile-Basics)

# How to collaborate

## Fork a repository

```git
$ git clone "Upstream repository URL"
$ cd <Repository name>
$ git fork
```

## Synchronizing forked repository with upstream repository (source of fork)

```git
$ git remote add upstream "<url of upstream>"
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
$ git push -f origin master
```

## Creating a workflow on another branch

```git
$ git branch <feature_branch>
$ git checkout <feature_branch>
```

Do your work on this branch and then perform following steps

```
$ git add <files>
$ git commit -m "commit message"
$ git push -f origin <feature_branch>
```

## Creating pull request

Create a pull request from your fork's feature branch to upstream's master branch.

[GitHub Documentation](https://help.github.com/en/articles/creating-a-pull-request)

## Merge a pull request (Code review if owner of repository)

**Step 1: Merge changes on local machine**
```git
$ git fetch origin
$ git checkout -b <branchname> origin/<branchname>
$ git merge master
```

**Step 2: Merge the changes and update on GitHub.**
```git
$ git checkout master
$ git merge --no-ff <branchname>
$ git push origin master
```
