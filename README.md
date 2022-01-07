# Sponza HDRP
![Sponza-HDRP-1](https://user-images.githubusercontent.com/1553981/148616553-2a1a0cde-470b-40df-af91-5dd4efcd19dd.jpg)
## Summary
The Atrium Sponza Palace scene is widely used by graphics programmers and artists. It provides with an ideal lighting test environment, as it features both indoor and outdoor areas. 

The goal of the HDRP conversion was to modernize the project in key areas, making it compliant with modern rendering standards.

This project project - among many others - was used extensively when testing Progressive CPU and GPU Lightmappers available in Unity.
### Features
- Full compatibility with Unity's High Definition Render Pipeline (HDRP)
- PBR-compliant materials and textures
- Physical lighting and exposure
- Manually authored lightmap UVs
- Source textures and models are included
## Setup
This project makes use of multi-scene workflow. In order to make sure that everything works as expected, please follow these steps:
1. In the _Project_ tab, navigate to Assets > SponzaHDRP > Scenes
2. Open _Sponza_ scene
3. Once it finishes loading, right-click on the _SponzaLightingDay_ scene and select the _Open Scene Additive_ option
4. In the _Hierarchy_ panel, right-click on the _SponzaLightingDay_ scene, and select the _Set Active Scene_ option

Note that the initial shader compilation stage might take some time. There is a chance that nothing might be visible in the viewport before its completion.
## Credits
- Original Sponza model acquired from [McGuire Computer Graphics Archive](https://casual-effects.com/data/)
- HDRI acquired from [NoEmotion HDRs](http://noemotionhdrs.net/)
- Special thanks to Kemal Akay and Laurent Harduin with the initial project setup
