26/11/2017

v1.5

Two new, fully modular and adjustable prop types were added: "Modular Toggle Switch" and "Modular Push Button".
With them, it is possible to create many different switches, both in form and in function. They were based on real switches from Korry and Zodiac Electric,
tumblers and buttons used by NASA in Apollo and Space Shuttle programs, as well as switches used by Boeing.

CAUTION! In the next major version of ASET PROPS old tumblers and buttons will be removed. All IVA makers are advised to switch to new, modular buttons.

  *Added props that extend MechJeb autopilot function support.
  *Added props for Chatterer support.
  *Added props interacting with stock CommNet.
  *Added props for controlling docking and undocking.
  *Updated Mod Indicator Panel prop (thanks to NukeboyT).
  *Portable Timer prop can now show time to the currnt KAC alarm.
  *MFD40X20 now supports Astrogator.
  *All MFDs now use the JSISteerableCamera module.
  *MFD button backlight can now be toggled with the other props.
  *kOSMonitor finished and updated to use full functionality of JSISteerableCamera.
  *Life Support Monitor now supports TAC, USI-LS and Kerbalism.
  *Finished transitioning from the old JSIVariableLabel to the more advanced JSILable.
  *Added configs for Primitive_TRIANGLE_90 and Primitive_TRIANGLE_90_Beveled Fixes for many other props.

---------------------------------------------------------------------------------------------------------------------------------------------------
08/02/2017

v1.4
 
What is changed:

  *Almost all props were rebuilt due to the migration to Unity5, and also for the possibility to use new RPM features
  *The module JSIVariableAnimator is replaced by JSICallbackAnimator where it is possible to improve performance
  *All alphanumeric indicators now use the new improved and flexible module JSILabel
  *Most props now support the "COLOR_OVERRIDE" feature, which give all IVA-makers ample opportunity to customize their own IVA
  *The switches "SwitchRotary" are now modular, you can combine the switch model, the collider model and label  using
        the MODEL{}module to create your variations of this  prop. 2 to 6 positions of the switch are supported.
  *Warning light indicator (TabloIndicator) was completely rebuilt, now all the labels are made with the module JSILabel,
        and texturesare used only for the indicator’s background
  *Some pages of MFD are improved, thanks to Nukeboyt
  *GPWS is now switched off by default
  *Extra optimization of textures is made

What’s new:

  -Brand new set of instruments in NASA-retro style:
  -Flight Director/Attitude Indicator (FDAI) with the dedicated control panel (FDAI GMCP) and switch set. Use  the MOARdv’s manualfor this device.
  -Altitude/Range Rate Tapemeter (ARRT) with the two dedicated toggle-switches for turning the devices on and off and for the mode
          selection (height/vertical speed or distance to target/closing speed), also with the error indicator. Use the MOARdv’s great manual for this device.
  -Thrust-to-Weight Indicator (TW) with the mode switch (current TWR / maximum possible TWR)
  -X-pointer with the mode and display range selectors, also with the error indicator. Use the MOARdv’s great manual for this device.
  -ASET_DSKY – LCD-display with the keyboard for the important flight information (orbit, orbit of target vessel),
          a rendezvous with the target, maneuver, timing, Delta V information). Use the MOARdv’s great manual for this device.
  -Monochrome CRT-display for the targets’ menu and external cameras’ output
  -Full set of the analog indicators (gauges)
  -Speed indicator (ASET_AnalogSpeedIndicator) with mode selector (auto, orbital, surface, relative)
  -Effective acceleration indicator (ASET_AnalogSpeedIndicator)
  -G-force indicator (NASA_G_Units_Indicator)
  -Slope indicator (NASA_Slope_Angl_Indicator)
  -Thrust limit indicator (NASA_Slope_Angl_Indicator)
  -Phase/Ejection/Moon ejection Angle indicator (ASET_PhaseAngleIndicator) with mode selector
  -Impact speed indicator (ImpactSpeedIndicator) with two scales for the current and the minimum possible touchdown speed
  -Full set of the vertical single and Edgewise meters, temperature and engine indicators
  -Numerical LCD-display for the current altitude and и surface height
  -Numerical LCD-display for the amount of resources on board and mode selector for it
  -Battery Charge gauge
  -Power Supply panel and the Power Source Selector (generator, fuel cell, solar panels and alternator)
  -Full set of the mechanical (aka  "barber pole") and warning light indicators ("low charge", "low fuel" etc)
  -Full set of the push-buttons (RetroButton) for all basic functions (custom groups, SAS modes etc)
  -The new navigation complex (ASET_IMP & ASET_IMP_LAT-LONG_GAUGE) with the dedicated mode selector, made after the
          Soviet navigation complex for the “Vostok” and “Voskhod” programs
  -Emergency Radio Beacon (RecoveryBeacon)
  -Advanced control and indication of the engine, electrical systems, landing gear and indication of temperature
  -New props for the indication of WARP-mode

---------------------------------------------------------------------------------------------------------------------------------------------------
21/07/2015

v1.3

    All props working algorithms was reworked to match the last RPM 0.21.
    Now all instruments stops working if the g-force is higher than 8 g (with dramatical flickering animation)

New props:

    Temperature indicators (for both capsule and shield)
    Chute controlling buttons (arm, deploy, cut)
    Throttle control buttons
    Buttons for the new MechJeb Smart A.S.S. functions
    Engine Flame Out, Shield Overheat and Ablation indicators
    Special separate display for the TAC Life support
    All Push buttons, Tumble and Tumble with cover switches were finished for all the standard and custom actions.
    Finished adding gauges for all stock resources.
    Fixed the bug with the sound disappearing after switching props lighting.
    Fixed the configs that used old resource names.
    Ground Proximity Warning System (GPWS) now can be turned off, I added buttons to control it.
    Altitude Voice Annunciator System (AVAS) now can be turned off, I added buttons to control it.
    Low Altitude Warning can now be set for different altitudes (100, 200, 300) or even be turned off.

MFD

    New Landing page, look at the User Manual for the additional information
    New Graphs page
    PFD was optimised for RPM 0.21
