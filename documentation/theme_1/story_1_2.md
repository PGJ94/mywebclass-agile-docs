"As a user, the pipeline should be set up to notify the team of any failures or errors during the build or deployment process"

Acceptance Criteria:

Given that the pipeline is set up for the website,
The pipeline should be set up to automatically notify the team via email or other communication channel of any build or deployment failures or errors.
The notifications should include a description of the failure or error, as well as the location and time of the error.
The pipeline should be able to differentiate between minor and critical errors, and provide a clear indication of the severity of the error.
The notifications should include a link to the relevant logs or reports to assist with troubleshooting and debugging.
The pipeline should be well-documented and easy to maintain, to ensure that any future updates or changes can be made easily and without impacting the notification system.

## Test Plan
* Build Failure Notification Test - This test allows the verification of pipeline sending notifcation to the team whenever build failure occurs. This test can be automated using a testing framework to simulate a build failure and verify that the is sent to the designated team members.
* Compliance Testing - Software testing that involves testing a software application or system to ensure that it complies with specific regulations, standards, or requirements.

## Measuring Effectiveness
* Notification frequency - To make sure that the pipeline is sending notications to the team as expected, through this, we can measure the number of notifications sent to the team during a specific period

## Tasks related to this story
1. [Set up pipeline notifications for build and deployment failures](task_1_2.md)
