# lab-agile-planning
This repository contains the lab for agile planning

---
#### Feature 1 : Need a service that has a counter
As a User,
I need a service that has a counter
So that I can keep track of how many times something has been done.

Details and Assumptions
New a way to increment a counter
Need a way to get the current value
Acceptance Criteria
Given I have incremented the counter to 2
When I make a call to get the current value
Then it should return 2 as the counter value

---
#### Feature 2: Must persist counter across restarts
As a Service Provider,
I need the service to persist the last known count
So that users don't lose track of their counts after the service is restarted.

Details and Assumptions
We will use a Redis database
Counter will be stored as a name-value pair
Acceptance Criteria
Given I have incremented the counter to 2
When I restart the service
Then the counter should still return 2

---
### Feature 5 : Deploy service to the cloud (50% finished)
As a Service Provider,
I need the service to be deployed in the cloud,
So that I can scale capacity with user demand

Details and Assumptions
We will use IBM Cloud
Deploy as a Cloud Foundry app
Acceptance Criteria
Given I have deployed to the cloud
When a customer comes to our URL
Then our service will be available
