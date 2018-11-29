# Engineering methodology

Date: 2018-11-29

* [Intro](#intro)
* [OKRs](#okrs)
* [Backlog and Features-Idea repositories](#backlog-and-features-idea-repositories)
* [Leads Meeting](#leads-meeting)
* [Team Sync Meeting](#team-sync-meeting)
* [Standup](#standup)
* [Demo](#demo)
* [Retrospective Meeting](#retrospective-Meeting)

## Intro

This methodology's an evolution of [previous workflows](https://github.com/src-d/guide/blob/abe7932e3bc58898e49a5c1c0e3e2cac6d387144/engineering/methodology.md) and experiences, and it's on constant evolution an open to change at any moment.

The current workflow is based on this main concepts:

* OKRs, company/team engineering OKRs are what should drive every single decision taken by the Engineering Team.
* A [Workflow](workflow.md), that defines the process of definition and development of the tasks, from the idea to the release.
* A Backlog and Features-Idea repositories, where the approved tasks and the suggestions are.
* Leads meeting, a meeting to align all efforts done by the different teams at engineering.
* Demo, a company-wide presentation where all the new functionality and important changes are communicated to the company once they are done.
* Retrospective Meeting, a place to improve the methodology.

## OKRs

Every single decision made at the Engineering Team (and company-wide as well),
should be made aligned with the quartes OKRs.

The company publishes OKRs every quarter at [OKRs](https://github.com/src-d/okrs)
the OKRs for the current quarter are hosted in the README.md file, the pasts
quartes can be found by his name in the same repository.

The OKRs are introduced and discussed via PRs to a feature branch and
merged once are reviewed by management.

The Management Team defines the company OKRs and the high lever OKRs,  meanwhile
the CTO and the Head of determining the Engineering Team OKRs
Architecture, with the help of the rest of the members of the team.

The OKRs per team are defined and published by the Lead of each team, aligned
with the company ones.

## Backlog and Features-Idea repositories

At source{d} we try to use git repositories as much, that's why our source
of true for the user histories and tasks are git repositories at GitHub, even
these repositories don't contain any code.

The [Fetures-Idea repository](https://github.com/src-d/feature-idea) is the
the place where everyone in the company can suggest new features, projects or
products to the Product Team/Engineering Team, this is doing creating an [issue](https://github.com/src-d/feature-idea/issues/new/choose) in the repository,
after the Product Team and CTO will review this at the Product Sync meeting that
happens once per week.

The [Backlog repository](https://github.com/src-d/backlog) contains the full
backlog for the Engineering Team and Product Team; these issues are managed by
the Head of Product and only him can create new issues there. Each issue at this repository represents an EPIC, and this EPIC should be linked to his Design
Document and his OKR. Every team involved in the development of this EPIC is
responsible for keeping it updated.

...

## Leads Meeting

It's a weekly event, were all the Lead Engineers and Product meets to discuss
the current problems, and future developments were are relevant for the other
teams:

* Tasks were the cooperation of other teams are required.
* Changes on the project's boundaries affecting other teams.
* Relevant question regardless of other teams projects.

Also, at the end of the meeting, the new design documents are presented
with a brief explanation and the maintainer is chosen.

## Team Sync Meeting

A Bi-weekly/weekly meeting of the CTO with the team lead and optionally with the
full team (to be decided by the lead), in order to comment on the status of the
projects.

At this meeting, the new tasks are added to the team backlog and the current
developments are reviewed. Also, the current status of the team is discussed.


## Standup

All standups are happening online and asynchronously, per-team in appropriate
`su-*` Slack channels. Standup reports are managed through Slack private messages with [geekbot](https://geekbot.io/).

## Demo

Demo meeting is a monthly event.

* Idea: let everybody know what's going on (on quite a technical level) that is relevant for others or affects others’ releases/deployments.
* Product does not need to be deployed, but the demo should be as real as possible.
* Should be concise, respecting other people's time.
* Fixed max time **per-team: 15min (including questions)**. Agree between teams in advance, if more time needed.

## Retrospective Meeting

Every month this methodology is reviewed in a meeting called Retrospective Meeting
this born from the Scrum methodology:

* What went well?
* What needs improvement?
* Next steps

To learn more about retrospectives, please read:
https://www.atlassian.com/team-playbook/plays/retrospectives