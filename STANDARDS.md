# Workflow 

We will be following a ticket-based workflow for all our projects. Each feature will be accompanied by a ticket, and you can choose what tickets you want to work on.  

Once you choose a ticket, you should make a git branch in the respective repository for that ticket and commit all your changes to that branch. You can push your branch to the remote repository as many times as you want.

When the feature is finished, open a pull-request and assign it to Roshan, Lucy and one of your peers. Everyone should be code-reviewing each other's code to make sure the code-style is maintained, there are no bugs and the feature is complete. Pull the code, run all the tests and test it out locally. Open issues at the pull-request if you find any, and if not, approve. You need 2 approvals and 100% tests passing to be able to merge your code into master. Once its done, delete your remote branch and start the next task! 

⚠️ Please don't push to master.


# Testing 

Every task needs to have both unit tests and integration tests. If possible, write tests when you decide the specification, and don't change them as you develop further. [This video](https://www.youtube.com/watch?v=uCxL7NGEohI) is a helpful primer. You should use the test framework chosen for the repo (Frontend uses [JUnit](https://kotlinlang.org/docs/reference/mpp-run-tests.html), Backend uses [Mocha](https://mochajs.org/)).

# Code Style

We will follow the industry-standard code styles across all repositories. The best way to configure them is to add a linter to your IDE so it automatically styles your code. Here's a handy guide to all of them: 

- [Kotlin](https://kotlinlang.org/docs/reference/coding-conventions.html)
- [Javascript](https://github.com/airbnb/javascript)
- [Python](https://www.python.org/dev/peps/pep-0008/)
  
Each repo will also have specific instructions to set up the codestyle plugins. Furthermore, each function or class should have docstrings explaining explicitly what it does, according to the given standards above. 
