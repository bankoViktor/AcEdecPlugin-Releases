# Release Notes

## [0.10.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.10.0.0) (2023-09-21)

### New Features
- Added command `GNDOL` for drawing Ground Ring/Triangle one line symbol.

### Improvements
- The Generator command for the site plan has been completed.

### Bug Fixes
- Added Underground Duct Banks title to the `DBGRADE` command.
- Fixed wrong layer for site plan symbols.
- Fixed site plan descriptions of symbols.


## [0.9.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.9.0.0) (2023-09-15)

### New Features
- Added new tutorial video: Принципы и основы подшивки проекта - Теория.
- Added warning message to the Power Meter one line symbol: 'For In Line ≤ 300A and for With CT's > 300A'.
- Added warning message to the Mini-Panelboard SER one line symbol: 'MB ≤ 600A, Branch CB ≤ 225A'.
- Added command `POWERMETERSP` for drawing Power meter site plan symbol.
- Added command `DRYTFRSP` for drawing Dry-Transformer site plan symbol.
- Added command `MINIPOWERZONESP` for drawing Mini-Power Zone site plan symbol.
- Added command `PANELBOARDSP` for drawing Panelboard site plan symbol.
- Added command `CIRCUITBREAKERSERSP` for drawing Circuit Breaker SER site plan symbol.
- Added command `CIRCUITBREAKERSP` for drawing Circuit Breaker site plan symbol.
- Added command `MTSSP` for drawing MTS site plan symbol.
- Added command `ATSSP` for drawing ATS site plan symbol.
- Added command `ATSSERSP` for drawing ATS SER site plan symbol.
- Added command `NONATSSP` for drawing Non-ATS site plan symbol.
- Added command `NONATSSERSP` for drawing Non-ATS SER site plan symbol.
- Added command `JUNCTIONBOXSP` for drawing Junction Box site plan symbol.
- Added command `WEATHERHEAD` for drawing Weatherhead site plan symbol.
- Added command `MANHOLESP` for drawing Manhole site plan symbol.
- Added command `HANDHOLESP` for drawing Handhole site plan symbol.
- Added command `HANDHOLEDT` for drawing Handhole Detail site plan symbol.
- Added command `WIREWAYSP` for drawing Wire Way site plan symbol.
- Added command `SPDSP` for drawing SPD site plan symbol.
- Added command `DBLINE` for drawing Duck Bank line for site plan.
- Added command `DBGRADE` for drawing Duck Bank Grade symbol.
- Added command `DBCONDUIT` for drawing Duck Bank Conduit symbols.
- Added command `DBTEXT` for drawing Duck Bank Template text.
- Added command `DBLEGEND` for drawing Duck Bank Legend symbol.
- Added command `GENERATORSTATIONARYSP` for drawing Stationary Generator site plan symbol (BETA).
- Added 16 reference pictures.

### Improvements
- Changed Circuit Breaker (One Line) command: `CIRCUITBREAKERSEOL` to `CIRCUITBREAKERSEROL`.
- Chagned Mini-Panelboard (One Line) command: `MINIPANELBOARDSEOL` to `MINIPANELBOARDSEROL`.
- Chagned ATS (One Line) command: ATSNONSEROL to `ATSOL`.
- Chagned Non-ATS (One Line) command: `NONATSNONSEROL` to `NONATSOL`.
- Chagned MTS (One Line) command: `MTSNONSEROL` to `MTSOL`.
- Added orthogonal mode for Area mode of Demolition tool.
- Added Polyline mode of Demolition tool.
- Changed NEMA rating lists.
- Changed notes list marker to "Xn".

### Bug Fixes
- Removed the GND conductor for input of the Main Breaker one line symbol.
- Changed the pole number (1PH -> 2P and 3PH -> 3P) for the Panelboard one line symbol.
- Fixed wrong drawing previews of tutorial videos and pictures.
- Fixed title of option windows.
- Chagned the signal name to 'ATS IN EMERGENCY POSITION' in generators note.
- Fixed tutorial window layout items.


## [0.8.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.8.0.0) (2023-08-15)

### New Features
- Added new tutorial video: Что такое измерительные инструменты и для чего они нужны? #1.
- Added site plan symbol for Utility transformer.

### Improvements
- Fixed back moving of view when a command canceled.
- Changed notes list marker to number.
- Changed default cable label to 'X #X & 1 #X GND IN X" C.'.
- Added AIC value to the Mini-Power zone one line symbol.
- Chagned row vertical align to left middle for schedule table.
- Changed other line type for Main Breaker SER and Mini-Panelboard SER one line symbols.
- Added detail label for Mini-Power zone component.

### Bug Fixes
- Chagned SER specification on 'SERVICE ENTRANCE RATED' for Main breaker (SER) and Mini-Panelboard (SER).
- Removed double 'SERVICE ENTRANCE RATED' specification for Mini-Panelboard (SER).
- Changed color for a note reference for utility transformer.
- Fixed the syntax error in the note row in the Mini-Power zone schedule.
- Added dot for Mini-Panelboard like 'CKT.'.
- Fixed memory leak for MText in MLeader.
- Fixed aborting the active placement command.
- Fixed cell align for panelboard schedule.


## [0.7.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.7.0.0) (2023-07-11)

### New Features
- Added command `MINIPOWERZONEOL` for drawing one line mini-power zone symbol.
- Added command `MINIPANELBOARDOL` for drawing one line mini panelboard symbol.
- Added command `MINIPANELBOARDSEOL` for drawing one line service entrance rated mini panelboard symbol.

### Improvements
- Changed generators notes.
- Changed text height to 0.1" for generators legend.
- Removed '(BY GEN. VENDOR)' for existing walk-in generator symbol.
- Appended signal descriptions for existing stationary generator symbol.
- Appended signal descriptions for existing transfer switch symbols.

### Bug Fixes
- Fixed memory leak for unmanaged objects.
- Fixed SPD model prefix to 'CAT#: '.
- Fixed formatting power lines description.
- Removed '(NOTE X)' for existing utility transformer.
- Fixed SPD cable label on 'EXISTING CABLES/CONDUIT' in ATS-SER and MB-SER components.


## [0.6.1.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.6.1.0) (2023-06-06)

### Bug Fixes
- Fixed error drawing secondary graphics.


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
