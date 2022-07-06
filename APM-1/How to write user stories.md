### Q. What is a User Story? 
- User Story is a tool in which requirements are captured in an easy to understand plain language, and is written from the perspective of an end user. 
- In software development and product management, a user story is an informal, natural language description of one or more features of a software system. User stories are often written from the perspective of an end user or user of a system
- In Agile software development, user stories are used to express the requirements from an end user perspective.  The format of the user story is
	  - **User :**  is the end user or the role of the user in the application software – “As a net banking customer” 
    - **perform an action :** the action the user is performing on the application software – “I want to add beneficiary in my account” 
    - **I expect.. :** outcome, desired value, the user expects out of the action performed – “so that I can transfer money to the added beneficiary”
    - The larger sized stories are called as “Epics” which are then decomposed to “Features” and then further decomposed to a “User Story”.  
    - Epic example: As a Bank, I want to provide net banking to customers, so that they can perform various transactions. 
    - The above Epic can then be decomposed into multiple features: few examples: 
    - As a Bank, I want to provide funds transfer feature to customer, so that they can transfer funds from one account to another account 
    - As a Bank, I want to provide account summary for all the customer’s type of accounts. 
    - As a Bank, I want to provide credit card details to customers. 
    - Now each feature can be decomposed further into multiple user stories.
- User stories, based on the estimate size, are taken for implementation in an iteration. User stories should be granular enough that they can be completed within an iteration and cannot be continued in the following iteration. 
- If a story cannot be completed within an iteration, the same should be split logically. User stories are prioritized by the product owner based on business priority and are available at the top of the product backlog. The dev team pulls the stories into an iteration backlog and implements them. 
- The Definition of Done(DOD) for user stories are decided by the team which includes acceptance criteria, processes that need to be followed like unit testing, regression testing, code review etc. The story is said to be “done” only when it meets the preset Definition of Done. 

### Q. Who writes user stories? 
- User stories are written throughout the lifecycle of the project. At the start of the project, user stories are written in Sprint '0', also called as pre-sprint. 
- Initially the product owner elicits the requirements from the stakeholder and they are stored as EPICS, Features and User Stories in the product backlog. 
- The requirements in agile software development are progressively elaborated and hence the need for writing user stories will arise throughout the project. 
- These are written mainly during the backlog grooming session where the product owner decomposes epics/features into granular stories. 
- Dev team writes stories along with the product owner during this session and also gets  involved in the 3 C’s (the next section describes this). 
	- “Card”, “Conversation” and “Confirmation” is a model that captures the components of a user story.  This is popularly known as the 3Cs model that helps in planning and estimating the user stories by the Agile team. 
	- Card : denotes a Post It note or physical card, typically 3”x5” size, where the important information of a user story is captured. The card should contain enough information (not too less or too much) that the team is able to understand in order to plan & estimate on the story. 
	- Conversation : this is the conversation that happens between the product owner and the dev team to discuss on the story and get into the details. This may also be a conversation with the users of the system. This conversation also brings out the creativity of the dev team and uncovers any unstated needs of the users. 
	- Confirmation - this brings out the acceptance criteria for a story based on the above conversation.  This criterion will be used to evaluate the story by the stakeholders when the user story is implemented by the dev team. 

### Q. Why create user stories? 
- It enables the team to understand the requirements from a user perspective. 
- The focus is on the user to provide value to them; the user story clearly describes the expected outcome of every action performed. 
- This manner of capturing requirements provides opportunities for the team to collaborate more with the product owner and business users. 
- By having conversations (in 3 Cs), the team is able to uncover the hidden requirements and also come up with creative solutions. 
- Provides a shared understanding of the requirements to the team so that everyone is aware of the outcome/goal of the story and is on the same page. 
- User stories help the team to achieve smaller product increments. 
- User stories are more understandable by all stakeholders (technical/non-technical/business/operations). 
- User stories help the team to implement features in smaller iterations ranging from one week to one-month durations. 
- User stories enable the team for progressive elaboration, where they can defer the story until more clarity is obtained. 
- User stories help create transparency of the priorities defined by the product owner and the customer. 
- User stories help the developers, product owner and business owners to reach a mutual consensus as they discuss the details and agree on the acceptance criteria. 
- This helps prioritize the product features by the stakeholders and also helps to take the right decisions at the right time. 

### Q. INVEST in User Stories
- Independent : User stories should be independent of other stories. There should be no overlap between them. They can however follow one after the other in a sequence, in a way that makes it easy to schedule and implement them.  
- Negotiable : The story should not be written in so much detail that it becomes a requirement document. If it is in too much detail, it does not give an opportunity for the dev team to have any conversation with the product owner or the business. The story should be written with just enough detail so that it paves the way to open discussions with the product owner or business, and helps to elicit details or come up with creative solutions. By negotiating on the story with the relevant stakeholders, teams can come to a common understanding. 
- Valuable : The story should be valuable to the customer. It should clearly state why we are doing this? How is it going to produce value to the customer? What value will the customer realize by implementing this story?
- Estimable : The user stories should have sufficient detail for the dev team to understand and estimate them. The conversation in 3 C’s helps the team to uncover the details with the product owner and stakeholders, so that they can size the story. If the story is too big and not sizeable, then the story should be refined or decomposed further. Whatever information the team may require should be available in the story for them to estimate it. In case there is a part of the story where the team has to do research, then a “spike” story may be created while the rest of the story can be estimated and taken for implementation. 
- Small : Good user stories should be small. This does not refer to the size or number of words written in a story. A small story is of the right length so that the implementation team can complete the story within an iteration. It should be small enough that the story is “fully delivered” during an iteration.
- Testable : A good user story should be testable in order to be “Done”. This is supported by the “Confirmation” in 3 C’s where the team comes up with acceptance criteria for every story after the detailed conversation with the stakeholders. 

### Splitting User Stories:
- Why is splitting user stories important?
  - User story splitting might seem too nitty-gritty, but it’s a valuable activity for Agile teams for a few different reasons, primarily: 
    - Story splitting user stories avoids overwhelm by giving the team smaller, more manageable pieces of work
    - Story splitting helps teams deliver value to customers early and often
    - Story splitting changes the mindset from thinking about layers of development to the experience of the user
    - Story splitting requires that the team prioritizes the highest-value goals and features for users 
- When To Split A User Story:
  - A user story should be split when it is too large to fit within a single iteration. Sometimes a user story won’t fit in an iteration because it is bigger than a full iteration. Clearly, a story in this situation needs to be split.
  - it can be useful to split a large user story (an epic) if a more accurate estimate is necessary.
- Split by capabilities offered
  - This is the most obvious way to split a large feature. Look at the different capabilities being offered and split each one into its own story. For example, the capabilities “sort and search” may each be its own story. Splitting further, each way of sorting or searching may be its own story.
- Split by user roles
  - Administrators interact with a system differently from normal users. Teachers interact with instructional software differently from students. By defining the different roles in your system, you can split features and stories to address the unique needs of each role.
- Split by target device
  - You can’t assume that users are interacting with your system using a standard computer. Various smartphones and IoT devices need to be considered in your stories. Splitting stories by device provides a more natural experience for your users.
