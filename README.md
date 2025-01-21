## GIT-1 / lesson-1 / git & github


# [What is GitHub](https://www.w3schools.com/whatis/whatis_github.asp)

![image](https://github.com/user-attachments/assets/06a50891-08c0-443b-a12f-a68b8c0c318f)

*GitHub is a code hosting platform for collaboration and version control.*

*GitHub lets you (and others) work together on projects.*

*GitHub essentials are:*
- Repositories
- Branches
- Commits
- Pull Requests
- Git (the version control software GitHub is built on)

** Example **

```
$ git push origin heroku
$ cd /etc/
$ ls
```

### Repository

A GitHub **repository** can be used to store a development **project**.

It can contain **folders** and any type of **files** ( <ins>HTML,  </int> <ins>CSS,  </int> <ins>JavaScript,  </int> <ins>Documents,  </int> <ins>Data,  </int> <ins> Images</int>).

A GitHub repository should also include a **licence** file and a __README__ file about the project.

A GitHub repository can also be used to store ideas, or any resources that you want to share.

### Branch

A GitHub branch is used to work with different **versions** of a repository at the same time. 

By default a repository has a **master** branch (a production branch).

Any other branch is a **copy** of the master branch (as it was at a point in time).

New Branches are for bug fixes and feature work separate from the master branch. When changes are ready, they can be merged into the master branch. If you make changes to the master branch while working on a new branch, these updates can be pulled in.

### Commits

> At GitHub, changes are called commits.

> Each commit (change) has a description explaining why a change was made.


### Pull Requests

Pull Requests are the heart of GitHub _collaboration._

With a pull request you are _proposing_ that your changes should be _merged_ (pulled in) with the master.

Pull requests show content _differences_, changes, additions, and subtractions in _colors_ (green and red).

As soon as you have a commit, you can open a pull request and start a discussion, even before the code is finished.

# What is Git: Features, Commands, Branch and Workflow in Git


_Git_ is a _DevOps_ tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. Linus Torvalds created Git in 2005 for the development of the Linux kernel.

```
Transform your DevOps career and learn the science of improving the operational and developmental activities by choosing our PGP in DevOps. Contact our admission counselor today and grab your seat!
```

Before diving deep, let’s explain a scenario before Git:

- Developers used to submit their codes to the central server without having copies of their own
- Any changes made to the source code were unknown to the other developers
- There was no communication between any of the developers

  ![image](https://github.com/user-attachments/assets/b592f036-875c-467d-a4f4-fca301a6b9d3)

Now let’s look at the scenario after Git:

- Every developer has an entire copy of the code on their local systems
- Any changes made to the source code can be tracked by others
- There is regular communication between the developers

- ![image](https://github.com/user-attachments/assets/fbfca28d-6f44-40da-9efd-7aa3f01479e9)

