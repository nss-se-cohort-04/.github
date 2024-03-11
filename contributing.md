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
- Please make sure your [PR description](https://www.pullrequest.com/blog/writing-a-great-pull-request-description/) explains the task/work/feature/bug.

## How do I get feedback on my Pull Requests? 

0 - Most all excersizes have tests and serve as automated feedback. If tests pass, your code functions as expected, is formatted properly ([checkstyle](https://checkstyle.sourceforge.io/)) and you implemented the functionality the tests expected.
    This is somethimes good enough. Options 1,2,3 below are additional feedback mechanisms for parts of the work that is hard to test via automated checks.

1 - [Request 1 group mate to provide reviews](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review) 
- The goal is to spread the review evenly across the class
- Alternate which group mate you ask for review

2 Your instructors [@gcziprusz](https://github.com/gcziprusz) and [@jody](https://github.com/ProbablyJody) will post solution branches to excercise in slack after the fact.
- You should compare your work to the solution to learn if you were going in the right direction or 
look for possible alternatives.

3 Your instructors [@gcziprusz](https://github.com/gcziprusz) and [@jody](https://github.com/ProbablyJody) will review every submission for: 
- a) Comprehensive coding assignments
- b) Unit projects (at the end of the unit)

No need to request a review from instructors, they are notified of all submissions automatically. 

Not every PR will be reviewed by the instructors. Use options 1 and 2 
above to still validate your work.

Since reviews are such an important part of learning this craft your instructors will 
try and review as many PR that arenn't in the a,b categories mentioned above like normal daily excercises/ tries etc.
but cant guarantee will be able to review all of them all the time consistently.

### How do I open the final PR for unit project including all building tasks to be reviewed by the instructors? 
Since students are getting reviews at each milestone from groupmates and merging the work as they go for each building task we need a way for all the changes from all tasks in a single big PR that your instructors will review.

Here is how you open the final PR for the project: 
  [Same instructions in video format](https://www.youtube.com/watch?v=6-GJIolLKZc)

- As you are working on the project at each checkpoint push your changes and have a PR reviewed by your peers then MERGE to `exercise`
- Once you are fully done with the project 
- go to github.com 
- look at the `excercise` branch
- click on 'commit'
- Click the <> diamond squares of the VERY FIRST COMMIT by github-classroom[bot]  
- In the branch switch dropdown and type `main`
- click the link "Create branch: main from `617bde06` "
- click on pull requests then the green `New pull request`
- Select base `main` <- `exersice` then `Create pull request`
- Make sure all you commits from all tasks are present 
- fill out your description template / make sure your tests are passing 
- tag both instructors for review 



### [How do I invite a group mate as a collaborator to my repo?](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-teams-and-people-with-access-to-your-repository#inviting-a-team-or-person)

### [How do I give feedback?](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request?tool=webui)

### [What feedback do I leave?](https://medium.com/hackernoon/how-to-give-and-get-better-code-reviews-e011c3cda55e)

### [How do I deliver my feedback?](https://rewind.com/blog/best-practices-for-reviewing-pull-requests-in-github/)

### Question you should ask yourself when reviewing a PR
#### Code Style and Formatting
- Are there consistent indentation, naming conventions, and code structure aka does the gradle checkstyle task pass?
- Is the code clear and concise with meaningful variable names and comments?
- Are all editor-specific or other local metadata files excluded from Git by adding them to .gitignore?
- Have all API keys or other sensitive information been excluded from the source code?
- Have relevant documentation updates been made, including Javadoc comments and README files PR description and title?
- Is it clear what changes are introduced? What bugs are fixed? If any new features added?
- Is it easy to understand the code?
- Did the author include all relevant context and informatiomn on how to test the code in the Pull request?
#### Functionality
- Does the proposed change implement the intended functionality, does it compile and run on the reviewers machine locally?
- Have various scenarios been tested to identify potential bugs or edge cases?
#### Testing
- Are there appropriate unit tests accompanying the changes?
- Are the unit tests passing?

Functionality:
Does the proposed change implement the intended functionality, does it compile and run on the reviewers machine locally?
Have various scenarios been tested to identify potential bugs or edge cases?

Testing:
Are there appropriate unit tests accompanying the changes?
Are the unit tests passing?


### Why do we do PR reviews? 
This is a great learning opportunity for both the author and the reviewer. Make the most of it ask question looks things you can use in your own code next time suggest things you would have done/did differently in your own work. 

### Should I expect my code to be re-reviewed? 
We will do a single round of reviews. Once you address feedback from the groupmate or in case of Comprehensives and end of unit Project instructor. Your PR is ready to be merged.

### When you should expect instructor reviews?
**Comprehensives and assessments** will be reviewed within 5 business days after the submission deadline. 

**Projects** will get in-depth review within 10 business days after the submission deadline.

**Daily exercises and other coding challenge** solutions will be released after the class concludes for the day. We will start the next day with a 20 minute review of the exercise from the previous day. 5-10 minutes of the review should be spent individually comparing the solution to your own work. The rest of the time will be spent discussing the solution and attempts.
