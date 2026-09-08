\# ReleaseGuard



A learning project focused on safely deploying and operating an

application on AWS, with measurable deployment and recovery results.



\## Problem



Application updates can introduce errors or slow responses.

Manual deployment and recovery can delay restoring a working service.



\## Planned solution



Build a platform around a small sample ordering application to:



\- Test and package application changes automatically.

\- Introduce new versions gradually.

\- Monitor errors and response times.

\- Restore the stable version when a release fails configured checks.

\- Replace failed application copies and test scaling under load.



\## Current progress



\- Created a dedicated AWS IAM user and group.

\- Configured EC2 read-only permissions.

\- Configured and verified the releaseguard-dev AWS CLI profile.

\- Created a $10 AWS budget with alerts at 50% and 75%.

\- Initialized the local Git repository.



No ReleaseGuard application or EC2 server has been deployed yet.



\## Learning environment



\- Windows laptop for editing code and running AWS CLI and Terraform.

\- MobaXterm for connecting to the planned AWS Linux server.

\- A planned single-server Kubernetes learning environment on AWS.



\## Measurement approach



Record baseline and automated results under comparable test conditions.

Publish only measured results; do not invent improvement percentages.

