# Telerik DevOps upskill program, CI/CD tasks 
A repository created for practicing Github Actions.  
Feel free to fork this repository and work in the forked version.

To make me feel that I've learn something from this chapter my goal is to produce a GitHub action that:
* Will build symple Crystal `hello-world` code into binary
* Embed Ameba for static code analysis tool
* Use linter to test the code
* Send a Slack notification (on success or fail) on all commit/PR/merge actions
* Save the binary as an GitHub artifact
  * Bonus point to use jFrog Artifactory
* Build the Crystal code on Linux, Windows and macOS (wish me luck with that)
* Use SonarCloud for code quality/code security (If supports Crystal)
* Use Snyk on the pipeline (if supports Crystal)
* Build docker container and publish it at hub.docker.com
