OPENCLASSROOMS TodoList - How to participate in the project
================================================

Workflow
--------
- Each member attached to the project will have restricted rights as a reporter: the push to the main repository is impossible.
- Everyone will have to work on a personal fork of the main repository.
- The merge to the main repository must be done by merge request on the develop branch subject to approval by the responsible owner.

"Fork" repository
------------
- Make a request by email to be added to the project as a collaborator.
- Create a personal fork from the main repository: https://github.com/celestin211/P8-BOSONGO-TODOLIST
- After the fork of the repository to your personal space and the clone on your machine, remember to add the link to the main that you will name "upstream": `git remote add upstream https://github.com/celestin211/P8-BOSONGO-TODOLIST
- Update the develop branch with a `git pull upstream develop` and proceed to install the project, see README.md

Contribute to the project
--------------------
- On github, create an issue that describes the work you are going to do
- Create a new feat/name branch from develop
- Write your code and write the tests
- Control the tests: `bin phpunit/phpunit docs/test-coverage`
- Commit and push your work to your personal fork
- On Github, create a merge request from your new branch to the develop branch of the main start.
