### Q. Why Release Planning is Essential?
- Release planning is the process of creating a very high-level plan that covers a period longer than an iteration. A typical release will cover perhaps three to six months and maybe three to twelve or more iterations, depending on how long
the iterations are.
- It helps the product owner and the whole team decide how much must be developed and how long that will take before they have a releasable product.The sooner the product can be released (and the better it is when it’s released), the sooner the organization will begin earning a return on their investment in the project.
- A release conveys expectations about what is likely to be developed and in what timeframe. Many organizations need this information because it feeds into other strategic planning activities.
- A release plan serves as a guidepost toward which the project team can progress. Without the concept of a release, teams move endlessly from one iteration to the next. A release plan provides context that allows iterations to combine into a satisfying whole. 

### The Release Plan:
- The general steps to planning a release are shown in Figure
  - Determine the Conditions of Satisfaction:
    - Before starting to plan a release, it is important to know the criteria by which the project will be evaluated as a success or a failure. For most projects, the ultimate scorecard is the amount of money saved or generated. As leading indicators of whether a project is likely to achieve these financial goals, most projects use the triumvirate of schedule, scope, and resources. 
  - Estimate The User Stories:
    - Because an estimate represents the cost of developing a user story, it is important that each has been estimated. 
    - It is not necessary to estimate everything that a product owner may ever want. It is only necessary to have an estimate for each new feature that has some reasonable possibility of being selected for inclusion in the upcoming release.
    - Often, a product owner will have a wish list that extends two, three, or more releases into the future. It is not necessary to have estimates on the more distant work.
  - Select an Iteration Length:
    - Most agile teams work in iterations of from one to four weeks. It’s possible to go slightly longer and some teams have experimented with even shorter iterations. When planning a release, an appropriate iteration length will need to be chosen.
  - Estimate Velocity:
    - If the team has experience working together, your best bet is often to use the velocity the team exhibited most recently. Naturally, if the technology or business domain changed dramatically, it may not be appropriate to use a team’s past velocity. Still, there are techniques you can apply that enable you to make an informed estimate of velocity based on past results. 
  - Prioritize User Stories:
    - Most projects have either too little time or too many features. It is often impossible to do everything that everyone wants in the time allowed. Because of this, the product owner must prioritize the features she wants developed. 
    - A good product owner will accept ultimate responsibility for prioritizing, but will listen to advice from the development team, especially about sequencing.
  - Select Stories And A Date:
    - you have an estimate of the team’s velocity per iteration and have an assumption about how many iterations there will be. It’s time to see if a release can be planned that meets the conditions of satisfaction for the project.
      - If the project is feature-driven, we can sum the estimates of all needed features and divide by the expected velocity. This will give us the number of iterations necessary to complete the desired functionality.
      - If the project is date-driven, we can determine the number of iterations by looking at a calendar. Multiplying the number of iterations by the expected velocity will tell us how many story points or ideal days will fit in the release. We can count off that many points or ideal days into the prioritized list of user stories and see how much functionality can be delivered in the desired time.
    - The next question to be addressed regards how detailed the release plan will be. Some teams in some environments prefer to create a release plan that shows what they expect to develop during each iteration. Other teams prefer simply to determine what they think will be developed during the overall release, leaving the specifics of each iteration for later. This is something to be discussed and decided during release planning.
    - Because there is a lot of give-and-take and what-if questions during a typical release planning session, we want an easy way to manipulate what’s in and out of the release and its iterations. The best way of achieving this, assuming everyone is collocated, is to work with 3” x 5” note cards or sticky pads with user stories or features written on them.
      - To plan a release, the product owner selects her top priority items that will fit in the first iteration. Cards are stacked or arranged to indicate which stories comprise each iteration. 
      - Cards can be arranged like this on a table or a wall. If you’re using a wall, a cork board is very effective because cards can be pinned to the board, rather than taped to the wall.
      <img width="738" alt="Screenshot 2022-07-08 at 2 54 27 PM" src="https://user-images.githubusercontent.com/49789867/177988797-ce49d4dd-5f31-49a1-8864-f1328cc08958.png">

