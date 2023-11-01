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


# NEW SPRINT (Change SP & Anoother things)
## [Backend] CC | FOTA Deployment | Enhance Check Active Deployment (8)
Detail:
- craete query db only check active deployment with specific fleet type
- update condition on deployment iteration when evaluate deployment

## [Backend] COTA Configuration | Config by pool | Create Deployment (4)
Detail:
- Handle API Create Cota deployment with Target Type pool

## [Backend] | Config By Pool | Handle Request COTA from IOT (4)
Detail:
- Handle Request COTA from IoT
- Can handle pool request

## [Backend] CC | Configuration | Create Configuration | targeted by pool | handle notification (8)
Detail:
- While activated COTA will notify with specific pool from devices

## [Backend] FOTA | Deployment | add target type Pool | Handle Evaluate Deployment (8)
Detail:
- [Backend] FOTA | Deployment | add target type Pool | Handle Evaluate Deployment

## [Backend] IOT Track forwarder | one vehicle multiple token | handle sync database 
Detail:
- concatenate multiple token with separator
- remove other duplicate vehicle

## [Backend] IOT Track forwarder | one vehicle multiple token | handle telemetry send to trackingbird
Detail:
- before send tracking, split token with define separator
- if length from split token grether than 1, looping send telemetry with different token
