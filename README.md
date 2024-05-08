# Assignment-3-Jenkins
Assignment-3-Jenkins

**For a detailed solution to this assignment, click this link:** https://medium.com/devops-guides/create-a-pipeline-when-one-job-is-successful-another-job-should-be-triggered-jenkins-assignment-3-cb50c33d577f

**Step 1:** Set Up the Jenkins Environment using Ubuntu Here.

**Step 2:** Set up the Jenkins Dashboard.

**Step 3:** Create Three Nodes as "Jenkins-Master", "Test-Node" & "Prod-Node".

**Step 4:** Create a GitHub repository as "Assignment-3-Jenkins".

**Step 5:** Create Two Jobs Test-Job & Prod-Job as a "Freestyle project". Add develop.txt & dev1.txt respectively here.

**Step 6:** Add a Webhook in GitHub.

**Step 7:** Add the develop1.txt & the "Test-Job" will be automatically triggered.

**Step 8:** Delete the develop1.txt in "Test-Job" & the "Prod-Job" pipeline will be automatically triggered.

**Step 9:** Also, go to the "local folder" in Test & Prod, you can access the content of develop1.txt & dev1.txt here.

**Step 10:** Create a pipeline, remove webhook settings, and Again Create develop1.txt in the "GitHub" develop branch. 

**Step 11:** Go to "Test-Job", click on "Run" & the two new builds created for "Test-Job" & "Prod-Job". The pipeline will be successfully triggered.
