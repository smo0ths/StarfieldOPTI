#### updated 7/11/2024 💫

##### contact me [smoothschannel](https://twitch.tv/smoothschannel) or [discord](https://discord.gg/tDZT7QSx8m)

##### Medium.ini replacement/optimization REMEMBER to change your overall quality to Medium in game after you replace and save the file contents*

##### delete Pipeline.cache in %localappdata%/Starfield

---

<details><summary>Open Medium.ini and copy paste you can use this shortcut or just find it</summary>
<p>
press <kbd>⊞ Win+R</kbd> then type cmd
<br>
specify the drive you have Starfield installed C: G: I: X: S: and copy paste
<br>
start %windir%\explorer.exe “C:\SteamLibrary\steamapps\common\Starfield\Medium.ini”
</p>
</details>

```python
[Display]
bVolumetricLightingEnable=1;high
bDepthOfFieldEnable=0;low

[Decals]
uMaxDecals=25;low
uMaxSkinDecals=5;med
uMaxSkinDecalsPerActor=5;med
iMaxDecalsPerFrame=3;low
iMaxSkinDecalsPerFrame=1;low

[Grass]
fGrassStartFadeDistance=75;custom
fGrassRandomCullFactor=2.5;low
fGrassStartRandomCullDistance=10;low
uGrassMeshInstanceCullingSSFootprint=12;low

[SAO]
fGTAORadius=0.3;def
fGTAOPower=1.5;low
fGTAOMaxAttenuationDistance=50;def
fDistantAOMidSAORadius=3.0;low
fDistantAOMidMaxAttenuationDistance=600;med
fDistantAOMidPower=2;low
fDistantAOMidBetaThicknessCorrection=0.2;def
fDistantAOFarSAORadius=8;low
fDistantAOFarMaxAttenuationDistance=1000;def
fDistantAOFarPower=2.5;low
fDistantAOFarBetaThicknessCorrection=0.15;def

[Shadows]
fShadowCascadeSplitDistance0=6;low
fShadowCascadeSplitDistance1=12;low
fShadowCascadeSplitDistance2=50;low
fShadowCascadeSplitDistance3=300;custom
uTerrainShadowMapSize=256;low
uShadowMapCount4096=0;low
uShadowMapCount2048=0;low
uShadowMapCount1024=0;custom
uShadowMapCount512=22;custom
uShadowMapCount256=128;low
uShadowMapCount128=128;low
uDirectionalLightShadowMapResolution=512;custom
uFocusShadowResolution=512;custom
uShadowFilteringQuality=0;low
uShadowFilteringTransparencies=0;high
bContactShadowsEnabled=0;low
uTotalDynamicShadowMapRenderCount=12;low
uAdditionalDynamicOnlyLightsBudget=0;low
bDirectionalShadowmapsUseLODFade=0;high
uDirectionalShadowmapsUseLODFadeLastCascadeIndex=0;med
uCascadeUpdateStrategyMode=1;med

[MotionBlur]
uMotionBlurQuality=0;custom

[GlobalIllumination]
uGIFallbackQuality=0;med
bHalfResIndirect=1;low

[Reflections]
uReflectionsResolution=128;med
uReflectionProbeFacesToRenderPerFrame=2;med
uReflectionProbeArraySize=24;high

[Particle]
uParticleLightingParticleCountQuality=1;med
bEnableHalfResParticles=0;ultra

[VolumetricLighting]
uraVolumetricQuality=0;low
bFogMapBlurHalfRes=1;low
bVolumetricIndirectForceFallback=1;high
uraVolumetricLightingPhaseFunction=1;low

[VariableRateShading]
fVariableRateShadingVarianceCutoff=0.15;low

[Crowd]
fCrowdActorPlatformSpecificSpawnScalar=0.5;custom
uMaxCrowdActorCount=75;custom

[Terrain]
bEnableStochasticTiling=1;ultra
bEnableStochasticTilingDominantPlane=0;high
bEnableTerrainPlanarMapping=1;ultra
fTerrainDisplacementErrorThreshold=1;med

[DynamicResolution]
fRenderResolutionSetting=0.5;med

[ContactShadows]
iContactShadowsQuality=0;off
bContactShadowsEnabled=0;off
bContactShadowHalfResolution=0;high
iBlurRadius=0;custom
bLayeredSkinnedContactShadows=0;med
bFirstPersonContactShadows=0;high

[ContactShadow]
iContactShadowsQuality=0;off

[PostEffects]
fCASSharpnessSetting=0;custom

[LODManager]
uLODStreamingAdjacencyLoad=2;med

[ViewDistance]
fBlockLevel0Distance=450;med
fBlockLevel1Distance=750;med
fBlockLevel2Distance=1200;med

[Transparency]
fEffectsHighMinAlphaThreshold=2;med
fEffectsLowMinAlphaThreshold=1.2;med
fEffectsAlphaThresholdFadeFar=30;med
fEffectsAlphaThresholdFadeNear=15;med
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
fAutoDoorFadeSecs=0.1;def 0.5
fFastTravelFadeSecs=0.1;def 0.5
fLoadGameFadeSecs=0.5;def 1
fNormalDoorFadeSecs=0.1;def 0.4
fNormalDoorFadeWait=0.01;def 0.01
uMainMenuDelayBeforeAllowSkip=1000;def 5000

[Interface]
fDataMenuFadeInToGameTime=0.1;def 0.5
fFadeToBlackFadeSeconds=0.5;def 1

[Controls]
bMouseAcceleration=0;
fIronSightsPitchSpeedRatio=1;
fMouseHeadingXScale=0.02;
fMouseHeadingYScale=0.02;
fPitchSpeedRatio=1;

[Camera]
fWorkshopIsoCamDistanceSpeed=1;def 1 set manually in prefs to be exact
fTPWorldFOV=75;def 75 set manually in prefs to be exact
fFPGeometryFOV=90;def 85 set manually in prefs to be exact
fFPWorldFOV=90;def 85 set manually in prefs to be exact
```
