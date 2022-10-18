
This is a fork of the GitLab repository: https://gitlab.com/libeigen/eigen.

In order to update this fork with its source repo, you have to follow [these](https://stackoverflow.com/questions/65023718/how-to-fork-a-gitlab-repository-to-github) instructions:

 - `git remote add upstream https://gitlab.com/libeigen/eigen`
 - `git fecth upstream`
 - `git merge upstream/master`
 - `git push`

**Main** should be the source branch and **cmake-ludo-update** should be the working branch, were we can merge the updates through pull requests.

---

> **Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.**
> 
> For more information go to http://eigen.tuxfamily.org/.
> 
> For ***pull request***, ***bug reports***, and ***feature requests***,
> go to https://gitlab.com/libeigen/eigen.
