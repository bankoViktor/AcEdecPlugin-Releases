# Release Notes

## [0.18.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.18.0.0) (2024-03-04)

### New Features
- Added command `RTUOL` for drawing Remote Terminal Unit (RTU) one line symbol.
- Added command `RTUSP` for drawing Remote Terminal Unit (RTU) site plan symbol.
- Added command `MATERIALSET` for drawing Material Schedule set.
- Added internal RTU option for Pump Control Panel (Lift Station) one line symbol.

### Improvements
- Changed Junction Box one line note.
- Renamed note category name 'GENERAL|TREATMENT PLANT|REQUIRED' to 'GENERAL|FOR MATERIAL SCHEDULE|..'.
- Renamed note category name '..|REQUIRE' to '..|REQUIRED'.
- Added note item 'ONE (1) 480V, 20A, 3P CIRCUIT BREAKER FOR ELECTRIC CRANE' to Pump Control Panel one line symbol.
- Added 'TRANSFORMER CONCRETE PAD' leader to Utility Transformer site plan symbol.

### Bug Fixes
- Fixed scale format for 'SIZE PLAN' to '1/16" - 1'-0"'.
- Fixed note numbers for Motion Sensor and Time Delay Switch for Security Light site plan symbol.
- Fixed duplicate notes for Motion Sensor and Time Delay Switch for Security Light site plan symbol.
- Fixed synt. errors in Security Light Wooden Pole Detail.
- Fixed site plan Utility Transformer leader to 'PAD MOUNTED UTILITY TRANSFORMER (NOTE X1)'.


## [0.17.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.17.0.0) (2024-02-12)

### New Features
- Added command `WETWELLVAULTOL` for drawing one line hazardous areas.
- Added command `WETWELLVAULTSP` for drawing one line leaders and labels.
- Added command `SUBMERSIBLEPUMPSP` for drawing Submersible Pump site plan symbol.
- Added command `PRESSURETRANSDUCERSP` for drawing Submersible Pressure Transducer site plan symbol.
- Added command `BACKUPFLOATSWITCHSP` for drawing Back-Up Level Float Switch site plan symbol.
- Added command `EQUIPRACK` for drawing Equipment Rack site plan symbol.
- Added command `FLOWMETEROL` for drawing Magnetic Flow Meter one line symbol.
- Added command `FLOWMETERSP` for drawing Magnetic Flow Meter site plan symbol.
- Added command `LEVELSENSORPROBEOL` for drawing Level Sensor Probe one line symbol.
- Added command `LEVELSENSORPROBESP` for drawing Level Sensor Probe site plan symbol.
- Added command `SECURITYLIGHTOL` for drawing Security Light one line symbol.
- Added command `SECURITYLIGHTSP` for drawing Security Light site plan symbol.
- Added command `FLOATSWITCHOL` for drawing Level Float Switches one line symbol.
- Added command `FLOATSWITCHSP` for drawing Level Float Switches site plan symbol.
- Added detail steps to site plan generator command: Bonding Lugs and Plates, Ground Test Well and Generator Grounding.
- Added note and details steps to site plan Duck bank line command.

### Improvements
- Added 4 pole item to all one line disconnect switches.
- Made lower case of list values for option window.
- Added 'SURGE PROTECTION DEVICE' item to one line Pump Control Panel note.
- Added 'Internal Space Heater' option in one line MCC and Switchboard.
- Changed test ground well leader text to 'PROVIDE ONE (1) TEST GROUND WELL'.
- Added units to 'Output Power' of generators.
- Added 'BACKUP' to Back-Up Level Float Switch one line symbol.
- Changed DB line thickness to 0.1 inch for Site Plan symbol.
- Made 'VFD' and 'VFD Advanced' options to one line Motor Starter.
- Added 'ONE LINE DIAGRAM' label as 4th step to Utility Transformer one line symbol.
- Updated 'Submersible Cable Anchors' installation detail.

### Bug Fixes
- Fixed syntax errors in one line Pump Control Panel note.
- Added '(' and ')' to motor (DUTY/STAND-BY) one line symbol.
- Cable label for existing Back-Up Level Float Switch one line symbol.
- Fixed "3CT's" for Switchboard and Motor Control Center one line symbols.


## [0.16.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.16.0.0) (2024-01-16)

### New Features
- Added "smart" MCC rectangle.
- Added `PRESSURETRANSDUCEROL` to Pressure Transducer one line symbol.
- Added `BACKUPFLOATSWITCHOL` to Back-Up Float Switch one line symbol.
- Added `GENERATORRESEPTACLESP` to Portable Generator Receptacle site plan symbol.
- Added `GENERATORCAMLOCKBOXSP` to Generator Cam Lock Connection Box site plan symbol.
- Added 'Minimum Size Equipment Grounding' tutorial image.

### Improvements
- Changed 'SS' to 'STAINLESS STEEL' in PCP note.
- Changed VFD item in PCP note.
- Changed VFD symbol (in/out phase) for PCP one line symbol.
- Changed DB legend line thickness to 0.1 inch.

### Bug Fixes
- Handhole installation detail title.
- Lift Station pump Seal-Off note.
- Lift Station Pump Control Panel site plan symbol.
- Fixed wire of 'E' (Emergency) terminal in Manual Transfer Switch one line.
- Fixed refer panelboard schedule text position in Panelboard Mini one line.
- Fixed Detail Lable block references.


