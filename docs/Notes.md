# TODO
- do upgrades
- Document models and endpoints
- Set required on required stuff
- Bunch of stuff more complicated because of the possibility of localization
- any other endpoints we'd need to consider?
- consider _my_ use? does this fit?


# Future

## General

- Include "available through" pack/box?
- Include ship arc angles?

## Fleets

- GET / Return a list of all fleets in the system. (bad idea??)
- GET /{fleetId} Return a specific fleet in the system.
- POST /Submit a fleet to the system.
- PATCH /{fleetId} (PUT?) Update a fleet in the system.
- DELETE /{fleetId} Can you prove you own a fleet? Should they be deletable?
- GET /{fleetId}/export Return a human readable fleet text output. 
