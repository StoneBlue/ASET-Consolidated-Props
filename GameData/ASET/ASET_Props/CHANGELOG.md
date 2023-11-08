
ASET Consolidated Props Pack by Alexustas, adopted by Stone Blue

---------------------------------------------------------------------------------------------------------------------------------------------------
2023-11-08

v2.0.7

- Changes:

  - Improvements to hatch props
  - Fix "has oxygen" readout on 60x30 MFD map page
  - Reduce number of gameobjects in SeatV2 for performance
  - Fix FI_Gear_DEPLOYED prop
  - Add new scifi yoke prop (thanks @SMAEL)

---------------------------------------------------------------------------------------------------------------------------------------------------

2023-04-13

v2.0.4

- Changes:

  by JonnyOThan:
	- Mapped some MechJeb SAS pushbuttons, to work as stock, where SAS functions are comparable, *when MechJeb is NOT installed*
	- Added moar precision to deltaV Digital Indicator
	- Fixed missing "Prev/Next" buttons on kOS Terminal, by reverting to old texture
	- Fixed texture reference in Flashlight prop

  by Stone Blue:
	- Added MRE Food Pack props
	- Fixed incorrect name for Food_BeveragePackage_TropicalPunch
	- Fixed a bunch of typo/syntax errors & cleaned up whitespace while I was in there, in prop cfgs:

		- Fixed missing closing "}" pb_ALCOR_NAV_LIGHT-FD4.cfg
		- Fixed missing closing "}" pb_MJ_ROLL_0-FT.cfg
		- Fixed missing closing "}" pb_MJ_ROLL_90-FT.cfg
		- Fixed missing closing "}" pb_MJ_ROLL_180-FT.cfg
		- Fixed missing closing "}" pb_MJ_ROLL_270-FT.cfg
		- Fixed missing closing "}" pb_THRTL_CUT-FT-G1.cfg
		- Fixed missing closing "}" pb_THRTL_FULL-FT-G1.cfg
		- Fixed extra closing "}" in tggl_NOSE_TRIM_T4M-D.cfg
		- Fixed extra closing "}" in tggl_SEAT_POSITION_T4M-S.cfg
		- Fixed half-commented out MODULE in tggl_AG01_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG02_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG03_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG04_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG05_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG06_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG07_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG08_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG09_T4W-S.cfg
		- Fixed half-commented out MODULE in tggl_AG10_T4W-S.cfg
		- Fixed extra closing "}" in tggl_LIGHTS_T4M-S.cfg
		- Removed extra "/" from EOS in CustomVariables_ALCOR_MFDs.cfg
		- Removed extra "}" from EOS in kOSTerminalGraphSets.cfg
		- Added missing "/" in comment in swTumbler_V3_AG01.cfg
		- Added missing "/" in comment in swTumbler_V3_AG02.cfg
		- Added missing "/" in comment in swTumbler_V3_AG03.cfg
		- Added missing "/" in comment in swTumbler_V3_AG04.cfg
		- Added missing "/" in comment in swTumbler_V3_AG05.cfg
		- Added missing "/" in comment in swTumbler_V3_AG06.cfg
		- Added missing "/" in comment in swTumbler_V3_AG07.cfg
		- Added missing "/" in comment in swTumbler_V3_AG08.cfg
		- Added missing "/" in comment in swTumbler_V3_AG09.cfg
		- Added missing "/" in comment in swTumbler_V3_AG10.cfg
		- Added missing "/" in comment in swTumbler_V3_Brakes.cfg
		- Added missing "/" in comment in swTumbler_V3_FuelCell.cfg
		- Added missing "/" in comment in swTumbler_V3_Gear.cfg
		- Added missing "/" in comment in swTumbler_V3_Lights.cfg
		- Added missing "/" in comment in swTumbler_V3_RCS.cfg
		- Added missing "/" in comment in swTumbler_V3_ResLock.cfg
		- Added missing "/" in comment in swTumbler_V3_SAS.cfg
		- Added missing "/" in comment in swTumbler_V3_StageLock.cfg
		- Added missing "/" in comment in swTumbler_V3_ThrustReverser.cfg

---------------------------------------------------------------------------------------------------------------------------------------------------
2023-03-10

v2.0.3 - Hotfix for MAS

- Changes:

  - Revert change to bg02.png texture. Its referenced by some MAS MFDs

---------------------------------------------------------------------------------------------------------------------------------------------------
2023-03-03

v2.0.2

