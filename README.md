# Semantiv versioning

This is a small tool to automate our versioning. 

## How to use it

1. When you create a PR add a label whether this will be a major, minor or patch update. You can change it later, too. 
2. After the Review push an empty commit with the comment "Update Version" and the action will automatically update the version according to the label that is set in step 1. 
2.1 The version should fail, if two PRs want to publish the same version number. The PR that gets merged first will do so successfully, but the following PRs will fail. Merging with main and commiting an "Update Version" commit will resolve it. 

Have fun testing it
