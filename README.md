# Sponza
![Sponza-HDRP-1](https://user-images.githubusercontent.com/1553981/148616553-2a1a0cde-470b-40df-af91-5dd4efcd19dd.jpg)

## Notice

**This repository will no longer be updated, and will be removed in the future**.

Please visit the [Classic Sponza](https://github.com/Unity-Technologies/Classic-Sponza) repository on Unity GitHub for latest updates.

## Summary

The Atrium Sponza Palace scene is widely used by graphics programmers and artists. It provides with an ideal lighting test environment, as it features both indoor and outdoor areas. 

The goal of the HDRP conversion was to modernize the project in key areas, making it compliant with modern rendering standards.

Please refer to the [Releases](https://github.com/radishface/Sponza-HDRP/releases) page for Unity editor version compatibility.

### Features
- Full compatibility with Unity's High Definition Render Pipeline (HDRP)
- All textures and materials are PBR-compliant
- Physical lighting and exposure
- Manually authored lightmap UVs
- Baked global illumination using the Progressive Lightmapper

## Setup
### Cloning the project
#### Important note
This project makes use of [Git Large Files Support (LFS)](https://git-lfs.github.com). You need to install LFS on your local machine first. **Do not download the project via the Download ZIP option.** Once you have installed LFS, please follow the steps outlined below.
#### Using the GitHub Desktop client
Click on the green Code button at the top, and select *Open in Desktop* option.
#### Using alternative git clients
Paste the following web URL into your preffered git client: `https://github.com/radishface/Sponza.git`.
#### Using command line or terminal
Open your preferred command line application and enter the following command: `git clone https://github.com/radishface/Sponza.git`.
### Setting up the project in Unity
This project makes use of multi-scene workflow. In order to make sure that everything works as expected, please follow these steps:
1. In the _Project_ tab, navigate to Assets > SponzaHDRP > Scenes
2. Open _Sponza_ scene
3. Once it finishes loading, right-click on the _SponzaLightingDay_ scene and select the _Open Scene Additive_ option
4. In the _Hierarchy_ panel, right-click on the _SponzaLightingDay_ scene, and select the _Set Active Scene_ option

Note that the initial shader compilation stage might take some time. There is a chance that nothing might be visible in the viewport before its completion.
## Credits
- Original Sponza model acquired from [McGuire Computer Graphics Archive](https://casual-effects.com/data/)
- HDRI acquired from [NoEmotion HDRs](http://noemotionhdrs.net/)
- Special thanks to [Kemal Akay](https://github.com/kemalakay) and [Laurent Harduin](https://github.com/laurenth-personal) for their assistance with the initial project setup
