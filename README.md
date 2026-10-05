# Borderlands 3 VR — DLSS / DLAA / Neural — v0.9

Adds an external OpenXR overlay with synchronized controls, independent OpenXR output resolution, and complete OFXR Classic / Djules75 settings.

- Open the overlay with F10 or the two-handed controller gesture.
- Apply, Apply and save, and Discard controls shared with the UEVR panel.
- Classic 2X and Djules75 2X/3X frame generation options. OFXR changes require restarting the game.
- Private runtime dependencies extracted automatically.
- Based on the accepted renderer, preserving the existing HUD and hand controls.

## Requirements

Official [UEVR Nightly 01143](https://github.com/praydog/UEVR-nightly/releases/tag/nightly-01143-4ee5c6b6162dee2291fc75f9dfc57667f6d45a2d), revision `4ee5c6b6162dee2291fc75f9dfc57667f6d45a2d`; DirectX 11, OpenXR, Native Stereo and Native Stereo Fix off. The complete Borderlands 3 profile is included.

Windows x64 and [Microsoft Visual C++ Redistributable x64](https://aka.ms/vc14/vc_redist.x64.exe) are required. This plugin targets Steam build `15245523`, with `Borderlands3.exe` SHA256 `923AFD263631681AFF88037ADD504BF353FC6F4CAA9045CFDB709E049FE4F101`. Other game executables are rejected by the plugin's identity check.

**Microsoft Edge is required only for the custom external overlay. It runs headlessly, without opening a browser window. The rendering features and the UEVR panel do not require Edge.**

## Installation

**[Download the complete Borderlands3.zip](https://github.com/Beren5556/B3VRDLSS-Downloads/releases/download/v0.9/Borderlands3.zip). Keep that exact filename for UEVR Import Config.**

With the game and UEVR closed, keep the previous profile outside `UnrealVRMod` as a backup. Use UEVR **Import Config** to import `Borderlands3.zip` into a clean profile. Configuration, CVars, controller bindings, HUD/hand attachments, runtime scripts, OpenHotfixLoader/hotfix and the DLSS plugin are included. No previous profile or private repository is required. Inject at your usual working point. F10 opens the custom overlay.

The corrected 0.9 package includes the overlay manifest and layer DLL before first injection, so the layer can be registered on the first launch. The rendering plugin remains unchanged.

The download contains the complete executable profile and third-party notices. Its private runtime dependencies are embedded and extracted automatically. UEVR, the game, drivers, saves, logs and development sources are not included. Buildable project sources, SDKs, tests and technical evidence stay in the private repository. HF8 is excluded.

## Third-party components

This is a community integration, not an official NVIDIA DLSS 5 product. The Neural mode uses the existing community pipeline. Included dependencies retain their licenses; see the notices in the download. The NVIDIA optical-flow driver is supplied by the installed display driver.
