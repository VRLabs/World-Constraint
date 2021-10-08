<div align="center">
  <h1>
    World Constraint
  </h1>
  <p>
    A world fixed object, held in place with a constraint.
  </p>
</div>

</br>

If you need help, our support channel is on [Discord](https://discord.gg/THCRsJc).

The package works by using a prefab as the source in a parent constraint. If the prefab is not in the scene, the parent constraint will be at the prefab transforms and not move with the avatar.

The World Constraint.prefab should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it and move the prefab to base of your avatar.

Expand the prefab, and locate World Constraint/ResetTarget. Move this object out of the prefab to anywhere else on your avatar.

The Parent Constraint on World Constraint/Container uses ResetTarget as a source. Disable this Parent Constraint component to leave your Container in world space, and enable it to reset the Container to ResetTarget.

Replace the Cube under World Constraint/Container with your own objects.