### Iteration Planning:
- An iteration plan is created in an iteration planning meeting. This meetingshould be attended by the product owner, analysts, programmers, testers, database engineers, user interaction designers, and so on. Anyone involved in taking
a raw idea and turning it into a functioning product should be present.
- an iteration plan can be as simple as a spreadsheet or a set of note cards with one task handwritten on each card. In either case, tasks and stories should be organized so that it’s possible to tell which tasks go with which stories.
- Tasks Are Not Allocated During Iteration Planning
  - Before looking at the things that are done during iteration planning, it’s important to clarify one thing that is not done. While planning an iteration, tasks are not allocated to specific individuals. At the start of the iteration it may appear obvious who will work on a specific task; however, based on the progress of the whole team against the entire set of tasks, what is obvious at the start may not be what happens during the iteration. 
- How Iteration Planning Differs From Release Planning
  - While the release plan looks forward through the release of the product, usually three to six months out at the start of a new project, the iteration plan looks ahead only the length of one iteration, usually one to four weeks.
  - The user stories of the release plan are decomposed into tasks on the iteration plan. Where the user stories of a release plan are estimated in story points or ideal days, the tasks on the iteration plan are estimated in ideal hours. 

    <img width="703" alt="Screenshot 2022-07-08 at 5 34 14 PM" src="https://user-images.githubusercontent.com/49789867/177990989-f1e84320-79bb-42e6-b8ce-bb83c74819a6.png">

### Velocity-Driven Iteration Planning:
  - Adjust Priorities
    - The project could progress by always taking stories from the top of this prioritized list to start each iteration. However, business and project conditions change quickly so it is always worth a quick reconsideration of priorities.
    - One source of changes to priorities is the iteration review meeting, which is held after an iteration is finished. During the iteration review, the new functionality and capabilities that were added during the iteration are demonstrated to stakeholders, the extended project community, and anyone else who is interested. Valuable feedback is often received during these iteration reviews. The product owner herself should generally not come up with new ideas or changes during the iteration review since she’s been involved daily throughout the iteration. However, many others (including potential customers and users) may be seeing the results of the iteration for the first time. They will often have good new ideas that could preempt previously high priority items.
  - Determine Target Velocity
    - The next step in velocity-driven iteration planning is to determine the team’s target velocity. The default assumption by most teams is that their velocity in the next iteration will equal the velocity of the most recent iteration. Beck and Fowler (2000) call this yesterday's weather since our best guess of today's weather is that it will be like yesterday's weather. Other teams prefer to use a moving average over perhaps the last three iterations.
  - Identify An Iteration Goal
    - With their priorities and target velocity in mind, the team identifies a goal they would like to achieve during the iteration. The goal succinctly describes what they would like to accomplish during the iteration. 
  - Select User Stories:
    - Next, the product owner and team select stories that combine to meet the iteration goal.
    - In selecting the stories to work on, the product owner and team consider the priority of each story. 
  - Split User Stories Into Tasks:
    - Once the appropriate set of user stories has been selected, each is decomposed into the set of tasks necessary to deliver the new functionality. 
  - Estimate Tasks:
    - The next step in velocity-driven iteration planning is to estimate each task. Some teams prefer to estimate tasks after all have been identified, other teams prefer to estimate tasks as each is identified. Task estimates are expressed in ideal time. So, if I think that a task will take me six hours of working time I give it an estimate of six hours. I do this even if six hours of time on the task will take me an entire day.
    - Even though we expect a specific individual will be the one to do a task and even though he may know the most about that task, it does not mean that others have nothing to contribute.
    - Hearing how long something is expected to take often helps teams identify misunderstandings about a user story or task. Upon hearing an unexpectedly high estimate, a product owner or analyst may discover that the team is heading toward a more detailed solution than necessary. 
    - when the person who will do the work provides the estimate, the person’s pride and ego may make him reluctant to later admit that an estimate was incorrect. When an estimate is made collaboratively, this reluctance to admit an estimate is wrong goes away.

