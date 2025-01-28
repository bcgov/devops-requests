---
name: Request for Remote Repo to be Added to Artifactory Project
about: To create a remote Maven repository in your Artifactory Project.
title: ''
labels: artifactory-remote-repo
assignees: caggles, ShellyXueHan

---

## Step 0
This request is ONLY to add one or more Maven remote repositories to your team's Artifactory Project. This is only necessary if you have a local Maven repository in your Artifactory Project and must use both it and another remote repository as a source for your Maven artifacts.

If you are looking to have a remote repository added to Artifactory so that you may use that repository exclusively (or in combination with the other remote repos), please contact the platform team on the #devops-artifactory channel on RocketChat. 

Please outline why your team requires this remote repository added to your Project as part of this step. **If no explanation is given, this ticket will not be actioned.**

## Step 1
Make sure no duplicated request exists, search here:
https://github.com/bcgov/devops-requests/issues

## Step 2
Provide the name of your Artifactory Project: 
(this will be the name of the Openshift namespace in which you requested the ArtifactoryProject with the name of the ArtProj object, like `a1b2c3-tools-myproj`)

## Step 3
Provide the following details about all the remote repos to be added:

- **Repo name**: (this is the name the repo will have in Artifactory, please give it the form `[name]-maven-remote`)
- **Repo URL**: (please ensure this is the URL from which the objects are pulled)
- **Maven Layout**: (does this repo use maven layout version 1 or version 2?)

Please ensure that your provide all three pieces of information for each of the repositories being requested.

## Step 4
If any of the remote repos in question are private and require authentication, please provide your RocketChat username here so a member of the Platform Team can contact you to discuss a way to share the authenticaton information.
