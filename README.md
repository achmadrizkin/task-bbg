# TASK BBG

### Handle Teltonika device type on integration parser (5)
Detail
- add new field on struct and db deviceInfo
- Handle incoming pubsub from cc api
- Create new endpoint RESTAPI for get list device
- add new field “deviceType” on inventory.proto
- Added and fixed bug in SyncDevice proto

## Add FMC650 to device type (3)
Detail:
- Task on sync manual device integration parser:
- add device type teltonika fmc650
- update query db
- add new field “deviceType” on inventory.proto

### Added ads configuration (8)
Detail:
- Make new configuration for Aqua Ads
- User Acceptance Criteria
- Given Configuration page 
- When click create configuration 
- Then show create configuration page 
- Then show Aqua ads configuration 
- When click the toggle button 

### Create Rest Api Tracking Forwarder (?)
Detail:
- Create Rest api for create, read, update, delete, device token thingsboard on service tracking forwarder,
auth using bbone

### [Backend] Tracking Forwarder | Sync token from Trackingbird (5)
Detail:
- Get token from trackingbird and store to trackingforwarder
- Need to synchronize data from database trackingbird to internal Redis and PostgreSQL

### [Backend] CC | Refactor FOTA Deployment | Detail (5)
Detail:
- Optimize/refactor the FOTA Deployment page to enhance the Detail feature's efficiency

### [Backend] CC | Device Monitor | Reboot IoT while not activated (5)
