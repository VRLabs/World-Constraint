<div>
  <h1>World Constraint</h1>
  <p>
     A world fixed object, held in place with a constraint.
  </p>
  <a href="https://github.com/VRLabs/World-Constraint/releases/latest">
    <img src="https://img.shields.io/github/v/release/VRLabs/World-Constraint.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/World-Constraint/releases/latest">
    <img src="https://img.shields.io/badge/Unity-2019.4-green.svg?style=flat-square">
  </a>
  <br />
    <img src="https://raw.githubusercontent.com/VRLabs/World-Constraint/main/Media/Main.jpeg" width="100%">
  <br />
</div>

## How it works

"World Constraint" uses "World.prefab" as a parent constraint source. "World.prefab" is not in the scene, so "World Constraint" and it's child hierarchy will not move with the avatar.

The parent constraint on "Container" uses "Reset Target" as a source, which is used to bring "Container" to your avatar.

## Install guide

https://user-images.githubusercontent.com/45078979/148663027-b809919d-9c3f-4ea8-99b6-1bb805b1b230.mp4

"World Constraint.prefab" should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it and move the prefab to base of your avatar.

Expand the prefab, and locate "Reset Target". Move this object out of the prefab to anywhere else on your avatar.

## How to use

Disable the "Container" parent constraint component to leave it in world space, and enable it to reset the "Container" to "Reset Target".

## Downloads

You can grab the latest version of the World Constraint in [Releases](https://github.com/VRLabs/World-Constraint/releases/latest).

## License

World Constraint is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/World-Constraint/blob/main/LICENSE).

## Contact us

If you need help, our support channel is on [Discord](https://discord.vrlabs.dev).
