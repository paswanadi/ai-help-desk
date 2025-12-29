# ai helpdesk saas 
## goal 
Build a multiple-tenant helpdesk knowledge base SaaS on AWS (serverless-first), using free/local AI first.
## Region 
ap-southeast-2 (Sydney)
##Naming 
Prefix: aihelpdesk 
Environment: dev
## MVP features 
-Auth (cognito)
-workspaces (multi-tenant)
-upload docs to s3
-process docs into chunks 
-Ask questions + sources (RAG later)
##API (planned)
-GET /health
-GET /me
-POST /workspaces 
-GET /workspaces
## Progress Log 
-[x] Day 1: repo + region + naming + budgets 
-[] Day 2: cognito setup