- Changes:

  by JonnyOThan
  - Updated some props with :NEEDS Chatterer, to remove log spam
  - Remove duplicate "escape" entry
  - Add ASET_WallLabel prop
  - Fix places that are using KDT instead of MET formatting
  - Wall Label: hook up persistence, add vr support for second button

  by StoneBlue
  - Clean up a bunch of log spam
     - Delete unecessary, duplicate .png textures: Switch_PUSH_Icons, kOSTerminalDiffuse, kOSTerminalEmissive, SwitchPanelDiffuse
     - Resized HDG.png by a few pixels
     - Resized bg02.png; discovered it may not even be used anywhere. Renamed it for possible deprecation/removal
     - Fixed typo in On_CHATTERER_ON.cfg

---------------------------------------------------------------------------------------------------------------------------------------------------
2023-02-19

v2.0.1

- Changes:

  by JonnyOThan
  - Add VR configuration to flashlight
  - Add flashlight prop
  - Add :NEEDS markers on a bunch of MFD pages that require specific mods
  - Move compatibility patches from RPM
  - Point download link in .version file to spacedock
  - Fix URLs in version file
  - Add some :NEEDS tags to MFDs for plugins
  
  by StoneBlue
  - Added .blends from some of the new MAS props
  - Added Flashlight prop .blend
  - Moved Flashlight prop license to created LICENSE.md

---------------------------------------------------------------------------------------------------------------------------------------------------
2023-02-11

v2.0.0

- Changes:

  - Duplicated ASET-derived props that are included in RasterPropMonitor Adopted,
       in preparation for final inclusion in ASET Consolidated Props Pack & removal from RPM itself, per request of JonnyOThan.
  - Moved forum thread from WIP/Add-Deveopment to Add-Releases
  - Released on SpaceDock & CKAN

----------------------------------------------------------------------------------------------------------------------------------------------------
2023-02-07

v1.9.1

- Changes:

  -Fix README
  
---------------------------------------------------------------------------------------------------------------------------------------------------
2023-02-07

v1.9.0

Initial adoption Release by Stone Blue
Since this is an initial adoption release, NO changes are made to the content, OTHER than those listed below.
Vers. 1.9.0 content is an *exact copy* of v1.5, other than noted below. All vers. 1.9.x changes will only contain repo and distribution changes to get the bugs worked out.
Once changes to actual mod content start, versioning will go to v2.0.x

