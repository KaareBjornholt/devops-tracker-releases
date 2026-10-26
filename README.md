# DevOps Tracker

A desktop app for macOS and Windows that keeps track of your Azure DevOps work across organizations and projects:

- **Your work items:** what's assigned to you now, what used to be, and what you've commented on, with sortable and filterable lists.
- **A dashboard you build yourself:** tiles with their own filters, such as counts, lists, a weekly chart, and a per-project overview. Drag tiles to rearrange them.
- **Activity for time registration:** your comments, mentions of you, and your own changes, by day or as a calendar, for this week, last week or any dates.
- **Auto-sync** for all projects or just the ones you pick.

Everything is stored locally on your computer. The app talks only to Azure DevOps and the Microsoft sign-in service.

This repository holds the installers and the issue tracker. The source code is kept private.

## Download

Get the latest version from [Releases](https://github.com/KaareBjornholt/devops-tracker-releases/releases/latest):

- **macOS** (Intel and Apple Silicon): the `.dmg` file
- **Windows** (64-bit): the `Setup .exe` file

## Install

Neither installer is signed with a paid certificate, so your system warns the first time:

- **macOS:** open the `.dmg` and drag DevOps Tracker to Applications. On first launch macOS blocks it. Open **System Settings → Privacy & Security**, scroll to the message about DevOps Tracker and choose **Open Anyway**.
- **Windows:** run the setup file. On the SmartScreen warning choose **More info**, then **Run anyway**.

To update, install the new version over the old one. Your organizations, history and dashboard are kept.

## Get started

1. Open **Settings** (the gear icon) and add your Azure DevOps organization by URL.
2. **Sign in** with your Microsoft account, or use a personal access token with the *Work Items (Read)* and *Project and Team (Read)* scopes.
3. Add the projects you want to track, then **Sync**.

## Report a bug or request a feature

Use [Issues](https://github.com/KaareBjornholt/devops-tracker-releases/issues/new/choose) and pick **Bug report** or **Feature request**.

This repository is public. Don't include customer or organization names, work item titles or contents, or tokens in issues or screenshots. Describe the situation in general terms, or blur screenshots.
