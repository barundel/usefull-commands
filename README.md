# usefull-commands
So you dont have to keep googling things 

# git

// tagging > sometimes you need to tag manually this is how: 
git tag --list // Lists the tags 

git tag -a v1.4 -m "my version 1.4" // creates a tag with a comment 

git push origin --tags // pushes your tags to repo 

# aws

aws apigateway get-deployments --rest-api-id YOURRESTIDHERE --profile ifneeded
// This gets the deployment ID if your creating a stage via terraform outside of a master deployment 
