# PPDeploymentWithGithubNew
Help to Crate GitHub Actions to deploye PP solution

Steps to Run 

Do the required change in solution. 

Change the version number and publish the changes. 

Go to Actions - >  Run Workflow: export-and-branch-solution-with-spn-auth. Wait for completion. 

Go to PR -> click on New Pull request -> select New branch in Compere and click Create pull request. 

Squash and Merget the request. Delete the branch. 

You may directly run the release-solution-to-prod-reusable or go to Code. 

Click on Releases -> Draft a new release - > Create and Select new tag ( ex - V1.0.0.15) 

Provide details and click Publish release. Now release-solution-to-prod-reusable run. 

You may go to Actions tab and see the Run history.
