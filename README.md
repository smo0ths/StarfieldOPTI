#### updated 9/9/2023 💫

###### contact me [smoothschannel](https://twitch.tv/smoothschannel) or [discord](https://discord.gg/tDZT7QSx8m)

###### High overall quality replacement/optimization REMEMBER to change your overall quality to HIGH again after you replace and save the file contents*

###### Turning down fRenderResolutionSetting and monitor resolution can drastically free up being gpu limited and gain fps.

###### DLSS v3.1.1.0(from cyberpunk) with Starfield FSR2 Bridge DLSS mod can look fine at lowest fRenderResolutionSetting and give you the most fps boost at your resolution.

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
bVolumetricLightingEnable=1;
bDepthOfFieldEnable=1;

[Decals]
uMaxDecals=25;low
uMaxSkinDecals=5;low
uMaxSkinDecalsPerActor=5;low
iMaxDecalsPerFrame=1;custom
iMaxSkinDecalsPerFrame=1;low

[Grass]
fGrassStartFadeDistance=150.0;custom
fGrassRandomCullFactor=0.25;custom
fGrassStartRandomCullDistance=0.25;custom added
uGrassMeshInstanceCullingSSFootprint=12;low

[SAO]
fGTAORadius=0.3;
fGTAOPower=1.4;med
fGTAOMaxAttenuationDistance=50.0;
fDistantAOMidSAORadius=2.5;
fDistantAOMidMaxAttenuationDistance=600.0;med
fDistantAOMidPower=1.3;med
fDistantAOMidBetaThicknessCorrection=0.2;
fDistantAOFarSAORadius=7.0;med
fDistantAOFarMaxAttenuationDistance=3000.0;
fDistantAOFarPower=2.0;med
fDistantAOFarBetaThicknessCorrection=0.15;

[Shadows]
fShadowCascadeSplitDistance0=7.0;med
fShadowCascadeSplitDistance1=25.0;med
fShadowCascadeSplitDistance2=60.0;med
fShadowCascadeSplitDistance3=400.0
uTerrainShadowMapSize=512;med
uShadowMapCount4096=0;
uShadowMapCount2048=0;custom
uShadowMapCount1024=16;
uShadowMapCount512=36;med
uShadowMapCount256=128;
uShadowMapCount128=128;
uDirectionalLightShadowMapResolution=1024;low
uFocusShadowResolution=1024;med
uShadowFilteringQuality=0;med
uShadowFilteringTransparencies=0;
bContactShadowsEnabled=0;off
uTotalDynamicShadowMapRenderCount=16;med
uAdditionalDynamicOnlyLightsBudget=1;med
bDirectionalShadowmapsUseLODFade=1;

[MotionBlur]
uMotionBlurQuality=0;off

[GlobalIllumination]
uGIFallbackQuality=0;med
bHalfResIndirect=1;low

[Reflections]
uReflectionsResolution=128;med
uReflectionProbeFacesToRenderPerFrame=2;med
uReflectionProbeArraySize=24;med

[Particle]
uParticleLightingParticleCountQuality=2;
bEnableHalfResParticles=0;

[VolumetricLighting]
uraVolumetricQuality=2;
bFogMapBlurHalfRes=1;low
bVolumetricIndirectForceFallback=1;
uraVolumetricLightingPhaseFunction=1;low

[VariableRateShading]
fVariableRateShadingVarianceCutoff=0.1;med

[Crowd]
fCrowdActorPlatformSpecificSpawnScalar=0.8;custom
uMaxCrowdActorCount=180;custom

[Terrain]
bEnableStochasticTiling=1;
bEnableStochasticTilingDominantPlane=0;med
bEnableTerrainPlanarMapping=1;
fTerrainDisplacementErrorThreshold=1.0;med

[DynamicResolution]
fRenderResolutionSetting=0.6;

[ContactShadows]
iContactShadowsQuality=0;off
bContactShadowsEnabled=0;off
bContactShadowHalfResolution=1;low
iBlurRadius=2;

[ContactShadow]
iContactShadowsQuality=1;med

[PostEffects]
fCASSharpnessSetting=0;off

[Geometry]
bEnableHalfResGeometries=1;added
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
fMaxAnisotropy=8;

[Camera]
fFPWorldFOV=90;
fTPWorldFOV=90;
fFarCameraDistanceOffset=-0.5;

[General]
SIntroSequence=0;
bAlwaysActive=1;

[Controls]
bMouseAcceleration=0;
fPitchSpeedRatio=1;
fIronSightsPitchSpeedRatio=1;
fMouseHeadingXScale=0.0199999996;
fMouseHeadingYScale=0.0199999996;
```
