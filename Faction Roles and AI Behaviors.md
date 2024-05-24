**
Sight: range at which they can ‘see’ enemies
- Scale 1-5, 1-7? Would translate to size of the circle around the unit in Unreal
- Is there camouflage?  Yes, but contextual (if you’re in the bushes it works).  Levels of camo: BDUs, ghillie suit, winter camo vs. jungle camo vs night.
- Can certain units ‘pierce’ camo?
- Buffs via gear: binoculars, night vision, scopes to pierce camouflage

Sound - range/volume they can detect
- Scale sameish as sight scale
- Would need sound emitted by the unit to overlap the hearing range of the detector.  Is there a more nuanced approach?  What if we treat sound emission as a buff/debuff to sound detection based on unit (tribesman reduces hearing range) and encumbrance (more gear boosts detection range)?
- More gear you wear, more sound you emit?  Faster you move, more you emit.
- Can be affected by weather?  Rain or wind lowers effective hearing range?
- Buffs via gear: headphones, drone radar, listening posts, etc.

That “scent” or other sense that could affect range impact of spore or other?  Maybe this is just more an AOE factor of the spore vs. a sense of the character?

<ins>Potential Stats to Consider:</ins>
- Health: Need to know when damage is lethal, how much to heal.
- Strength: Carry capacity, how far can run, how encumbrance impacts speed, noise.
- Stamina: How far you can move at speed
- Accuracy: NPCs have this stat, not players.  All weapons have MoA.  Do we have weapon sway?  Effected by Stamina?
- Aggression/Motivation/Morale: Affects response to debuffs, losing commander, wounds.  This might be better handled as a state management system rather than stat
- ~~Charisma/Wisdom:  Make this skill based.
- ~~Speed: Do we need this?  Or would Strength and Stamina suffice.  Start without and try from there.
- Spore-related sense develops over game?  6th sense/spidey sense?  Predator-like blur or color indicator or sound signal that is directional to indicate what you’re picking up on?

<ins>Other discussion points:</ins>
Does each faction use the spores differently?  

Named units?  Commanders, NPCs with special abilities or impact.

Morale/Demoralize impact based on commander death or total amount of damage taken in period of time.  Do they run around direction-less?  Do they flee?  Do they hide?

Do any of these capabilities/factors below suggest any other Skill implications?  Like, if we have traps or trip wires do we need a skill for spotting or disarming traps?

I like the idea that enemy ‘commanders’ have some sort of remote support Skill that isn’t just about shooting: mortar, jamming comms, calling medevac, whatever.

Sound effects when hitting a headshot, or visual feedback

<ins>Faction Roles and AI Behaviors </ins>

**Indigenous Forces:  

Their goal is to defend their land and keep the world-changing benefits of the spores out of the hands of outsiders.  Proposed capabilities of this faction are they fight like indigenous guerillas; they know the lands and have tunnel systems (think Vietcong?); they strike/ambush and disappear; they plant traps; they use the spores to alter battles.  Most humanitarian version of spore use?    

Tribesman:  Sneaky,uses cover, tunnels, terrain and camo to flank or ambush (Camo would be based on texture on the model, at longer range use a nearly invisible texture - think predator).   Traps or trip wires like Zero Hour.  Shotgun.  High detect range, very low emission range, very high camouflage, high speed, low strength, high endurance, very low accuracy.  

Archer:  Hit and hide attacks, WWII or AK-like primitive firearm.  Kill from range or draw enemy closer to Tribesman traps/ambush.  Low to avg accuracy, higher detect range, avg endurance, high camo, very low emission.  If the player breaks their desired range, they would move away.

Shaman (Most named units for this faction):  Use spores to debuff enemy … spore nades or traps that slow, blur vision, lower sight and sound detection (kind of a stun effect?).  Can use spores to heal units.   Very high detect, very low emission, avg speed, high camo.  Killing Shaman buffs team aggression/motivation but debuffs detect/emission benefits.  Those within range of the shaman dying would exhibit the change of behavior, but when those units approach their friendlies, the friendlies would pickup that behavior.
  
**Chynastan:  

