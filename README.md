# internship-task--3-Multi-cloud-Architecture-


## Objective
Design a multi-cloud architecture where services are distributed across two cloud providers (simulated using two Google Cloud projects).

## Components
- **Project 1:** Frontend Service (acts as Cloud A)
- **Project 2:** Backend Service (acts as Cloud B)

## Architecture Diagram
Frontend Function → sends request → Backend Function  
Backend Function → processes and responds → Frontend Function displays output

## Tools Used
- Google Cloud Functions
- Cloud Storage
- Pub/Sub
- IAM Permissions

## Output
Successful communication between two projects confirming interoperability.

## How to Run
1. Deploy backend function and note its trigger URL.
2. Deploy frontend function with backend URL in code.
3. Test frontend function using “Test Function” in Cloud Console.

## Result
Frontend and backend communicate successfully — simulating a multi-cloud integration.
