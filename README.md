# GitHub Repository for Learning Git by Anna Skoulikari

<img src="learning_git_cover.png" width=450>

This GitHub repository is meant to be used as a supplementary resource for Learning Git: A Hands-on Approach to Understanding the Basics of Git by Anna Skoulikari.

Table of Contents:

- [(Chapter 6) Create a personal access token in GitHub](#create-a-personal-access-token-in-github)
- [(Chapter 6) Create an app password in Bitbucket](#create-an-app-password-in-bitbucket)
- [(Chapter 6) Set up SSH authentication](#set-up-SSH-authentication)
- [(Chapter 12) Creating a pull request (merge request)](#create-a-pull-request-merge-request)

## Set up HTTPS authentication

## Create a personal access token in GitHub

In Chapter 6 of Learning Git, you are instructed to choose a hosting service and set up an authentication method. If you choose to use the HTTPS authentication method and you are using GitHub, you must create a personal access token.

The instructions for how to create a personal access token in GitHub are available at: [GitHub Docs - Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

While going through the instructions above, keep in mind the below notes that were presented to you in Chapter 6.

When creating the personal access token in GitHub:

- The Note field represents the name for the personal access token
- When selecting an expiration time, we recommend choosing at minimum a time period within which you can finish reading and doing the exercises in the entire book. Otherwise, your personal access token may expire while you're going through the book and you will have to go through the process to create a new one to complete the exercise in the book.
- The scope defines what this token will have access to do or authenticate. For the purpose of this book, you must select at least the repo scope.
- Save the personal access token in a safe place.

## Create an app password in Bitbucket

In Chapter 6 of Learning Git, you are instructed to choose a hosting service and set up an authentication method. If you choose to use the HTTPS authentication method and you are using Bitbucket, you must create an app password.

The instructions for how to create an app password in Bitbucket are available at: [Bitbucket Support - Create an App password](https://support.atlassian.com/bitbucket-cloud/docs/create-an-app-password/).

While going through the instructions above, keep in mind the below notes that were presented to you in Chapter 6.

When creating an app password in Bitbucket:

- The Label field represents the name for the app password.
- The permissions describe what this app password will be able to authenticate. For the purposes of this book you should select at least the options under the sections, Account, Workspace membership, Projects, Repositories, and Pull Requests.
- Save the app password in a safe place.

## Set up SSH authentication

In Chapter 6 of Learning Git, you are instructed to choose a hosting service and set up an authnetication method, either HTTPS or SSH. If you choose to use the SSH authentication method, then you may use the links below that provide instructions for how to set up SSH authentication for each hosting service.

GitHub

- [GitHub Docs - Connecting to GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

GitLab

- [GitLab Docs - Use SSH keys to communicate with GitLab](https://docs.gitlab.com/ee/user/ssh.html)

Bitbucket

- [Bitbucket Support - Set up an SSH key](https://support.atlassian.com/bitbucket-cloud/docs/set-up-an-ssh-key/)

## Create a pull request (merge request)

In Chapter 12 of Learning Git, you are instructed to create a pull request in the `rainbow-remote` repository. For more information on how to do this in each hosting service, see:

GitHub

- [GitHub Docs - Creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Additional notes: You may skip the overview content and go directly to the numbered list of setps in the [Creating the pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request?tool=webui#creating-the-pull-request) section.

GitLab

- [GitLab Docs - Creating merge requests](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)

Additional notes: I recommend you use the instructions provided in the [From the merge request list](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html#from-the-merge-request-list) section.

Bitbucket

- [Bitbucket Support - Create a pull request](https://support.atlassian.com/bitbucket-cloud/docs/create-a-pull-request/)

Additional notes: You may skip the overview content and other sections and go directly to the [Create a pull request](https://support.atlassian.com/bitbucket-cloud/docs/create-a-pull-request/#Create-a-pull-request) section.
