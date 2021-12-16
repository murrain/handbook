# Sprint and Project Management

Aptible is a remote organization, and much of our work occurs asynchronously. Working remotely and asynchronously poses some challenges. We use our Sprint and Project Management processes to help counteract many these challenges.

## Why Aptible "does" Project Management
Aptible will never build onerous or rigid sprint and project processes--it’s just not in our DNA. But, we have designed our **Aptible Sprint and Project Management (“ASPM”)** processes to help us realize some key benefits:

| Challenge | ASPM Benefit |
| --- | --- |
| Hard to see how my work fits in with broader company goals | Create alignment by clearly connecting individual units of work (Stories) with company strategic goals (Milestones) through Epics |
| Hard to know what everyone else is working on | Drive clarity by enforcing a Sprint structure and Sprint-planning process where we clearly lay out the Stories that will be completed within a Sprint, and keep those Stories up to date |
| Easy to get distracted by new ideas or initiatives | Enforce focus by ensuring all work is clearly documented in our project management system rather than via Slack conversations/threads |
| Hard to know who is doing what or if we are succeeding or failing | Promote accountability by assigning Epics and Stories to teams and individuals, and setting reasonable deadlines |
| Wasting time by forgetting or re-litigating already-made decisions | Documentation in the form of clear descriptions on Milestones, Epics, and Stories that is referenceable by all team members--nothing of consequence should be only findable by searching Slack |

Beyond this, it never feels good to be unclear what is expected of you, or what you can expect your teammates to deliver. Poor project management is stressful: it makes for a less pleasing and more difficult work environment, and makes it less likely that we will achieve our mission or strategic goals.

## How the ASPM Works
Using project management effectively requires commitment, but it shouldn’t be difficult or time consuming. We should enjoy outsized returns for just a little bit of time invested in project management. 

With this in mind, we are continuously iterating on how we ask teams to use project management based on feedback collected via bi-weekly retros, team surveys, all hands meetings, and ad hoc discussions. 

### Sprint Cadence
Aptible works on 2-3 week Sprints. Sprints generally start on Mondays and end on Fridays. Sprint dates are posted in the Iterations section of Shortcut.

We typically extend the length of Sprints around holidays to account for time when our “office” is closed. We do not run a Sprint around major holidays (e.g. between Christmas and New Years).

![Example cadence of a 2-week sprint.](images/sprint-cadence.png "Example cadence of a 2-week sprint.")

| Day relative to Sprint Start | Item |
| --- | --- |
| **Sprint Kickoff**<br />Day -1 | * During all hands or async, leadership team provides any feedback/guidance on subsequent Sprint to “kick off” Sprint planning |
| **Sprint Planning**<br />Day 1 | * Functional teams create and assign Epics and Stories for the Sprint, tying all Stories to an Epic and all Epics to Milestones<br />* Functional teams should move all previous Sprint stories that are incomplete to the subsequent Sprint <br />* Functional teams can also move Stories that are not ready for immediate prioritization to future Sprints |
| **Sprint Feedback**<br />Day 2 | * CEO and COO provide feedback (async or sync as needed) on Epics/Stories created on Day 1 |
| **Sprint!**<br />Day 1-10/15 | * Once Stories are set, team members should begin progressing on Sprint, keeping Story and Epic states and comments up to date |
| **Sprint Forecast**<br />Day 8/13 | * 2 days before the Sprint is to end, functional leads should create a list of Stories that will likely not be finished during the Sprint <br />* These Stories should likely have been broken into smaller Stories -or- were incorrectly prioritized / or we misunderstood something about them<br />* Unfinished Stories should be tagged with the label Likely Unfinished During Sprint documenting with a comment explaining:<br /> ** Estimated time remaining<br />** Perceived blockers <br />** When we should return to them (next sprint or some other time)?<br /> * At the Conclusion of the Sprint, we’ll move any unfinished Stories with this label to subsequent Sprint(s), discuss them if needed during the Retro, and subsequently remove the label |
| **Sprint Close**<br />Day 10/15 | * On the last day of Sprint, each team shows the progress, learnings, and outcomes from the Sprint |
| **Sprint Retro**<br /> Day +2 | * A few days after the Sprint Close, Retro the previous Sprint live to collect feedback and discuss how we can improve |

