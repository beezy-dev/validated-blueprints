# validated-blueprints

This repository contains all the NetApp validated patterns to populate the NetApp BluePrint plugin for Backstage.io/Red Hat Developer Hub. 

## How to contribute a BluePrint
To submit a pattern, clone this repository and use the ```my-bp-example``` forlder as baseline:  
- ```manifest.yaml``` describing the pattern to populate the NetApp BluePrint plugin catalog, including a stack overviewl, the tooling used for the workflow. 
- the folder ```workflow``` to define the provisioning workflow, in theory, this content should be usable as-is with the chosen automation orchestrator to provisiong the environment.
- the folder ```docs``` to define the workflow's the desired state, purposes, and one or multiple guided use cases. 

Note: at the current stage, the documentation should be written using a single page. 

