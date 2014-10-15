#colider について
###Actor::updateMassFromShapes: Compute mesh inertia tensor failed for one of the actor's mesh shapes! Please change mesh geometry or supply a tensor manually!　というのがでたとき

3dオブジェクトにたいして mesh colider が自動で張られているのでそれが原因
他のコライダをあててやるか、多分適切なプロパティ(マテリアル？)を設定すればおk