<img width="780" alt="Screenshot 2022-07-08 at 5 52 47 PM" src="https://user-images.githubusercontent.com/49789867/178132058-6272b09a-5455-42d7-9d3b-e01d3540eb85.png">

### Commitment-Driven Iteration Planning
- Ask For A Team Commitment
  - During an iteration planning meeting I ask the team, “Can you commit to delivering the features we’ve discussed.” Notice that the question I ask is not “Can you commit to delivering the tasks we’ve identified?” That is a very different question, and a far weaker commitment since it is a commitment to complete a set of tasks rather than a commitment to deliver new functionality.
  - Summing The Estimates:
    - The best way I’ve found for a team to determine whether they can commit to a set of user stories is to sum up the estimates given to the tasks and see if the sum represents a reasonable amount of work. There may very well be a large amount of uncertainty on some tasks because the work hasn’t been designed and requirements are vague. However, summing the estimates still gives some indication of the overall size of the work.
  - Individual Commitments:
    - When assessing the ability to commit to completing a set of new functionality, some teams prefer to allocate each task to a specific person and then assess whether each individual is able to commit to that amount of work.
    - If you do find a need to allocate tasks to individuals while planning an iteration, the allocations should be considered temporary and subject to complete change once the iteration is planned and underway.

### Factors In Selecting An Iteration Length:
- The length of the release being worked on
  - If a team is working toward a release that is perhaps only three months away, month-long iterations will give them only two opportunities to gather end-of-iteration feedback, measure progress, and correct course. This is probably insufficient.
  - My general rule-of-thumb is that any project will benefit from having at least four or five such opportunities. This means that if the overall project duration will be four or more months, it might be worth considering monthly or four-week iterations. If the overall release will, however, be shorter, the project will benefit from proportionally shorter iterations
- The amount of uncertainty
  - Uncertainty comes in multiple forms. There is often uncertainty about exactly what the customer or users need, what the velocity of the team will be, and about technical aspects of the project.
  - When there is a great deal of uncertainty about the work to be done or the product to be built, short iterations allow more frequent opportunites for the team to measure its progress through its velocity and more opportunities to get feedback from stakeholders, customers, and users
- The ease of getting feedback
  - Iteration length should be chosen to maximize the amount, frequency, and timeliness of feedback to the whole team. Depending on the environment, this may mean longer or shorter iterations.
  - Choose your iteration length to maximize the value of the feedback that can be received from those within and outside the organization.
- How long priorities can remain unchanged
  - A key consideration is how long it takes a good new idea to be turned into working software. Consider the case of a team using four-week iterations. If we assume that new ideas are equally likely to occur any time during an iteration then, on average, a new idea can be said to occur in the middle of the iteration.
- Willingness to go without feedback
  - Even with a well-intentioned and highly communicative team, it is possible that the results of an iteration could be found worthless when shown to the broader organization at the conclusion of the iteration. 
- The overhead of iterating
  - There are costs associated with each iteration. For example, each iteration must be fully regression tested. If this is costly (usually in terms of time), the team may prefer longer, four-week iterations. Naturally, one of the goals of a successful agile team is to rapidly reduce (or nearly eliminate) the overhead associated with each iteration. But, especially during a team’s early iterations, this cost can be significant and will influence the decision about the best iteration length.
- A feeling of urgency is maintained
  - The solution to this, of course, is to select an iteration length that evens out the pressure the team feels. The point is not to put the team under more pressume (“You will deliver today!”). Rather, it is to take the total amount of stress they’d normally feel and distribute it more evenly across a suitably long iteration.

### Estimating Velocity:
- Use Historical Values:
  - Historical values are great—if you have them. The problem with historical values is that they’re of the greatest value when very little has changed between the old project and team and the new project and team. Any personnel or significant technology changes will reduce the usefulness of historical measures of velocity.
- Run An Iteration:
  - An ideal way to forecast velocity is to run an iteration (or two or three) and then estimate velocity from the observed velocity during the one to three iterations. Because the best way to predict velocity is to actually observe velocity, this should always be your default approach. 
