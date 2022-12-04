# GitHub Repository for Learning Git by Anna Skoulikari

<img src="learning_git_cover.png" width=450>

This GitHub repository is meant to be used as a supplementary resource for Learning Git: A Hands-on Approach to Understanding the Basics of Git by Anna Skoulikari.

Table of Contents:

- [(Chapter 1) Installing Git for Microsoft Windows](#installing-git-for-microsoft-windows)
- [(Chapter 1) Installing Git for macOS](#installing-git-for-macOS)
- [(Chapter 6) Create a personal access token in GitHub](#create-a-personal-access-token-in-github)
- [(Chapter 6) Create an app password in Bitbucket](#create-an-app-password-in-bitbucket)
- [(Chapter 6) Set up SSH authentication](#set-up-SSH-authentication)
- [(Chapter 12) Creating a pull request (merge request)](#create-a-pull-request-merge-request)

## Installing Git for Microsoft Windows

To install Git for Microsoft Windows, go to [https://git-scm.com/download/win](https://git-scm.com/download/win).

For the Learning Git book, we recommend you use the first and main download option to install Git which provides an installer. To do so, select the **Click here to download** link. This will download an installer that you will use to go through the step-by step installation process. You should accept all the default settings as you go through the installer.

By using this download option to install Git, you will also have a version of Git installed which is definitely greater than 2.23 which is the minimum version we recommend in order to have access to all the commands in this book.

|     | Follow Along #-#                                                                                                                 |
| --- | :------------------------------------------------------------------------------------------------------------------------------- |
| 1   | On the **Select Destination Location** screen, accept the default location and select **Next**.                                  |
| 2   | On the **Select Components** screen, accept the default location and select **Next**.                                            |
| 3   | On the **Select Start Menu Folder** screen, accept the default location and select **Next**.                                     |
| 4   | On the **Choosing the default editor used by Git** screen, accept the default location and select **Next**.                      |
| 5   | On the **Adjusting the name of the initial branch in new repositories** screen, accept the default location and select **Next**. |
| 6   | On the **Adjusting your PATH environment** screen, accept the default location and select **Next**.                              |
| 7   | On the **Configuring the line ending conversions** screen, accept the default and select **Next**.                               |
| 8   | On the **Configuring the terminal emulator to use with Git Bash** screen, accept the default and select **Next**.                |
| 9   | On the **Choose the default behavior of `git pull`** screen, accept the default and select **Next**.                             |
| 10  | On the **Choose a credential helper** screen, accept the default and select **Next**.                                            |
| 11  | On the **Configuring extra options** screen, accept the default and select **Next**.                                             |
| 12  | On the **Configuring experimental options** screen, accept the default and select **Next**.                                      |
| 13  | On the **Completing the Git Setup Wizard** screen, select **Finish**.                                                            |

## Installing Git for macOS

To install Git for macOS, go to [https://git-scm.com/download/mac](https://git-scm.com/download/mac).

For the Learning Git book, we recommend you use Homebrew to install Git. To install Git using Homebrew, you must have Homebrew installed. If you don’t have Homebrew installed then you must download it from the official Homebrew website [https://brew.sh/](https://brew.sh/).

By using Homebrew to install Git, you will also have a version of Git installed which is definitely greater than 2.23 which is the minimum version we recommend in order to have access to all the commands in this book.

|     | Follow Along #-#                                                                                                                                                                                         |
| --- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Go to the Homebrew website [https://brew.sh/](https://brew.sh/) and copy the command to install Homebrew.                                                                                                |
| 2   | Open a command line window and paste the command to install Homebrew where the cursor is. The directory location in the command line is not important when you execute this command in step 3.           |
| 3   | $ <strong>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"\</strong><br>===> Checking for `sudo` access (which may request your password)...<br>Password: |
| 4   | When the command prompts you to enter a password, enter the password for your user on your computer.                                                                                                     |
| 5   | To complete the installation press Enter.                                                                                                                                                                |
| 6   | \$ **brew --version**<br>Homebrew 3.6.7<br>Homebrew/homebrew-core (git revision 4917c76d4d2; last commit 2022-10-29)                                                                                     |

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
