<div align="center">
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
  <a href="https://github.com/VRLabs/World-Constraint/issues">
    <img src="https://img.shields.io/github/issues-raw/VRLabs/World-Constraint.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/World-Constraint/issues?q=is%3Aissue+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-closed-raw/VRLabs/World-Constraint.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/World-Constraint/pull">
    <img src="https://img.shields.io/github/issues-pr-raw/VRLabs/World-Constraint.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/World-Constraint/pulls?q=is%3Apr+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-pr-closed-raw/VRLabs/World-Constraint.svg?style=flat-square">
  </a>
  <br />
  <br />
</div>

## How it works

This package works by using World.prefab as a parent constraint source. World.prefab is not in the scene, so the parent constraint will not move with the avatar.

## Install guide

The World Constraint.prefab should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it and move the prefab to base of your avatar.

Expand the prefab, and locate World Constraint/ResetTarget. Move this object out of the prefab to anywhere else on your avatar.

The parent constraint on World Constraint/Container uses ResetTarget as a source. Disable this parent constraint component to leave your Container in world space, and enable it to reset the Container to ResetTarget.

Replace the Cube under World Constraint/Container with your own objects.

## Downloads

You can grab the latest version of the World Constraint in [Releases](https://github.com/VRLabs/World-Constraint/releases/latest).

## License

World Constraint is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/World-Constraint/blob/dev/LICENSE).

## Contact us

If you need help, our support channel is on [Discord](https://discord.vrlabs.dev).
