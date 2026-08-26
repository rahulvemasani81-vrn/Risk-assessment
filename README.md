# Risk-assessment
~~~
EXPERIMENT 5
AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL
Objective
To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as:

User identity
Event name
Event time
AWS service
Region
Operation status
1. Requirements
AWS Account
Web Browser
Internet Connection
Amazon S3 Access
AWS CloudTrail
PART A — ACCESS AWS CLOUDTRAIL
Step 1: Login to AWS
Open the AWS Management Console.
Sign in using your AWS account.
In the AWS search bar, type CloudTrail.
Select AWS CloudTrail.
Screenshot 1: AWS CloudTrail Dashboard
~~~
~~~
~~~
<img width="1600" height="731" alt="WhatsApp Image 2026-08-26 at 9 19 07 PM" src="https://github.com/user-attachments/assets/22d609ec-bd22-41e6-8f5f-c93908b0cd1c" />
~~~
~~~
~~~
Step 2: Open Event History
In the CloudTrail navigation menu, select Event history.
CloudTrail displays recent AWS activity.
Review the available events.
The Event History page may display information such as:

Event Time
Username
Event Name
Event Source
Resource Type
Resource Name
~~~
<img width="1600" height="730" alt="WhatsApp Image 2026-08-26 at 9 19 48 PM" src="https://github.com/user-attachments/assets/db760ad7-4e9e-4697-a33b-36cc8ef306f9" />
~~~
PART B — ANALYZE A CLOUDTRAIL EVENT
Step 3: Select an Event
From the Event History list, select an S3-related event.
Click the event to open its details.
Examine the event information and the event record/JSON.
For this experiment, a CreateKeyPair event can be used.

Step 4: Analyze the CreateKeyPair Event
The CreateKeyPair event indicates that an Amazon EC2 bucket creation operation occurred.

CreateKeyPair Event Observation
Meaning of Important Fields
Field	Meaning / Observation
Event Time	August 04, 2026, 13:55:44 (UTC+05:30) — Time at which the activity occurred
User Name	root — User/identity associated with the activity
Event Name	CreateKeyPair — AWS operation that was performed
Event Source	ec2.amazonaws.com — AWS service that generated the event
AWS Region	eu-north-1 — Region where the activity occurred
Read-only	false — The event involved a change/creation operation
Error Code	- — No error code was reported
~~~
<img width="1035" height="357" alt="WhatsApp Image 2026-08-26 at 9 37 05 PM" src="https://github.com/user-attachments/assets/29755dab-d768-4559-a4d7-420a9e2dda75" />

Step 6: Analyze the Second Event

<img width="1036" height="418" alt="image" src="https://github.com/user-attachments/assets/9647f996-00e2-466d-ac3e-b05b29770ca1" />
~~~
RESULT
The cloud activities in AWS were successfully audited using AWS CloudTrail Event History.

Different AWS events were examined based on:

Event time
User identity
Event name
Event source
AWS Region
Read-only status
Error status
The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.
~~~
