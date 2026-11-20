# BuMoChi starter assets

Godot avatar projects and recorded motion clips for [BuMoChi](https://github.com/iani/BuMoChi).

## Install

In SuperCollider, evaluate:

```supercollider
Platform.userAppSupportDir.postln;
```

Download this repository using **Code → Download ZIP**, extract it, rename the extracted `BuMoChi_Assets-main` folder to **BuMoChiAssets**, and place it directly inside the directory printed above. The underscore belongs to the repository name, not the installed folder name.

Alternatively, clone this repository into that directory with the destination folder name `BuMoChiAssets`:

```sh
git clone https://github.com/iani/BuMoChi_Assets.git BuMoChiAssets
```

On macOS the default installation is `~/Library/Application Support/SuperCollider/BuMoChiAssets`. On other platforms use the path printed by SuperCollider; do not substitute a macOS path.

If you already have assets, back them up and merge new examples without overwriting your own clips. You can also keep this checkout elsewhere and select it using **Select Asset Folder** in `Bmc.assetEditor`.

## Included material

- `GodotProjects/VMC_1_Avatar_M`: single-avatar Ishidomaru project.
- `GodotProjects/VMC_1_Avatar_F`: single-avatar Mother project.
- `GodotProjects/VMC_2_Avatars`: two-avatar project.
- `AnimationClips`: existing recorded motion clips and their associated files.

Install Godot **4.5 standard**, as used by these projects, separately. The projects include their add-ons; Godot generates its import cache when a project is first opened. Allow that first import to complete.

Open `Bmc.assetEditor;`, start the pipeline, select a Godot project and scene, open it, select an avatar and a clip, and press **Play**. Refer to the BuMoChi README and Tutorial for software prerequisites and Godot executable configuration.

## Local material excluded from Git

`GodotProjects/BBDemos`, and all directories named `Photos`, `SoundFiles`, and `Videos`, are excluded, together with Godot import caches. Existing local files are retained. BuMoChi creates its empty working directories when needed; audio files and demonstration videos are not supplied by this repository.

Retain the individual copyright and licence notices included with models and add-ons. This repository does not change those assets' licences.