## Project Management Rules
These rules are what Aptible has agreed to with respect to defining and tracking work.

* Stories vs. Epics vs. Milestones vs. Tasks
	* **Stories** are typically the smallest unit of work that we use at Aptible. What's a Story?
		* Atlassian defines Stories as one simple narrative; Shortcut defines Stories as the basic unit of work.
		* A Story must be achievable within a Sprint; if it can't be, it should be broken into smaller Stories associated with an Epic.
		* Examples of a Story might be:
			* `Write the Q4 customer newsletter`
			* `Update IAM permissions so that the restart operation works`
			* `Research tradeoffs of EKS`
		* A Story must be associated with a Sprint OR have a deadline or both
		* A Story must have an owner
		* A Story must have an Epic, unless purely operational/transitory and not clearly relevant to broader company goals
	* **Epics** are collections of Stories that make up a broader group of work. Epics can be thought of a Projects.
		* Examples of Epcis might be:
			* `Year-end customer comms`
			* `20.04 rollout`
			* `Any Cloud prototyping`
		* An Epic has a status
		* An Epic has start/end dates
		* An Epic has an assigned owner(s) and team
		* An Epic is usually associated with a Milestone
		* An Epic spans multiple sprints
	* **Milestones** are bigger strategic goals.
		* Milestones cover a specific time period (have a start and end date)
		* Today, Milestones are tied to Company-level goals, but in the future we can use Milestones for more granular goal setting (e.g. team goals)
	* **Tasks** are generally frowned upon but can be used for quick to do lists
		* If you start collecting Tasks that require different ownership or due dates, it's time to split each into a Story (which fortunately Shortcut has a specific button for)
		* If you associate all these Stories that were converted from Tasks to a specific Epic you will be able to track progress collectively across the Epic, using the Epic view
* Process
	* Teams should work together to define Stories and Epics
	* Daily Updates: Individual Story and Epic owners are responsible for keeping status, start/end dates, comments, etc. updated.
		** We ask for updates on In Progress work at least 1x per day
		** It's also a good idea to at least 1x per day consider whether your work is appropriately represented in Shortcut. If it isn't, you should create additional Stories and Epics. If you are unsure, talk with your manager. 
	* End of Sprint / Sprint Forecast
		* If a Story is likely to remain unfinished at the end of the Sprint, and no later than 2 days before Sprint close, functional leads (or individual team members) should:
			* Add the label `Likely Unfinished During Sprint`.
			* Comment re: Estimated time remaining
			* Comment re: Perceived blockers
			* Comment re: When we should return to them (next sprint or some other time)
		* During Sprint planning, we will move Stories with the label 'Likely Unfinished During Sprint' (and remove the label) as needed

## Project Management Guidelines
These guidelines are just recommendations, not hard-and-fast rules. However, we believe that the closer we can align around these guidelines, the easier and more beneficial project management will be for Aptible and for each individual team member. Have a suggestion for how we can improve? Don’t be shy: open a PR or raise for discussion during our next Retro (or async via Slack).
* Five minute rule. If something takes you more than 5 minutes, and it isn’t logged in Zendesk (e.g. a Zendesk ticket) or tracked in our CRM, there should be an associated Story or Stories in our Project Management tool. 
	* Obviously not every 5 minute tasks deserves a Story, but this is a heuristic to evaluate when to create a Story vs. just to complete the work: ideally, any significant work would be documented and prioritized for future reflection/evaluation.
	* For a specific controversial example: writing an email response that takes more than 5 minutes doesn’t feel especially relevant to track in a project management tool. But, if that email response is in a running thread with a customer where we are working through a topic that will require multiple rounds of followup to get to resolution, that should likely be managed through Zendesk or, if not, logged as a Story in Shortcut so we don’t lose track of the work.
* Daily Status Updates and Comments. At least 1x per business day, you should create any new and update active existing Stories and Epics: ensure that the State for each Story and Epic is current, and leave comments addressing your progress so anyone can see and follow along.
* Limit the use of Subtasks. Use Subtasks sparingly - default to creating separate Stories under an Epic, so each Story can have a discrete deadline. Subtasks are fine for simple items, but often it is better to create separate Stories for discoverability and flexibility to set specific deadlines, owners, etc.



## Additional resources
* [Using Shortcut](using-shortcut.md)
