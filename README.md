# ai-cicd-logging
simply demonstrate how to set up CICD in github actions
create a folder locally
run code . to open vscode for this folder
add a working folder .github/workflows
under workflows folder add a file ci.yml
put CI codes for build 
check in to github
this check in trigger build automatically
job can be run successfully to mark build as done
in ci.yml add a new job to deploy
deploy at first will connect to azure cloud
secondly will copy the codes into clooud
finally test if this deployment is working as expected and marked it done
