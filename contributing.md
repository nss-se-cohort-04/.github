# Contribution guidelines reviews and more

## How do I open a good pull request?
- Follow the instruction in [canvas](https://nss.instructure.com/) to checkout the 
code and create a feature branch (most likely need to append `-feature` like `{original_branch_name}-feature`
- run the test suite `gradle test` before you make any changes to ensure the project builds and the expected test types pass (Code Coverage & Unit Tests  & Codestyle & Project Validation IRTs)
- Do your work `while(!done) do work`
- Once you are done with your work, push your changes to github and open a Pull Request (PR)
- Fill out the PR template
- Jokes are great and encouraged in slack and during class time. Please keep them out of PR's/ commit messages. Commits are 
part of documentation.

## How do I get feedback on my Pull Requests? 

0 - Most all excersizes have tests and serve as automated feedback. If tests pass, your code functions as expected, is formatted properly ([checkstyle](https://checkstyle.sourceforge.io/)) and you implemented the functionality the tests expected.
    This is somethimes good enough. Options 1,2,3 below are additional feedback mechanisms for parts of the work that is hard to test via automated checks.

1 - [Request 1 group mate to provide reviews](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review) 
- The goal is to spread the review evenly across the class
- Alternate which group mate you ask for review

2 Your instructors [@gcziprusz](https://github.com/gcziprusz) and [@rtillies](https://github.com/rtillies) will post solution branches to excercise in slack after the fact.
- You should compare your work to the solution to learn if you were going in the right direction or 
look for possible alternatives.

3 Your instructors [@gcziprusz](https://github.com/gcziprusz) and [@rtillies](https://github.com/rtillies) will review every submission for: 
- a) Comprehensive coding assignments
- b) Unit projects (at the end of the unit)

No need to request a review from instructors, they are notified of all submissions automatically. 

Not every PR will be reviewed by the instructors. Use options 1 and 2 
above to still validate your work.

Since reviews are such an important part of learning this craft your instructors will 
try and review as many PR that arenn't in the a,b categories mentioned above like normal daily excercises/ tries etc.
but cant guarantee will be able to review all of them all the time consistently.



### [How do I give feedback?](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request?tool=webui)

### [What feedback do I leave?](https://medium.com/hackernoon/how-to-give-and-get-better-code-reviews-e011c3cda55e)

### [How do I deliver my feedback?](https://rewind.com/blog/best-practices-for-reviewing-pull-requests-in-github/)

### Why do we do PR reviews? 
This is a great learning opportunity for both the author and the reviewer. Make the most of it ask question looks things you can use in your own code next time suggest things you would have done/did differently in your own work. 

### Should I expect my code to be re-reviewed? 
We will do a single round of reviews. Once you address feedback from the groupmate or in case of Comprehensives and end of unit Project instructor. Your PR is ready to be merged.

### When you should expect instructor reviews?
Your instructor will communicate by when will have all submissions reviewed. If They do not communicate this ask!

