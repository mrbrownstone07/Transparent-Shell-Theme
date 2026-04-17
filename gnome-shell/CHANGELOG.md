# Changelog

All notable changes to the Transparent GNOME Shell theme will be documented in this file.

## [2026-04-11] - Sonoma Modernist Refinements

### Added
- New design specification for "Sonoma Modernist" UI, focusing on modular cards and frosted glass materials.
- Formal implementation plan for Sonoma Modernist transition.

### Changed
- **Standardized UI Materials:** Updated background, hover, and focus colors across the shell to match the macOS-inspired Sonoma Modernist palette.
  - Normal Background: `rgba(25, 25, 25, 0.65)` (Deep Black Glass)
  - Hover Background: `rgba(217, 217, 217, 0.08)`
  - Focus Background: `rgba(27, 27, 27, 0.65)`
- **Shadows & Depth:** Implemented a multi-layered macOS-style shadow system for better visual hierarchy and depth.
  - Popovers: Dual-layer ambient and direct shadows (`0 10px 40px rgba(0, 0, 0, 0.25), 0 2px 10px rgba(0, 0, 0, 0.1)`).
  - Modular Cards: Subtle 12px lifting shadows for internal containers like the Calendar and Widgets.
- **Quick Settings:** Updated toggles and icon buttons with new standardized colors, refined focus shadows, and a soft white glow for active states.
- **Calendar & Date Menu:**
  - Applied standardized background and lifting shadows to the main calendar container and its interactive elements.
  - Updated Weather, World Clocks, and Events buttons with matching frosted glass effects and refined shadows.
- **Notifications:** Standardized message card backgrounds, hover states, and shadows for consistency with the rest of the UI.
- **Typography & Spacing:** Adjusted transitions (standardized to 200ms) and padding in several components to improve visual "breathing room."

### Fixed
- Corrected typo in CSS selector for `.world-clocks-button:active`.
- Resolved inconsistent focus shadow weights across different interactive elements.
