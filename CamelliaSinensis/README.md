# CamillaSinensis

## Production methods

- Green tea 
	- Pick fresh leaves, steam them, leave to dry.
- Brick tea
	- Pick fresh leaves, steam them, pulverize into paste, set in mold, leave to dry.
- Black tea
	- Pick fresh leaves, sun dry (wither), then smoke over wood fire.
- Yellow tea 
	- Pick fresh leaves, steam them, seal in a container, leave to dry.
- Pu'er tea 
	- Pick fresh leaves, steam them, leave to dry, wrap up for aging.

## Some dev notes

- Drying: Use transitional state, model on toolheads/bowstaves
- Fermenting: see drying.
- Steaming: ... will just be cooking, but we'll add a steamer
- Brewing: will also just be cooking.
- Tea leaf items will need to be made for all intermediate stages of production
	- A sort of decision tree follows

- Picked: useless
	- Sun dry: useless
		- Smoke: Black tea
	- Steam them: useless
		- Allow to dry: green tea
			- Wrap up for aging: becomes pu'er.
		- Seal in a container: Becomes yellow tea
		- Crush: macha
			- Set in mold: becomes tea brick.
## Roadmap

✔×

### 0.1 ✔

- Art assets created.

### 0.2 ✔

- Tea plants in game.
- Tea plants spawn in nature.

### 0.3 ×

- Tea related items added to the game.

### 0.4 ×

- Tea-related
- Tea brewing and processing mechanics added.

### 0.5 ×

- Tea items added to loot tables for ruins etc.
- Connects with Better Ruins.

### 0.6 ×

- Teaware clay recipes added.

### 0.7 ×

- Tea buffs working.

### 0.8 ×

- Connects with X-Skills.

### 0.9 ×

- Tea pets, with C# logic to pour tea over them.

### 1.0 ×

- Refactors, bug fixes, improvements from 0.9 based on user feedback.