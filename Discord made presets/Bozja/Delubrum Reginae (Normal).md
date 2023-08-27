# Delubrum Reginae Normal (by Alderan)
## Trinity Seeker
### Merciful Fourfold (Blades of Mercy) / Merciful Blooms (growing aoe) / Merciful Moon (gaze)
```
~Lv2~{"Name":"Trinity Seeker","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Forward Right","type":3,"Enabled":false,"refY":19.96,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":0.7853982,"refActorVFXPath":"vfx/common/eff/m0690_stlp_fr_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Forward Left","type":3,"Enabled":false,"refY":19.96,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":5.497787,"refActorVFXPath":"vfx/common/eff/m0690_stlp_fl_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Back Right","type":3,"Enabled":false,"refY":19.92,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":2.3561945,"refActorVFXPath":"vfx/common/eff/m0690_stlp_br_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Back Left","type":3,"Enabled":false,"refY":19.92,"radius":23.19,"thicc":0.4,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2489],"refActorComparisonType":7,"includeHitbox":true,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.9269907,"refActorVFXPath":"vfx/common/eff/m0690_stlp_bl_00c_n1.avfx","refActorVFXMin":9500,"refActorVFXMax":13500},{"Name":"Merciful Blooms","type":1,"radius":20.5,"color":1677721855,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[23213],"refActorCastTimeMin":4.0,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorComparisonType":3,"onlyUnTargetable":true,"Filled":true},{"Name":"Gaze","type":1,"radius":0.44,"color":3355507455,"overlayFScale":3.0,"thicc":3.0,"overlayText":"Look Away","refActorDataID":12594,"refActorRequireCast":true,"refActorCastId":[23212],"refActorComparisonType":3,"includeRotation":true,"tether":true}]}
```
**To do**
```diff
! Iron Splitter (Sand & Tiles) Unknown how to do it for now
! Improve timing on Mercy
```

## Dahu
### Firebreath / Charge
```
~Lv2~{"Name":"Dahu","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Firebreath","type":4,"radius":36.25,"coneAngleMin":-50,"coneAngleMax":50,"refActorDataID":12454,"refActorRequireCast":true,"refActorCastId":[22361,22362],"refActorUseCastTime":true,"refActorCastTimeMax":5.0,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"Filled":true},{"Name":"Charge","type":3,"refY":59.24,"radius":4.65,"thicc":0.0,"refActorDataID":12454,"refActorRequireCast":true,"refActorCastId":[22372],"FillStep":1.0,"refActorComparisonType":3,"includeRotation":true,"LimitDistanceInvert":true,"DistanceMin":17.300001,"DistanceMax":90.799995}]}
```
**To do**
```diff
! Knockback from Dahu Arrow or Line to know where you land
```

## Queen's Guard
### Shield & Sword Omen (Knight) / Bombs (Warrior) / Secrets Revealed (Soldier) / Turret's Tour (Gunner)
```
~Lv2~{"Name":"Queen's Guard","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Shield Omen","type":1,"radius":5.0,"Donut":19.34,"color":1677721855,"thicc":6.0,"refActorRequireCast":true,"refActorCastId":[22515],"FillStep":0.25,"refActorComparisonType":7,"onlyTargetable":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0408_stlp3_c0d1.avfx","refActorVFXMax":8000},{"Name":"Sword Omen","type":1,"radius":10.0,"color":1677721855,"thicc":6.0,"refActorRequireCast":true,"refActorCastId":[22514],"refActorComparisonType":7,"onlyTargetable":true,"onlyVisible":true,"Filled":true,"refActorVFXPath":"vfx/common/eff/m0285_stlp4c0c.avfx","refActorVFXMax":8000},{"Name":"Above Board","type":1,"radius":2.0,"color":1677786910,"overlayText":"Safe","refActorDataID":12478,"refActorCastReverse":true,"refActorRequireBuff":true,"refActorBuffId":[2447],"refActorRequireBuffsInvert":true,"refActorComparisonType":3,"Filled":true},{"Name":"Reversal of Forces","type":1,"radius":1.0,"color":3355508496,"overlayText":"Safe","refActorDataID":12477,"refActorUseCastTime":true,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2447],"refActorComparisonType":3,"Filled":true},{"Name":"Secrets Revealed","type":1,"radius":20.0,"color":1677721855,"overlayText":"Unsafe AOE","refActorComparisonType":7,"onlyUnTargetable":true,"onlyVisible":true,"Filled":true,"refActorVFXPath":"vfx/channeling/eff/chn_m0237s.avfx","refActorVFXMax":18000},{"Name":"Turret's Tour","type":3,"refY":40.0,"radius":3.0,"thicc":1.0,"refActorNPCNameID":9847,"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"onlyVisible":true}]}
```

## Bozjan Phantom
### Cube Shape / Knockback
```
~Lv2~{"Name":"Bozjan Phantom","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Cube Shape","type":3,"refY":50.0,"radius":6.0,"thicc":0.1,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[22437],"FillStep":1.0,"refActorComparisonType":3,"includeRotation":true},{"Name":"Knockback","type":1,"radius":0.0,"color":3355508719,"thicc":3.0,"refActorDataID":12461,"refActorComparisonType":3,"tether":true}]}
```

## Trinity Avowed
### Arsenal (Staff-Sword-Bow) / Gleaming Arrow
```
~Lv2~{"Name":"Trinity Avowed","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Allegiant Arsenal Staff","type":1,"radius":10.0,"color":1677721855,"refActorDataID":12518,"refActorRequireCast":true,"refActorCastId":[22919],"refActorCastTimeMax":60.0,"refActorUseOvercast":true,"refActorComparisonType":3,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Allegiant Arsenal Bow","type":4,"radius":35.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorDataID":12518,"refActorRequireCast":true,"refActorCastId":[22918],"refActorCastTimeMax":30.0,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Allegiant Arsenal Sword & Shield","type":4,"radius":35.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorDataID":12518,"refActorRequireCast":true,"refActorCastId":[22917],"refActorCastTimeMax":30.0,"refActorUseOvercast":true,"refActorComparisonType":3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":3.1415927,"Filled":true},{"Name":"Gleaming Arrow","type":3,"refY":50.0,"radius":5.0,"thicc":0.1,"refActorNPCNameID":9854,"refActorRequireCast":true,"refActorCastId":[22861],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"onlyVisible":true}]}
```
###  Hot & Cold (Meteors)
Ice 1 Meteor Safe Spot
```
~Lv2~{"Name":"Trinity Avowed 1 Cold","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"DCond":5,"ElementsL":[{"Name":"Meteors","type":1,"radius":22.0,"color":1258356504,"overlayText":"Safe","refActorDataID":12525,"refActorComparisonType":3,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Match":"vfx/common/eff/m0689_stlp4_c0t1.avfx spawned on me"},{"Type":3,"Match":"vfx/common/eff/m0689_stlp1_c0t1.avfx spawned on me"}]}
```
Fire 1 Meteor Safe Spot
```
~Lv2~{"Name":"Trinity Avowed 1 Fire","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"DCond":5,"ElementsL":[{"Name":"Meteors","type":1,"radius":22.0,"color":1258356504,"overlayText":"Safe","refActorDataID":12523,"refActorComparisonType":3,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Match":"vfx/common/eff/m0689_stlp2_c0t1.avfx spawned on me"},{"Type":3,"Match":"vfx/common/eff/m0689_stlp1_c0t1.avfx spawned on me"}]}
```
**To do**
```diff
! Ice and Fire 2 Meteor safe spots
! Arrow solver : May need a script to solve it (maybe ask Bossmod Dev if he could tell us)
! Blades of Entropy solver 
```

## The Queen
### Northswain's Glow / Judgement Blade (half arena cleave) / Heaven's Wrath / Bombs (Warrior)
```
~Lv2~{"Name":"The Queen","Group":"Delubrum Reginae Normal","ZoneLockH":[936],"ElementsL":[{"Name":"Northswain's Glow","type":1,"radius":20.0,"color":1677721855,"refActorNPCNameID":9863,"refActorRequireCast":true,"refActorCastId":[22980],"refActorUseCastTime":true,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorComparisonType":6,"onlyUnTargetable":true,"Filled":true},{"Name":"Judgement Blade - Left Side","type":3,"refX":10.0,"refY":55.0,"offX":10.0,"radius":7.16,"thicc":0.1,"refActorNPCNameID":9863,"refActorRequireCast":true,"refActorCastId":[22978],"refActorUseCastTime":true,"refActorCastTimeMax":5.5,"refActorUseOvercast":true,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true},{"Name":"Judgement Blade - Right Side","type":3,"refX":-10.0,"refY":55.0,"offX":-10.0,"radius":7.16,"thicc":0.1,"refActorNPCNameID":9863,"refActorRequireCast":true,"refActorCastId":[22977],"refActorUseCastTime":true,"refActorCastTimeMax":5.5,"refActorUseOvercast":true,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true},{"Name":"Heaven's Wrath","type":3,"refY":25.0,"radius":0.75,"color":3355508509,"thicc":0.1,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[22983],"refActorComparisonType":3,"includeRotation":true,"onlyUnTargetable":true,"AdditionalRotation":1.5707964},{"Name":"Above Board","type":1,"radius":2.0,"color":1677786910,"overlayText":"Safe","refActorDataID":12559,"refActorCastReverse":true,"refActorRequireBuff":true,"refActorBuffId":[2447],"refActorRequireBuffsInvert":true,"refActorComparisonType":3,"Filled":true},{"Name":"Reversal of Forces","type":1,"radius":1.0,"color":3355508496,"overlayText":"Safe","refActorDataID":12558,"refActorUseCastTime":true,"refActorCastTimeMax":10.0,"refActorUseOvercast":true,"refActorRequireBuff":true,"refActorBuffId":[2447],"refActorComparisonType":3,"Filled":true}]}
```
**To do**
```diff
!  Chess Solver (may need a script) first queen edict only show you what to do when you get it, second one is usually with the chess pieces that will have unsafe lines and columns
```
