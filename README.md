<h><b>Kube Manifest</b></h>  
This repository is a wip example deployment of [Cardano GovTool](https://github.com/IntersectMBO/govtool) for Mainnet  

Current support covers the main components contained with the [Cardano GovTool repo](https://github.com/IntersectMBO/govtool) i.e. Frontend, Backend and Metadata Validation services, [Governance Outcomes Pillar](https://github.com/IntersectMBO/govtool-outcomes-pillar), [Proposal Discussion Forum](https://gov.tools/proposal_discussion) 

The Images referenced within this repo have been built from forks of the parent repo i.e. [Cardano GovTool](https://github.com/IntersectMBO/govtool),[Governance Outcomes Pillar](https://github.com/IntersectMBO/govtool-outcomes-pillar), [Proposal Discussion Forum](https://gov.tools/proposal_discussion) for any development work this would be the recommended approach as it enables any proposed additions to the parent repos to be tested locally before raising a PR respectively 

This repo has been set-up to allow anyone intereseted to clone and deploy their own version of [GovTool](https://gov.tools) using a local minikube cluster with the primary objective of encouraging community involvement with the project and providing a safe playground where anyone can explore the inner working of the application.

For Instructions on how to get started please refer to the [wiki section](https://github.com/aaboyle878/kube-manifest/wiki)