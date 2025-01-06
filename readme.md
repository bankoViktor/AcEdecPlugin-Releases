![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/bankoViktor/AcEdecPlugin-Releases/total?style=for-the-badge) ![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/bankoViktor/AcEdecPlugin-Releases/latest/total?style=for-the-badge)

# Release Notes

## [0.30.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.30.0.0) (2025-01-06)

### New Features
- Added line types: Lightning Protection and Exposed Grounding.
- Added note for Manual, Automatic and Non-Automatic Transfer Switch symbols for one line diagram.
- Added command `MOTORSYMBOLSWD` for drawing Motor Symbols for Wiring Diagram.

### Improvements
- Changed 'feet-inch' format for Classified Area for site plan graphics.
- Changed 50' to 4'-2" for Grounding of Material Set note.
- Added 'Remote Commination' parameter to SCADA Panel for wiring diagram.
- Added 'Modifications' parameter for notes Remote Telemetry Unit symbols.
- Aligned wire line length for Submersible Pump, Level Pressure Transducer and Level Float Switches symbols for one line diagram.

### Bug Fixes
- Fixed ethernet wire length for Wiring Diagram.
- Fixed unnecessary equipment for Motor for Wiring Diagram.
- Fixed empty lines for Material notes.
- Fixed red color cell for Material Set tables.
- Removed 'Low Fuel Level Alarm' signal for natural gas Stationary Generator one line symbol.
- Fixed internal RTU note number for Lift Station Pump Control Panel for one line diagram.
- Fixed CB position in MCC, Full Panelboard and Switchboard for one line diagram.


## [0.29.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.29.0.0) (2024-12-19)

### New Features
- Added command `DETAILLABELMED` for drawing Detail Label block for Elementary Diagram.
- Added command `MOTORWD` for drawing Motor for wiring diagram.
- Added symbols: overload, transformer to Elementary Diagram symbols block.
- Added symbol time delay relay to Elementary Diagram time delay symbols block.
- Added 'Vfd Shielded Cable' parameter for Power Wiring.

### Improvements
- Added 'INCLUDE FEED THROUGH LUGS' for Main Lugs Only to Mini Panelboard scheudles.
- Added block real dimensions for Disconnect Switches for site plan.

### Bug Fixes
- Fixed '2-runs of ...' wiring label if motor horsepower more or equals 100, for the Motor and the Lift Station Motor for one line.
- Removed Low Fuel Level signal for Natural Gas generator note.
- Fixed Dry Transformer sizes for site plan.
- Fixed position of 'Dimensions' parameter for Disconnect Switch SER for site plan.


## [0.28.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.28.0.0) (2024-11-07)

### New Features
- Added command `SWITCHESWD` for drawing Switches for wiring diagram.
- Added command `FITMAGNETICWD` for drawing Magnetic Flow Meter for wiring diagram.
- Added command `FITVENTURIWD` for drawing Venturi Flow Meter for wiring diagram.
- Added schematic wiring diagram detail label to second step of Legend of the wiring diagram.
- Added command `EQUIPMENTSP` to site plan.
- Added command `CONCRETEBOLLARDSP` for drawing Concrete Bollard for site plan.
- Added new 'MOTOR ELEMENTARY DIAGRAM' tab to the ribbon.
- Added command `SYMBOLSMED` for drawing symbol block for Motor elementary diagram.
- Added command `TIMEDELAYSYMBOLSMED` for drawing Time Delay symbol block for Motor elementary diagram.
- Added command `SENSORSYMBOLSWD` for drawing Sensor and Switches symbol block for Wiring diagram.
- Added command `INPUTSYMBOLSWD` for drawing Button and Toggle switches symbol block for Wiring diagram.

