# Take Home Tech Test  

## Build a Live Sports Scoring App  

### Summary  
The task is to build a live sports scoring app that displays ongoing matches with real-time scores and match details, such as:  
- Team names  
- Current score  
- Match status  
- Time elapsed  

Feel free to spend as much or as little time on the exercise as you like, as long as the following requirements have been met (We recommend 6-8 hours). However, we understand people have busy lives. If you have recently completed a similar task as part of another interview process, we are open to reviewing that task as long as it allows us to effectively evaluate your skills.  

---

### Requirements  
- Display a list of ongoing sports matches with real-time scores using the API here and following the design below: https://pyates-twocircles.github.io/two-circles-tech-test/fixtures.json

![Fixture List](https://pyates-twocircles.github.io/two-circles-tech-test/fixture-list.png)

There are 3 different match states available in the response:
1. Top design - Upcoming - Status: U
2. Middle design - In Progress - Status: I
3. Bottom design - Complete - Status: C

- Allow users to tap on a match to view a detail screen using the API here and following design below: https://pyates-twocircles.github.io/two-circles-tech-test/match.json

![Match Detail](https://pyates-twocircles.github.io/two-circles-tech-test/match-detail.png)

- As there is only one match detail response, all matches will transition to the same match centre regardless of which match is tapped. However be prepared to discuss how you would transfer state from one screen to the next (such as match id).
- To display the goal timeline filter the events array by the key type 'G', you will then need to lookup the player name from the teamLists using the personId from the event list.

- Implement real-time updates using periodic polling (every 30 seconds).

Feel free to improve the design and add further details if you wish and have the time. Make as many assumptions as you need, we can discuss as part of the review process. Remember this is an opportunity to show off and show what you are capable of.

### Technical Requirements
- Feel free to use any frameworks, however be prepared to justify why you need them. The focus should be on pure engineering rather than a framework for everything approach.
- Use the latest features available from your operating system / toolset / language, there are no minimum support requirements.
- Unit Tests.

### Evaluation Criteria
- Code quality and readability.
- Scalability and extensibility of architecture.
- User experience and UI responsiveness.
- Correct handling of API data.
- Ability to justify decisions during review.

### Delivery  
To avoid bounced emails, please submit your results using either:  
- A shared Google Drive link, or  
- A publicly available GitHub repository.  

**Provide a `README.md` file detailing:**  
1. How to set up and run the project.   
2. Features implemented and known limitations.  
3. Any assumptions made.