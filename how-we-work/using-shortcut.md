# Using Shortcut
Aptible uses [Shortcut](https://www.shortcut.com) for project management.

## The Roadmap View
We use Shortcut to allow us to see progress at the Company level (The [Roadmap view](https://app.shortcut.com/aptible/roadmap?view=quarters)) as well as to zoom into individual units of work (aka Stories and Epics).

![Roadmap View](/images/shortcut-roadmap.png "Roadmap View")

This zooming in and out is why, as described in the Guidelines section above, we seek to define Stories granularly, associate them with Epics.

## Milestones and Epics
[The Milestones index](https://app.shortcut.com/aptible/milestones) shows all active Milestones with their associated Epics. You can easily move Epics between Milestones by dragging and dropping. Clicking into a Milestone allows you to see the Milestone status, Description, Start date and Due date as well as associated Epics where you can easily update Start and Due Dates, State, etc.

[The Epics index](https://app.shortcut.com/aptible/epics) will show all Epics and allow you to use filters to, for example, find all Epics for which you are the owner.

![Filtered Epic Index](/images/shortcut-filtered-epic-view.png "Filtered Epic Index")

Clicking on a specific Epic will show all Stories related to that Epic, and will show an option for Creating a Story within an Epic, if new Stories are needed.

![Epic Show](/images/shortcut-epic-show-page.png "Epic Show page")

## Your Dashboard aka "Home"
[Your Dashboard](https://app.shortcut.com/aptible/dashboard) lists all stories you are assigned to, making it easy for you to find those that you need to make progress on or update. In the screenshot below, note the “Upcoming Due Dates” list showing tasks that are overdue and in need of an update.

## Github + Shortcut Integration (aka automatically updating stories via Github commits)
The Github integration allows for automatic status progression of the story. If your branch contains the shortcut story number prefixed with sc- (i.e. story 236 would be associated with branch “sc-236”), if it’s branched off of aptible’s main branch (not a fork) any commit with specific keywords will update Shortcut.
* “Start” will move the story to in progress (you can rebase this commit away later)
* Opening a PR against master will move the story to “ready for review”
* Once it is merged it will move to “ready for deploy”.

From here it will need to be manually moved once the deployment actually happens to get the feature out the door.

Obviously these helpers only work when there is only one repo per story. If multiple repos are involved, you can manually associate them by commenting “[sc-###]” on the PR (just the story id format in brackets - any other text won’t work).

## Shortcut Object Reference
| Object | Definition | Notes | Requirements |
| --- | --- | --- | --- |
| Milestone | Company goals<br> Later, we’ll use for functional team goals |Milestones roughly correspond to the various company strategic goals/roadmap items. Teams working on these milestones should groom the milestone cards to ensure the description is clear (including the “why”). Any “how” or specific tasks should instead be captured as epics and stories. | * Should have a Start and Due Date<br>* Should have a description<br>* For now, @Henry Hund will maintain |
| Epic | Projects; collections of Stories | Epics correspond to projects that the working groups are taking on or plan to take on. Each epic should have a meaningful due date to help keep the roadmap clean, and should generally take on the start date of the first sprint that work is done on it. The teams working on the epic should groom the epics themselves to make sure the description is clear, the success criteria/goals are defined and the due dates are achievable. | * Should have at least 1 Owner<br>* Should have a Team<br>* Should have a Start and Due Date<br>* Should have a description<br>* Status should be kept up to date |
| Story | Unit of work, must be achievable in less than 2 weeks<br>Idea or deprioritized backlog items are more flexible | Stories are the actual day to day tasks being done by engineers and should usually involve code. For example, the epic could be “Automated instance recovery” with a story of “Create operation for draining app instances”. The story is only one piece of work and doesn’t need to complete the epic, but is fine grained enough for a person to work on and complete within a sprint. | * Should have at least 1<br>* Owner<br>* Should have a Team<br>* Should have Sprint (Iteration)<br>* Should have a Due Date<br>* Should have a description<br>* Status should be kept up to date |
| Projects | UNUSED | - | Shortcut seems to be deprioritizing the use of Projects in favor of Epics |
