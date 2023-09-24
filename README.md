<div align="center">

# World Constraint

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/World-Constraint/total?label=Downloads)](https://github.com/VRLabs/World-Constraint/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/World-Constraint/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

A world-fixed object, held in place with a constraint.

![Alt text]()

### ⬇️ [Download latest Unitypackage](https://github.com/VRLabs/World-Constraint/releases/latest)

<!-- 
### 📦 [Add to VRChat Creator Companion]() -->

</div>

---
## How it works

* "World Constraint" uses "World.prefab" as a parent constraint source. "World.prefab" is not in the scene, so "World Constraint" and it's child hierarchy will not move with the avatar.
* The parent constraint on "Container" uses "Reset Target" as a source, which is used to bring "Container" to your avatar.

## Install guide

https://user-images.githubusercontent.com/45078979/148663027-b809919d-9c3f-4ea8-99b6-1bb805b1b230.mp4

* Drag & drop the ``World Constraint`` prefab into the base of your Hierarchy.
* Right click and unpack the prefab, then drag & drop it onto your avatar.
* Expand the prefab, and locate "Reset Target". Move this object out of the prefab to anywhere else on your avatar.

## How to use

* Disable the "Container" parent constraint component to leave it in world space, and enable it to reset the "Container" to "Reset Target".

## Additional Notes

* By default, the Container and its contents will not scale with your avatar. If you want the Container and its contents to scale with your avatar, add a Scale Constraint to the "Container" object, set your avatar as the source, and activate it.
* If your Reset Target is directly under your avatar, it won't properly rotate with you in full body.

## Performance stats

```c++
Constraints:        3
```

## Hierarchy layout

```html
World Constraint
|-Container
|  |-Cube
|-Reset Target
```

## Contributors

* [lin](https://github.com/oofdesu)

## License

World Constraint is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/World-Constraint/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

---