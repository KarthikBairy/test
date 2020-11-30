# A Simple K8s Test

## Given
- A git repository and a working K8s cluster

## Problem Statement
- User updates the git repository code
- The contents(e.g index.html) are deployed and avaliable to view on browser endpoint
- Latest content is always avaliable on the endpoint

Conditions:
- The webserver should not clone the repository - it is expected this image is provided to you by a 3rd party and does not understand git. 
The image expects the contents to be avaliable at a specific location which is exposed by the server
- No external CI/CD pipeline should be used
- You can deploy anything else inside the cluster as required.

There can be multiple solutions to this problem. One such solution has been implemented in k8s folder.
Once deployed, you can browse on port: 31370.

Enjoy !!