### Improvements
- Added colored conduit size for Power Wiring command.
- Added 'POWER' text (for power source side) and set the CB text right aling for power connection when powered by Control Panel.
- Changed process description placeholder text.
- Added MPZ power source option to Power Wirings.
- Renamed bus material option name Cuprum to Copper.
- Added vertical lines (on defpoint layer) to Junction Box block for wiring diagram.
- Added update polyline color per gray color changed.
- Added 'AS PER MATERIALS SCHEDULE ON DWG. E-XXX' option to the Equipment Rack Installation Details.
- Added notes 2, 3 and 4 to the 'INSTRUMENTATION AND CONTROLS', note 12 to 'GENERAL', and changed notes 13
and 14 in 'POWER DISTRIBUTION AND CONDUITS INSTALLATION REQUIREMENTS' of the Material Schedule notes.
- Renamed Handhole to Underground Pull Box site plan command.
- Added 'Main #1' and 'Main #2' labels and double grounding connections to Motor Control Center and Switchboard site plan symbols.
- Changed Lighting Contactor Schematic, added pole contactor block.
- Added 'CEMENT BOLLARDS (TYPICAL FOR XX)' leader to Wetwell/Vault site plan command.
- Updated all wiring diagram to new blocks.
- Updated Schematic Wiring diagram of Ligting Contactor.

### Bug Fixes
- Fixed crash application on 0 of input and output quantity of Control and Signal wiring.
- Fixed reference label letter & number for Circuit Breaker (SER) and Disconnect Switch (SER) one line diagram.
- Fixed NEMA rating default value for Circuit Breaker (SER) one line diagram.
- Fixed the position of Ground Rods for Triangle Grounding command.
- Fixed wire line length for Control and Signal wiring commands.
- Fixed color of lights (to red) in Obstruction Lights Controller wiring diagram.
- Fixed parameter name to Deep for Equipment, Switchboard and MCC site plan commands.


## [0.27.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.27.0.0) (2024-10-18)

### Improvements
- Added 'Door Mounted' symbol to wiring diagram legend.
- Changed some icons.
- Changed Junction Box description for wiring diagram.
- Changed Terminal block to Terminal Bar block for Disconnect Switch for wiring diagram.
- Added wiring to Disconnect Switch for wiring diagram.
- Added units format `XX'-XX"` to some notes.
- Updated Equipment Rack installation details.
- Added process name brace to Control ans Signal wiring commands for wiring diagram.
- Added updating Gray color changing for Table entity.
- Remove spaces for transformer & generator descriptions.
- Update existing cable/conduit labels.
- Added 'Recomended Primary CB' and 'Recomended Secondary CB' parameters to Dry-Transformer one line symbols.
- Replaced Time Delay symbol for Security Light one line graphics.
- Added 'Break Line' parameter to Equipment of wiring diagram.
- Changed Security Light graphics for one line and site plan and details.
- Renamed "NEMA Rating" parameter to "Enclosure NEMA Rating" for MCC and Switchboard one line symbols.
- Added CB amperage for power source is Control Panel for Power Wiring.
- Added Normally Open and Normally Closed type for terminal dry contact for Wiring diagram.
- Added "Protocol' parameter to Ethernet Wiring.
- Added "Bus Material" parameter to Panelboards, Mini-Power Zone, Switchboard and Motor Control Center one line symbols.
- Added 'Drawout' parameter for ICCB for Switchboard one line symbol.
- Added 'Full Description' parameter for Disconnect Switch for wiring diagram.

### Bug Fixes
- Fixed highlight of cable size of non-power wiring label.
- Fixed wrong terminal name of shielded wire.
- Fixed Disconnect Switch tag and description for wiring diagram.
- Fixed Disconnect Switch height (with DS status contact) for wiring diagram.
- Fixed skip space in note for site plan Equipment Rack graphics (with concrete pad).
- Fixed position of wiring diagram of motion sensor & time delay for Security Light.
- Fixed units and errors in installation details.
- Fixed AIC Rating paramter names.
- Fixed drawout wires typeline in MCC one line symbol.
- Fixed overlay of Kirk-Key text and Power Meter text in MCC one line symbol.
- Fixed missed wire cross connection dot for 'Main Lugs Only' option in Switchboard and Motor Control Center one line symbols.
- Fixed notes for Switchboard and Motor Control Center one line symbols.
- Fixed swapped orientation of Receptacles one line symbol.
- Fixed drawout graphics for MCCB for Switchboard one line symbol.
- Fixed terminal type for Disconnect Switch for wiring diagram.
- Fixed wire quantity for Power Wiring.


