# Starship Combat

## Action Economy
Ships can take up to 2 actions per round and 1 Bonus Action.

However, only 1 person can use the Tactical System, and 1 person can use the Helm system. It takes a Move (or a Dash) action to exectute a ship action.

## Protection/Threshold
Protection comes from Shields. As does threshold.

As a ship takes damage its shields will loose Strength for ever extra success that the enemy hits them with over their Protection rating.

| Strength | Effect                                     |
| -------- | ------------------------------------------ |
| 10       | Full strength                              |
| 9        | -1 Protection                              |
| 8        |                                            |
| 7        | -1 Protection                              |
| 6        |                                            |
| 5        | -1 Threshold                               |
| 4        |                                            |
| 3        | -1 Threshold                               |
| 2        | -1 Threshold                               |
| 1        | -1 Threshold                               |
| 0        | SHields down. Protection is 5 no Threshold |

## Ranges
Range is very abstract in space combat. It has 5 range bands.

Close -> Short -> Medium -> Long -> Extended

Close Range is close enough to dock or land smallcraft.

Ships move further or nearer one another with Helm Actions. The GM decides what range ships are at when combat begins.

### Optimal Range
All weapons have an Optimal Range.

Projectile/Energy Weapons have an Optimum Range of Short. They are at disadvantage to hit at Medium and Close Range. These weapons typically cannot damage anything further than medium range.

Missile Weapons and Torpedoes have an Optimum Range of Long. They are at disadvantage to hit at Extended, Medium, and Short range. Missile weapons cannot damage targets at Close range.

## Initiative
The GM declares the range of the engagement and the player rolls 2d6+Ships sensor rating for that range. Highest goes first and then the next and so forth.

## Damage
Damage is predetermined by offensive power. 

If the targets protection is hit, the Threshold is taken away from the damage, and then anything that remains left over is applied to the ships Structure.

Every 5 points of Structure damage causes a Breach. Roll on the Breach Chart and then reduce that systems effectiveness down one and they will suffer the next ranks penalties.

### Breach Chart
| Dice Roll | System       |
| --------- | ------------ |
| 1         | Life Support |
| 2         | Operations   |
| 3-6       | Propulsion   |
| 7-9       | Sensors      |
| 10-15     | No System    |
| 16-17     | Shields      |
| 18-20     | Weapons      |

### System Damage Chart
| System Name  | F               | E          | D               | C                           | B                  | A                             |
| ------------ | --------------- | ---------- | --------------- | --------------------------- | ------------------ | ----------------------------- |
| Sensors      | -1 Helm         | -1 Actions | -1 Actions      | -2 Tactical                 | Lock On Impossible | Offline Ship Blind            |
| Operations   | -1 Computer Use | -1 Command | -1 Computer Use | -1 Actions                  | -2 Actions         | Offline No Cloak/Computer     |
| Life Support | -1 Physical     | -          | -               | Gravity offline -2 Physical | 2d6 stun thin atmo | Offline 2d6 rounds to abandon |
| Propulsion   | -1 Power        | -1 Helm    | -1 Power        | -2 Helm                     | -2 Power           | Offline Core Breach           |
| Weapons      |
| Shields      |

Sensors

## Power
Actions take Power.

Each ship has its power in size. 

## Actions

### Helm
| Name         | Power Cost | Action Cost | TN                | Effect                                                          | Prequisite        |
| ------------ | ---------- | ----------- | ----------------- | --------------------------------------------------------------- | ----------------- |
| Close/Open   | 1+         | 1           | 10                | Change distance by power spent                                  | None              |
| Maneuver     | 0          | 1           | 10                | Change distance by 1 zone                                       | Cannot have moved |
| Come About   | 1          | 1           | 10                | Breaks Lock and add +5 to protection against 1 target           | None              |
| Go to Warp   | 3          | 2           | 10+5 per opponent | If successful the ship jumps to Warp to get away unless pursued | None              |
| Full Stop    | 0          | 1           | None              | Ship stops. Granting +5 to hit but Protection -5                | Cannot have moved |
| Hard About   | 2          | 1           | 15                | Same as come about except you can increase/decrease range by 1  | None              |
| Clear Hazard | 0          | 2           | TN of Hazard      | This will navigate the hazard in the scene such as Asteroids    | None              |

### Tactical
| Name          | Power Cost | Action Cost | TN                          | Effect                                               | Prequisite                                |
| ------------- | ---------- | ----------- | --------------------------- | ---------------------------------------------------- | ----------------------------------------- |
| Fire          | 1          | 1           | Protection                  | Fire weapon at target                                | None                                      |
| Lock On       | 0          | 1           | Protection                  | Grants a +3 to target until broken                   | None                                      |
| Multifire     | 1/taregt   | 2           | Protection +3/Opponent      | Fires at multiple ships                              | All targets must be in same range bracket |
| Multiweapon   | 3          | 2           | Protection +5/weapon system | Make one attack vs TN enemy suffers aggregate damage | Lock On                                   |
| Spread        | 1 per -1   | 2           | Protection                  | Take +3 for -1 dmg up to -3                          | None                                      |
| Target System | 2          | 1           | Protection +10              | Damage a system directly after threshold 1 box per 3 | Lock On                                   |

### Command
| Name          | Power Cost | Action Cost | TN   | Effect                                                                               | Prequisite                      |
| ------------- | ---------- | ----------- | ---- | ------------------------------------------------------------------------------------ | ------------------------------- |
| Rally         | 0          | Bonus       | 10   | Once per scene this can be done it is meant to be used to generate Adversity         | Not been done this scene        |
| Direct        | 0          | Bonus       | None | This is the help action granting Advantage on a roll can only be done once per scene | Has not been done in this scene |
| Self Destruct | 0          | 2           | None | Sets the Auto Destruct sequence must be Captain                                      | None                            |

# NPC Crews

| Crew Quality | Base Modifiers |
| ------------ | -------------- |
| Basic        | +5             |
| Proficient   | +6             |
| Talented     | +7             |
| Exceptional  | +8             |
| Elite        | +9             |