Their goal is to master the more effective mind altering potential of the spores to ensure the “cooperative and productive” life of all people, which is either world peace or slavery.  For gameplay this faction might feel most like zombies or like vermintide or deep rock.  When it comes to capabilities, their equipment is basic but plentiful regarding weapons, food, ammo, ground transport.  They have limited medical capabilities out of philosophy and because people are an unlimited resource.  They have limited tech and weak tech security.  

Trooper:  Run and gun.  The storm trooper, avg to below avg stats, poor aim, but high number of units.  SMGs and AKs.

Sapper:  Blitz charges with explosives.  Also has pistol or knife for after.   Low stats per but decent number of units (less than troopers).  

Commander:  Main role is to coordinate troops, can call in limited mortar strikes (of poor accuracy), can we have a whistle sound that the strike is inbound and approx where it will land?  Barrage of mortar strikes that increase in damage.  Decent rifle as well.  Avg to above avg stats.  Killing commanders seriously debuffs unit aggression/motivation or causes chaotic behavior.  

Maybe one dynamic is they get more zombie-like (higher motivation, more coordinated charges) as Chynastan develops spores (do the eventually wear masks to sniff spores full time?).

**United Alliance:  

The goal is to ensure whatever this resource is, it belongs to the duly elected leaders of the West and not the zealots of the region or soulless corporate pirates.  Plus, after watching the Iran Contra thing and seeing how hopeless the War on Drugs is, the UA commander ain’t exactly blind to opportunity for a little spore distribution scheme on the side.  From a gameplay perspective, the capabilities of this faction include very small, but heavily armed and armored A-teams.  They have the best weapons and strong troops.  They also have the best transport assets, including choppers for quick deployments and extractions.  

Sensing ranges are lower, emission range is higher due to gear.  They have the best unit tactics (use of cover, covering each other) and can heal self (though takes time and cannot fight during).

Rifleman:  M16ish with optics.  Consistent use of cover, will not stay in one spot too long.  Avg to high stats, maybe higher accuracy or less kick.  Self-heal kit.

Gunner:  M249-ish.  Good use of cover but will mount and stay unless enemy moves from LOS.  Avg to high stats, though stronger and slower than Rifleman.

Captain:  High stats.  Can heal self and team.  SMG, med kit.  Stays near team, uses his higher detect stat to direct team awareness/fire.  Dropping captain will cause team to try to get to him to heal or recover body and then tactically retreat (still fighting but trying to exfil).  Can call in chopper for exfil or 1-2 reinforcements?

**HumaniCo:  

Bates’ goal is to secure the intellectual property behind the spores – via friendly licensing with the locals or sabotage or force – to monopolize and monetize the multibillion dollar medical potential.  For gameplay, this faction’s capabilities feature heavily armored mini-tanks for strong defense and remotely controlled RC helicopters for recon and air strikes.  But, it’s the 80s, so these are not AI; they all require a commander in near proximity to control them, who are vulnerable if you can spot them.  They also have elite hackers and tech to disrupt the communication and electronics of foes.  This faction has the most advanced comms and tech security.  Their assets are expert, small in number, but very expensive.  

Drone Scout RC helicopter or johnny 5 track bot: (scans area for target location, onboard gun similar to recon/sniper?)  Very high sight and sound detection, high speed.  High sight and sound emission.  Fragile.  Highly susceptible to chaff ECM, if that’s even a thing.  Could they have a tracking round that tags the player for the bomber to strike?  The tag would do DoT (chemical marker), player needs to do something to remove it and the chemical (would need medic skill or some item that the players need to acquire through mission or market).

Drone Bomber (basically grenades from the sky, but very limited?)  High sight and sound detection.  High sight and sound emission.  Avg speed but flies at higher altitude.  Better armor than Scout.  Uses the tags from the scout to find targets, without a tag they hover in a space and wait for players to enter their detect range.  Highly susceptible to chaff ECM.

Hacker/Controller.  Pistol for self-defense.  One controller for every 3 or 4 drones?  Usually operating from a hardened position or vehicle, but has to be within range of drones so has to use whatever cover is available.  Focuses on drone control, but will defend him/herself when attacked.  Drones have a limited range and if they are at max range from the controller they would stop and hover.  Can debuff enemy comms/electronics to affect coordination, air/arty support, etc.  If controller taken out, drones default to autopilot and return to their launch platform?   Do they patrol?  Kamikazee?  Spores improve the controllers ability to control more drones increasing bot density on the battlefield.

**