## [0.15.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.15.0.0) (2023-12-28)

### New Features
- Added `MCC_CB` to MCC circuit breaker one line symbol.
- Added `MCC_FVNR` to MCC FVNR-starter one line symbol.
- Added `MCC_FVR` to MCC FVR-starter one line symbol.
- Added `MCC_RVSS` to MCC RVSS one line symbol.
- Added `MCC_VFD` to MCC VFD one line symbol.

### Improvements
- Added 'DUTY/STAND-BY' to Submersible Pump one line symbol.
- Added parameters to Submersible Pump one line symbol and details.
- Changed NEMA 'SS' to 'STAINLESS STEEL' for CB/MB/MTS/ATS/NON-ATS.
- Changed one line generator note.
- Removed amps of main circuit breaker in generator note.
- Changed one line note for Pump Contro Panel (Lift Station).
- Changed conductors label for transfer switches.
- Removed 'Is ..' in option label.

### Bug Fixes
- Fixed note of Pump Control Panel for Lift Station.
- Fixed low case for main device title in panelboard one line symbols.


## [0.14.2.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.14.2.0) (2023-12-20)

### Improvements
- Added description 'DENOTES EQUIPMENT WILL BE BACKED UP BY GENERATOR' to generator legend.
- Aligned generator legend by left bottom corner (base point).

### Bug Fixes
- Fixed huge text for some components.


## [0.14.1.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.14.1.0) (2023-12-15)

### Bug Fixes
- Swapped generator legend items.


## [0.14.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.14.0.0) (2023-12-12)

### New Features
- Added command `GNDSP` for drawing Triangle Grounding one line symbol.
- Added command `SWITCHBOARDOL` for drawing Switchboard one line symbol.
- Added command `MOTORCONTROLCENTEROL` for drawing Motor Control Center one line symbol.
- Added command `PUMPCONTROLPANELOL` for drawing Pump Control Panel one line symbol.
- Added command `PUMPCONTROLPANELSP` for drawing Pump Control Panel site plan symbol.
- Added command `SUBMERSIBLEPUMPOL` for drawing Submersible Pump one line symbol.
- Added command `GENERATORRESEPTACLEOL` for drawing Portable Generator Receptacle one line symbol.
- Added command `GENERATORCAMLOCKBOXOL` for drawing Generator Cam Lock Receptacle one line symbol.

### Improvements
- Changed Duct Bank linetypes to: direct, conctete and reinforced concrete.
- Added new DB linetypes to command `DBLINE`.
- Added 36 notes to the note generator.

### Bug Fixes
- Added 'V' letter after voltages for Dry-Transformer one line symbol.
- Fixed default value of NEMA rating to '3X SS' for Mini-Panelboard one line symbol.
- Added refer to note to leader for Manhole site plan symbol.


## [0.13.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.13.0.0) (2023-10-25)

### New Features
- Added command `PULLBOXOL` for drawing Pull Box one line symbol.
- Added command `PULLBOXSP` for drawing Pull Box site plan symbol.

### Improvements
- Added 'FLC' reference property for Motor one line symbol.
- Changed publish files name (.PDF) to 'XXXXX_NN', where XXXXX - a project number and NN - ordered number.
- Replaced local color to layer color for existing schedules tables.

### Bug Fixes
- Added reference cable label for Motor one line symbol.
- Removed 'MANUAL' drop-down menu item of 'Horsepower' property for Motor one line symbol, if the phase quantity is not defined.


## [0.12.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.12.0.0) (2023-10-24)

### New Features
- Added command `MOTORSTARTEROL` for drawing Enclosed Motor Starter one line symbol.
- Added command `CONTROLPANELOL` for drawing Control Panel one line symbol.
- Added command `DISCONNECTSWITCHOL` for drawing Disconnec Switch one line symbol.
- Added command `DISCONNECTSWITCHFUSEOL` for drawing Disconnec Switch Fuse one line symbol.
- Added command `MOTOROL` for drawing Motor one line symbol.

### Improvements
- Added 360 notes to the note generator.
- Added CB notes for generators.
- Added spaces for generators one line symbols.
- Added demolition legend command to one line ribbon tab.

### Bug Fixes
- Replace NEMA rating value "3R SS" to "4X SS" for panelboards.


## [0.11.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.11.0.0) (2023-10-12)

### New Features
- Added command `DEMOLITIONLEGEND` for drawing Demolition Legend symbol.
- Added command `PANELBOARDOL` for drawing Panelboard one line symbol.

### Improvements
- The number of rod wells set to red color for generator note.
- Moved origin point for Duct Bank legend.
- Added disappearance the 'Main Breaker Size' property for the 'Main Device' property equal 'MLO' for Mini-Panelboard component.

### Bug Fixes
- Fixed color entities for the `DBLEGEND` command.
- Changed the pole number (1PH -> 2P and 3PH -> 3P) for the Panelboard SER and Mini-Power Zone one line symbol.
- Fixed AIC value for the Panelboard, Panelboard SER and Mini-Power Zone one line symbol.
- Swaped schedule table values 'Voltage (L-N)' and 'Voltage (L-L)' of properties for Mini-Power Zone one line symbol.
- Fixed layout of the Detail block reference.


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
