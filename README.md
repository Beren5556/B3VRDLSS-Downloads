# Borderlands 3 VR — DLSS / DLAA / Neural — v0.9

Adds an external OpenXR overlay with synchronized controls, independent OpenXR output resolution, and complete OFXR Classic / Djules75 settings.

- Open the overlay with F10 or the two-handed controller gesture.
- Apply, Apply and save, and Discard controls shared with the UEVR panel.
- Classic 2X and Djules75 2X/3X frame generation options. OFXR changes require restarting the game.
- Private runtime dependencies extracted automatically.
- Based on the accepted renderer, preserving the existing HUD and hand controls.

## Requirements

Official [UEVR Nightly 01143](https://github.com/praydog/UEVR-nightly/releases/tag/nightly-01143-4ee5c6b6162dee2291fc75f9dfc57667f6d45a2d), revision `4ee5c6b6162dee2291fc75f9dfc57667f6d45a2d`; DirectX 11, OpenXR, Native Stereo, Native Stereo Fix off, and an existing compatible Borderlands 3 UEVR profile.

**Microsoft Edge is required only for the custom external overlay. It runs headlessly, without opening a browser window. The rendering features and the UEVR panel do not require Edge.**

## Installation

Back up your existing profile with the game and UEVR closed. Extract the executable package and copy `plugins/B3_Observer.dll` to the `plugins` directory of your Borderlands 3 profile. Inject at your usual working point. F10 opens the overlay.

The download contains the executable plugin and third-party notices. Its private dependencies are embedded and extracted automatically. UEVR, the game, drivers and a personal profile are not included. Source code and personal profiles are kept private. HF8 is excluded.

## Third-party components

This is a community integration, not an official NVIDIA DLSS 5 product. The Neural mode uses the existing community pipeline. Included dependencies retain their licenses; see the notices in the download. The NVIDIA optical-flow driver is supplied by the installed display driver.
