---
uid: arcore-whats-new
---
# What's new in version 5.0

Summary of changes in ARCore XR Plug-in package version 5.0.

The main updates in this release include:

**Added**

- Added support for a new [OcclusionPreferenceMode.NoOcclusion](xref:UnityEngine.XR.ARSubsystems.Configuration.OcclusionPreferenceMode) mode that, when set, disables occlusion rendering on the camera background when using [ARCameraBackground](xref:UnityEngine.XR.ARFoundation.ARCameraBackground) and [AROcclusionManager](xref:UnityEngine.XR.ARFoundation.AROcclusionManager).

**Changed**

- The minimum Unity version for this package is now 2021.2.

**Removed**

- Removed deprecated APIs: `ARCorePlaneProvider` and `ARCoreImageTrackingProvider`.

**Fixed**

- Fixed a missing dependency on built-in [UnityWebRequest](https://docs.unity3d.com/2021.2/Documentation/ScriptReference/Networking.UnityWebRequest.html) module.

For a full list of changes and updates in this version, see the [ARCore XR Plug-in package changelog](xref:arcore-changelog).
