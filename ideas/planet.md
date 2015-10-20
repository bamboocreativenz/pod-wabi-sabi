##planet

*planning / time and task visualisation interface*

this idea has come out of multiple discussions between iain and dan, and searching for a tool across the team that can visualise and pipeline our upcoming work and financial situation.
current solutions do some of what we are after, but not all.
we feel like there may be an opportunity to build an app that does what we need, and that this may be useful across a number of Enspiral ventures (and further: i.e. startups)

*PROBLEMS*
- we want to be able to see our team's allocation of human resources to projects, over time
- we want to see our team's human resources allocation to projects OUTSIDE of our team too (i.e. teaching team)
- we want to be able to define higher-level business rules and stories for a project (above user stories and units in Trello)
- we want to be able to see the financial state of the team
- we want to be able to see the projected financial state of the team

*CURRENT SOLUTIONS: PROS AND CONS*
- teamweek
- elegannt
- excel spreadsheet

*IDEAS*

- a block-based graph, with time as the x-axis, where each block represents time allocated to a specific project.
- ability to toggle the y-axis between:
  - project-based view, where each row is defined by a project (and blocks of time represent people working on the project?)
  - people-based view, where each row is defined by a person's available time (and blocks of time represent projects)
- a 'focus' area beneath the graph which reveals drill-down data about a person, or a project (when clicked on / selected?)
  - Iain prefers in-viz expansion and contraction, particularly if the drill-down data is still over time, as this should be more intuitive and comprehendable by the user
  - a focus area provides opportunity for additional styles / types of viz (i.e. pie graphs etc)
- a 'financial' area beneath the graph, which shows the financial position of the team / person in question?
  - Iain would prefer this to be combined with the graph somehow, though significant risk of info overload... tough to integrate successfully.
- sections that can collapse if the user doesn't want to see them? (i.e. the Rohan proposition)
- ability to visualise by teams, and allow a person to belong to multiple teams.
- exploration of how this app could work within the Open App Ecosystem?
- common data structures to other Enspiral apps?
- integration with Trello and Toggl
- a notion of signalling with the viz for financial situation and time allocation situation: i.e. a green / red signal that finances are good / bad (per team / per person), some signal whether a person is free / not free for a certain time period.
- how could this tool potentially serve other purposes (i.e. rostering solution for kindergarten?) in conjunction with our immediate use case? if it can? ideal here being to build a modular tool that can be applied to a variety of use cases, while still being intuitive and simple to use. a 'generic' tool rather than a specific tool?
