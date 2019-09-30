# Incident Response - Lego Service

Participants start all together in one room. There are N teams defined, each with a name and a physical location where 8-10 people can work together. Team names and locations are written on a board for all to see. There is one lego kit for each team, but the kit will be handed out in parts throughout the response phases. Participants are added to the teams in each phase. 

Advance setup: Nine kits labelled by team name. Each kit contains a bucket of parts from the first phase of construction, and unopened bags for remaining phases. The bucket of opened parts needs to contain at least some part(s) that are easy to identify what set it belongs to (for example a minifig or large unique part). 4-5 of the biggest bags are ear-marked to hand out during phase 5. The final numbered bag from each set is randomly moved to another kit.

## Phase 1: Alert
Participant: A person with the lowest company tenure for each team (eg people who joined this year).
Instructions: You are oncall for the legoscale service. You receive an alert for full outage of the lego service. Go to your allocated room and figure out how to restore service. 
Materials: A small bucket of parts and a base plate from one of the sets. Include at least some unique piece that doesn’t exist in other sets. No instructions.
Setup: Rooms/areas allocated for each team. A list of team names and locations in a prominent spot in the briefing room.


## Phase 2: Investigation
Participant: A person from for each team.
Instructions: You are support floor leads from two different regions. You need to read through reports from merchants to figure out what service was affected. All phase 3 participants are given all of the instruction manuals, and given 5 minutes to look through them together in a separate room. You can use your phones but you cannot communicate with the incident team yet. After 5 minutes you return the manuals to the briefing room and then go join your team. If you figure out what service is affected, update the status page to indicate which set your team is building and set the incident status to “identified”.
Materials: Instruction manuals

## Phase 3: Incident
(during 5 minutes when phase 2 people are out of room)
Participant: A person with high company tenture, for each team, with a laptop.
Instructions: You are IMOC. You will join your team and start an incident in spy and on the status page. Create a slack channel and do  `spy incident local`. Use the “Shopify Testing” status page account. There will be a template for the lego service.
Materials: Laptop.
Setup: Create a template for lego service outage on test status page

## Phase 4: Identified
Participant: Someone who works remotely for each team.
Instructions: You are a legoscale team member who maintains the team playbooks. Once your team updates the status page with the set name, take the instruction manual down to the team and join in the response/construction. Make sure the team updates the spy incident when new participants join or when major discoveries are made.
Materials: Instruction manuals
Setup: One organizer needs to watch the status page and dispatch legoscale team members once their set is identified.

## Phase 5: Part allocation
Participant: Two people based in different company offices, with a laptop.
Instructions: You are from the partscale team, which provides underlying resources for the legoscale service. One of you will stay in this room, and the other will go to the incident room for your team. Between you, your job is to figure out what resources belong to your team and provision them to your team.

For every other participant: You are a resource needed by the lego service. Each participant gets one parts bag. You will join the team that is building the service that bag belongs to. Talk to the partscale oncalls around the room and figure out what team to join. Once you figure that out, go join your team and work on restoring service.

Once all parts are identified, partscale oncall people also join their team and work on restoring service.

Materials: All remaining parts bags.

## Phase 6: Cluster balancing
Bad news! Some of the resources were mislabeled and applied to the wrong cluster. One parts bag in each box is in the wrong set. One person from each team should return to the briefing room with that bag and swap with others to make sure they have the right bag.

## Phase 7: Fixing
All teams work to restore service for their service (build their lego kit). Once complete, mark the status page resolved and end the spy incident. Create a draft service disruption but do NOT publish it.
