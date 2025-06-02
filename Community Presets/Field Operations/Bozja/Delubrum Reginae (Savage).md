# 🔴 Delubrum Reginae *(Savage)*
## 🟠 Trinity Seeker
### Merciful Fourfold (Blades of Mercy) | Seasons of Mercy (growing aoe + gaze) | Baleful Firestorm (Dashes)
* Merciful Fourfold is deactivated by default until I find a way to have better timing
```
~Lv2~{"Name":"Trinity Seeker","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"ElementsL":[{"Name":"Forward Right","type":3,"Enabled":false,"refY":19.96,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":0.7853982,"refActorVFXPath":"vfx/common/eff/m0690_stlp_fr_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Forward Left","type":3,"Enabled":false,"refY":19.96,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":5.497787,"refActorVFXPath":"vfx/common/eff/m0690_stlp_fl_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Back Right","type":3,"Enabled":false,"refY":19.92,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":2.3561945,"refActorVFXPath":"vfx/common/eff/m0690_stlp_br_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Back Left","type":3,"Enabled":false,"refY":19.92,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.9269907,"refActorVFXPath":"vfx/common/eff/m0690_stlp_bl_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Merciful Blooms","type":1,"radius":20.0,"color":1677721855,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[23242],"refActorCastTimeMin":4.0,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorComparisonType":3,"onlyUnTargetable":true,"Filled":true},{"Name":"Gaze","type":1,"radius":0.44,"color":3355507455,"overlayFScale":3.0,"thicc":3.0,"overlayText":"Look Away","refActorDataID":12599,"refActorObjectLife":true,"refActorLifetimeMin":0.0,"refActorLifetimeMax":7.0,"refActorComparisonType":3,"includeRotation":true,"onlyVisible":true,"tether":true},{"Name":"Baleful Firestorm","type":3,"refY":50.0,"radius":10.0,"color":1258291455,"refActorNPCNameID":9835,"refActorRequireCast":true,"refActorCastId":[23256],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"onlyVisible":true}]}
```
### Baleful Blade (Hide behind Barricades)
```
~Lv2~{"Name":"Trinity Seeker - Baleful Blade Hide","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"DCond":5,"ElementsL":[{"Name":"Baleful Blade Hide","refY":278.0,"refZ":8.000001,"radius":20.0,"color":1677721855,"overlayVOffset":0.5,"overlayFScale":2.0,"overlayText":"Behind Barricades","refActorNPCNameID":9834,"refActorRequireCast":true,"refActorCastId":[23230],"refActorComparisonType":6,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Baleful Blade Hide South","type":5,"refY":278.0,"refZ":8.0,"radius":25.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677721855,"thicc":4.0,"includeRotation":true,"Filled":true},{"Name":"Baleful Blade Hide West","type":5,"refY":278.0,"refZ":8.0,"radius":25.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677721855,"thicc":4.0,"includeRotation":true,"AdditionalRotation":1.5707964,"Filled":true},{"Name":"Baleful Blade Hide North","type":5,"refY":278.0,"refZ":8.0,"radius":25.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677721855,"thicc":4.0,"includeRotation":true,"AdditionalRotation":3.1415927,"Filled":true},{"Name":"Baleful Blade Hide East","type":5,"refY":278.0,"refZ":8.0,"radius":25.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677721855,"thicc":4.0,"includeRotation":true,"AdditionalRotation":4.712389,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"MatchIntl":{"En":"Trinity Seeker starts casting 23230 (9834>23230)"}}]}
```
### Baleful Blade (Knockback into Barricades)
```
~Lv2~{"Name":"Trinity Seeker - Baleful Blade Knockback","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"DCond":5,"ElementsL":[{"Name":"Baleful Blade Knockback","refY":278.0,"refZ":8.000001,"radius":0.0,"color":1677786880,"overlayVOffset":0.5,"overlayFScale":2.0,"thicc":0.0,"overlayText":"In front of Barricades","refActorNPCNameID":9834,"refActorRequireCast":true,"refActorCastId":[23230],"refActorComparisonType":6,"onlyTargetable":true,"onlyVisible":true},{"Name":"Baleful Blade Knockback SW","type":5,"refY":278.0,"refZ":8.0,"radius":20.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677786880,"thicc":4.0,"includeRotation":true,"AdditionalRotation":0.7853982,"Filled":true},{"Name":"Baleful Blade Knockback NW","type":5,"refY":278.0,"refZ":8.0,"radius":20.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677786880,"thicc":4.0,"includeRotation":true,"AdditionalRotation":2.3561945,"Filled":true},{"Name":"Baleful Blade Knockback NE","type":5,"refY":278.0,"refZ":8.0,"radius":20.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677786880,"thicc":4.0,"includeRotation":true,"AdditionalRotation":3.9269907,"Filled":true},{"Name":"Baleful Blade Knockback SE","type":5,"refY":278.0,"refZ":8.0,"radius":20.0,"coneAngleMin":-22,"coneAngleMax":22,"color":1677786880,"thicc":4.0,"includeRotation":true,"AdditionalRotation":5.497787,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"MatchIntl":{"En":"Trinity Seeker starts casting 23231 (9834>23231)"}}]}
```
### Baleful Onslaught (Tankbuster Cone)
```
Placeholder
```
### Baleful Swathe (Side Swipes)
```
Placeholder
```
### Act of Mercy (Cross Shape)
```
Placeholder
```
**To do**
```diff
! Side Swipes, Tankbuster cone and Cross shape
! Iron Splitter (Sand & Tiles) : No way to diffrerentiate using base Splatoon, it would need a script that calculate distance of boss + Avatar castin Iron Splitter from the Center of Arena
! Timing on Blades of Mercy : Resolution have faster cast time than the readyness so it resolve faster than the layout have time to disappear or appear
! Dead Iron (Earthshaker) : find a way to make cones from boss to people with specific VFX on them
! Burning Chains : do I need to explain with a text over your character ?
! Merciful Arc : Tankbuster cleave but not the same as Baleful Onslaught ? Cast Once before first Baleful Swathe
```
***
## 🟠 DUEL - Stygimoloch Warrior
### Surge of Vigor (Dispel) | Unrelenting Charge (Anti Knockback) | Vicious Swipe (Out/In) | The 4 Traps to use | Sun's Ire (Enrage)
```
~Lv2~{"Name":"Duel - Stygimoloch Warrior","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"ElementsL":[{"Name":"Surge of Vigor","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"DISPEL THE BUFF","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22422],"refActorUseCastTime":true,"refActorCastTimeMax":5.0,"refActorUseOvercast":true,"refActorComparisonType":6,"onlyVisible":true},{"Name":"Unrelenting Charge","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"USE ARMS LENGTH/SURECAST","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22425,22426],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Vicious Swipe","type":1,"radius":0.04,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"OUT THEN IN FOR KNOCKBACK","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22423],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Withering Curse","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"USE MINI TRAP (Pink)","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22405,22406],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Surging Flames","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"USE FROST TRAP (Blue)","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22401,22402],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Surging Flood","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"USE FROG TRAP (Green)","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22403,22404],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Leaping Spark","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":1.5,"thicc":0.0,"overlayText":"USE FROG TRAP AGAIN","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22410,22411],"refActorComparisonType":6,"onlyVisible":true},{"Name":"Sun's Ire (Enrage)","type":1,"radius":0.0,"overlayVOffset":1.0,"overlayFScale":2.0,"thicc":0.0,"overlayText":"KILL HIMMMMMM (ENRAGE)","refActorNPCNameID":9754,"refActorRequireCast":true,"refActorCastId":[22394,22395,22446],"refActorComparisonType":6,"onlyVisible":true}]}
```
**To do**
```diff
! Instructions Pre Duel
```
***
## ${\sf \color{orange}Dahu}$
### Firebreathe | Hot Charge | Feral Howl
```
~Lv2~{"Name":"Dahu","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"ElementsL":[{"Name":"Firebreathe","type":4,"radius":36.25,"coneAngleMin":-45,"coneAngleMax":45,"refActorDataID":12456,"refActorRequireCast":true,"refActorCastId":[22380],"refActorUseCastTime":true,"refActorCastTimeMax":4.5,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"Filled":true},{"Name":"Charge","type":3,"refY":59.24,"radius":4.0,"thicc":0.0,"refActorDataID":12456,"refActorRequireCast":true,"refActorCastId":[22387],"FillStep":1.0,"refActorComparisonType":3,"includeRotation":true,"LimitDistanceInvert":true,"DistanceMin":17.300001,"DistanceMax":90.799995},{"Name":"Feral Howl","type":3,"offY":40.0,"radius":0.0,"thicc":10.0,"refActorNPCNameID":9751,"refActorRequireCast":true,"refActorCastId":[22375],"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"FaceMe":true}]}
```
**To do**
```diff
! Spit Flame : Maybe this will need a script to tether to the Waymark you need to go to
```
***
## 🟠 Queen's Guard
### Shield & Sword Omen (Knight) | Secrets Revealed (Soldier)
* Shield & Sword Omen is 1/4th done
```

```
**To do**
```diff
! Spellforge/SteelSting + Dispel Warrior: text + AOE Circle under them with same color as needed buff
! Optimal Offensive: Shield Omen (Knockback) + Sword Omen (Big Circle AOE) : Aetherial Sphere in center with a charge towards it (Need to make a Line preset so people don't stay in the charge and take a Doom Stack)
! Optimal Play : Shield Omen (Donut) + Sword Omen (Circle) : Need to find a way to target the Blades VFX for a Cone Aoe combined with the Shield or Sword
! Bombslinger & Above Board: Big Bombs drop before small bombs and Players drop like small bombs normally
! Reversal of Forces : Tethered players and/or Bombs will drop first
! Winds of Weight : 2 Wind and 2 Lightning AOE appear : Tethered players need to go wind, not tethered go to Lightning
! Reading + Queen's Shot : Gets an Unseen buff with a 1 open side vfx on you, face Queen's Gunner with open side before Queen's Shot is cast then to the turret on the side of the arena
! Gun Turret : Adds that need to be killed or wipe
! Higher Power : Dispel damage buff in Gun Turrets
! Great Ball of Fire : Summon 4 Fireballs (2 small and 2 big), Draw size of aoe depending on the size of the ball
! Icy/Fiery Portent: Move/Stop Moving when cast : Text
! Double Gambit + Secrets Revealed : Already Works I think
! Aura Sphere casting Fracture : AOE circle with Text for Healer Reflect
! Coat of Arms : maybe see if the spell is different for sides and Front/back so I can put Cones for best angle
```
***
## ${\sf \color{orange}Bozjan \space Phantom}$
### Cube Shape
```

```
**To do**
```diff
! Follow the Raid leader orders
```
***
## 🟠 Trinity Avowed
### Allegiant Arsenal (Staff-Sword-Bow) | Gleaming Arrow
```
~Lv2~{"Name":"Trinity Avowed","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"ElementsL":[{"Name":"Allegiant Arsenal Staff","type":1,"radius":10.0,"color":1677721855,"refActorDataID":12508,"refActorRequireCast":true,"refActorCastId":[22919],"refActorCastTimeMax":60.0,"refActorUseOvercast":true,"refActorComparisonType":3,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Allegiant Arsenal Bow","type":4,"radius":35.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorDataID":12508,"refActorRequireCast":true,"refActorCastId":[22918],"refActorCastTimeMax":30.0,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Allegiant Arsenal Sword & Shield","type":4,"radius":35.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorDataID":12508,"refActorRequireCast":true,"refActorCastId":[22917],"refActorCastTimeMax":30.0,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.1415927,"Filled":true},{"Name":"Gleaming Arrow","type":3,"refY":50.0,"radius":5.0,"thicc":0.1,"refActorNPCNameID":9854,"refActorRequireCast":true,"refActorCastId":[22861],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"onlyVisible":true}]}
```
**To do**
```diff
! Freedom of Bozja : Ice and Fire 1&2 Meteor safe spots (And with the Brand)
! Arrow solver : May need a script to solve it (maybe ask Bossmod Dev if he could help us)
! Blades of Entropy solver : I think this may end up as a gigantic preset with how many combination there is
! Wrath of Bozja : Cone Aoe
```
***
## 🟠 Stygimoloch Lord
### Ball of Earth/Fire (Healers) | Devastating Bolt Inner & Outer Rings | 1111-Tonze Swing
```
~Lv2~{"Name":"Stygimoloch Lord","Group":"Delubrum Reginae Savage","ZoneLockH":[937],"ElementsL":[{"Name":"Devastating Bolt Inner","type":1,"radius":12.0,"Donut":5.0,"refActorNPCNameID":9759,"refActorRequireCast":true,"refActorCastId":[22470],"FillStep":0.2,"refActorComparisonType":6},{"Name":"Devastating Bolt Outer","type":1,"radius":25.0,"Donut":5.0,"refActorNPCNameID":9759,"refActorRequireCast":true,"refActorCastId":[22470],"FillStep":0.2,"refActorComparisonType":6},{"Name":"Ball of Earth","type":1,"radius":0.0,"color":255,"overlayVOffset":1.0,"overlayFScale":1.5,"overlayText":"Dispel then hit","refActorNPCNameID":9763,"refActorComparisonType":6},{"Name":"Ball of Fire","type":1,"radius":6.0,"color":1677721855,"overlayVOffset":1.0,"overlayFScale":1.5,"overlayText":"Reflect","refActorNPCNameID":9761,"refActorRequireCast":true,"refActorCastId":[22494],"refActorComparisonType":6,"Filled":true},{"Name":"1111-tonze-swing","type":1,"radius":20.0,"color":1677721855,"refActorNPCNameID":9759,"refActorRequireCast":true,"refActorCastId":[22488],"refActorComparisonType":6,"Filled":true},{"Name":"WIP Crushing Hoof","type":1,"Enabled":false,"radius":25.0,"color":1677721855,"refActorDataID":12466,"refActorRequireCast":true,"refActorCastId":[22485,22486],"refActorComparisonType":3,"Filled":true},{"Name":"WIP Crushing Hoof","type":1,"Enabled":false,"radius":25.0,"color":1677721855,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[22485,22486],"refActorComparisonType":3,"Filled":true},{"Name":"WIP Pull","type":3,"Enabled":false,"radius":0.0,"refActorNPCNameID":9759,"refActorRequireCast":true,"refActorCastId":[22473,22474],"refActorRequireBuff":true,"refActorBuffId":[2430],"refActorComparisonType":6,"includeRotation":true,"FaceMe":true},{"Name":"WIP Push","type":3,"Enabled":false,"radius":0.0,"refActorNPCNameID":9759,"refActorRequireCast":true,"refActorCastId":[22473,22474],"refActorRequireBuff":true,"refActorBuffId":[2431],"refActorComparisonType":6,"includeRotation":true,"Filled":true,"FaceMe":true}]}
```
**To do**
```diff
! Foe Splitter : Tankbuster CLeave, maybe put a cone here
! Vicious Swipe : Put a text to tell to use Arms Length or Surecast
! Push and Pull Debuff resolution
! Crashing Hoof (Meteor Dive) AOE on the destination: Can't find the VFX for the proximity marker
```
***
## 
## 🟠 The Queen
```

```
**To do**
```diff
! Queen’s Will + Beck and Call to Arms : Cross Shape AOE
! Northswain’s Glow : Make sure it still works from the Normal version
! Gods Save the Queen : Lightning balls that need to be reflected, Make an AOE on the still active balls to mark the AOE circle for people that don't want to use a Light Curtain
! The Queen also gain 4 buffs that needs to be dispelled, I need to find a way to show text when shehas those buffs
! Queen's Edict : Chess Solver (may need a script)
! Judgment Blade : Half Room Cleave 
! Relentless Play : make sure Queen's Guard Mechs applies here because most Spell ID are different so I need to refind them
```
