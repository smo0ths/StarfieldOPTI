#### release 9/8/2023 💫

###### contact me [smoothschannel](https://twitch.tv/smoothschannel) or [discord](https://discord.gg/tDZT7QSx8m)

###### high overall quality replacement/optimization REMEMBER to change your overall quality to HIGH again after you replace and save the file contents***

###### Use fRenderResolutionSetting=0.6 if you use FSR2 or need more res. but using Starfield FSR2 Bridge DLSS mod and nvngx_dlss.dll v3.1.1.0 (from cyberpunk) at default quality looks fine.

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
iMaxDecalsPerFrame=3;low
iMaxSkinDecalsPerFrame=1;low

[Grass]
fGrassStartFadeDistance=130.0;test
fGrassRandomCullFactor=2.3;test
fGrassStartRandomCullDistance=20.0;added low
uGrassMeshInstanceCullingSSFootprint=12;low

[SAO]
fGTAORadius=0.3;
fGTAOPower=1.4;med
fGTAOMaxAttenuationDistance=50.0;
fDistantAOMidSAORadius=2.5;med
fDistantAOMidMaxAttenuationDistance=600.0;med
fDistantAOMidPower=1.3;med
fDistantAOMidBetaThicknessCorrection=0.2;
fDistantAOFarSAORadius=7.0;med
fDistantAOFarMaxAttenuationDistance=3000.0;
fDistantAOFarPower=2.0;med
fDistantAOFarBetaThicknessCorrection=0.15;

[Shadows]
fShadowCascadeSplitDistance0=6.0;low
fShadowCascadeSplitDistance1=12.0;low
fShadowCascadeSplitDistance2=50.0;low
fShadowCascadeSplitDistance3=400.0;low
uTerrainShadowMapSize=512;med
uShadowMapCount4096=0;
uShadowMapCount2048=8;
uShadowMapCount1024=16;
uShadowMapCount512=32;
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
uGIFallbackQuality=0;med test
bHalfResIndirect=1;low test

[Reflections]
uReflectionsResolution=128;med
uReflectionProbeFacesToRenderPerFrame=2;med
uReflectionProbeArraySize=24;med

[Particle]
uParticleLightingParticleCountQuality=1;med
bEnableHalfResParticles=0;

[VolumetricLighting]
uraVolumetricQuality=1;med
bFogMapBlurHalfRes=1;low test
bVolumetricIndirectForceFallback=1
uraVolumetricLightingPhaseFunction=0;test

[VariableRateShading]
fVariableRateShadingVarianceCutoff=0.1;med test

[Geometry]
bEnableHalfResGeometries=1;added test

[Crowd]
fCrowdActorPlatformSpecificSpawnScalar=0.6000;med test
uMaxCrowdActorCount=175;custom test

[Terrain]
bEnableStochasticTiling=1;
bEnableStochasticTilingDominantPlane=1;
bEnableTerrainPlanarMapping=1;
fTerrainDisplacementErrorThreshold=0.5;

[DynamicResolution]
fRenderResolutionSetting=0.5;test

[ContactShadows]
iContactShadowsQuality=1;med
bContactShadowsEnabled=0;off
bContactShadowHalfResolution=1;low
iBlurRadius=2;

[ContactShadow]
iContactShadowsQuality=1;med

[PostEffects]
fCASSharpnessSetting=0;custom none
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
uMainMenuDelayBeforeAllowSkip=0;
bAlwaysActive=1;

[Controls]
bMouseAcceleration=0;
fPitchSpeedRatio=1;
fIronSightsPitchSpeedRatio=1;
fMouseHeadingXScale=0.0199999996;
fMouseHeadingYScale=0.0199999996;
```
