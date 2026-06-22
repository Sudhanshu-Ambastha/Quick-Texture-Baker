# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2026-06-22

### Changed

- **Blender 5.1+ Compatibility**: Fully refactored for the latest Blender API.
- **API Cleanup**: Removed deprecated `material.use_nodes` property; the add-on now relies on modern node-tree handling as the default standard.
- **Robustness**: Added material node-tree existence checks to prevent runtime errors during texture creation.
- **Version Metadata**: Updated `bl_info` to target Blender 5.1.2.0.

## [1.0.0] - 2025-11-01

### Added

- **Core Automation**: Initial implementation of the "Quick Texture Baker" system.
- **Texture Node Management**: Automated creation of `ShaderNodeTexImage` nodes with integrated naming logic and automatic image buffer allocation (1024x1024).
- **Baking Pipeline**: Integrated `bpy.ops.object.bake` with automatic engine switching to Cycles and preset configuration for Diffuse-only passes.
- **UI/UX**: Custom panel implementation in the 3D Viewport sidebar (`Shader Editor > Sidebar > Quick Texture Baker`) for simplified one-click workflows.
- **Safety Features**: Integrated basic error handling for active object selection, mesh validation, and material verification.