## [0.26.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.26.0.0) (2024-10-08)

### New Features
- Added note ('SHELF SPARE VFD') to the note dictionary.
- Added "Lighting Recomendation" table to tutorial materials.
- Added command `LEGENDWD` for drawing Terminals Legend for wiring diagram.
- Added command `WIRINGCONTROLWD` for drawing Control Wiring for wiring diagram.
- Added command `WIRINGSIGNALWD` for drawing Signal Wiring for wiring diagram.
- Added command `WIRINGPOWERWD` for drawing Power Wiring for wiring diagram.
- Added command `WIRINGETHERNETWD` for drawing Ethernet Wiring for wiring diagram.
- Added command `WIRINGFIBEROPTICWD` for drawing Fiber Optic Wiring for wiring diagram.
- Added command `EQUIPMENTWD` for drawing Empty Equipment for wiring diagram.
- Added command `DISCONNECTSWITCHWD` for drawing Disconnect Switch wiring diagram.
- Added command `JUNCTIONBOXWD` for drawing Junction Box for wiring diagram.
- Added command `PLANTSCADAWD` for drawing Plant SCADA for wiring diagram.
- Added command `CONTROLPANELWD` for drawing Control Panel for wiring diagram.
- Added command `RTUWD` for drawing Remote Telemetry Unit for wiring diagram.
- Updating 'gray' color of entities in current space.

### Improvements
- Removed specific rod quantity and size wire in the Generator Grounding installation detail.
- Added note for existing Stationary and Walk-In Generators one line symbols and the note dictionary.
- Hide 'Enclosure Type' parameter for existing Stationary Generator one line symbol.
- Added note for existing non-relocated cellular Remote Telemetry Unit one line symbol.
- Fixed dimension values and add notes to Duct Bank installation details.
- Reworked "Cables Installation Coming From Classified Area" (Air Gap) installation detail.
- Separate notes for conduit air gap and separate conduit for signal cables.
- Updated "gray" elements in follow installation details:
	- Generator Grounding,
	- Equipment Rack,
	- Security Light Poles,
	- Security Light Pole Base,
	- Submersible Cable Anchors,
	- Submersible Pressure Transducer,
	- Storage Water Tank,
	- Dry Transformer and
	- Sun and Rain Hood.
- Continuous numeration of name of the output pdf-files, where comparing by name starting with `XXXXX_<YY>`, where: `XXXXX` - project number and `YY` - order number of the file, chars after `YY` no affect.
- Excluded sheets and subsets in sheetset which marked as 'don't plot', from plotting process via 'plot to server' command.
- Changed label FIT/SS and PIT/SS.
- Added dynamic block for Conductor/Conduit Schedule Table.
- Added 'Type' parameter with value 'Rows' for drawing Conductor/Conduit Schedule Table rows.
- Changed wire labels to 'VENDOR CABLE' and 'EXISTING CABLE(S)/CONDUIT(S)'.
- Changed Obstruction Light Controller wiring diagram detail.
- Changed Lighting Contactor wiring diagram detail.
- Changed Photo Cell with Motion Sensor wiring diagram detail.

