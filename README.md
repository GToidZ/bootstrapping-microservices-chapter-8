# [Bootstrapping Microservices](https://www.bootstrapping-microservices.com/) Chapter 8

This repository contains code examples 1, 2 and 3 from chapter 8 of said book.

This is created because all the examples have different repositories and if you want to test them out, you are required to fork a lot of repositories.

Each of the workflows are referenced from each subdirectory, `example-1`, `example-2` and so on.

Each subdirectory will contain the workflow YAML, though they are not used by GitHub Actions, in `.github/workflows` directory will have those YAML named as respective subdirectory already.

## List of Changes
Here are the things you need to know if you're using this repository,
* Example 2 and 3 has automatic workflow runs disabled, you only need to run them from Actions tab.
* Example 2 and 3 does not use your changes, in fact there are no source code from original repositories,
  * The workflows uses original source from their public GitHub repo. If you want to modify it to work for yourself, see the checkout action.