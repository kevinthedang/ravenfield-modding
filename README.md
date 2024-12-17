<div align="center">
  <h1>Ravenfield Modding Learning</h1>
</div>

[Ravenfield](https://ravenfieldgame.com/) is a singleplayer team-on-team AI shooter game.

### Requirements for Modding
* [Blender](https://www.blender.org/) for 3D Modeling
* [Unity](https://unity.com/)
* The Ravenfield Modding Tools
* Lua/Ravenscript for creating [Mutators](https://ravenfield.fandom.com/wiki/Mutators_(Vanilla))

### Guides
* [Weapon Modding 101](https://steamcommunity.com/sharedfiles/filedetails/?id=1300559352) and [Mellamo's Weapon Modding Guide](https://steamcommunity.com/sharedfiles/filedetails/?id=2068973497)
* [Krev's Skinmaking](https://steamcommunity.com/sharedfiles/filedetails/?id=2769041707) and [The Art of Creating Skins](https://steamcommunity.com/sharedfiles/filedetails/?id=2353562345&searchtext=skin)
* [Tank Vehicle Modding](https://steamcommunity.com/sharedfiles/filedetails/?id=1596471450)

### Game Mechanics
* [Infantry](https://steamcommunity.com/sharedfiles/filedetails/?id=1300559352)
* [Weapons](https://ravenfield.fandom.com/wiki/Category:Weapons)
* [Vehicles](https://ravenfield.fandom.com/wiki/Category:Vehicles)
* [Game Modes](https://ravenfield.fandom.com/wiki/Category:Game_Modes)
* [Maps](https://ravenfield.fandom.com/wiki/Category:Maps) and the [Map Editor](https://ravenfield.fandom.com/wiki/Map_editor)

Here are some things that can probably be modded in Ravenfield:
### Weapons
| Name              | Weapon Class   | Weapon Slot  | Type                                | Introduced |
|-------------------|----------------|--------------|-------------------------------------|------------|
| Rk-44             | Assault        | Primary      | Assault Rifle                       | Beta 1     |
| Greaser           | Assault        | Primary      | SMG                                 | EA 4       |
| Signal DMR        | Assault        | Primary      | Battle Rifle                        | Beta 3     |
| Quicksilver       | Assault        | Primary      | Suppressed SMG                      | EA 1       |
| Patriot           | Assault        | Primary      | Assault Rifle                       | EA 1       |
| Patriot GL        | Assault        | Primary      | Assault Rifle /w Attachment         | EA 13      |
| Patriot TAC       | Assault        | Primary      | Suppressed Assault Rifle            | EA 21      |
| SL-Defender       | Marksman       | Primary      | Sniper Rifle                        | Beta 1     |
| Recon LRR         | Marksman       | Primary      | Long Rangle Battle Rifle            | Beta 4     |
| M1 Garrett        | Marksman       | Primary      | Battle Rifle                        | EA 5       |
| 76 Eagle          | Close-Quarters | Primary      | Pump-Action Shotgun                 | Beta 1     |
| Automatico-Akimbo | Close-Quarters | Primary      | Dual Machine Pistols                | EA 4       |
| HMG               | Support        | Primary      | Portable Mounted MG (Joke)          | EA 1       |
| S-IND7            | Handgun        | Secondary    | Pistol                              | Beta 1     |
| S-IND7 (SUP)      | Handgun        | Secondary    | Suppressed Pistol                   | Beta 1     |
| .357 Condor       | Handgun        | Secondary    | Revolver                            | EA 1       |
| Blundle O' Buss   | Handgun        | Secondary    | Single-Use Blunderbusses            | EA 5       |
| AA-AA             | PDW            | Secondary    | Anti-Air Flak Machine Pistol (Joke) | EA 4       |
| Automatico        | PDW            | Secondary    | Machine Pistol                      | EA 4       |
| Dagger            | Anti-Armor     | Slot Utility | Infantry Rocket Launcher            | Beta 1     |
| Slam-R            | Anti-Armor     | Slot Utility | Recoilless Rifle                    | EA 1       |
| Scalpel           | Anti-Armor     | Slot Utility | Lock-on Missile Launcher            | Beta 2     |
| Railgun           | Anti-Armor     | Slot Utility | Electromagnetic Launcher            | EA 8       |
| Hydra             | Anti-Armor     | Slot Utility | Lock-on Cluster Missile Launcher    | EA 1       |
| Frag              | Grenade        | Slot Utility | Fragmentation Grenade               | Beta 1     |
| Spearhead         | Grenade        | Slot Utility | Stun Grenade                        | Beta 1     |
| Smoke Grenade     | Grenade        | Slot Utility | Smoke Grenade                       | EA 13      |
| C4                | Grenade        | Slot Utility | Remote-Detonated Explosives         | EA 23      |
| Thumper           | Grenade        | Slot Utility | Grenade Launcher                    | EA 13      |
| Wrench            | Equipment      | Slot Utility | Repair Tool                         | Beta 5     |
| Sabre             | Equipment      | Slot Utility | Cavalry Sabre                       | EA 5       |
| Squad Leader Kit  | Equipment      | Slot Utility | Support Tool                        | EA 1       |
| Resistance Sword  | Equipment      | Slot Utility | Longsword                           | EA 17      |
| Ammo Bag          | Equipment      | Slot Utility | Deployable AOE Support Tool         | Beta 1     |
| Medic Bag         | Equipment      | Slot Utility | Deployable AOE Support Tool         | Beta 1     |
| Airhorn           | Equipment      | Slot Utility | Sonic Weapon                        | EA 1       |

### Vehicles
| Name                           | Vehicle Type | Appearance  | Armor Type | Vehicle Description                  | Re-skinned |
|--------------------------------|--------------|-------------|------------|--------------------------------------|------------|
| Razorback Jeep                 | Car          | Beta 1      | Medium     | Light Utility Transport              | EA 16      |
| Razorback MG                   | Car          | Beta 6/EA 1 | Medium     | Armed Light Transport                | EA 16      |
| Prowler Quadbike               | Car          | Beta 4      | Light      | ATV                                  | EA 15      |
| Rhino Tank                     | Car          | Beta 3      | Heavy      | Tank                                 | EA 15      |
| Mudskipper APC                 | Car          | EA 14       | Heavy      | Amphibious Armoured Personal Carrier | Not Yet    |
| Raptor Helicopter              | Helicopter   | Beta 1      | Medium     | Attack Helicopter                    | EA 25      |
| Blackbird Transport Helicopter | Helicopter   | EA 9        | Medium     | Transport Helicopter                 | EA 22      |
| Buzzard                        | Plane        | Beta 6/EA 1 | Light      | Light Fighter/Attack Plane           | EA 24      |
| Cassowary Bomber               | Plane        | EA 2        | Medium     | Medium Bomber Plane                  | EA 24      |
| Marlin RHIB                    | Boat         | Beta 1      | Light      | RHIB                                 | EA 18      |
| Attack Boat                    | Boat         | Beta 6/EA 1 | Heavy      | Fast Attack Craft/Patrol Boat        | Not Yet    |

