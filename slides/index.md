- title : Git intro
- description : Short presentation about GIT and Git flow
- author : Olav Nybø
- theme : sky
- transition : default

***

## Git

- Clone from TFS
- Git flow
- Tools og Git 101
    - Source tree
    - GitFlow for Visual Studio

***
### Migration TFS -> GIT
#### Oppskrift her
https://github.com/git-tfs/git-tfs/blob/master/doc/usecases/migrate_tfs_to_git.md

Det viktigste er å kjøre
    git tfs clone collection --with-branches

---
## Men
- Vi fikk det ikke til å fungere på web claims
- Clonet uten historie
- Planen var å beholde repository i TFS for historie
- Men vi har ikke tilgang?
- Foreløpig ikke noe stort problem

***

# Git flow
- En mulig branchingstrategi
    - Centralized, Feature Branch, Forking
- Vincent Dressen, 2010
    - http://nvie.com/posts/a-successful-git-branching-model/

---
![git flow basic](images/gitflow.svg)

<p style="font-size: 8px;"> source: &nbsp; https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow </p>

---
![git flow release](images/gitflow-release.svg)


<p style="font-size: 8px;"> source: &nbsp; https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow </p>

***
## SourceTree
http://www.sourcetreeapp.com/

---
#### Open repository
![source tree open](images/Sourcetree-open.png)

---
#### GIT Clone
![git clone](images/git_clone.png)

---
#### GIT Add Commit and Push
![git add commit push](images/git_add_commit_push.png)

---
#### GIT Fetch Merge Pull
![git fetch merge pull](images/git_fetch_merge_pull.png)

---
#### GIT Branches
![git Branches](images/git_branches.png)

---

### SourceTree commit and push
![SourceTree commit](images/sourcetree_commit.png)

---
## GitFlow for Visual Studio
- godt alternativ til SourceTree om en ikke har node foldere i prosjektet
https://visualstudiogallery.msdn.microsoft.com/27f6d087-9b6f-46b0-b236-d72907b54683

![GitFlow extension](images/GitFlow_extension.png)

***

### Erfaringer
- Mye kjappere
- npm og windows er ikke gode venner
- En bedre utvikler hverdag
