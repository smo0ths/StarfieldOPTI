#### updated 9/15/2023 💫💫💫💫

###### contact me [smoothschannel](https://twitch.tv/smoothschannel) or [discord](https://discord.gg/tDZT7QSx8m)

###### High overall quality replacement/optimization REMEMBER to change your overall quality to HIGH again after you replace and save the file contents*

###### Turning down fRenderResolutionSetting and monitor resolution can drastically free up being gpu limited and gain fps.

###### Starfield FSR2 Bridge DLSS MOD is your friend

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
bDynamicResolutionEnabled=1;added
bEnableVsync=0;added
fFilmGrainIntensity=0.5;added
fMaxAnisotropy=8;added

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
fGTAORadius=0.3;high
fGTAOPower=1.4;med
fGTAOMaxAttenuationDistance=50;high
fDistantAOMidSAORadius=2.5;high
fDistantAOMidMaxAttenuationDistance=600;med
fDistantAOMidPower=1.3;med
fDistantAOMidBetaThicknessCorrection=0.2;high
fDistantAOFarSAORadius=7;med
fDistantAOFarMaxAttenuationDistance=3000;high
fDistantAOFarPower=2;med
fDistantAOFarBetaThicknessCorrection=0.15;high

[Shadows]
fShadowCascadeSplitDistance0=6;low
fShadowCascadeSplitDistance1=12;low
fShadowCascadeSplitDistance2=50;low
fShadowCascadeSplitDistance3=400;low
uTerrainShadowMapSize=128;custom
uShadowMapCount4096=0;custom
uShadowMapCount2048=0;custom
uShadowMapCount1024=11;custom
uShadowMapCount512=0;custom
uShadowMapCount256=1;custom
uShadowMapCount128=16;custom
uDirectionalLightShadowMapResolution=1024;med
uFocusShadowResolution=256;custom
uShadowFilteringQuality=0;med
uShadowFilteringTransparencies=0;high
bContactShadowsEnabled=1;high
uTotalDynamicShadowMapRenderCount=16;med
uAdditionalDynamicOnlyLightsBudget=1;med
bDirectionalShadowmapsUseLODFade=1;high

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
uraVolumetricQuality=1;med
bFogMapBlurHalfRes=1;low
bVolumetricIndirectForceFallback=1;high
uraVolumetricLightingPhaseFunction=1;low

[VariableRateShading]
fVariableRateShadingVarianceCutoff=0.15;low

[Crowd]
fCrowdActorPlatformSpecificSpawnScalar=0.5;custom
uMaxCrowdActorCount=125;custom

[Terrain]
bEnableStochasticTiling=1;high
bEnableStochasticTilingDominantPlane=0;med
bEnableTerrainPlanarMapping=1;high
fTerrainDisplacementErrorThreshold=1;med

[DynamicResolution]
fRenderResolutionSetting=0.60;custom

[ContactShadows]
iContactShadowsQuality=1;med
bContactShadowsEnabled=1;high
bContactShadowHalfResolution=0;high
iBlurRadius=1;custom

[ContactShadow]
iContactShadowsQuality=1;med

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
