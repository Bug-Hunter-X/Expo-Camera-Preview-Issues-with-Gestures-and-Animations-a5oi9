# Expo Camera Preview Bug

This repository demonstrates a bug in Expo's Camera API where the preview freezes or shows corrupted frames when used with simultaneous UI animations or gestures. The issue is more prominent on lower-end devices.

## Bug Description

When interacting with the UI, particularly with gestures or animations, the camera preview may stop updating correctly, displaying frozen frames or visual artifacts. This severely impacts the user experience.

## Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Interact with the UI elements.  Observe the camera preview for freezing or corruption during animations.

## Solution

A potential workaround is to optimize animations, reduce UI complexity, and consider using requestAnimationFrame for smoother updates.  Further investigation and possible improvements to Expo's Camera API might be necessary for a complete fix.