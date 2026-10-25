# Stroke Rehabilitation VR Prototype

A Unity VR interaction prototype created for DDES9902. It explores how everyday and playful hand and arm activities could be presented as engaging upper-limb rehabilitation exercises. This is a design prototype, not a clinically validated rehabilitation tool.

## What is in the prototype

The project opens with an optional tutorial and then moves into a room containing seven activities:

| Activity | Interaction |
| --- | --- |
| Wipe the table | Move a rag across the table. |
| Spin the wheel | Turn a large wheel. |
| Arrange flowers | Pick up and place flowers. |
| Cupcakes | Pick up and interact with cupcakes. |
| BBQ | Handle food around a grill. |
| Basketball | Pick up and throw a ball. |
| Hammering | Use a hammer to break jars. |

The main scene includes instructional videos, visual callouts, audio guidance, teleport points, and a progress display for completed interactions. Activities are intended to explore reaching, grasping, releasing, turning, and coordinated arm movement through VR interactions.

## Open the project

1. Install **Unity 6000.3.8f1** through Unity Hub.
2. In Unity Hub, choose **Add project from disk** and select this directory (`DDES9902Assessment_prototype_Zoey`), which contains `Assets`, `Packages`, and `ProjectSettings`.
3. Open `Assets/__My Prototype/TutorialScene.unity` and press Play to start at the tutorial. Use **Skip Tutorial** to go directly to the main scene, or open `Assets/__My Prototype/MainScene.unity` to inspect the activities directly.

The project uses Unity's XR Interaction Toolkit, XR Hands, OpenXR, and Universal Render Pipeline. Its Android OpenXR settings include Meta Quest support. A compatible XR setup is needed to experience the intended hand interactions; opening the scenes in the editor is also useful for inspecting the design. No headset or build verification is claimed here.

## Project structure

- `Assets/__My Prototype/` — project scenes, scripts, prefabs, audio, and tutorial videos.
- `Assets/EZPZ Interaction Toolkit/` — Matt Cabanag's interaction toolkit used as a starting point for the project.
- `Assets/EZPZ Examples/` — examples supplied with the toolkit.
- `Assets/XR/` and `Assets/XRI/` — XR and interaction configuration and assets.
- `Packages/manifest.json` — Unity package dependencies.
- `ProjectSettings/EditorBuildSettings.asset` — build scene order: tutorial, then main scene.

## Credits and licenses

This prototype is by Zoey W for DDES9902. It uses **EZPZ Interaction Toolkit by Matt Cabanag**. The toolkit is distributed under the MIT License; its copyright notice, license text, and asset acknowledgements are retained in [`Assets/README_EZPZ.txt`](Assets/README_EZPZ.txt). The [original toolkit guide](https://youtu.be/mIoewQ2zQBI) and [EZPZ video tutorials](https://www.youtube.com/playlist?list=PLZP8wzCUfgsKfgJDXuiHHAw-qjcEev1k-) provide further background.

The repository also includes other Unity packages and third-party art, audio, and effects. Their own license or attribution files, where supplied, remain with the corresponding assets. The EZPZ MIT License does not automatically cover those assets or this prototype as a whole.
