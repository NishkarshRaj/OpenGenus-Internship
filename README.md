# OpenGenus-Internship

[Link to my Blogs @ OpenGenus](https://iq.opengenus.org/author/nishkarsh/)

Published articles during my intern @OpenGenus

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

# How to collaborate

## Fork a repository

```git
$ git clone "original repo url"
$ cd <og repo>
$ git fork
```

## Synchronizing forked repository with original repository

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
