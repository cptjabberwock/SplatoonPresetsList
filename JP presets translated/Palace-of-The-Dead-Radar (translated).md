### Palace of The Dead Radar

Displayed on all floors

Display range : 100m
```
~Lv2~{"Name":"Palace of The Dead Radar","Group":"Palace of The Dead ","ZoneLockH":[593,561,562,563,564,565,594,595,596,597,598,599,600,601,602,603,604,605,606,607],"ElementsL":[{"Name":"Target Sensing Range","type":1,"radius":10.0,"color":3355508512,"refActorType":2,"includeHitbox":true},{"Name":"Mimic Sensing Range","type":1,"radius":14.0,"color":3355497983,"refActorNPCNameID":2566,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Mandragora Sensing Range","type":1,"radius":14.0,"color":3370974976,"refActorNPCNameID":5041,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Turning Enemies","type":1,"radius":1.5,"color":3372023552,"refActorType":2,"tether":true},{"Name":"Metastasis Tracker","type":1,"radius":2.0,"overlayText":"転移の石塔","refActorDataID":2007188,"refActorComparisonType":3,"includeRotation":true,"tether":true},{"Name":"Treasure Chest Gold","type":1,"radius":4.0,"color":3372220415,"overlayText":"Gold Chest","refActorDataID":2007358,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Silver","type":1,"radius":4.0,"color":3372158208,"overlayText":"Silver Chest","refActorDataID":2007357,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":802,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze2","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":804,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze3","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":784,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze4(Mimic)","type":1,"radius":2.5,"color":3371433728,"overlayText":"Mimic","refActorDataID":2006020,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze5","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":785,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze6","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":786,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze7","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":788,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze8","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":789,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze9","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":790,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze10","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":803,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze11","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":783,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze12","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":787,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze13","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":782,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze14","type":1,"radius":2.5,"color":3355496447,"refActorDataID":805,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Morphological change Range","type":1,"radius":20.0,"color":3372217088,"refActorType":1,"includeOwnHitbox":true},{"Name":"stepped on the trap","type":1,"radius":0.5,"color":3372024063,"overlayText":"stepped on the trap","refActorModelID":480,"refActorComparisonType":1},{"Name":"always pixel perfect","type":1,"radius":0.0,"color":3357277952,"refActorType":1},{"Name":"Contact Range","type":1,"radius":0.55,"refActorType":1,"includeOwnHitbox":true},{"Name":"Trap Hitbox","type":1,"radius":1.2,"color":3355508480,"refActorType":1,"includeOwnHitbox":true},{"Name":"Turning Enemies Right point","type":1,"offX":1.5,"radius":0.1,"color":3372023552,"refActorType":2,"includeRotation":true,"Filled":true},{"Name":"Turning Enemies Left point","type":1,"offX":-1.5,"radius":0.1,"color":3372023552,"refActorType":2,"includeRotation":true,"Filled":true},{"Name":"Turning Enemies Forward","type":4,"radius":10.0,"coneAngleMin":-45,"coneAngleMax":45,"color":3372023552,"FillStep":90.0,"refActorType":2,"includeHitbox":true,"includeRotation":true,"Filled":true},{"Name":"Buried treasure","type":1,"radius":0.0,"color":3355508731,"overlayText":"埋もれた財宝","refActorNPCID":2007542,"refActorComparisonType":4,"tether":true}]}
```
* Target Sensing Range

Display a green circle with a radius of 10m + target hitbox centered on the target

Simplified approximation of the detection range of the targeted enemy

* Mimic Sensing Range

Display a yellow circle with target hitbox + 14m radius centered on the mimic

Approximate detection range of mimic

* Mandragora Sensing Range

Display a light blue circle with target hitbox + 14m radius centered on the mandragora

Approximate location of mandragora by enemy change

* Turning Enemies

Displays a light blue circle with a radius of 1.5 m centered on the target

Displays a straight line connecting the target and itself (tether)

Guide to turning enemies (check tether if you like)

* Metastasis Tracker

自身と転移の石塔を結ぶ赤色の直線を表示

転移の石塔を中心に、赤色の半径 2m の円を表示

転移の石塔の場所の目安

always pixel perfect（足元のdot）が表示された円に入ると転移が開始される

* Treasure Chest Gold

金箱を中心に、白色の半径 target hitbox + 4m の円を表示

金箱の場所の目安

always pixel perfect（足元のdot）が表示された円に入ると取得可能
  
* Treasure Chest Silver

銀箱を中心に、青色の半径 target hitbox + 4m の円を表示

銀箱の場所の目安

always pixel perfect（足元のdot）が表示された円に入ると取得可能
  
* Treasure Chest Bronze(2,3,5,6,7,8,9,10,11,12,13,14)

銅箱を中心に、橙色の半径 target hitbox + 2.5m の円を表示

銅箱の場所の目安

always pixel perfect（足元のdot）が表示された円に入ると取得可能（正確でない）

* Treasure Chest Bronze4(Mimic)

銅箱(ミミック)を中心に、水色の半径 target hitbox + 2.5m の円を表示

銅箱（ミミック）の場所の目安

always pixel perfect（足元のdot）が表示された円に入ると取得可能（正確でない）

* Morphological change Range

自身を中心に、水色の半径 your hitbox + 18m の円を表示

形態変化のレンジの目安（敵のターゲットサークルが円に触れていれば有効）

* stepped on the trap

トラップを踏んだ跡地を中心に、紫色の半径 0.5m の円を表示

（銀箱を開けた跡地にも表示される）

* always pixel perfect

自身を中心に、緑色の半径 0m の円を表示（ドット）

hitboxの目安として常に表示される

* Contact Range

自身を中心に、赤色の your hitbox + 0.55m の円を表示

円が敵の中心に触れたら接触判定として感知されてもおかしくはないくらいの目安（あまり正確ではない）

接触扱いで感知される範囲は、ターゲットサークルの大きさに関わらず敵によってバラバラ

* Trap Hitbox

自身を中心に、緑色の your hitbox + 1.2m の円を表示

罠に接触するかの目安

表示された円が、Deep Dungeon Helper プラグインによって表示された点に触れると、その場所に罠が存在した場合は起爆する。

同様に、財宝感知で発見した財宝も、Trap Hitboxで表示された円の範囲内に入れる事で掘り起こす事が出来る。

* Turning Enemies (Right/Left) point

ターゲット対象を中心とした半径1.5mの円周上の角度（0/180）度（敵の真横）の位置に水色の半径 0.1m の円を塗りつぶしで表示

敵回しの目安 （塗りつぶした円の位置に立ち続けられるように回し続ける）

* Turning Enemies Forward

ターゲット対象を中心に、水色で前方90度の扇範囲を描画

敵回しの目安 （表示された線を踏み越えないように回し続ける）

* Buried treasure

自身と財宝探知によって発見された埋もれた財宝を黄色の直線で結ぶ

    財宝探知で発見された埋もれた財宝の場所の目安
