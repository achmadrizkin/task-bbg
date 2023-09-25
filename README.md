# TASK BBG

## SPRINT 1
### Handle Teltonika device type on integration parser (5)
Detail
- add new field on struct and db deviceInfo
- Handle incoming pubsub from cc api
- Create new endpoint RESTAPI for get list device
- add new field “deviceType” on inventory.proto
- Added and fixed bug in SyncDevice proto

## Add FMC650 to device type (3)
Detail
- Task on sync manual device integration parser:
- add device type teltonika fmc650
- update query db
- add new field “deviceType” on inventory.proto

## SPRINT 2 - BIOT SPRINT 74 (9/5/2023)
### Added ads configuration (8)

## SPRINT 3 - 
### [Backend] Tracking Forwarder | Sync token from Trackingbird (5)
Detail:
- Get token from trackingbird and store to trackingforwarder
- Need to synchronize data from database trackingbird to internal Redis and PostgreSQL

### [Backend] CC | Refactor FOTA Deployment | Detail (5)
Detail:
- Optimize/refactor the FOTA Deployment page to enhance the Detail feature's efficiency
