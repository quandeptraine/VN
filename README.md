# Farm Việt V12 iOS

V12 is a SpriteKit + SwiftUI farming game prototype for iPhone/iPad.

Features:
- Large pixel-art farm map
- 30 crop plots with growth
- Character movement and virtual joystick
- NPCs and pets
- Fishing: cast, bite, jerk, reel
- Farm / Village / Market / Fishing / Forest area portals
- Inventory, shop, energy and save
- Day/night mode
- GitHub Actions workflow that builds an unsigned iOS IPA

The workflow copies source/assets into the generated `FarmViet/` resource directory and creates compatibility aliases for animation frames referenced by the Xcode project.
