# DxRBoilerplate
Platform-agnostic boilerplate of DxR visualization framework (https://sites.google.com/view/dxr-vis).

Within the DxR folder, UWP-specific functionality (e.g. only for HoloLens and other Microsoft headsets) has been blocked off within "#if UNITY_WSA_10_0" blocks such that you can compile your scenes to any target platform.

Note that this takes away the the HoloLens interactivity, but it allows you to make your own.
