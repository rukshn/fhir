## What is FHIR Auth?

<img src="https://i.imgur.com/2d6TQtq.png" height="256" />

FHIR Auth is a robust authentication service for FHIR servers. 
FHIR Auth helps you to validate incoming requests to your FHIR server and allows only privileged request to communicate with your FHIR server. 

You can create applications and grant them privileges to connect with your FHIR server to perform CURD (Create, update, read and delete) actions.

FHIR Auth use JWT open standard to generate authentication tokens.

## How you can grant privileges?
In FHIR Auth, you can create applications and grant them privileges, depending on the requirements.
After creating the application in the FHIR Auth dashboard, you can provide the generated token and secret to the developers who want to communicate with your FHIR server.
