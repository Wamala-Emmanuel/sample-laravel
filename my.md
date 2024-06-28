# Azure Infrastructure Guide Checklist #
## Network ##
- [x] Firewall Rules
    - [X] Application subnet access to resevior
    - [x] Application subnet access to API Connect
    - [x] Application subnet access to mail server (Implemented by Default)
    - [x] Application Azure Postgresql subnet access to .41 jumpbox (For running queries on the private database)
- [x] Application webapp should access Storage Connector webapp using DNS name
## Infrastructure ##
- [x] Submit application domain name to Angelo to attach to the Azure Application LoadBalancer (optional)

## SSL ##
- [x] Submit application domain name to Angelo to create and attach SSL

## DNS ##
- [x] Map DNS


#  Deployment Guide Checklist #
- [x] 
