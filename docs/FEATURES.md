# REAX Feature Reference

This document summarizes the main capabilities available in the REAX editor (as reflected by the current product). The live app is the source of truth: https://reax.ndkdev.tech

## 1. Audio

- **Audio import**: load a track into the editor to drive visuals.
- **Frequency analysis**: real-time FFT-based analysis used for reactive visuals.
- **Band mapping**: visuals/effects can react to `bass`, `mids`, `highs`, or `all`.
- **Beat/kick response**: beat-aware behavior for supported visuals and scene effects.
- **Playback controls**: play/pause/seek/scrub workflow in the editor timeline.
- **Trim**: audio trimming for preview/export workflow.
- **Playback rate**: slowed playback controls (preview/export behavior supported in the app).

## 2. Visualizer & wave layers

- **Visualizer layer** with multiple styles/modes, including:
  - Circular / radial bars
  - Spectrum
  - Waveform
  - Dual mirror
  - Square bars
  - Orbit-style visuals
- **Radial Wave layer**:
  - Multiple configurable wave parameters (shape, amplitude, radius, thickness, color/gradient, smoothing, symmetry, direction/rotation, glow, band/sensitivity and related controls)
  - Designed for audio-reactive circular/wave compositions

## 3. Particles

- Particle layers with presets/modes for ambient and reactive motion (e.g. dust/stars/sparks/glow/vortex-style behaviors depending on preset/config).
- Audio-reactive and beat-influenced particle behavior where supported.

## 4. Image, text, shape, and background

- **Image layers**: place artwork/covers and compose with other layers.
- **Image visualizer overlays** (app-supported modes include bottom bars and other reactive overlay options).
- **Text layers**: titles/labels for compositions.
- **Shape layers**: geometric elements for layout and accents.
- **Background/composition controls**: scene background and canvas composition settings.

## 5. Layer system & editing

- Add/remove/select layers
- Reorder layers (z-order / stack)
- Toggle visibility and edit layer properties
- Transform controls (position/scale/rotation and layout-related adjustments)
- Per-layer configuration for appearance and audio reaction

## 6. Timeline & project workflow

- Timeline-based editing with playback head and scrubbing
- Clip timing/trim controls
- Project settings (canvas/composition settings exposed in editor)
- Templates/presets for quick starts
- Local saved projects in browser storage (as supported by the app)

## 7. Effects & beat-reactive scene controls

- Beat-reactive canvas/scene effects (e.g. blur, shake, punch)
- Mirror/static mirror-related modes (as available)
- Timing/sync tuning controls (offset/duration/sensitivity/source options where exposed)
- Composition/post-style adjustments supported by the editor

## 8. Export

- Export music videos from the REAX studio workflow.
- Local/browser-based export pipeline (implementation details may change; see live app).

## 9. Platform notes

- Runs in modern browsers.
- Local-first workflow for editing/rendering in the browser (no guarantee stated here about every environment/device; behavior depends on browser capabilities).