- Changes

  - Created new forum release thread: [ASET Consolidated- Avionics, Props, & IVA Pack](https://forum.kerbalspaceprogram.com/index.php?/topic/211905-1125-181-aset-consolidated-avionics-props-iva-packs/)
  - Created Github repo
  - Addition of .version file
  - Updated/formatted CHANGELOG & README
  - Relevant documentation added to repo
  - Added Extras folder, initially contains map of Earth, by slaintemaith, to replace Kerbin map on some props, for use in RO/RP-1

---------------------------------------------------------------------------------------------------------------------------------------------------

*****  Below is original changelog from alexustas' last v1.5 release ****

---------------------------------------------------------------------------------------------------------------------------------------------------
26/11/2017

v1.5

Two new, fully modular and adjustable prop types were added: "Modular Toggle Switch" and "Modular Push Button".
With them, it is possible to create many different switches, both in form and in function.
They were based on real switches from Korry and Zodiac Electric,tumblers and buttons used by NASA in
Apollo and Space Shuttle programs, as well as switches used by Boeing.

- CAUTION! In the next major version of ASET PROPS old tumblers and buttons will be removed. All IVA makers are advised to switch to new, modular    buttons.

  * Added props that extend MechJeb autopilot function support.
  * Added props for Chatterer support.
  * Added props interacting with stock CommNet.
  * Added props for controlling docking and undocking.
  * Updated Mod Indicator Panel prop (thanks to NukeboyT).
  * Portable Timer prop can now show time to the currnt KAC alarm.
  * MFD40X20 now supports Astrogator.
  * All MFDs now use the JSISteerableCamera module.
  * MFD button backlight can now be toggled with the other props.
  * kOSMonitor finished and updated to use full functionality of JSISteerableCamera.
  * Life Support Monitor now supports TAC, USI-LS and Kerbalism.
  * Finished transitioning from the old JSIVariableLabel to the more advanced JSILable.
  * Added configs for Primitive_TRIANGLE_90 and Primitive_TRIANGLE_90_Beveled Fixes for many other props.

---------------------------------------------------------------------------------------------------------------------------------------------------
08/02/2017

v1.4
 
- What is changed:

  * Almost all props were rebuilt due to the migration to Unity5, and also for the possibility to use new RPM features
  * The module JSIVariableAnimator is replaced by JSICallbackAnimator where it is possible to improve performance
  * All alphanumeric indicators now use the new improved and flexible module JSILabel
  * Most props now support the "COLOR_OVERRIDE" feature, which give all IVA-makers ample opportunity to customize their own IVA
  * The switches "SwitchRotary" are now modular, you can combine the switch model, the collider model and label using
      the MODEL{}module to create your variations of this  prop. 2 to 6 positions of the switch are supported.
  * Warning light indicator (TabloIndicator) was completely rebuilt, now all the labels are made with the module JSILabel,
      and texturesare used only for the indicator’s background
  * Some pages of MFD are improved, thanks to Nukeboyt
  * GPWS is now switched off by default
  * Extra optimization of textures is made

- What’s new:

  - Brand new set of instruments in NASA-retro style:
  - Flight Director/Attitude Indicator (FDAI) with the dedicated control panel (FDAI GMCP) and switch set. Use  the MOARdv’s manualfor this device.
  - Altitude/Range Rate Tapemeter (ARRT) with the two dedicated toggle-switches for turning the devices on and off and for the mode
      selection (height/vertical speed or distance to target/closing speed), also with the error indicator. Use the MOARdv’s great manual for this       device.
  - Thrust-to-Weight Indicator (TW) with the mode switch (current TWR / maximum possible TWR)
  - X-pointer with the mode and display range selectors, also with the error indicator. Use the MOARdv’s great manual for this device.
  - ASET_DSKY – LCD-display with the keyboard for the important flight information (orbit, orbit of target vessel),
      a rendezvous with the target, maneuver, timing, Delta V information). Use the MOARdv’s great manual for this device.
  - Monochrome CRT-display for the targets’ menu and external cameras’ output
  - Full set of the analog indicators (gauges)
  - Speed indicator (ASET_AnalogSpeedIndicator) with mode selector (auto, orbital, surface, relative)
  - Effective acceleration indicator (ASET_AnalogSpeedIndicator)
  - G-force indicator (NASA_G_Units_Indicator)
  - Slope indicator (NASA_Slope_Angl_Indicator)
  - Thrust limit indicator (NASA_Slope_Angl_Indicator)
  - Phase/Ejection/Moon ejection Angle indicator (ASET_PhaseAngleIndicator) with mode selector
  - Impact speed indicator (ImpactSpeedIndicator) with two scales for the current and the minimum possible touchdown speed
  - Full set of the vertical single and Edgewise meters, temperature and engine indicators
  - Numerical LCD-display for the current altitude and и surface height
  - Numerical LCD-display for the amount of resources on board and mode selector for it
  - Battery Charge gauge
  - Power Supply panel and the Power Source Selector (generator, fuel cell, solar panels and alternator)
  - Full set of the mechanical (aka  "barber pole") and warning light indicators ("low charge", "low fuel" etc)
  - Full set of the push-buttons (RetroButton) for all basic functions (custom groups, SAS modes etc)
  - The new navigation complex (ASET_IMP & ASET_IMP_LAT-LONG_GAUGE) with the dedicated mode selector, made after the
       Soviet navigation complex for the “Vostok” and “Voskhod” programs
  - Emergency Radio Beacon (RecoveryBeacon)
  - Advanced control and indication of the engine, electrical systems, landing gear and indication of temperature
  - New props for the indication of WARP-mode

---------------------------------------------------------------------------------------------------------------------------------------------------
21/07/2015

v1.3

All props working algorithms was reworked to match the last RPM 0.21.
Now all instruments stop working if the g-force is higher than 8 g (with dramatical flickering animation)

- New props:

  - Temperature indicators (for both capsule and shield)
  - Chute controlling buttons (arm, deploy, cut)
  - Throttle control buttons
  - Buttons for the new MechJeb Smart A.S.S. functions
  - Engine Flame Out, Shield Overheat and Ablation indicators
  - Special separate display for the TAC Life support
  - All Push buttons, Tumble and Tumble with cover switches were finished for all the standard and custom actions.
  - Finished adding gauges for all stock resources.
  - Fixed the bug with the sound disappearing after switching props lighting.
  - Fixed the configs that used old resource names.
  - Ground Proximity Warning System (GPWS) now can be turned off, I added buttons to control it.
  - Altitude Voice Annunciator System (AVAS) now can be turned off, I added buttons to control it.
  - Low Altitude Warning can now be set for different altitudes (100, 200, 300) or even be turned off.

- New MFD stuff:

  - New Landing page, look at the [User Manual](https://www.dropbox.com/s/1e2lsx92z5uxt1z/LandingScreenManual.pdf?dl=0) for additional info
  - New Graphs page
  - PFD was optimised for RPM 0.21
