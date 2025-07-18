---

title: Git Integration for Jira Cloud - Release Notes
description:
taxonomy:
    category: git-integration-for-jira-cloud

---

We publish new features, bug fixes, security updates/patches, and Jira compatibility regularly. Below are highlights of the changes.

**Important links**

*   [Atlassian Marketplace listing](https://marketplace.atlassian.com/apps/4984/git-integration-for-jira?hosting=cloud&tab=overview)

*   [Git Integration for Jira Cloud Status](https://status.bigbrassband.com)

*   [Git Integration for Jira Cloud Security](https://www.gitkraken.com/git-integration-for-jira/security-and-trust)

If you have any questions, please contact us through our [Support Portal](https://help.gitkraken.com/git-integration-for-jira-cloud/gij-cloud-contact-support/).

* * *

### GitHub App

`6 June 2025` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>Admins</b>

GitHub.com users can now connect integrations via Github App. Using this integration option can help with rate limiting, and also uses the app as context for permissions rather than a user.

![](/wp-content/uploads/gij-github-app.png)

### Advanced Edition

`14 May 2025` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURES</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Git Integration for Jira now offers two Editions - Standard and Advanced - with separate pricing and features. Existing subscriptions prior to this release are automatically converted to Standard Edition. 

Advanced Edition was purpose-built based on insights and usage patterns from some of our most demanding enterprise customers. It’s designed for high-performing software teams that rely on deep Git/Jira integration to maintain velocity, surface risks early, and deliver complex projects at scale—going well beyond basic integration to help teams fully leverage their development data.

Refer to the following pages to learn more about the changes, new features, and differences between Standard and Advanced Editions.
*   [GIJ Advanced Launch Article](https://www.gitkraken.com/blog/introducing-git-integration-for-jira-cloud-advanced-edition)
*   [Marketplace Listing - Pricing & Features](https://marketplace.atlassian.com/apps/4984?tab=pricing&hosting=cloud)
*   [Usage Limits & Non-Feature Entitlements](/git-integration-for-jira-cloud/gij-standard-vs-advanced/)
*   [Feature Comparison](git-integration-for-jira-cloud/GIJ-Standard-vs-Advanced-features/)

Note: Standard Edition introduces a 200 connected repository limit, whereas the limit is 10k for Advanced. For subscriptions that were active prior to May 14, 2025: 
*   Monthly Subscriptions (remaining on Standard): We are providing a ‘grace period’ that will end on July 1, 2025. At that point you will not be able to make changes to your connected repositories until you get below the 200 repo threshold.
*   Annual Subscriptions (remaining on Standard): The ‘grace period’ (for connecting over 200 repos) extends until the end of your current subscription. Beginning on your next renewal date, you will be unable to make changes to your connected repositories until you get below the 200 repo threshold.  

### Admin Notifications

`11 Nov 2024` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>Admins</b>

Jira Admins and GIJ Managers now have the option to receive an email alert any time there is an issue with indexing a repository! Anything that causes an error state for an integration or repository will trigger these emails. Here's how to get started:

*   In Jira, select Git Integration: Manage Integrations from the Apps dropdown
*   Navigate to the General Settings page and select "Enable alerts..." under Email Alerts
*   Individual Admins and GIJ Managers can opt out of receiving these emails by going to User settings and disabling "Send me alerts..." under Admin / manager email alerts
*   To ensure you receive the emails, whitelist gij-notifications@gitkraken.com

### Manager Permissions

`01 Nov 2023` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>Admins</b>

Jira Administrators can now share app control (e.g. managing settings and integrations) with other (non admin) Jira users. By utilizing Jira Groups and Global Permissions, Jira Admins can select which Jira users they want to provide managerial access to. Once given the "Manage Git Integration for Jira by GitKraken" permission, these users can perform actions that were previously limited to Jira Admins - update app settings, connect new integrations, manage existing integrations, etc.

Check out the [help article](/git-integration-for-jira-cloud/manager-permissions-gij-cloud/) or [walkthrough video](https://www.youtube.com/watch?v=2tmWvRxj9Ls) for more information.

### GitLens for Visual Studio Code Integration

`29 Mar 2023` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

This workflow improvement is a great addition for developers that are using Visual Studio Code to edit source code. [GitLens](https://www.gitkraken.com/gitlens) is a Visual Studio Code extension that helps users visualize code, explore Git repositories, use powerful compare commands and so much more. From within Jira, clicking on the GitLens icon next to repositories, commits, tags, and branches will open them in VS Code.

![](/wp-content/uploads/gij-gitcloud-deeplink-gitlens-issue-git-commits.png)

This enables team members to quickly transition between Jira and their code editor without losing context. GitLens deep links are located within Jira issues and the Repository Browser. [View the help article](/git-integration-for-jira-cloud/deep-linking-into-gitlens-gij-cloud/) for more information.

### GitHub OAuth: Deep link admins into their GitHub account to the correct app settings

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Adds a link to GitHub to quickly view which GitHub organizations are authorized for use with Git Integration for Jira.

![](/wp-content/uploads/gij-github-autoconnect-grant-auth-screen-c.png)

### Manage repositories: Ability to reindex or disable individual repositories

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

This is a new feature that allows you to reindex individual repositories or disable them without having to remove them.

![](/wp-content/uploads/gij-gitcloud-gitmgr-reindex-and-disable-selected.png)

### Manage repositories: New settings are now visible

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Some new features have been brought to the Manage repositories screen such as:

*   permissions

*   smart commits

*   the state of indexing triggers for webhooks

*   Last indexed (shows dates for the last time it was indexed)


The status field has been upgraded to be much more accurate as well as show a symbol to let you know the state of progress.

![](/wp-content/uploads/gij-gitcloud-repomgr-column-repo-status-features.png)

### Manage repositories: Commits/branches/PR count added

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

New column headers to view the number of branches, commits and pull requests.

![](/wp-content/uploads/gij-gitcloud-gitmgr-branches-commits-pr-columns-feature.png)

### Manage repositories: Improved access to indexing logs

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

The Repository Indexing Log has been greatly improved by now showing just the most-recent 15 lines of the log, and providing the ability to copy it to the clipboard or download the full log.

![](/wp-content/uploads/gij-gitcloud-repomgr-improved-view-logs.png)

### Manage repositories: Refresh data

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

You will get nice clean pagination when you refresh the data using this handy new feature.

![](/wp-content/uploads/gij-gitcloud-gitmgr-page-refresh.png)
![](/wp-content/uploads/gij-gitcloud-manage-repos-refresh-list.png)

### Manage repositories: Multi-select

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

This new features lets you select all repositories in your list or pick and choose repositories, then apply the function “Reindex selected”, “Enable selected”, or “Disable selected”.

![](/wp-content/uploads/gij-gitcloud-repomgr-enabled-selector.png)

### Manage repositories: Option to reindex individual repositories manually

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Reindex any selected repository.

![](/wp-content/uploads/gij-gitcloud-repomgr-selector-actions-reindex-disable.png)

### Manage repositories: Filtering (status, name, integration)

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

You can use this new dropdown menu to filter all integrations, status, and perform text searches for the names of repositories (very helpful if you have a high number of repositories).

![](/wp-content/uploads/gij-gitcloud-repomgr-list-filters.png)

### Manage repositories: Sorting (repo, integration, last indexed, # of commits/branches/PRs)

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

With this new feature you can now sort your list of repositories by repo name, integration name, last indexed time, or number of branches, commits, or PRs.

![](/wp-content/uploads/gij-gitcloud-repomgr-column-sorting.png)

### New section: Manage repositories

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

There are many new and improved features in this section including: Sorting (repo, integration, last indexed, # of commits/branches/PRs), filtering (status, name, integration), a new option to reindex individual repositories manually, multi-select feature for repositories, ability to refresh data, improved access to indexing logs, commits/branches/PR count added, and the new ability to reindex or disable individual repositories.

There are also an array of new settings now visible from this screen such as: permissions, smart commits, the state of indexing triggers for webhooks, status, and last indexed.

![](/wp-content/uploads/gij-gitcloud-new-repo-manager-section.png)

### Manage integrations: Implement filtering by name and status

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Using the new status dropdown selector you can now filter by which state you’re in – useful if you have a large number of integrations. Filtering by name is also made possible.

![](/wp-content/uploads/gij-gitcloud-gitmgr-integration-status-selector-and-search.png)

### Manage integrations: Disabling/Enabling feature

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Using this new feature, you can now stop or pause the integration without having to remove it.

![](/wp-content/uploads/gij-gitcloud-gitmgr-integration-enable-disable.png)

### Manage integrations: New settings are now visible

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Some new features have been brought to the Manage integrations screen such as:

*   permissions

*   smart commits

*   the state of indexing triggers for webhooks

*   Last indexed (shows dates for the last time it was indexed)


The status field has been upgraded to be much more accurate as well as show a symbol to let you know the state of progress.

![](/wp-content/uploads/gij-gitcloud-gitmgr-integration-index-and-status-features.png)

### Manage integrations: Select orgs/repositories feature

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

This new features allows you to pick and choose which repositories to connect, without having to add them all.

![](/wp-content/uploads/gij-gitcloud-managed-ui-github-repo-sel.png)

### Manage integrations: improved access to indexing logs

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

The Repository Indexing Log can be accessed from the gear icon located under Actions, and has been greatly improved by now showing just the most-recent 15 lines of the log, and providing the ability to copy it to the clipboard or download the full log.

![](/wp-content/uploads/gij-gitcloud-gitmgr-integration-view-logs-notes.png)

### Manage integrations: Repo count

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

This handy new feature we’ve included on the Manage integrations page shows the number of connected repositories for each instance.

![](/wp-content/uploads/gij-gitcloud-gitmgr-integration-repos-counter.png)

### Manage integrations: Integrations list with wizard for adding to list

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

*   Admins will be able to take advantage of a new wizard to add integrations in a streamlined fashion. The wizard features an easy 3-step setup process:

    *   Select integration type

    *   Select Git service

    *   Select repositories

    *   The wizard makes it clear to admins where they are in the process and guides them through each step to completion.


![](/wp-content/uploads/gij-gitcloud-gitmgr-add-new-integration-template.png)

### Manage integrations: Welcome message showing details of your integrations

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

When you access the new “Manage integrations” menu item, you will now get a welcome message that includes details about your integrations. For example, upon getting started you will see the message “You have no integrations yet.” along with an accompanying button to “Add integrations”. This new improvement makes it easier to understand right from the start where you stand and what needs to be done upfront, while providing a handy button to proceed to get your integrations added.

![](/wp-content/uploads/gij-gitcloud-managed-ui-webhook-idx-setup-c.png)

### New section: Manage integrations

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

There are many new and improved features in this section including: An improved integrations list, repo count, improved access to indexing logs, a new select orgs/repos feature, disable/enable feature for integrations, and you can now implement filtering by name and status.

There are also an array of new settings now visible from this screen such as: permissions, smart commits, the state of indexing triggers for webhooks, status, and last indexed.

![](/wp-content/uploads/gij-gitcloud-managed-ui-git-integration-list.png)

### "Manage Git repositories" menu item has now been split into two new menu items

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

The "Manage Git repositories" menu item (from previous versions) has now been split into two new menu items named "Manage integrations" and "Manage repositories".
Take a look at what each of these new sections entail in the following entries.

![](/wp-content/uploads/gij-gitcloud-integration-repo-menu-split-new.png)

### New User Interface for Admins

`25 Mar 2022` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

We’ve launched an all-new management user interface, supporting the goal of making the UI more self-serving for admins. The new UI contains improved functions from new sorting features to viewing the number of repos connected on each instance. More specific details are provided in the other Release Notes entries on this page. The new UI also features an improvement which now allows you to configure your repositories visually.

![](/wp-content/uploads/gij-gitcloud-gitmgr-edit-integrations-options-and-features.png)

* * *

### Deep Linking to GitKraken

`21 Sep 2021` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

With the [acquisition](https://www.gitkraken.com/blog/gitkraken-acquires-git-integration-jira-bigbrassband) of BigBrassBand's Git Integration for Jira app (GIJ) by GitKraken, we have introduced deep linking between GIJ and GitKraken so users can now have a stronger integration between the two. You can now click to open commits, branches, tags and repositories directly in GitKraken from the Jira issue view giving you a seamless transition from your Jira issues to GitKraken.

[Learn more](/git-integration-for-jira-cloud/deep-linking-to-the-gitkraken-client-gij-cloud)

You will see the added ability to open the GitKraken client from our app in various locations. See an example of what this looks like below.

![](/wp-content/uploads/gij-gitcloud-deeplink-gitkraken-user-settings.png)

### Default branch for a repository + project + user

`13 Jun 2021` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Now you can configure a Default branch for a repository when creating new branches. When using this feature, you will no longer have to select the branch each time you pick the repository.

![](/wp-content/uploads/gij-gitcloud-user-settings-default-repo-feature.png)

You may immediately set the selected branch as default for the current repository when using the create branch dialog.

![](/wp-content/uploads/gij-gitcloud-user-settings-create-def-branch-dlg.png)

For more information on this feature, see article [Default branch feature](/git-integration-for-jira-cloud/default-branch-feature-gij-cloud).

### Webhook indexing integration

13 May 2021 <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Webhook indexing integration allows your connected git servers to work behind a firewall but will have limited features which are stated under the Connect the your Git server features comparison table. For detailed information on this new feature, see [Git Integration for Jira Cloud: Webhook indexing integration](/git-integration-for-jira-cloud/webhook-indexing-explainer-gij-cloud).

![](/wp-content/uploads/gij-gitcloud-managed-ui-git-integration-type-github.png)
![](/wp-content/uploads/gij-gitcloud-add-new-integration-type-webhook-indexing.png)


### User PATs have been moved to a new page

`07 Mar 2021` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

We've created a new Jira user settings screen to allow individual Jira users to manage their Personal Access Tokens (PATs) for use in creating/deleting branches and pull requests from Jira.

![](/wp-content/uploads/gij-gitcloud-user-settings-pat-options.png)

* * *

### Support for Dark Mode in Jira Cloud Mobile

`25 Jan 2021` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Enabled dark mode support for iOS, MacOS and Android for the Jira Cloud mobile apps.

![](/wp-content/uploads/gij-gitcloud-aui-mobile-problem-example.png)

* * *

### Expand to see more code in diff screens

`23 Nov 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Expand to see more of a file when doing quick code reviews in Jira Cloud.

![](/wp-content/uploads/gij-gitcloud-code-diff-expand-view-controls.png)

Quick access guide:

![](/wp-content/uploads/gij-gitcloud-code-diff-expand-view-control-sample.gif)

* * *

### Support for iOS, Android, and Mac Apps

`05 Nov 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Development Information (branches, commits, and pull requests) are now visible in:

*   [Jira Cloud iOS app](https://www.atlassian.com/software/jira/mobile-app)

*   [Jira Cloud Android app](https://www.atlassian.com/software/jira/mobile-app)

*   [Jira Cloud MacOS app](https://www.atlassian.com/software/jira/mac)

This information is visible in the native Jira Cloud development information area + the Git Integration glance where you can view branches, commits, pull requests and tags. You can create branches and pull requests all from the above applications.

**Mobile apps**

| Jira iOS/Android app:<br>View development information | Jira iOS/Android app:<br>Branches detail | Jira iOS/Android app:<br>Commits detail |
| --- | --- | --- |
| ![](/wp-content/uploads/gij-gitcloud-mobile-dev-info-panel.png) | ![](/wp-content/uploads/gij-gitcloud-mobile-branches-detail.png) | ![](/wp-content/uploads/gij-gitcloud-mobile-commits-detail.png) |

| Jira iOS/Android app:<br>Pull/merge requests detail | Jira iOS/Android app:<br>Git Integration "glance" view | Jira iOS/Android app<br>Glance: Create branch |
| --- | --- | --- |
| ![](/wp-content/uploads/gij-gitcloud-mobile-pullreq-detail.png) | ![](/wp-content/uploads/gij-gitcloud-mobile-integration-glance-view.png) | ![](/wp-content/uploads/gij-gitcloud-mobile-create-branch-view.png) |

| Jira iOS/Android app -- Glance: Create branch |
| :---: |
| ![](/wp-content/uploads/gij-gitcloud-mobile-create-pullreq-view.png) |

### Default repository for projects

`05 Sep 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Developers will often work in a single repository in a given Jira project. Each Jira user can now set their own default repository for a Jira project.

![](/wp-content/uploads/gij-gitcloud-user-settings-set-default-repo.gif)

Default repository selection for Jira projects is available in the [Create branch](/git-integration-for-jira-cloud/create-branch-gij-cloud) and [Create pull / merge request](/git-integration-for-jira-cloud/create-pull-or-merge-request-gij-cloud) features of the app.

All default selections can be reviewed and updated in [User Settings](/git-integration-for-jira-cloud/user-settings-gij-cloud):

![](/wp-content/uploads/gij-gitcloud-user-settings-default.png)

* * *

### Pagination for Repository Browser screen

`06 Jun 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

All Jira users with the `View development tools` permission have access to the **Repository browser** screen (_formerly View all repositories_) in Jira Cloud. We have added pagination to this screen to better support large numbers of repositories and the ability to filter the list by search term.

**Note:** Permissions to specific repositories can be limited using Project Permissions (see [Permissions](/git-integration-for-jira-cloud/permissions-gij-cloud) for more information).

![](/wp-content/uploads/gij-gitcloud-repo-browser-pagination-feature.gif)

* * *

### Webhook Log Viewer

`02 May 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

![](/wp-content/uploads/gij-gitcloud-indexing-triggers-webhook-log-sample.png)

The **Webhooks** page now includes logs of inbound webhooks sent to the Git Integration for Jira Cloud app. Status, reindex status, type, and related repository are shown in the table to assist Jira administrators in troubleshooting and identifying which webhooks are triggered for reindexing.

Webhook logs are retained for 7 days.

* * *

### Add Jira issue link to Pull / Merge Request description

`28 Feb 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

When a Jira user creates a pull request or merge request (GitLab) using the Git Integration for Jira app ([Create pull / merge request](/git-integration-for-jira-cloud/create-pull-or-merge-request-gij-cloud)), a link to the Jira issue is included in the pull request / merge request description.

| **GitLab** | **GitHub** | **Bitbucket** |
| --- | --- | --- |
| ![](/wp-content/uploads/gij-gitcloud-jira-issue-link-in-MR-message-gitlab.png) | ![](/wp-content/uploads/gij-gitcloud-jira-issue-link-in-PR-message-github.png) | ![](/wp-content/uploads/gij-gitcloud-jira-issue-link-in-PR-message-bitbucket.png) |

| **Azure DevOps** | **AWS Code Commit** |
| --- | --- |
| ![](/wp-content/uploads/gij-gitcloud-jira-issue-link-in-PR-message-vsts.png) | ![](/wp-content/uploads/gij-gitcloud-jira-issue-link-in-PR-message-aws.png) |

* * *

### Show integration type + org/owner name + repo name in lists of repositories

`05 Feb 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>NEW FEATURE</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ALL USERS</b>

Integration type icons and org/group names have been added to user facing repository selectors to help distinguish between similarly named repositories across different git servers and orgs/groups.

![](/wp-content/uploads/gij-gitcloud-manage-repo-icons-org-plus-repo-name.png)

* * *

### Display name for integrations and repositories

`02 Feb 2020` <b style='background-color:#E2FCEF; padding:1px 5px; color:#006745; border-radius:3px; margin: 0 5px; font-size: small;'>IMPROVEMENT</b> <b style='background-color:#EAE5FE; padding:1px 5px; color:#412C92; border-radius:3px; margin: 0 5px; font-size: small;'>ADMINS</b>

Jira administrators can now edit the names of integrations and repositories that are shown in Jira Cloud.

![](/wp-content/uploads/gij-gitcloud-integration-repo-display-name-feature.gif)

<div class="bbb-callout bbb--tip">
    <div class="irow">
    <div class="ilogobox">
        <span class="logoimg"></span>
    </div>
    <div class="imsgbox">
        Use the Display Name feature to record information about the git server account.
    </div>
    </div>
</div>

![](/wp-content/uploads/gij-gitcloud-edit-integration-repo-settings-display-name.png)

* * *
