#### updated 10/6/2023 💫💫

###### contact me [smoothschannel](https://twitch.tv/smoothschannel) or [discord](https://discord.gg/tDZT7QSx8m)

###### High overall quality replacement/optimization REMEMBER to change your overall quality to HIGH again after you replace and save the file contents*

###### Turning down fRenderResolutionSetting and monitor resolution can drastically free up being gpu limited and gain fps.

###### Starfield FSR2 Bridge DLSS MOD is your friend preset_override.txt set to D

###### Increase fRenderResolutionSetting or monitor resolution till you are satified with the rasterization quality and your gpu isn't 100% usage all the time.

---

<details><summary>Open High.ini and copy paste you can use this shortcut or just find it</summary>
<p>
press <kbd>⊞ Win+R</kbd> then type cmd
<br>
specify the drive you have Starfield installed C: G: I: X: S: and copy paste
<br>
start %windir%\explorer.exe “C:\SteamLibrary\steamapps\common\Starfield\High.ini”
</p>
</details>

```python
[Display]
bVolumetricLightingEnable=1;high
bDepthOfFieldEnable=0;low

[Decals]
uMaxDecals=50;med
uMaxSkinDecals=5;med
uMaxSkinDecalsPerActor=5;med
iMaxDecalsPerFrame=5;med
iMaxSkinDecalsPerFrame=3;med

[Grass]
fGrassStartFadeDistance=100;low
fGrassRandomCullFactor=2.5;low
fGrassStartRandomCullDistance=10;low
uGrassMeshInstanceCullingSSFootprint=12;low

[SAO]
fGTAORadius=0.3;default
fGTAOPower=1.5;low
fGTAOMaxAttenuationDistance=50;default
fDistantAOMidSAORadius=3;low
fDistantAOMidMaxAttenuationDistance=600;med
fDistantAOMidPower=1.8;custom
fDistantAOMidBetaThicknessCorrection=0.2;default
fDistantAOFarSAORadius=8;low
fDistantAOFarMaxAttenuationDistance=3000;default
fDistantAOFarPower=2.3;custom
fDistantAOFarBetaThicknessCorrection=0.15;default

[Shadows]
fShadowCascadeSplitDistance0=6;low
fShadowCascadeSplitDistance1=12;low
fShadowCascadeSplitDistance2=50;low
fShadowCascadeSplitDistance3=400;low
uTerrainShadowMapSize=128;custom
uShadowMapCount4096=0;custom
uShadowMapCount2048=0;custom
uShadowMapCount1024=0;custom
uShadowMapCount512=16;custom
uShadowMapCount256=2;custom
uShadowMapCount128=24;custom
uDirectionalLightShadowMapResolution=512;custom
uFocusShadowResolution=256;custom
uShadowFilteringQuality=0;med
uShadowFilteringTransparencies=0;high
bContactShadowsEnabled=0;off
uTotalDynamicShadowMapRenderCount=16;med
uAdditionalDynamicOnlyLightsBudget=1;med
bDirectionalShadowmapsUseLODFade=0;med

[MotionBlur]
uMotionBlurQuality=0;custom

[GlobalIllumination]
uGIFallbackQuality=0;med
bHalfResIndirect=1;low

[Reflections]
uReflectionsResolution=128;med
uReflectionProbeFacesToRenderPerFrame=2;med
uReflectionProbeArraySize=24;med

[Particle]
uParticleLightingParticleCountQuality=1;med
bEnableHalfResParticles=0;high

[VolumetricLighting]
uraVolumetricQuality=0;low
bFogMapBlurHalfRes=1;low
bVolumetricIndirectForceFallback=1;high
uraVolumetricLightingPhaseFunction=1;low

[VariableRateShading]
fVariableRateShadingVarianceCutoff=0.15;low

[Crowd]
fCrowdActorPlatformSpecificSpawnScalar=0.6;med
uMaxCrowdActorCount=150;med

[Terrain]
bEnableStochasticTiling=1;high
bEnableStochasticTilingDominantPlane=0;med
bEnableTerrainPlanarMapping=1;high
fTerrainDisplacementErrorThreshold=1;med

[DynamicResolution]
fRenderResolutionSetting=0.5;med

[ContactShadows]
iContactShadowsQuality=0;off
bContactShadowsEnabled=0;off
bContactShadowHalfResolution=0;high
iBlurRadius=0;custom

[ContactShadow]
iContactShadowsQuality=0;off

[PostEffects]
fCASSharpnessSetting=0;custom
```

---

<details><summary>Also make a StarfieldCustom.ini in Documents/My Games/Starfield use this shortcut or just find it</summary>
<p>
press <kbd>⊞ Win+R</kbd> then copy paste
<br>
%USERPROFILE%/Documents/My Games/Starfield
<br>
</p>
</details>

```python
[Display]
bDynamicResolutionEnabled=1;
bEnableVsync=0;
bUseReducedShadingRate=1;
bHalfResClouds=1;
bHalfResolutionBlendedPasses=1;
bHalfResolutionCorrection=1;
bHDRColorGradingLUT=0;
bTemporalAA_idTech7=0;
fMaxAnisotropy=8;
fMipBiasOffset=-1;

[General]
bAlwaysActive=1;
SIntroSequence=0;
uMainMenuDelayBeforeAllowSkip=1000;

[Controls]
bMouseAcceleration=0;
fIronSightsPitchSpeedRatio=1;
fMouseHeadingXScale=0.0199999996;
fMouseHeadingYScale=0.0199999996;
fPitchSpeedRatio=1;

[Camera]
fFarCameraDistanceOffset=0;
fFPWorldFOV=90;
fTPWorldFOV=87;
```
