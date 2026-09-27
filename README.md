# AR Furniture Placement App

## Overview
A native Android application that lets users visualize furniture in their own space before buying it. Using ARCore, the app places 3D furniture models directly into a live camera view of the user's room, at true-to-life scale — so they can judge fit, proportion, and style before committing to a purchase.

## Features
- Real-time AR scene rendering powered by ARCore
- Furniture models placed as nodes within the AR scene, anchored to detected real-world surfaces
- True-to-scale visualization — walk around and view the virtual object from multiple angles, just like the real piece
- Built natively on Android for smooth, responsive AR performance

## Tech Stack
- **Language:** Java
- **AR Engine:** ARCore (motion tracking, surface/plane detection, scene graph nodes)
- **Build System:** Gradle
- **UI:** XML layouts

## How It Works
ARCore handles environmental understanding — detecting flat surfaces like floors and tabletops through the device camera. Furniture models are attached to anchor nodes within the AR scene graph and rendered at real-world scale, so the object behaves as if it were physically present in the room as the camera moves.

## Setup
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle
4. Run on an ARCore-supported Android device

## Future Improvements
- Support for a larger furniture catalog
- Save/share AR previews
- Multi-object placement in a single scene
