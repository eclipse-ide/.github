# Contributing to Eclipse

Thanks for your interest in contributing to Eclipse.
Contributions are more than welcome and are a great opportunity to join a vibrant community, learn new skills, and make a real impact!

This document is intended to guide you through the general contribution process.
Although each Eclipse project has its own specific workflow and rules, the basic initial steps are are the same in all cases

1. [Creating an Eclipse Development Environment](#creating-an-eclipse-development-environment)
2. [Setting up an Eclipse and GitHub Account and legal requirements](#setting-up-an-eclipse-and-github-account)
3. [Submitting a contribution to a Eclipse project hosted at Github](#submitting-a-contribution-for-a-project-hosted-at-github)

## Creating an Eclipse Development Environment

To provision an Eclipse installation and workspace to work on Eclipse we recommend to use the Eclipse Installer powered by `Eclipse Oomph`.

Most projects provide an _Oomph setup button_ prominently on their main page, similar to:
[![Create Eclipse Development Environment for Eclipse Platform](https://download.eclipse.org/oomph/www/setups/svg/Eclipse_Platform.svg)](
https://www.eclipse.org/setups/installer/?url=https://raw.githubusercontent.com/eclipse-platform/eclipse.platform/master/releng/org.eclipse.platform.setup/PlatformConfiguration.setup&show=true
"Click to open Eclipse-Installer Auto Launch or drag into your running installer")

The [`Provisioning tutorial`](https://wiki.eclipse.org/Eclipse_Platform_SDK_Provisioning) explains how to setup the full Eclipse development environment automatically using the _Oomph setup button_ of the desired project.

## Setting up an Eclipse and GitHub Account

Create an [Eclipse account](https://accounts.eclipse.org/) if you don't already have one. 
See the ["Eclipse Foundation Account" section](https://www.eclipse.org/projects/handbook/#contributing-account) in the Eclipse Committer Handbook.

All contributors must electronically sign the [Eclipse Contributor Agreement (ECA)](https://www.eclipse.org/legal/ECA.php)
via their [Eclipse account](https://accounts.eclipse.org/).
For more information, please see the [Eclipse Committer Handbook](https://www.eclipse.org/projects/handbook/#contributing).

To verify the Eclipse Contributor Agreement, GitHub contributions must use the 
same email address like your [Eclipse account](https://accounts.eclipse.org/).
If your GitHub account was registered with a different address, you can [add your Eclipse
email address to the account](https://github.com/settings/emails) instead.

The vast majority of projects contributing to the Eclipse IDE is hosted on [GitHub](https://github.com/).
Therefore you need a Github account to contribute to these projects.
You can also add your GitHub account name to your [Eclipse account](https://accounts.eclipse.org/) to enable automated management of access rights for Eclipse project members. 
You can do this by logging into your Eclipse account, choosing ["Edit Profile"](https://accounts.eclipse.org/user/edit) and add your GitHub account name in the social media links section.

To be able to push to your repository you should also add your [SSH public key to your GitHub account](https://github.com/settings/keys).
Pushing via `https` is not recommended.

## Submitting a contribution for a project hosted at Github

The recommended way for contributions via GitHub is to create a fork of the main project repository and to create changes only in that fork
(see [fork and pull model](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models#fork-and-pull-model)
as well as [working with fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks) in the GitHub documentation).
Then you can create a pull request (PR) from your fork to propose your changes for submission into the main project repository.

See also
- https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks
- https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork
- https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories
