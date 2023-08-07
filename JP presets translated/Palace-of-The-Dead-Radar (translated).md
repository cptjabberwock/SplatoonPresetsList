# Palace of The Dead Radar

Displayed on all floors

Display range : 100m
```
~Lv2~{"Name":"Palace of The Dead Radar","Group":"Palace of The Dead ","ZoneLockH":[593,561,562,563,564,565,594,595,596,597,598,599,600,601,602,603,604,605,606,607],"ElementsL":[{"Name":"Target Sensing Range","type":1,"Enabled":false,"radius":10.0,"color":3355508512,"refActorType":2,"includeHitbox":true},{"Name":"Mimic Sensing Range","type":1,"radius":14.0,"color":3355497983,"refActorNPCNameID":2566,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Mandragora Sensing Range","type":1,"radius":14.0,"color":3370974976,"refActorNPCNameID":5041,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Turning Enemies","type":1,"radius":1.5,"color":3372023552,"refActorType":2},{"Name":"Metastasis Tracker","type":1,"radius":2.0,"overlayText":"Cairn of Passage","refActorDataID":2007188,"refActorComparisonType":3,"includeRotation":true,"tether":true},{"Name":"Treasure Chest Gold","type":1,"radius":4.0,"color":3372220415,"overlayText":"Gold Chest","refActorDataID":2007358,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Silver","type":1,"radius":4.0,"color":3372158208,"overlayText":"Silver Chest","refActorDataID":2007357,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":802,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze2","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":804,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze3","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":784,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze4(Mimic)","type":1,"radius":2.5,"color":3371433728,"overlayText":"Mimic","refActorDataID":2006020,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze5","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":785,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze6","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":786,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze7","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":788,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze8","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":789,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze9","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":790,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze10","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":803,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze11","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":783,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze12","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":787,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze13","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":782,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze14","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":805,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Morphological change Range","type":1,"radius":20.0,"color":3372217088,"refActorType":1,"includeOwnHitbox":true},{"Name":"Stepped on the trap","type":1,"radius":0.5,"color":3372024063,"overlayText":"Stepped on the trap","refActorModelID":480,"refActorComparisonType":1},{"Name":"always pixel perfect","type":1,"radius":0.0,"color":3357277952,"refActorType":1},{"Name":"Contact Range","type":1,"radius":0.55,"refActorType":1,"includeOwnHitbox":true},{"Name":"Trap Hitbox","type":1,"radius":1.2,"color":3355508480,"refActorType":1,"includeOwnHitbox":true},{"Name":"Turning Enemies Right point","type":1,"offX":1.5,"radius":0.1,"color":3372023552,"refActorType":2,"includeRotation":true,"Filled":true},{"Name":"Turning Enemies Left point","type":1,"offX":-1.5,"radius":0.1,"color":3372023552,"refActorType":2,"includeRotation":true,"Filled":true},{"Name":"Turning Enemies Forward","type":4,"radius":10.0,"coneAngleMin":-45,"coneAngleMax":45,"color":3372023552,"FillStep":90.0,"refActorType":2,"includeHitbox":true,"includeRotation":true,"Filled":true},{"Name":"Buried Treasure","type":1,"radius":0.0,"color":3355508731,"overlayText":"Buried Treasure","refActorNPCID":2007542,"refActorComparisonType":4,"tether":true}],"MaxDistance":100.0,"UseDistanceLimit":true,"DistanceLimitType":1}
```
* Target Sensing Range
   * Display a green circle around targeted enemies (radius : 10m + target hitbox)
   * Simplified approximation of the detection range of the targeted enemy (Disable if you use the Mobs preset to keep the Detection type coloring)

* Mimic Sensing Range
   * Display a yellow circle around Mimics (radius : 14m + target hitbox)
   * Approximate the detection range for mimic

* Mandragora Sensing Range
   * Display a light blue circle around Pygmaioi Mandragoras (radius : 14m + target hitbox)
   * Estimated appearance of Pygmaioi by enemy change

* Turning Enemies
   * Display a light blue circle around targeted enemies (radius : 1.5m)
   * Display a straight line connecting the target and yourself (tether)
   * Guideline for turning enemies (check tether to your preference)

* Metastasis Tracker
   * Display a red straight line connecting you and the Cairn of Passage
   * Display a red circle around the Cairn of Passage (radius : 2m)
   * Detect the location of the Cairn of Passage
   * The transition is initiated when you enter the circle with the "always pixel perfect" (dot at your feet).

* Treasure Chest Gold
   * Display a white circle around the Gold Chest (radius : 4m)
   * Detect the location of the Gold Treasure Chest
   * Can be obtained by entering the circle with the "always pixel perfect" (dot at your feet).
  
* Treasure Chest Silver
   * Display a blue circle around the Silver Chest (radius : 4m)
   * Detect the location of the Silver Treasure Chest
   * Can be obtained by entering the circle with the "always pixel perfect" (dot at your feet).
  
* Treasure Chest Bronze(2,3,5,6,7,8,9,10,11,12,13,14)
   * Display an orange circle around the Bronze Chest (radius : 2.5m)
   * Detect the location of the Bronze Treasure Chest
   * Can be obtained by entering the circle with the "always pixel perfect" (dot at your feet).

* Treasure Chest Bronze4(Mimic)
   * Display a light blue circle around the Bronze Chest (Mimic) (radius : 2.5m)
   * Detect the location of the Bronze Treasure Chest (Mimic)
   * Can be obtained by entering the circle with the "always pixel perfect" (dot at your feet).

* Pomander of Witching range
   * Display a light blue circle around yourself (radius : 20m + your hitbox)
   * Approximate range of form change (effective if the enemy's target circle touches the circle)

* Stepped on the trap
   * Display a purple circle around spot of the trap that was stepped onthe Cairn of Passage (radius : 0.5m)
   * (Also appears at the site where a Silver Chest was opened)

* always pixel perfect
   * Display a green circle around yourself (radius : 0 (a dot))
   * Always displayed as a guide for hitboxes

* Contact Range
   * Display a red circle around yourself (radius : 0.55m + your hitbox)
   * If the circle touches the center of the enemy, it may be considered as contact (not very accurate).
   * The range of contact detection varies depending on the enemy, regardless of the size of the target circle.

* Trap Hitbox
   * Display a green circle around yourself (radius : 1.2m + your hitbox)
   * How to know if you are in contact with a trap
      * When the displayed circle touches the point indicated by the [Deep Dungeon Helper](https://github.com/Speshkitty/DalamudPlugins/blob/main/repo.json) plug-in, the trap will detonate if one exists at that location.
      * Similarly, treasures found by treasure detection can be dug up by placing them within the circle displayed by the Trap Hitbox.

* Turning Enemies (Right/Left) point
   * Display a light blue circle (radius: 0.1m) at an angle (0/180) degrees (right beside the enemy) on a circle with a radius of 1.5m centered on the target with the light blue circle filled in.
   * (Keep turning so that the target can keep standing at the position of the filled circle)

* Turning Enemies Forward
   * Display a 90-degree forward cone in light blue with the target at its center.
   * (Keep turning so as not to step over the indicated line.)

* Buried Treasure
   * Display a yellow straight line connecting you and the Buried Treasure
   * Detect the location of the Accursed Hoard detected by Pomander of Intuition **(I guess)**
