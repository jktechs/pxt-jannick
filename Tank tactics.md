
Api endpoint | disc | data
--- | --- | ---
player get | gets player data |  (position, health, range?, username/id, position, {score})
settings get | get board settings | (board size, player count)
actions get | get the board history | (list of action objects)
actions post | execute action | (action object)
messages get | get unread messages | (list of messages) (206 if empty)
message post | send message | (message object)

Action:
* move: position, player (authed)
* shoot: player, player (authed)
	* gift
	* damage
	* vote
* join: position player (authed)

Message: player, player (authed)
* decline
* accept
* Allays?
* {} trustworthy?
* My Allays: {}, ...
* kill ({} via {}, ..), ...?
* I kill {} via {},...
* 