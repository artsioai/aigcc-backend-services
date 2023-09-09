# aigcc-backend-services

This document describe high level of relationships and guideline of AIGCC micro-services.

**Golden Rules** : A service must only make REST calls to peer services or lower-tier services.


## Tier 3 - Application
- aigcc-app-service

## Tier 2 - Commonware
- aigcc-asset-service
- aigcc-llmindex-service
- aigcc-artgen-service

## Tier 1 - Data & Platform
- aigcc-platform-service
