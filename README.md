# cloud-events-dashboard
This repo allows the visualization (Table) which shows cross-account, cross-region Cloud Events in near real-time

## Dashboard stack:
- AWS Amplify connected to this Github Repo for easy Hosting and CICD = )
- AWS AppSync (GraphQL)
- Amazon Cognito for Auth for our app
- DynamoDB NoSQL Global data store to keep our events in with automatic cross-region syncing
- Vue.js, with a few popular libraries, for the UI/UX

## cloud-events-router
We will separate the router of our Cloud Events into a different repo to allow for easier maintenance and iteration = )
