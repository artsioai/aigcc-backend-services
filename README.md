# AIGCC Production Services

This document describe high level of relationships and guideline of AIGCC production micro-services.

**Golden Rules** :
- A service must only make REST calls to peer services or lower-tier services.
- Demo project can copy / clone from the production services


## Tier 3 - Application
- aigcc-apps-service

## Tier 2 - Commonware
- aigcc-asset-service
- aigcc-llmindex-service
- aigcc-artgen-service

## Tier 1 - Platform
- aigcc-platform-service

## Tier 0 - Data & Cloud
- DynamoDB
- AWS Services
