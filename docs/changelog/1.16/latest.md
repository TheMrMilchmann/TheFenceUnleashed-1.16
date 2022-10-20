### 1.0.2-1.16.5-1.0

_Released 2022 Oct 20_

#### Requirements
- **MinecraftForge:** 1.16.5-36.2.2

#### Improvements

- Added an advancement to inform players about the mod. [[GH-4](https://github.com/TheMrMilchmann/TheFenceUnleashed/issues/4)]
    - The advancement is granted the first time a player walks through a fence
      gate.
    - The advancement grants two leads upon unlock to make it easier to get
      started with the mod.
- Changed the artifact base name to "TheFenceUnleashed" (from "Fency") to avoid
  potential confusion.

#### Fixes

- Added MineColonies' visitors (`minecolonies:visitor`) to the default allowlist.
    - This will only take effect for new installations. If you wish to whitelist
      MineColonies' citizens to an existing installation, you will still have to
      add the exception manually.
- Fixed a bug that caused carriage-return characters to be visible in the mod's
  description in some places.