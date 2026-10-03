# <p align=center> BLEAK </p>

<p align=center>
	<img alt="Version" src="https://img.shields.io/badge/Version-1.2.2-orange">
	<img alt="Available for" src="https://img.shields.io/badge/Available_for-KSP_1.9%2B-blue">
	<img alt="Requires" src="https://img.shields.io/badge/Requires-TUFX-blueviolet">
	<img alt="License" src="https://img.shields.io/badge/License-GPL_3.0-red">
</p>

<p align=center>
	<a href="https://spacedock.info/mod/4626/BLEAK"><img src="https://cdn.jsdelivr.net/gh/aspctt/MouseAimFlightRedux@main/docs/badges/spacedock.svg" alt="Available on SpaceDock"></a>
	<a href="https://github.com/aspctt/BLEAK"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact-minimal/available/github_vector.svg" alt="Available on GitHub"></a>
</p>

## Description

BLEAK is a set of TUFX post-processing profiles for Kerbal Space Program.

The look it goes for is cold and washed out rather than punchy. Saturation is pulled well below stock, the colour filter leans slightly blue, and an ACES tonemap keeps highlights from blowing out over bright terrain and ice. Auto exposure is set to adapt progressively, so moving from a shadowed launch pad into direct sunlight settles over a moment instead of snapping.
There is no attempt here to make KSP look photoreal. The intent is closer to a colour grade on footage that already exists: the game's own art holds up fine, it just reads flat under stock lighting. Contrast, bloom threshold and exposure do most of the work, and effects that draw attention to themselves are used sparingly or not at all.
Antialiasing is left off in every profile so it stays under your own graphics settings, and HDR is on throughout.

* **Umia** - the baseline grade. Cool filter, heavy desaturation, gentle contrast lift, soft bloom and motion blur.
* **Everon** - Umia's grade with a cooler temperature, a stronger tone curve toe for deeper shadows, and a touch of chromatic aberration.
* **Borealis** - a darker, higher-bloom variant with ambient occlusion and a custom tonemap. Built for orbital and night-side scenes.
* **Borealis - Editor** - the Borealis grade without ambient occlusion or bloom, so the VAB and SPH stay readable while you build.

In game, open TUFX from the toolbar and pick a profile.

## Installation

To install, place the GameData folder inside your Kerbal Space Program folder, and install the dependencies below. If asked to overwrite files, please do so. BLEAK is also on CKAN.

**REMOVE ANY OLD VERSIONS BEFORE INSTALLING**.

## Dependencies

* [TUFX](https://github.com/KSPModStewards/TUFX) and its own dependencies

## Licensing

BLEAK is licensed under the **GNU General Public License v3.0**. The full terms are in [LICENSE](./LICENSE). In short:

* Use, share and change it freely.
* Anything you release that's built from it must be GPL 3.0 too, keep the copyright notices and credit, and not pass itself off as BLEAK.
* It's GPL 3.0 only. Moving it to a later GPL version is not allowed.

See [NOTICE](./NOTICE) for copyrights and trademarks.

## Credits

* aspctt - profiles, maintenance
* Shadowmage - the original [TUFX](https://github.com/shadowmage45/TUFX)
* KSPModStewards - maintaining [TUFX](https://github.com/KSPModStewards/TUFX)

Full history is in [CHANGELOG](./CHANGELOG.md).

<p align=center>
	<a alt="BuyMeACoffee" href="https://buymeacoffee.com/aspctt"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/donate/buymeacoffee-singular_vector.svg"></a>
</p>