- Make a Forecast:
  - Estimate the number of hours that each person will be available to work on the project each day.
  - Determine the total number of hours that will be spent on the project during the iteration.
  - Arbitrarily and somewhat randomly select stories and expand them into their constituent tasks. Repeat until you have identified enough tasks to fill the number of hours in the iteration.
  - Convert the velocity determined in the prior step into a range.

### Tracking and Communicating:
- Monitoring The Release Plan
  - Velocity measures the amount of work completed by a team each iteration. Velocity should be calculated using an all-or-nothing rule. If a story is finished, the team counts its full estimate when counting velocity. If a story is partially completed during an iteration, it is not counted at all when determining velocity.
  - A release burndown chart shows the number of story points or ideal days remaining in the project as of the start of each iteration. A team’s burndown is never perfectly smooth. It will vary because of inaccurate estimates, changed estimates, and changes in scope, for example. A burndown chart may even show a burnup during an iteration. This means that even though the team probably completed some work they either realized the remaining work was underestimated or they increased the scope of the project.
  - A release burndown bar chart offers a sometimes useful variation on the standard release burndown chart. It does so by separating a team’s progress against planned work and changes to the scope of the release. Scope changes are shown by dropping the bar below the horizontal axis. This type of chart is more expressive than a standard burndown chart, but must be used with care as it may cause arguments in some organizations about whether a change affects the top or the bottom of a bar in the chart.
- Monitoring The Iteration Plan:
  - A task board, which is often a white board, cork board, or just a designated space on a wall, helps a team organize and visualize their work. The columns of a task board are labelled and team members move task cards through the columns as work progresses.
  - An iteration burndown chart is similar to a release burndown chart but is used to track only the work of the current iteration. It graphs the number of hours remaining on the vertical axis and the days of the iteration on the horizontal axis.
  - Teams should be reluctant to track the actual hours expended on tasks in order to get better at estimating. The risks and the effort to do so usually outweigh the benefits.
  - Teams should not calculate or track individual velocity.
- Monitoring The Iteration Plan:
  - The Task Board
   - A task board serves the dual purpose of giving a team a convenient mechanism for organizing their work and a way of seeing at a glance how much work is left.
   - It is important that the task board (or something equivalent to it) allow the team a great deal of flexibility in how they organize their work. Individuals on an agile team do not sign up for (or get assigned) work until they are ready to work on it. This means that except for the last day or two of an iteration, there are typically many tasks that no one has yet signed up for. A task board makes these tasks highly visible so that everyone can see which tasks are being worked on and which are available to sign up for.
   - An iteration burndown chart is similar to a release burndown chart but is used to track only the work of the current iteration. It graphs the number of hours remaining on the vertical axis and the days of the iteration on the horizontal axis.
- Communicating:
  - Communicating the Plan:
    - When asked about the schedule for a project, it is tempting to sum the number of story points to be delivered, divide by a guess of velocity, and say something like “we’ll ship on June 14, which is 7.2 iterations from now.” ” This is wrong because it gives the impression that the knowledge from which we construct the plan is sufficiently precise as to support this type of estimate When possible, include with your communication of a target date either your degree of confidence in the estimate, a range of possible dates, or both. For example, you may say:
      - I am 90% sure we’ll complete the planned functionality by July 31
      - Based on our assumptions about the project size and team performance, the project will take three to four months
    - sample communication:Right now, this appears to be a 200-point project. Based on our performance on other projects (or a random guess), with N programmers on it, and your intimate involvement in the project, a project of this size will take between 4 and 6 months. However, we will be shipping software to you every two weeks, and we’ll be ticking off these feature stories to your satisfaction. The good news is that if you’re not satisfied, you can stop. The better news is that if you become satisfied before all the features are done, you can stop. The bad news is that you need to work with us to make it clear just what your satisfaction means. The best news is that whenever there are enough features working to make the program useful, you can ask us to prepare it for deployment, and we’ll do that. As we go forward, we’ll all see how fast we’re progressing, and our estimate of the time needed will improve. In every case, you’ll see what is going on, you’ll see concrete evidence of useful software running the tests that you specify, and you’ll know everything as soon as I know it.
