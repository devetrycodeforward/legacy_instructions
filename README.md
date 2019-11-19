### Legacy Groups:

#### Group 1:
- Theresa
- Jenele
- Bronson

#### Group 2:
- Pete
- Steve
- Kristen


### Stand up
- Completed tasks
    - new task assignment
    - Is it okay that I take this task?
- CAN Schedule time with partnters to work stuff out
- DON'T do it DURING the stand up time
- How will what I have been working on impact my teammates
    - I changed this, so if you are going to work with it, you should know about this
- If you are blocked by something from another teammate
    - If you're blocked for more than several hours, talk to your teammembers
        - IF you and your teammembers can't get it resolved, reach out to a TA



### Using [Trello](https://trello.com/)
- Create account
- One person creates board (shares with other teammates)
- Set up board in the following way:
    - Backlog (add to Todo when a task is completed)
        - (Add user info to front-end after having it in db and backend)
    - Todo
    - In Progress 
        - Every person should have only ONE in-progress task
        - Move to done when complete
        - Update, backlog if applicable
    - Done
- Share board with instructors

### Getting Set up on GitHub

- ONE TEAM MEMBER: Create GitHub organization
- From the org account: FORK the Source Code
- Make a `dev` branch based on the current state of the code
    - Make this from the current `master`
- Every team member clones from that org's source

### GIT WORKFLOW:
- `git checkout dev`
- `git branch -b my-new-feature-branch`
- ADD, COMMIT, PUSH TO YOUR FEATURE BRANCH
- WHEN Feature is functional:
    - `git checkout dev`
    - `git pull origin dev`
    - `git checkout my-new-feature-branch`
    - `git merge dev`
    - HANDLE local Conflicts
    - Git add, commit, and push
    - AFTER conflicts are resolved:
        - ON Github.com: Open a PULL request feature branch INTO the `dev` branch
        - Have a teammate review your Pull Request
        - Teammate Merges PR

### MISC:
- Each Team Member is working on a 'full-stack' feature!
- Before your start coding:
    - AS A TEAM: Decide what app you want to inherit
    - AS A TEAM: Decide what features you want to add/change about the app you inherit
    - AS A TEAM: Create trello tickets for the work that needs to get done
- COMMUNICATE
    - You are no longer a lone developer
    - Don't be an A**Hole
    - Practice Patience
    - Practice being a good teacher and a good listener
    - DON'T refactor your teammates code b/c you don't like how they implemented something
        - Stick to your full stack feature(s)
- Resume Driven Development
    - Do something that encapsulates the full stack
    - Impressive to discuss with hiring managers