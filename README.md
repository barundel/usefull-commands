# usefull-commands
So you dont have to keep googling things 

# git

// tagging > sometimes you need to tag manually this is how: 
git tag --list // Lists the tags 

git tag -a v1.4 -m "my version 1.4" // creates a tag with a comment 

git push origin --tags // pushes your tags to repo 

--

To set repository-specific username/email configuration:
From the command line, change into the repository directory.

Set your username:
git config user.name "FIRST_NAME LAST_NAME"

Set your email address:
git config user.email "MY_NAME@example.com"

Verify your configuration by displaying your configuration file:
cat .git/config

# aws

aws apigateway get-deployments --rest-api-id YOURRESTIDHERE --profile ifneeded
// This gets the deployment ID if your creating a stage via terraform outside of a master deployment 