### Bug Fixes
- Fixed errors in the notes dictionary.
- Added "EACH" to conductor label for Remote Telemetry Unit one line symbol.
- Fixed error in brand name of the Remote Telemetry Unit one line symbol.
- Fixed display error message.
- Fixed long insertion of "Bonding Lugs and Plates" installation detail.
- Fixed missed punctuation signs in Material Schedule Note.
- Fixed error in name of "Non-Reinforced Duct Bank" installation detail.
- Fixed leader text in Wetwell/Vault one line command.
- Fixed plotting to server error because the layout name in sheet set and layout name in drawing whith it reference, was diffrent.
- Fixed visibility the 'Main Circuit Breaker Size' paramerter in Mini-Panelboard one line symbol.
- Fixed MLO label for Mini-Panelboard one line symbol and Panelboard schedules.


## [0.25.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.25.0.0) (2024-08-10)

### New Features
- Added 'THE' to Material Schedule Note.
- Added command `CLASSIFIEDAREAOL` for drawing Classified Area one line symbols.
- Added command `CLASSIFIEDAREASP` for drawing Classified Area size plan symbols.

### Improvements
- Changed content of Wetwell/Vault one line and site plan symbols.
- Added note in Demolition Legend one line symbol.
- Changed note ([CITY], [COUNTY], [OWNER]) in 'GENERAL|FOR MATERIAL SCHEDULE|REQUIRED' category.
- Fixed 'SCOPE' note in 'GENERAL|FOR MATERIAL SCHEDULE|REQUIRED' category.
- Added part of about aluminum steps to generator notes.
- Added 'FROM/TO' additions for I/O's to the Remote Telemetry Unit notes.
- Added RTU brand 'High Tide Technoligies' to Remote Telemetry Unit and Lift Station Pump Control Panel one line symbols.
- Added RTU type 'Cellular (By Zile Technology)' to Remote Telemetry Unit and Lift Station Pump Control Panel one line symbols.
- Changed Aluminum Security Lighting Pole detail.

### Bug Fixes
- Fixed long time insertion of detail.
- Fixed graphics of the 'Bonding Lugs and Plates' detail.
- Fixed duplications notes for site plan commands.
- Fixed properties visible for Remote Telemetry Unit and Lift Station Pump Control Panel one line symbols.


## [0.24.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.24.0.0) (2024-07-26)

### New Features
- Added command `STORAGETANKINTERIORLIGHTS` for drawing Storage Tank Interior Lights site plan symbols.
- Added command `STORAGETANKLOGOLIGHTS` for drawing Storage Tank Logo Lights site plan symbols.
- Added command `GNDPIGTAILSP` for drawing Grounding Pigtail (for Future Grounding Connection) site plan symbols.
- Added command `STUBUP` for drawing Stub-Up symbol.
- Added command `LIGHTSYMBOLS` for drawing Light symbols.
- Added command `LINESSP` for drawing various line types.

### Improvements
- Added Grounding Pigtail (for Future Grounding) Connection symbol for Grounding Multi Tools.
- Removed float for activate alarm horn and strobe from Bypass one line Note.
- Fixed tag for Panelboard Full one line symbol.
- Changed motor tags Motor one line symbol.
- Removed material from the Submersible Pressure Transducer installation detail.
- Changed "NEMA 4X SS" to "NEMA 4X STAINLESS STEEL" for Stationary Generator one line symbol.
- Changed receptacle name 'Heat Trace (By-Pass Connection)' for Receptacle one line and site plan symbols.
- Removed 'FOR (WITH SUN SHIELD)' in 'INDICATING LIGHTS' for one line Pump Control Panel note.

### Bug Fixes
- Fixed Emergency Push Button drawing for Stationary Generator one line symbol.
- Fixed syntax errors.
- Fixed missing back bracket in 'IF REQUIRED'.


## [0.23.1.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.23.1.0) (2024-07-02)

### Bug Fixes
- Fixed orientation of the receptacles one line symbol.


## [0.23.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.23.0.0) (2024-07-01)

