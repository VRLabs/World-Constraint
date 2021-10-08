# World Constraint
**_A world fixed object, held in place with a constraint._**

If you need help, our support channel is on [Discord](https://discord.gg/THCRsJc).

The package works by using World.prefab as a parent constraint source. World.prefab is not in the scene, so the parent constraint will not move with the avatar.

The World Constraint.prefab should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it and move the prefab to base of your avatar.

Expand the prefab, and locate World Constraint/ResetTarget. Move this object out of the prefab to anywhere else on your avatar.

The Parent Constraint on World Constraint/Container uses ResetTarget as a source. Disable this Parent Constraint component to leave your Container in world space, and enable it to reset the Container to ResetTarget.

Replace the Cube under World Constraint/Container with your own objects.

