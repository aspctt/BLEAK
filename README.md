# <p align=center> BLEAK </p>

![Version](https://img.shields.io/badge/Version-1.2.1.0-blue)
![Available for](https://img.shields.io/badge/Available_for-KSP_1.8%2B-orange)
![Requires](https://img.shields.io/badge/Requires-TUFX-blueviolet)
![License](https://img.shields.io/badge/License-GPL_3.0-red)

## Description

BLEAK is a set of TUFX post-processing profiles for Kerbal Space Program.

The look it goes for is cold and washed out rather than punchy. Saturation is pulled well below stock, the colour filter leans slightly blue, and an ACES tonemap keeps highlights from blowing out over bright terrain and ice. Auto exposure is set to adapt progressively, so moving from a shadowed launch pad into direct sunlight settles over a moment instead of snapping.
There is no attempt here to make KSP look photoreal. The intent is closer to a colour grade on footage that already exists: the game's own art holds up fine, it just reads flat under stock lighting. Contrast, bloom threshold and exposure do most of the work, and effects that draw attention to themselves are used sparingly or not at all.
Antialiasing is left off in every profile so it stays under your own graphics settings, and HDR is on throughout.

### Profiles

* **Umia** - the baseline grade. Cool filter, heavy desaturation, gentle contrast lift, soft bloom and motion blur.
* **Everon** - Umia's grade with a cooler temperature, a stronger tone curve toe for deeper shadows, and a touch of chromatic aberration.
* **Borealis** - a darker, higher-bloom variant with ambient occlusion and a custom tonemap. Built for orbital and night-side scenes.
* **Borealis - Editor** - the Borealis grade without ambient occlusion or bloom, so the VAB and SPH stay readable while you build.

## Installation

1. Delete any previous version of BLEAK.
2. Install [TUFX](https://forum.kerbalspaceprogram.com/index.php?/topic/192212-19x-tufx-post-processing/).
3. Place the `GameData` folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.
4. In game, open the TUFX button in the toolbar and pick a profile.

**REMOVE ANY OLD VERSIONS BEFORE INSTALLING**.

## Dependencies

* Hard dependencies:
	+ [TUFX](https://forum.kerbalspaceprogram.com/index.php?/topic/192212-19x-tufx-post-processing/)

## Licensing

This work is licensed as follows:

* [GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). See [here](./LICENSE)
	+ You are free to:
		- Use : unpack and use the material in any computer or device
		- Redistribute : redistribute the original package in any medium
		- Adapt : Reuse, modify or incorporate source code into your works (and redistribute it!)
	+ Under the following terms:
		- You retain any copyright notices
		- You recognise and respect any trademarks
		- You don't impersonate the authors, neither redistribute a derivative that could be misrepresented as theirs.
		- You credit the author and republish the copyright notices on your works where the code is used.
		- You relicense (and fully comply) your works using GPL 3.0
			- Please note that upgrading the license to any posterior GPL **IS NOT ALLOWED** for this work, as the author **DID NOT** added the "or (at your option) any later version" on the license.
		- You don't mix your work with GPL incompatible works.

Please note the copyrights and trademarks in [NOTICE](./NOTICE)

## Credits

* aspctt - profiles, project lead
* Shadowmage - [TUFX](https://github.com/shadowmage45/TUFX), which every profile here runs on
