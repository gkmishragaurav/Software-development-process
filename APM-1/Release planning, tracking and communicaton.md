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