### New Features
- Added command `RECEPTACLEOL` for drawing Receptacle one line symbol.
- Added command `RECEPTACLESP` for drawing Receptacle site plan symbol.
- Added command `POWEREQUIPSYMBOLS` for drawing Power Equipment Symbols.
- Added command `BYPASSPUMPOL` for drawing Bypass Pump one line symbol.
- Added command `BYPASSPUMPSP` for drawing Bypass Pump site plan symbol.
- Added command `OBSTRUCTIONLIGHTCONTROLLEROL` for drawing Obstruction Light Controller one line symbol.
- Added command `OBSTRUCTIONLIGHTCONTROLLERSP` for drawing Obstruction Light Controller site plan symbol.
- Added save/restore parameter name column width in palette of insertion parameters.
- Added Existing Utility Service Upgrade note to the Notes tool.

### Improvements
- Changed the note of one line grounding.
- Changed Security Light installation detail ('FROM POWER SOURCE'). 
- Added 'RADIO TOWER' to radio antenna leader of RTU one line symbol.
- Changed color of part of notes, about separate conduit for signals cables.
- Removed 'Company Name' parameter for Utility Transformer one line symbol.
- Added 'Service Upgrade' for existing Utility Transformer one line symbol.
- Removed 'One Line Diagram' detail label for Utility Transformer one line symbol.
- Added parameter 'PIT/SS' for Level Pressure Transducer one line and site plan symbol.

### Bug Fixes
- Fixed syntax error in Surge Suppressor note.
- Fixed NEMA rating (NEMA 4X) for Surge Suppressors.
- Fixed format of prompt text for installation details.
- Fixed color of Level Float Switch (and Backup).
- Fixed parameters for Manhole and Handhole one line symbols.
- Fixied ('WILL' to 'TO') Generator legend.
- Fixed conduit size for Conduit Text command.


## [0.22.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.22.0.0) (2024-06-14)

### New Features
- Added command `GNDSYMBOLS` for drawing Grounding Symbols.
- Added command `REVISION` for drawing Revision clouds and revision titles.
- Added command `MOTORSP` for drawing Motor and sensors site plan symbols.
- Added command `DISCONNECTSWITCHSP` for drawing Disconnect Switch site plan symbol.
- Added command `DISCONNECTSWITCHFUSESP` for drawing Fused Disconnect Switch site plan symbol.
- Added command `DISCONNECTSWITCHFUSESERSP` for drawing Fused Disconnect Switch SER site plan symbol.
- Added command `HANDSTATIONOL` for drawing Hand Station (Emergency Stop Push Button) one line symbol.
- Added command `HANDSTATIONSP` for drawing Hand Station (Emergency Stop Push Button) site plan symbol.
- Added command `MOTORSYMBOLS` for drawing Motor and Instrument site plan symbols.

### Improvements
- Added '(VFD SHIELDED)' to conductor label for VFD (MCC) and Enclosed Motor Starter (VFD type).
- Changed Automatic Transfer Switch (SER) one line symbol.
- Added second connection grounding to fence.
- Added grounding notes.
- Changed 'GND Size' and added 'Exisitng' parameters to Motor Frame Grounding.
- Renamed 'Existing Grounding' to "Grounding Multi Tool" and added 'Existing' parameter.
- Changed 'EXISTING' in notes for 'Motor Frame Grounding' and 'To Ground Grid'.
- Changed line type for Vendor's cables/conduits.
- Added 'MB Amperage' parameter to Grounding Triangle site plan symbol.
- Added 'AWG' to note of Grounding one line symbol.
- Changed minimal grounding conductor size to #1.
- Changed radius site plan symbols: Motor - 0.15" and Instrument - 0.1".
- Changed Discharge Pressure Transducer installation detail.
- Changed ('WITH GASKET' added and others) Meterial Schedule Tables.
- Added option parameters (Junction Box and Disconnect Switch connection) for Submersible Pump site plan symbol.
- Added option parameters (Junction Box connection) for Level Float Switches site plan symbol.
- Added option parameters (Junction Box connection) for Level Pressure Transducer site plan symbol.
- Added option parameters (Junction Box connection) for Back Up Level Float Switches site plan symbol.
- Added option parameters (Junction Box connection) for Level Sensor Probe site plan symbol.
- Added presets of conduits notes to Duct Bank Text command.
- Changed notes of Pump Control Panel (LS).

