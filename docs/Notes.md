## Draft Documentation Goals
- To start discussion with other Armada developers on what a common API might look like.

## API Goals
- To accelerate the creation of innovative apps based on the Star Wars Armada tabletop board game, so that the community can grow together.
- To increase the concentration of static data maintainers in order to attempt to get all apps updated sooner.
- To standardize inputs and outputs to reduce maintenance headache for importing or exporting apps.

## Open Questions
- Currently API is being designed to account for localization. Should it? Or should the individual app maintainers be responsible for that?


## TODO
- write up on design principles around XId vs X vs PrintedX
- do upgrades
- Document models and endpoints
- Set required on required stuff
- any other endpoints we'd need to consider?
- consider _my_ use? does this fit?


## Future

# General

- Include "available through" pack/box?
- Include ship arc angles?

# Fleets

- GET / Return a list of all fleets in the system. (bad idea??)
- GET /{fleetId} Return a specific fleet in the system.
- POST /Submit a fleet to the system.
- PATCH /{fleetId} (PUT?) Update a fleet in the system.
- DELETE /{fleetId} Can you prove you own a fleet? Should they be deletable?
- GET /{fleetId}/export Return a human readable fleet text output. 
