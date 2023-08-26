# Misc
Bozjan Riders & Doll in Z3 that we always aggro while trying to farm the Starmob
Proximity Ring (9m + Target Hitbox)
```
~Lv2~{"Name":"Bozja V Mobs Proximity Detection","Group":"Bozja CE & Misc","ZoneLockH":[920],"ElementsL":[{"Name":"Bozjan Doll (Proximity)","type":1,"radius":9.0,"refActorNPCNameID":9573,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Bozjan Rider (Proximity)","type":1,"radius":9.0,"refActorNPCNameID":9575,"refActorComparisonType":6,"includeHitbox":true}],"MaxDistance":60.0,"UseDistanceLimit":true,"DistanceLimitType":1}
```
# Bozja Critical Engagements
## Zone 1
### Kill It with Fire

```

```
### The Baying of the Hound(s)

```

```
### The Shadow of Death's Hand

```

```
### Vigil for the Lost
```diff
! Everything on this fight is already telegraphed and I see no reason to make a layout for it
```
### Duel - Aces High

```

```
## Zone 2
### The Final Furlong

```

```
### The Fires of War

```

```
### Patriot Games

```

```
### The Hunt for Red Choctober

```

```
### Duel - Beast of Man

```

```
## Zone 3
### Trampled under Hoof

```

```
### Rise of the Robots
* Cones front and back for Basic Training and Train (just run here, it is fast)
* Put text on the boss with what HP you should have to resolve the mechanic
   * You have Forced March for both of the 2 try to put yourself in the right position to end up on the good bonus HP AOE
   * If you have already a good number for the mechanic, stay out of a bonus HP AOE
```
~Lv2~{"Name":"Z3 Rise of the Robots","Group":"Bozja CE & Misc","ZoneLockH":[920],"ElementsL":[{"Name":"Basic Training -front","type":4,"radius":30.0,"coneAngleMin":-30,"coneAngleMax":30,"refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20672],"refActorUseCastTime":true,"refActorCastTimeMax":15.0,"refActorUseOvercast":true,"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Basic Training -back","type":4,"radius":30.0,"coneAngleMin":-30,"coneAngleMax":30,"refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20672],"refActorUseCastTime":true,"refActorCastTimeMax":15.0,"refActorUseOvercast":true,"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.1415927,"Filled":true},{"Name":"Math - Indivisible","type":1,"radius":0.0,"color":255,"overlayBGColor":3355443200,"overlayVOffset":5.0,"overlayFScale":3.5,"overlayText":"HP = 2-3-5-7-11","refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20680],"refActorComparisonType":6},{"Name":"Math - Divide by Three","type":1,"radius":0.0,"color":255,"overlayBGColor":3355443200,"overlayVOffset":5.0,"overlayFScale":3.5,"overlayText":"HP = 3-6-9-12","refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20677],"refActorComparisonType":6},{"Name":"Math - Divide by Four","type":1,"radius":0.0,"color":255,"overlayBGColor":3355443200,"overlayVOffset":5.0,"overlayFScale":3.5,"overlayText":"HP = 4-8-12","refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20678],"refActorComparisonType":6},{"Name":"Math - Divide by Five","type":1,"radius":0.0,"color":255,"overlayBGColor":3355443200,"overlayVOffset":5.0,"overlayFScale":3.5,"overlayText":"HP = 5-10","refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20679],"refActorComparisonType":6},{"Name":"Train -front","type":4,"radius":30.0,"coneAngleMin":-30,"coneAngleMax":30,"refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20673,20674,20675,20683,20684,20685,20686],"refActorUseCastTime":true,"refActorCastTimeMax":20.0,"refActorUseOvercast":true,"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Train -back","type":4,"radius":30.0,"coneAngleMin":-30,"coneAngleMax":30,"refActorNPCNameID":9426,"refActorRequireCast":true,"refActorCastId":[20672,20673,20674,20675,20683,20684,20685,20686],"refActorUseCastTime":true,"refActorCastTimeMax":20.0,"refActorUseOvercast":true,"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.1415927,"Filled":true}]}
```
### Where Strode the Behemoth
Took the one from Kit as a start:
* Added Wildhorn cone to not be in range for the Tankbuster
* Fixed Zombie Breath size (was too wide) 
* Fixed Thunderbolt (made it longer to reach full aoe)
```
~Lv2~{"Name":"Z3 Where Strode the Behemoth","Group":"Bozja CE & Misc","ZoneLockH":[920],"ElementsL":[{"Name":"Tankbuster Wildhorn","type":4,"radius":10.0,"coneAngleMin":-45,"coneAngleMax":45,"color":1677721855,"refActorNPCNameID":9427,"refActorRequireCast":true,"refActorCastId":[20193],"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Corpse Thunderbolt","type":4,"radius":40.0,"coneAngleMin":-45,"coneAngleMax":45,"refActorNPCNameID":9428,"refActorRequireCast":true,"refActorCastId":[20197],"refActorComparisonType":6,"includeHitbox":true,"includeOwnHitbox":true,"includeRotation":true,"onlyUnTargetable":true,"Filled":true},{"Name":"Blazing Meteor","type":1,"radius":0.0,"color":255,"overlayBGColor":4278190080,"overlayTextColor":4294967295,"overlayVOffset":3.0,"overlayText":"HIDE!!!","refActorNPCNameID":9427,"refActorRequireCast":true,"refActorCastId":[20194],"refActorComparisonType":6,"onlyTargetable":true,"onlyVisible":true},{"Name":"Zombie Breath","type":3,"refY":40.0,"radius":3.0,"color":838861055,"refActorNPCNameID":9427,"refActorRequireCast":true,"refActorCastId":[20198],"FillStep":0.3,"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true}]}
```
### Metal Fox Chaos

```

```
### Duel - And the Flames Went Higher

```

```