### Bug Fixes
- Fixed grounding 10 ft copper ground rod size.
- Fixed leader position of test ground well.
- Fixed abort command after note step for Grounding Triangle site plan symbol.
- Fixed "FOR POWER AND CONTROLS (PB-P-SCRN) AND SIGNALS (PB-S-SCRN)" in the Pull Boxes note in the "ELECTRICAL SITE PLANS -> POWER PLANS" category.
- Changed "FUSIBLE" to "FUSED" for Disconnect Switches.


## [0.21.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.21.0.0) (2024-05-24)

### New Features
- Added command `GNDEXISTINGSP` for drawing of Existing Grounding site plan symbol.
- Added command `GNDMOTORFRAMESP` for drawing of Motor Frame Grounding site plan symbol.
- Added command `LIGHTINGCONTACTOROL` for drawing of Lighting Contactor one line symbol.
- Added command `LIGHTINGCONTACTORSP` for drawing of Lighting Contactor site plan symbol.
- Added command `DISCHARGEPRESSURETRANSMITTEROL` for drawing of Discharge Pressure Transmitter one line symbol.
- Added command `DISCHARGEPRESSURETRANSMITTERSP` for drawing of Discharge Pressure Transmitter site plan symbol. 
- Added command `SPDOL` for drawing of Surge Protection Device one line symbol.

### Improvements
- Added 'Equipment Rack' paramerter in the Power Meter site plan symbol.
- Added 'Passive Filter' list item to 'Line Reactor/Filter' parameter of the MCC VFD device one line symbol.
- Added 'VFD Torque Type' parameter of the MCC VFD device one line symbol.
- Added VFD Torque Legend step of the MCC VFD device one line symbol.
- Renamed the 'MATERIAL' ribbon tab to 'MISCELLANEOUS'.
- Added new symbol and parameters for VFD to `MOTORSTARTEROL` command.
- Added 'Concrete Pad' parameter to Equipment Rack site plan symbol.
- Added 'Switchboard' and 'MCC' panels to the 'SITE PLAN' tab of ribbon.
- Added 'RVSS Bypass Contactor' parameter (for RVSS motor starter type) for Enclosed Motor Starter one line symbol.
- Added 'Quantity' parameter for Conductors Schedule Table.
- Added range to titles of number parameters.


## [0.20.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.20.0.0) (2024-05-16)

### New Features
- Implemented the placement mechanism (palette of parameters).
- Added command `SWITCHBOARD_CB` for drawing of Circuit breaker device of Switchboard one line symbol.
- Added command `SWITCHBOARD_SPACE` for drawing of Space circuit breaker device of Switchboard one line symbol.
- Added command `SWITCHBOARDSP` for drawing of Switchboard site plan symbol.
- Added command `MCC_SPACE` for drawing of Space devices of Motor Control Center one line symbol.
- Added command `MCCSP` for drawing of Motor Control Center site plan symbol.
- Added command `GNDBUILDINGSP` for drawing of Building Grounding site plan symbol.

### Improvements
- Changed dimention label ("4' MIN" on "4 FT MIN") for Equipment Rack site plan symbol.
- Formatted detail 'Bonding Lugs and Plates'.
- Added button to ribbon for Poratable Generator (Trailer Mounted) one line symbol.
- Removed quantity of ground rods in grounding notes.
- Changed item of Pump Control Panel note to '120V, 5A RATED DRY CONTACTS AND SIGNALS PREWIRED TO FIELD TERMINALS'.
- Changed command name `MOTORCONTROLCENTEROL` to `MCCOL` of Motor Control Center one line symbol.
- Changed command name `GNDSP` to `GNDTRIANGLESP` of Grounding site plan symbol.
- Added symbols 'GROUND BUS BAR' and 'BUILDING CONNECTION' to the `GROUNDING_SYMBOLS_*` block.
- Added details steps to Triangle Grounding site plan symbol.

