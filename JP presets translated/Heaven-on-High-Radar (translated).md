# heaven-on-High Radar

Displayed on all floors

Display range : 100m
```

```
* Target Sensing Range
   * Display a green circle around targeted enemies (radius : 10m + target hitbox)
   * Simplified approximation of the detection range of the targeted enemy (Disable if you use the Mobs preset to keep the Detection type coloring)

* Mimic Sensing Range **(WIP)**
   * Display a yellow circle around Mimics (radius : 14m + target hitbox)
   * Approximate the detection range of mimic (Pomander of Alteration)

* Mandragora Sensing Range **(WIP)**
   * Display a light blue circle around Pygmaioi Mandragora (radius : 14m + target hitbox)
   * Approximate the detection range of mandragora (Pomander of Alteration)

* Turning Enemies **(I don't see the point of this layout when you add all others)**
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

* Morphological change Range **(WIP)**
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

* Turning Enemies (Right/Left) point **(WIP)**
   * Display a light blue circle (radius: 0.1m) at an angle (0/180) degrees (right beside the enemy) on a circle with a radius of 1.5m centered on the target with the light blue circle filled in.
   * (Keep turning so that the target can keep standing at the position of the filled circle)

* Turning Enemies Forward **(WIP)**
   * Display a 90-degree forward cone in light blue with the target at its center.
   * (Keep turning so as not to step over the indicated line.)

* Buried Treasure
   * Display a yellow straight line connecting you and the Buried Treasure
   * Detect the location of the Accursed Hoard detected by Pomander of Intuition **(I guess)**
