1 Tick Flick Overhead Fix - Change Summary

This update adds a selectable visual style for the timing bar while preserving the original click tracking and combo logic.

Included changes:
- Added a Style config option with Original and RuneLite choices.
- Original style renders as a movable/resizable screen overlay.
- RuneLite style renders over the player using RuneLite PrayerBarOverlay positioning and dimensions.
- Added separate Original Style and RuneLite Style config sections.
- Kept the combo counter as its own movable overlay with configurable text, size, opacity, and color.
- Preserved quick-prayer orb click tracking and optional prayer book click tracking.

Key files:
- OneTickFlickPlugin.java
- OneTickFlickConfig.java
- OneTickFlickOverlay.java
- OneTickFlickOriginalOverlay.java
- OneTickFlickComboOverlay.java
- OneTickFlickBarStyle.java
