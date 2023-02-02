---
uid: arcore-upgrade-guide
---
# Upgrading to ARCore XR Plug-in version 5.0

To upgrade to ARCore XR Plug-in package version 5.0, you need to do the following:

- Use Unity 2021.2 or newer.
- `ARCoreXRDepthSubsystem` is now `ARCoreXRPointCloudSubsystem`.

**Use Unity 2021.2 or newer**

This version of the package requires Unity 2021.2 or newer.

**`ARCoreXRDepthSubsystem` is now `ARCoreXRPointCloudSubsystem`**

Due to the rename of `XRDepthSubsystem` to `XRPointCloudSubsystem` in the AR Foundation package, the ARCore provider implementation of the subsystem has been renamed from `ARCoreXRDepthSubsystem` to `ARCoreXRPointCloudSubsystem`. All the APIs within the implementation remain the same as before. This renamed shouldn't require any actions from most users of AR Foundation.
