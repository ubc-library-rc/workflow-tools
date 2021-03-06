---
layout: default
title: Survey of tools
nav_order: 4
---

# Survey of tools

One major consideration is whether a tool is hosted in Canada. This information is usually found in terms of service under a section that explicitly addresses "storage" or "data privacy". Make sure you are aware of the risks.

If a tool keeps data on US servers and does not have Canadian hosting options, do not share sensitive information using the tool.
* [This is what personally identifiable information is](https://isit.arts.ubc.ca/personally-identifiable-information).
* Always follow <a href="https://universitycounsel.ubc.ca/subject-areas/access-and-privacy-general/useful-resources/">these guidelines from University Counsel</a>.

The below list is by no means comprehensive and is meant to introduce you to a few tools that may be useful for your work.

<hr>
## General workflow tools

[OSF](https://osf.openscience.ubc.ca/)

<img src="images/osf-logo.png" alt="OSF logo" width="100px" height="auto">

  * The OSF is a powerful and flexible interdisciplinary workflow management tool.
  * UBC has OSF for institutions which means that UBC-affiliated OSF projects are brought together on a UBC landing page. You can also use your UBC credentials to log in to this tool.
  * OSF has limited project storage of 5GB for private projects and 50GB for public projects. Individual files and objects need to be under 5GB in size. For larger items, OSF has many integrations with storage providers.
    * Good run-down of [storage caps by provider](https://help.osf.io/hc/en-us/articles/360019737894-FAQs#what-is-the-cap-on-data-per-user-or-per-project).
  * OSF allows for granular management of access to parts of an objects via "Components" feature.
  * Files uploaded to OSF are hosted on Canadian servers (if that option is selected while creating a repository).
  * Collaborators do not need to be at UBC to be added to a project and different "Components" can be hosted in different places (eg. other countries).
  * Projects can be private or public.
  * [Learn more and sign up via UBC login](https://guides.library.ubc.ca/OSF)

<hr>
## Task tracking and project overviews

[Asana](https://app.asana.com/)

<img src="images/asana-logo.png" alt="Asana logo" width="100px" height="auto">

  * Project management tool which can be used as a personal to-do list.
  * Free "limited" version is free indefinitely and fairly flexible.
    * Limited number of collaborators (15)
    * Limited ways to view tasks: list, calendar, and KanBan board (todo, doing, done columns)
  * Can have many inter-related projects.
  * Information is hosted on US servers.
  * [Take a look at this excellent Youtube Playlist courtesy of the folks at Asana](https://www.youtube.com/playlist?list=PLJFG93oi0wJDMccrrEbbZha0v64Jo63K8)

[Trello](https://trello.com/)

<img src="images/trello-logo.png" alt="Trello logo" width="100px" height="auto">

  * Owned by Atlassian which also owns JIRA and Confluence. These tools can integrate with Trello.
  * Project management tool which can be used as a personal to-do list.  
  * Can have many inter-related projects.
  * Free version is free indefinitely.
    * Limited number of collaborators.
  * Information is hosted on US servers.
  * [Learn More with this excellent playlist from Trello](https://www.youtube.com/playlist?list=PL4H_oPRK80z5Rq0aBNxeeS5sVPyDrNXCh)

[JIRA](https://www.atlassian.com/software/jira/free)

<img src="images/jira-logo.png" alt="JIRA logo" width="100px" height="auto">

* Ticketing and task management system for projects
* Works well with Agile approach
* Free option is free forever but limited in storage and number of users
* Hosted in the US (through AWS)
* Integrates well with Trello for visual task tracking and Confluence for notes and documentation (all are Atlassian products)

<hr>
## Chatting with your team

[Microsoft Teams](https://it.ubc.ca/services/email-voice-internet/microsoft-teams)

<img src="images/teams-logo.png" alt="Teams logo" width="100px" height="auto">
  * Free for UBC students, faculty, and staff).
  * UBC IT offers support with Teams.
  * Integrated with Microsoft Office suite.

[Slack](https://slack.com/intl/en-ca/)

<img src="images/slack-logo.png" alt="Slack logo" width="100px" height="auto">
  * Chat tool for teams, not supported by UBC IT.
  * Commonly used in industry; useful to be aware of.
  * Free to use with limitations.
  * Hosted on US servers; not ideal for conversations about sensitive topics.

<hr>
## Version control
A lot of tools have some form of built-in version control for files. Git is worth being aware of generally as a useful version control tool for text files.

Why is version control important? Learn more here:

[Git](https://git-scm.com/)

<img src="images/git-logo.png" alt="Git logo" width="100px" height="auto">

  * Git is a version control tool that is the backbone of services like Github and GitLab.
  * It is fully open source and used widely in many different disciplines as well as in industry.
  * Git provides line by line versioning for text files, showing edits made, who made them, and when.
  * Works best with text files.

[GitHub](https://github.com/)

<img src="images/github-logo.png" alt="GitHub logo" width="100px" height="auto">

  * Owned by Microsoft.
  * US-hosted service that uses Git as a back-end.
  * Free to use with some constraints.
  * Free web hosting through Github Pages which runs off of a Github repository.
  * Github is designed to work with text files. This means files under 100MB (works best with files under 50mb). As a result it is not for large file storage.
    * That said, Git does have provision for large file storage through <a href="https://git-lfs.github.com/">"git-lfs"</a>. In the context of Github this means that you can now push files <a href="https://docs.github.com/en/github/managing-large-files/about-git-large-file-storage">up to 2GB in side with a free Github account</a>. This is not ideal for storing research data but is useful for large live text files that you are working with.
    * Github has a web hosting service called Github Pages through which you can publish a simple website. Git LFS does not work with Github Pages.

[GitLab](https://about.gitlab.com/)

<img src="images/gitlab-logo.png" alt="GitLab logo" width="100px" height="auto">

  * Open Source tool for the use of Git, similar to Github.
  * GitLab is an newer service but very useful for overall workflow management.

<hr>
## Storage for files you're regularly updating

These tools are for "live" files which are currently being worked on. They are not appropriate for long term storage of research data. Explore our Research Data Management guide to learn more about <a href="https://researchdata.library.ubc.ca/plan/preserve-your-data/">long term preservation of research data</a>.

OSF (again)

<img src="images/osf-logo.png" alt="OSF logo" width="100px" height="auto">

  * Lots of integrations for file storage providers via [OSF Add-Ons](https://www.cos.io/blog/osf-add-ons-help-you-maximize-research-data-storage-and-accessibility)
  * Unlimited total storage; individual files can be up to 5GB
  * Hosting of data uploaded to a project is on Canadian servers (in Montreal) but some data about the project (eg. project metadata and information about project collaborators) is stored on US servers.

[OneDrive](https://it.ubc.ca/services/web-servers-storage/microsoft-onedrive)

<img src="images/onedrive-logo.png" alt="OneDrive logo" width="100px" height="auto">

  * Unlimited cloud storage available for free to UBC faculty, staff, and students as part of the Microsoft suite.
  * UBC IT offers support.

[Box](https://www.box.com)

<img src="images/box-logo.png" alt="Box logo" width="100px" height="auto">

  * Unlimited file storage and no file type limitations.
  * [Not free past 14 day trial](https://www.box.com/pricing)
  * Canadian hosting options (unlike the similar service, DropBox which is US-based)

<hr>

## Note-talking
This is something we won't go deeply into but the following tools are worth exploring:

* OSF has a built-in Wiki
* Confluence is a wiki that integrates with JIRA and Trello and allows collaborative editing

A common useful structures for note-taking is the "single document" approach where one document is used for all notes relating to a topic, project meetings, or a span of time.
