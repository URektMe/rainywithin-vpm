# Rainywithin's VPM Repository

This is a VRChat Creator Companion (VCC) repository hosting custom Unity Editor tools and avatar utilities.

### How to Install
Click the button below to automatically add this repository to your VCC:

[![Add to VCC](https://img.shields.io/badge/VCC-Add%20to%20VCC-0b5c5c.svg?style=for-the-badge)](https://urektme.github.io/rainywithin-vpm/)

### Included Packages

* **Auto-Save:** Prevents lost work by intercepting modifications to unsaved/untitled scenes (like dragging in prefabs) to force a save-and-name prompt, followed by configurable background auto-saving at custom intervals.
* **Outfit Linker:** A Unity Editor tool that automatically generates VRCFury toggles, organizes meshes, and seamlessly links modular avatar outfits to your base armature without destructive hierarchy changes.
* **Hair Linker:** Streamlines avatar customization by automatically generating VRCFury toggles and linking new hair assets directly to your avatar's head and physics bones.
* **Optimizer Tools:** A comprehensive, lazy-friendly suite for avatar performance optimization, containing three core modules:
  * **Poly Reducer:** Scans your avatar hierarchy and integrates with Meshia to safely decimate polygons and reduce overall mesh complexity.
  * **1-Click Optimizer:** Automatically configures d4rkAvatarOptimizer and Anatawa12's AvatarOptimizer (AAO) for maximum draw-call reduction, unused bone removal, and mesh merging.
  * **VRAM Evaluator:** A standalone scanner that calculates exact texture VRAM usage, recommends optimal bit-depth formats (like DXT1 vs BC7), and safely crunches textures to reduce download size using a JSON-backed backup system.
