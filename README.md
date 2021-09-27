# patterns-and-naming-git
Patterns for creating branches and commits

#### It's advisable to create predefined and standardized prefixes to identify branches and commits, I personally have my pattern, but it doesn't have to be yours, it's important that you create a pattern that makes sense to you and your team.

* bugfix
* feature
* hotfix
* improvement

#### A brave description about each prefix.

* #### bugfix:
It's a BUG, as the name suggests. Needs to be fixed urgently.

* #### feature:
A new feature that will be added to the project.

* #### hotfix:
Used for fixes, not urgent but needing to be fixed.

* #### improvement:
Unlike a feature that is something new, this is an improvement to a feature.


## Prefix Patterns for Commits

* #### build: 
Changes that affect the build system or external dependencies

* #### ci: 
Changes to our CI configuration files and scripts

* #### cd: 
Changes to our CD configuration files and scripts

* #### chore: 
Serves for related stuff, configs and the like

* #### docs: 
Documentation changes only

* #### feat: 
A new feature for the project

* #### improve: 
Any code change that improves the behavior of a resource

* #### fix: 
An application bug fix

* #### perf: 
Code change that improves application performance and does not change the way the user uses the application

* #### refactor: 
Code change, which does not fix a bug or change the way the user uses the application

* #### revert: 
Revert to a previous commit

* #### style: 
Changes that do not affect the meaning of the code (white space, formatting, semicolon, etc.)

* #### test: 
Adding Missing Tests or Fixing Existing Tests

* #### static: 
Changes to static file content (.json data, images, etc)


## Based on the standards of:

  * Github: https://github.com/commitizen/cz-cli
 

