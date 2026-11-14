# Changelog

## v1.0.0 — First public release (2026-11-14)

- Native **Converter** tab in Forge Neo with model and text encoder modes.
- Model conversion targets: NVFP4, FP8, MXFP8, INT8, INT8 ConvRot, INT4 ConvRot, W4A8 ConvRot, FP16 and FP32 (subject to installed comfy-kitchen support).
- Precision-protected text encoder conversions and architecture-aware model profiles.
- Forge Neo-compatible mixed precision metadata for converted safetensors.
- Scans model and encoder folders, including configured directories and junctions, with progress/error logs.
- Original implementation and model profiles adapted from the MIT-licensed Starnodes Model Converter.

> First tagged GitHub release of the existing Forge Neo Converter source. No changes to the conversion engine in this release preparation.
