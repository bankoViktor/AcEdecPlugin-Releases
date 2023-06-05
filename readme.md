# Release Notes

## [0.6.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.6.0.0) (2023-06-05)

### New Features
- Added command `NOTESGEN` for configure and drawing notes.


## [0.5.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.5.0.0) (2023-05-26)

### New Features
- Added command `GENERATORWALKINOL` for drawing one line walk-in generator symbol.

### Improvements
- Added note for stationary generator commponent.
- Added "Exernal SPD" option for service entrance rated transfer switches.

### Bug Fixes
- Increased the output power list (up to 2000kW) in stationary generator command `GENERATORSTATIONARYOL`.
- Changed cable label template (removed GND) for utility transformer.


## [0.4.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.4.0.0) (2023-05-20)

### New Features
- Added command `MTSNONSEROL` for drawing one line manual transfer switch symbol.
- Added command `ATSNONSEROL` for drawing one line automatic transfer switch symbol.
- Added command `ATSSEROL` for drawing one line service entrance rated automatic transfer switch symbol.
- Added command `NONATSNONSEROL` for drawing one line non-automatic transfer switch symbol.
- Added command `NONATSSEROL` for drawing one line service entrance rated non-automatic transfer switch symbol.
- Added `Reset` button for set to default values for properties in options window.
- Added command `UTILITYSPLICINGOL` for drawing one line utility splicing symbol.
- Added command `JUNCTIONBOXOL` for drawing one line junction box symbol.
- Added command `CONDULETOL` for drawing one line condulet symbol.
- Added command `WIREWAYOL` for drawing one line wireway symbol.
- Added command `MANHOLEOL` for drawing one line manhole symbol.
- Added command `HANDHOLEOL` for drawing one line handhole symbol.
- Added command `GENERATORSTATIONARYOL` for drawing one line stationary generator symbol (exclude notes).

### Improvements
- The insertion point for some components changed to convenience.
- Added CB ARC note for generic circuit breaker and main breaker component.

### Bug Fixes
- Fixed place SPD note for Automatic transfer switch (SER).


## [0.3.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.3.0.0) (2023-05-05)

### New Features
- Automatic check available update on startup AutoCAD.
- Added command `CIRCUITBREAKERSEOL` for drawing one line service entrance rated circuit breaker symbol.
- Added command `CIRCUITBREAKEROL` for drawing one line generic enclosed circuit breaker symbol.

### Improvements
- Updated dialog and details dialog.
- Updated Dry-Transformer detail.

### Bug Fixes
- Removed not implemented `WIRESCHEDULEROW` command.
- Fixed working `DEMOLITION` command on plugin created rectangles.
- Fixed company name to upper case in `UTILITYTFROL` command.


## [0.2.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.2.0.0) (2023-04-29)

### Bug Fixes
- Fixed error in creating line type in `WIRELABELFULL` command.


## [0.1.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.1.0.0) (2023-04-29)

### New Features
- Added command `EUPDATE` for check and download update.
- Added command `WIRELABELFULL` for drawing full cable label.
- Added command `WIRELABELREF` for drawing reference cable label.
- Added command `WIRESCHEDULE` for drawing cable schedule table.
- Added command `UTILITYTFROL` for drawing one line utility transformer symbol.
- Added command `DRYTFROL` for drawing one line dry-transformer symbol.
- Added command `DRYTFRDT` for drawing detail of dry-transformer.
- Added command `POWERMETEROL` for drawing one line power meter symbol.
- Added command `DEMOLITION` for drawing demolition area.
- Added command `NUMERATOR` for numeration `Text` and `MText` objects.
- Added command `SSSERVERPUBLISH` for publishing sheet set in the internal company server.
- Added command `TUTORIALCLUB` for opening window with links to tutorials.