### Bug Fixes
- Fixed SPD button name.
- Fixed error witch doesn't show a folder of the plotted file after plotting.


## [0.19.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.19.0.0) (2024-04-24)

### New Features
- Added the Gray Color tool.
- Added video tutorials: 'Как добавить Site Plan на чертеж' and 'Лечение Add ON Удаление не нужных вкладок'.

### Improvements
- Enhanced the ribbon initialization and handling workspace changing.
- Set color of '30mA' in MPZ and Panelboard Schedules.
- Added auto disable `FRAME` for Ductbank Line command.
- Show limit values for the Cable Schedule Table and incresed max value to 75 rows.
- Added 'AND INSTALL' to note of SPD.
- Changed cable labels for the Motor and the Motor (LS) one line symbols.
- Added RTU into Pump Control Panel one line symbol.
- Added reference cable labels for RTU and RTU in PCP one line symbols.

### Bug Fixes
- Fixed note translation errors.
- Remove unused layer from Detail Label block.
- Fixed syntax error in Natural Gas Stationary Generator note.
- Fixed syntax error in Bottom CB for MCC and Switchboard.
- Fixed text position in Control Panel one line component.
- Fixed layer for wetwell/vault site plan and one line diagram elements.
- Fixed 'XX' in cable label for RTU.
- Fixed graphic connection SPD to CB SER and DS Fused SER for one line symbols.
- Fixed note of the Junction Box one line symbol.
- Fixed notes of Security Light for site plan symbols.
- Fixed note of Ductbank Line site plan symbol.
- Fixed note of Flow Indication Transmitter one line symbol.
- Fixed loads text for Switchboard and MCC one line symbols.
- Fixed error on open tutorials window.


## [0.18.1.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.18.1.0) (2024-04-04)

### New Features
- Added command `SEALOFFOL` for drawing Seal-Off one line symbol.
- Added font size changing in Notes window.
- Added translation of notes to the Notes window.
- New declaration of plugin tabs in the ribbon.

### Improvements
- Changed description for test ground well to 'PROVIDE ONE (1) TEST GROUND WELL' and disable `FRAME`.
- Through numeration of circuit breakers in multi-section mini-panelboard schedule table.
- Changed cable/conduit label format to double 'XX' for not confirmed values.
- The color of the tags in the description of the submersible motor (LS) was set to red.
- Changed cable/conduit label for submersible motor to '2 RUNS OF CABLE BY VENDOR IN XX" C. EACH (TYP. FOR XX)'.
- Added checkbox for optional drawing grounding ring for stationary generator for site plan.
- Added dimentions in Wetwell/Vault one line command.
- Added 'SEE PANELBOARD SCHEDULE ON THIS SHEET' to Full Panelboard one line symbol.
- Notification per available update by changing 'Check update' button icon.
- Changed color for 'FUTURE CONNECTED LOAD' and 'FUTURE RUNNING LOAD' for Full Panelboard one line symbol.

### Bug Fixes
- Fixed errors for `SSSERVERPUBLISH` command.
- Fixed wrong RTU antenna (radio and cellular).
- Fixed wrong 'MAGNETIC WARNING TAPE' text position in Duct Bank grade.
- Fixed syntax error 'SLEEVE' in Generator Receptacle (one line) note.
- The color of reference cable type label changed.
- Fixed text position in Motor Starter one line component.


## [0.18.0.0](https://github.com/bankoViktor/AcEdecPlugin-Releases/releases/tag/0.18.0.0) (2024-03-04)

### New Features
- Added command `RTUOL` for drawing Remote Telemetry Unit one line symbol.
- Added command `RTUSP` for drawing Remote Telemetry Unit site plan symbol.
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
