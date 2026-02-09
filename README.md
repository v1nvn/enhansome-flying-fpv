# Awesome Flying FPV [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<!--lint disable awesome-toc no-repeat-punctuation match-punctuation -->

This is a list of Free Software and Open Hardware dedicated for multicopters as well as airplanes or flying wings. We list esp. established projects with a active community and also some classics that might be legacy but important projects with a lot of mods.

We hope to give you some orientation where to start and present you the full spectrum of open source development on the world of UAVs.

> **Warning**
> You as creator, mechanic, spotter and pilot **are responsible** for your drone and doing. It is on you to avoid damages and not to hurt any person or animal.
> You are also responsible to match the local regulations of your country and to know where and how to fly with a minimum risk to others and yourself.
> Please respect [good airmanship](https://en.wikipedia.org/wiki/Airmanship).

> **Warning**
> In past and recent wars and **military conflicts**, parties make use of UAVs and sometimes DIY aircraft to spot and attack opponents.
> My intention on this technology is in opposite a peaceful research and learning on tech and nature, not on killing people! [stopkillerrobots.org](https://www.stopkillerrobots.org)

## Contents

* [Airframes](#airframes)
  * [Multicopters 🚁](#multicopters-)
  * [Fixed Wing / Planes 🛩️](#fixed-wing--planes-%EF%B8%8F)
  * [VTOLs 🚀](#vtols-)
* [Batteries & Power Control 🔋](#batteries--power-control-)
* [Motor Control ⚙️](#motor-control-%EF%B8%8F)
* [Flight Control 👨‍✈️](#flight-control-%EF%B8%8F)
* [RC Transmitters & Handcontroller 🎮](#rc-transmitters--handcontroller-)
  * [Modules 🧩](#modules-)
* [VTX 📺](#vtx-)
* [Camera & Gimbals 🎥](#camera--gimbals-)
* [GPS 🛰️](#gps-%EF%B8%8F)
* [Sensors 🌡️](#sensors-%EF%B8%8F)
* [Video Receivers 📶](#video-receivers-)
* [Antennas and Trackers 📡](#antennas-and-trackers-)
* [Telemetry & Logs 📊](#telemetry--logs-)
* [Mission Control & Basestation 🗺️](#mission-control--basestation-%EF%B8%8F)
* [Companion Computers & Integration 💻](#companion-computers--integration-)
* [Computer Vision 🤖](#computer-vision-)
* [Complete Systems 🎁](#complete-systems-)
* [Security & Safety 🪂](#security--safety-)
  * [Simulators 🌐](#simulators-)
  * [Checklists 📋](#checklists-)
  * [ID Systems 🛂](#id-systems-)
  * [Hacking & Hijacking 🔓](#hacking--hijacking-)
* [Accesoirs 🪠](#accesoirs-)
  * [Mobile Apps 📱](#mobile-apps-)
  * [Workbench 🧰](#workbench-)
* [Legal Information 🏛️](#legal-information-%EF%B8%8F)
* [Communities 🗣️](#communities-%EF%B8%8F)
  * [Forums & Social Media](#forums-social-media)
  * [Video Channels](#video-channels)

## Airframes

The body of a UAV depends on the kind of aircraft and is optimized for it's usecase. Is it high speed for racing, improved agility for acrobatic freestyle, a heavy lifter for filming , long distance observations, ... . This requirements result in different mechanics and materials and take DIY aspect into account.

You will find also a lot of spare parts or mods / extensions to commercial vehicles, which we don't list up here!

> **Note**
> Building a UAV from scratch is a **pretty challenging task** for a beginner, esp. if you have limited amount of time.
> So it might be wise, to try existing solutions or kits before, so you don't get stuck to early and have a handy manual. Later on, you can try different mods or start with custom builds, if you have gained more experience and know how to avoid common pitfalls.
> See also: [My Raspberry Pi drone: the story so far by Matchstic](https://www.youtube.com/watch?v=ZCOlT_sz6Gs).

### Multicopters 🚁

Copters are built using different materials from alu / carbon profiles to CNC cuts to full 3D printed cases and have different configurations for different number of rotors (bi... octo):

* [TBS Source One](https://github.com/tbs-trappy/source_one) ⭐ 582 | 🐛 23 | 📅 2025-09-17 - Carbon racing frame in 5 revisions, 2021.
* [JeNo 5.1"](https://github.com/WE-are-FPV/JeNo-5.1) ⭐ 54 | 🐛 0 | 📅 2025-12-23 - Modern carbon wide X-frame with accessoirs
* [TBS Source X](https://github.com/ps915/source_x) ⭐ 39 | 🐛 1 | 📅 2019-06-10 - Carbon racing frame, 2019.
* [TBS Source Podracer](https://github.com/ps915/source_podracer) ⭐ 36 | 🐛 1 | 📅 2020-07-18 - 3D carbon racing frame, 2020.
* [Sub 250g autonomous drone](https://www.youtube.com/watch?v=u_ArriXbrR0) - 3D printed bare minimum frame with Liion and GPS
* [Goblin v3](https://www.printables.com/de/model/396395-goblin-fpv-drone) - 3D printed frame, 4S power, 16x16 AIO stack, 2023.
* [NanoLongRange](https://www.thingiverse.com/thing:4769576) - 3D printed frame with mostly a 18650 Liion cell and a all-in-one board for whoops, 2021.
  * [Discovery Edition](https://www.thingiverse.com/thing:5428365) - Optimized frame with integrated battery holder, 2022.
  * [NanoLongRange 2](https://www.thingiverse.com/thing:4818009) - With GPS and slightly lighter in 3 variants also for 21700 cells, 2021.
* [NLR35](https://www.thingiverse.com/thing:5428923) - Lighter and similar to NLR, but 21700 cell, 2022.
* [hefty](https://hackaday.com/2023/09/01/hefty-3d-printed-quadcopter-meets-nasty-end/) - Full 3d printed heavy quadcopter with custom made motors, 2023
* [Ultimate 3D printable Cinewhoop](https://www.thingiverse.com/thing:4502805) - 2020.
* [TinyTina](https://blog.prusaprinters.org/how-to-build-a-3d-printed-micro-drone_29310/) - 3D printed whoop, 2018.
* [Heavy Lift Quadcopter Frame](https://www.thingiverse.com/thing:4089842) - CNC cut by carbon, 2020.
* [The CogniFly](https://thecognifly.github.io) - Robust frame for research, swarms and indoor with RPI companion computer, 2021.
* [TBS Source Two](https://www.team-blacksheep.com/products/prod:source_two_5in) - Carbon racing frame, 2019.
* [TBS Source V](https://www.team-blacksheep.com/products/prod:source_v) - 5" carbon racing frame, 2021.
* [AESIR II](https://www.thingiverse.com/thing:4868250) - Modular and customized 3D and carbon frame, 2021.
* [Foldable Drone Frame](https://www.thingiverse.com/thing:2004357) - 3D printed with gimbal option 2017.
* [OpenRC Quadcopter](https://www.thingiverse.com/thing:793425) - 3D printed with closed case , 2015.
* [Hovership MHQ2](https://www.thingiverse.com/thing:511668) - 3D printed foldable, 2014.
* [Crossfire 2](https://www.thingiverse.com/thing:234867) - Huge quad 3D printed, 2014.
* [Spyda 500](https://www.thingiverse.com/thing:160607) - Huge quad 3D printed, 2013.

### Fixed Wing / Planes 🛩️

Traditional RC airplanes are created using balsa wood and foil covered rips for the wings. Commercial models make often use of foam, that you can also cut by CNC and lasers to create wing profiles.  Also fully 3D printed planes are possible, that you glue and strength with carbon roods. There is also a growing community for (commercial) 3D printed models like [Craycle Hobby](https://craycle.com/), [Eclipson airplanes](https://www.eclipson-airplanes.com/),[3D lab print](https://3dlabprint.com/product-category/printable-airplanes/), [Plane Print](https://www.planeprint.com/) , [OWLplane](https://owlplane.com/) or [rc-jetprint.de](https://rc-jetprint.de/en/) using lightweight PLA to save weight.

* [HAWk Modular RC Wing Airplane v1](https://www.printables.com/de/model/422806-hawk-modular-rc-wing-airplane) - 3D printed LW-PLA 1m++ pusher / puller wing, full BOM + manual docs, 2023.
* [V-Tail Aircraft for Long Range FPV & Autonomous Missions - by AeroStuff FPV](https://www.youtube.com/watch?v=sTjXVeo_lpQ) - Use folded depron panels for body and wings for a V-Tail pusher.
* [Highly Modular Design -1 (HMD1)](https://forum.flitetest.com/index.php?threads/large-modular-uav-design.69987/) - 3D printed ABS V-tail plane for research, 2022.
* [Ranger V2](https://craycle.com/product/ranger-v2-800-mm-3ch-trainer-stl-file/) - Sub 1m pusher trainer plane, 2022.
* [Berkik 3 wing](https://www.youtube.com/watch?v=ZA8fGOzJB10) - 1.3m depron wing ,2021.
* [LukiSegler](https://www.printables.com/de/model/76098-lukisegler-electric-rc-glider) - Glider, 2021.
* [SakhWing](https://www.thingiverse.com/thing:4547317) - Drak like fixed wing printed with PETG, 2020.
* [GemINIce](https://www.youtube.com/watch?v=PcScS4Cj_Iw\&list=PLEH_vTrFddgP8bRQFMK_z8rwmRth60Fen) - 2 props dpron airplane, 2016.
* [Joywing](https://www.youtube.com/watch?app=desktop\&v=X6hJCQNxVzs) - Simple race wing, 2019.
* [Eclipson Model V](https://www.thingiverse.com/thing:4011218) - Mostly 3D printed commercial airplane with wheels, 2019.
* [Eclipson Model Y](https://www.thingiverse.com/thing:2752892) - Mostly 3D printed commercial airplane with wheels, 2018.
* [Northern Pike](https://www.thingiverse.com/thing:3040294) - 36" fixed wing 3D printed, 2018.
* [Moose](https://www.thingiverse.com/thing:3023606) - 1m puller plane made of PLA, 2018
* [Supernove](https://www.thingiverse.com/thing:2187747) - Jet like pusher RC plane.
* [RC Flying Wing](https://www.thingiverse.com/thing:2044074) - Sub 1m 3D printed pusher plane 2017.
* [GASB Three](https://www.thingiverse.com/thing:3605665) - Fixed wing 3D printed, 2019.
* [GASB Two](https://www.thingiverse.com/thing:1831295) - Fixed wing jet 3D printed with electric ducted fan (EDF) instead of classic propeller, 2016.
* [GASB One](https://www.thingiverse.com/thing:1659724) - 80cm fixed wing 3D printed, developed in 6 revisions, 2016.
* [Red swan](https://www.thingiverse.com/thing:453090) - 1950mm printed plane with wing ribs, sucessor of Red Duck modell, 2014.
* [Le Fish glider](https://lefish.fandom.com/wiki/Building_Le_Fish#Plans) - Open Source aerobatics glider with a lot of remixes, 2005.

### VTOLs 🚀

Vertical take-off and landing are air vehicles that transform from copter to a gliding wing, making it very easy to start/land but require a more complex mechanic and become a tip heavier than fixed wings.

* [MiniHawk-VTOL v2.0](https://github.com/StephenCarlson/MiniHawk-VTOL) ⭐ 274 | 🐛 16 | 📅 2022-06-19 - 3d printed with 3 props
* [VTOL in 5 revisions](https://www.youtube.com/watch?v=gPEeCjVrTBw) - 3D printed and foam, 2018.
  * [wing profile](https://www.printables.com/de/model/261434-vase-mode-wing) - Resulting wing profile 3D printing with LW-PLA.
* [bicopter kit](https://hackaday.com/2018/08/27/the-best-new-quad-is-a-bicopter/) - CNC carbon, 2018.

## Batteries & Power Control 🔋

Commercial LiPo battery packs are common in RC, but can be replaced with custom 18650 based Liion packs. The onboard power bus drives the ESC and FC directly, which offer 5V outputs to supply onboard units.

* 18650 LiIon packs
  * [Using Li-Ion Battery Pack for Long Range FPV Flying](https://oscarliang.com/li-ion-battery-long-range/) - 4S and background infos, 2023.
  * [build a „LongRange“ Lithium Ion Battery](https://blog.seidel-philipp.de/diy-build-a-longrange-lithium-ion-battery/) - 4S 3000mAh, 2020.
  * [DIY FPV Goggle Battery Pack](https://nuxnik.com/diy-fpv-goggle-battery-pack/) - For googles, with charge meter and 3D case, 2021.
  * [18650 spaceholder](https://www.printables.com/de/model/1181-18650-improved-spacerholder) - 3D print for easier packaging, 2023.
* Solar plane
  * [Solar Dragon - Solar Plane Might Be Able To Last Through The Night](https://hackaday.com/2022/08/06/solar-plane-might-be-able-to-last-through-the-night/) - Plane with PV beplanned ribs, 2022.
  * [rctestflight series](https://www.youtube.com/watch?v=1OGrDvInUAY) - 8hrs30 fixed wing full of solar cells with great measurements and background infos ([might last 24hrs](https://hackaday.com/2022/09/27/24-hours-of-le-airplanes/)), 2022.
* [diyBMS v4](https://github.com/stuartpittaway/diyBMSv4) ⭐ 1,083 | 🐛 34 | 🌐 HTML | 📅 2025-07-25 - Battery management PCB and firmware for LiIon packs.

## Motor Control ⚙️

Usually brushless DC motors (BLDC) are used for their power and precision. They require Electronic Speed Controller (ESC) per motor.

* [BLheli\_S](https://github.com/bitdump/BLHeli) ⭐ 2,188 | 🐛 411 | 🌐 Assembly | 📅 2025-08-21 - Popular Firmware for ESCs with fine-grained control.
* [AM32-MultiRotor-ESC-FW](https://github.com/am32-firmware/AM32) ⭐ 749 | 🐛 96 | 🌐 C | 📅 2026-02-03 - DSHOT, telemetry, 2024
* [PIDtoolbox](https://github.com/bw1129/PIDtoolbox) ⭐ 636 | 🐛 8 | 🌐 MATLAB | 📅 2024-10-02 - tuning your PID settings for max. performance of your specific modell.
* [BlueJay](https://github.com/mathiasvr/bluejay) ⭐ 545 | 🐛 23 | 🌐 Assembly | 📅 2022-08-31 - BLheli fork, Digital ESC firmware for controlling brushless motors. More features like custom melodies. Since 2020.
* [ESC Configurator](https://github.com/stylesuxx/esc-configurator) ⭐ 218 | 🐛 37 | 🌐 JavaScript | 📅 2025-12-08 - Web app to setup your BLHeli / Bluejay ESC.
* [MESC FOC ESC](https://github.com/davidmolony/MESC_FOC_ESC) ⭐ 50 | 🐛 1 | 📅 2021-04-02 - Open Hardware and Firmware for STM32 basrd ESC.

## Flight Control 👨‍✈️

Modern autopilot software require STM32 based boards with F4/F7 chip generation and usually no longer support legacy boards like NAZE32, CC3D, ArduPilot, etc. Most projects are base on Baseflight / Cleanflight firmware and Desktop Configurator.

* [betaflight](https://github.com/betaflight/betaflight) ⭐ 10,592 | 🐛 342 | 🌐 C | 📅 2026-02-08 - Focus on racing and agility for wings and copters.
* [CleanFlight](https://github.com/cleanflight/cleanflight) ⭐ 2,706 | 🐛 1 | 🌐 C | 📅 2023-10-20 - Legacy fork of baseflight , stall.
* [Paparazzi UAV](https://github.com/paparazzi/paparazzi) ⭐ 1,655 | 🐛 66 | 🌐 C | 📅 2026-02-08 - ?.
* [dRehmflight](https://github.com/nickrehm/dRehmFlight) ⭐ 1,335 | 🐛 6 | 🌐 C++ | 📅 2025-01-20 - Dedicated to VTOLs and it's transformation during flight process, Teensy Boards only.
* [BaseFlight](https://github.com/multiwii/baseflight) ⭐ 524 | 🐛 23 | 🌐 C | 📅 2016-01-18 - Legacy and oldest FW of the days of Wii gyro hacks and 8bit, stall.
* [EmuFlight](https://github.com/emuflight/EmuFlight) ⭐ 487 | 🐛 59 | 🌐 C | 📅 2025-10-24 - Focus on modern algorithms.
* [madflight](https://github.com/qqqlab/madflight) ⭐ 372 | 🐛 2 | 🌐 C | 📅 2026-02-05 - For Arduino based target boards, different sensors supported, 2024
* [LibrePilot](https://github.com/librepilot/LibrePilot) ⭐ 348 | 🐛 18 | 🌐 C | 📅 2023-12-14 - Stall since 2018.
* [dRonin](https://github.com/d-ronin/dronin/) ⭐ 305 | 🐛 118 | 🌐 C++ | 📅 2021-09-13 - Supporting Openpilot and other target boards.
* [QUICKSILVER firmware](https://github.com/BossHobby/QUICKSILVER) ⭐ 210 | 🐛 14 | 🌐 C | 📅 2026-01-11 - ?.
* [The Cube Autopilot](https://github.com/proficnc/The-Cube) ⭐ 153 | 🐛 0 | 🌐 HTML | 📅 2026-02-02 - FC hardware like the Pixhawk 2,
* [HPR-Rocket-Flight-Computer](https://github.com/SparkyVT/HPR-Rocket-Flight-Computer) ⭐ 134 | 🐛 0 | 🌐 C++ | 📅 2025-05-18 - High speed rockets firmware
* [Rotorflight](https://github.com/rotorflight/rotorflight) ⭐ 73 | 🐛 14 | 📅 2024-07-05 - Firmware for traditional single-rotor helicopters.
* [INAV](https://github.com/light/inav) - Focus on GPS based flight planning / autonomous flights for wings and copters.
* [Ardupilot](https://ardupilot.org) - Full ecosystem including professional / research use for wings and copters and even land or water vehicles. A lot of information, experiences and possibilities, but also more complex than INAV.
* [Risc V Powering a 3D Printed Drone](https://www.youtube.com/watch?v=TJCeLOiP7lU) - RISCV cpu experiments on DIY quadcopter.

## RC Transmitters & Handcontroller 🎮

Radio control transmitters (RC TX, your side) support extension bays with the [JR / JR lite formfactor](https://github.com/pascallanger/DIY-Multiprotocol-TX-Module/blob/master/docs/Module_BG_4-in-1.md) ⭐ 1,830 | 🐛 113 | 🌐 C++ | 📅 2025-09-26 and serial interfaces to adapt to different radio protocols. See also Ground station.
Most receivers (RX, drone side) support standard serial protocols like Crossfire (CSRF) to talk with the FC.

* [OpenTX](https://github.com/opentx/opentx) ⭐ 2,168 | 🐛 296 | 🌐 C++ | 📅 2025-12-19 - Firmware for popular handtransmitters including Desktop manager and sound packs.

* [EdgeTX](https://github.com/EdgeTX/edgetx) ⭐ 2,166 | 🐛 732 | 🌐 C | 📅 2026-02-09 - Successor of OpenTX under active development.

* [Ardino Transmitter for ELRS](https://github.com/kkbin505/Arduino-Transmitter-for-ELRS) ⭐ 346 | 🐛 3 | 🌐 C++ | 📅 2025-04-05 - Simple gamepad like hand transmitter based on Arduino

* [freedomTX](https://github.com/tbs-fpv/freedomtx) ⭐ 69 | 🐛 20 | 📅 2025-09-05 - OpenTX fork, stall since 2020.

* [OpenAVRc](https://github.com/Ingwie/OpenAVRc_Hw) ⭐ 23 | 🐛 0 | 🌐 HTML | 📅 2026-02-08 - Custom TX based on Arduino Mega2560 boards.

* [opentx-lua-widgets](https://github.com/Matze-Jung/opentx-lua-widgets) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2019-12-07 - More UI widgets to present telemetry.

* [VTx](https://github.com/teckel12/VTx) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2019-01-30 - Stripped down betaflight Lua script to control only your VTX.

* [opentx-lua-running-graphs](https://github.com/Matze-Jung/opentx-lua-running-graphs) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2019-11-12 - More visual graphs as widgets.

* [betaflight-tx-lua-scripts](https://github.com/Matze-Jung/betaflight-tx-lua-scripts) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2019-09-27 - Extended BF lua script.

* [OpenTX-Pong](https://github.com/SpechtD/OpenTX-Pong) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2021-09-30 - Simple game for your TX.

* [inav-opentx-sounds](https://github.com/JyeSmith/inav-opentx-sounds) ⭐ 2 | 🐛 0 | 📅 2018-04-03 - Addon sounds for modes.

* [transmitter-sound-pack](https://inavfixedwinggroup.com/guides/transmitter-models/transmitter-sound-pack/) - INAV sounds and complete configs for wings.

* [ER9X](http://www.er9x.com) - Alternative Firmware for 9XR handtransmitter.

### Modules 🧩

Hardware and firmware to establish custom radio links. Nowadays usually a bidirectional link, so pure TX / RX side.

* [ExpressLRS](https://github.com/ExpressLRS/ExpressLRS) ⭐ 4,712 | 🐛 53 | 🌐 C | 📅 2026-02-08 - ELRS for long range or better latency. support. flashing some existing hardware, but also provide commercial modules for 868/915 MHz or 2.4 / 5.8 GHz.
  * [ELRS Airport Firmware](https://github.com/ExpressLRS/ExpressLRS/pull/1904) ⭐ 4,712 | 🐛 53 | 🌐 C | 📅 2026-02-08 - 2 way link for more complex telemetry downlink.
* [Multi Module](https://github.com/pascallanger/DIY-Multiprotocol-TX-Module) ⭐ 1,830 | 🐛 113 | 🌐 C++ | 📅 2025-09-26 - Supports different protocols like FrSky, FlySky, Walkera, Futaba, ... .
* [mLRS](https://github.com/olliw42/mLRS) ⭐ 513 | 🐛 19 | 🌐 C | 📅 2026-02-08 - Mavlink compatible LRS.
* [openLRSng](https://github.com/openLRSng/openLRSng) ⭐ 288 | 🐛 45 | 🌐 C | 📅 2018-11-22 - Next generation of OpenLRS, stall since 2018.
* [Raven LRS](https://github.com/RavenLRS/raven) ⭐ 171 | 🐛 9 | 🌐 C | 📅 2020-06-04 - Lora based, 2019.
* [OpenSky](https://fishpepper.de/projects/opensky/) - Alternative firmware for FrSky modules, 2016.
* [DeviationTX](https://deviationtx.com/) - Alternative firmware for Walkera, 2016.

## VTX 📺

Videotransmitter (VTX) are analog or digital radio transmitter on your drone, which send usually a videostream of your front camera (first person view - FPV) but can also transmit arbitrary information or establish a somewhat regular bidirectional link between the drone and a groundstation which also offers control uplink etc. See also Ground station.

* [OpenHD](https://github.com/OpenHD/Open.HD) ⭐ 2,292 | 🐛 27 | 🌐 C++ | 📅 2026-02-08 - Use 2.4 / 5.8 GHz wifi hardware and SBCs on air and groundside to provide a video and telemetry downlink and an optional control uplink. Try to develop a more efficient dedicated hardware board. [Compare different open digital links](https://openhd.gitbook.io/open-hd/general/openhd-vs-alternatives).
* [Wifibroadcast NG](https://github.com/svpcom/wifibroadcast) ⭐ 1,387 | 🐛 22 | 🌐 Python | 📅 2026-02-03 - Use 2.4 / 5.8 GHz wifi hardware and RPIs to provide a video and telemetry downlink.
* [DroneBridge](https://github.com/DroneBridge/DroneBridge) ⭐ 894 | 🐛 17 | 🌐 C | 📅 2022-01-07 - Use 2.4 GHz wifi hardware and RPIs, ESP32 and Android App for bidirectional link, [Comparison](https://dronebridge.gitbook.io/docs/comparison) to the other protocols here.
* [EZ Wifibroadcast](https://github.com/rodizio1/EZ-WifiBroadcast) ⭐ 892 | 🐛 62 | 🌐 C | 📅 2024-01-31 - Oldest and first wifi based VTX setup.
* [OpenVTx](https://github.com/OpenVTx/OpenVTx) ⭐ 451 | 🐛 19 | 🌐 C | 📅 2024-04-04 - Free firmware for open hardware anlog VTX.
* [wtfos](https://github.com/fpv-wtf/wtfos) ⭐ 310 | 🐛 37 | 🌐 Shell | 📅 2025-04-13 - Rooting and mod DJI FPV sender and receiver.
* [DigiView-SBC](https://github.com/fpvout/DigiView-SBC) ⭐ 107 | 🐛 10 | 🌐 CSS | 📅 2021-06-23 - Receive DJI HD signal, alpha 2021.
* [wfb-ng on OpenIPC](https://github.com/OpenIPC/sandbox-fpv) ⭐ 65 | 🐛 0 | 🌐 C | 📅 2024-01-10 - Wifibroadcast NG on OpenIPC compatible CCTV modules, capable of 120fps or 4k video feeds with telemetry
* [VTX Power Measure](https://github.com/mrRobot62/vtx_power_measure) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-11-29 - Python scripting the Immersion RF-Meter V2.
* [RubyFPV](https://rubyfpv.com) - Use 2.4 / 5.8 GHz wifi hardware and RPIs to provide a video and telemetry downlink and an optional control uplink. No source provided but plugin system.

## Camera & Gimbals 🎥

Cameras feed the onboard videotransmitter for downlink or record as DVR with higher quality. See also VTX for custom systems which allow you different camera setups.

* [Gyroflow](https://github.com/gyroflow/gyroflow) ⭐ 8,235 | 🐛 61 | 🌐 Rust | 📅 2026-01-14 - Use IMU sensor data to smooth HD video recordings.
* [STORM32BGC](https://github.com/olliw42/storm32bgc) ⭐ 710 | 🐛 3 | 🌐 C++ | 📅 2025-11-30 - Firmware and brushless gimbal controller.
* [RC Headtracker](https://github.com/dlktdr/HeadTracker) ⭐ 446 | 🐛 55 | 🌐 C++ | 📅 2025-12-08 - Turn camera gimbal when you turn your googles. Based on Arduino and Bluetooth.
* [OpenHD on thermal cameras](https://openhd.gitbook.io/open-hd/hardware/cameras) - How to user RPI to read this sensors.
* [Open Brushless Gimbal](https://www.thingiverse.com/thing:110731) - 2013.

## GPS 🛰️

Global Navigation Systems like GPS allow to determine the current position of your drone. Consumer GPS modules are cheap, but some can be tweaked to gain better accuracy on postprcessing or live.

* [GNSS SDR](https://gnss-sdr.org) - Software toolchain to process radio signals of GPS, Baidu, GLONASS that are received by SDR hardware radio backends.
* [rtklib](https://www.rtklib.com) - Software toolchain to increase precision of GNSS signals by applying realtime or post-processing to eliminate interferences. Signals recorded by SDR or some commercial GPS modules.
* [Vicon MavLink](https://github.com/bo-rc/ViconMAVLink) ⭐ 27 | 🐛 1 | 🌐 C | 📅 2019-06-13 - Get indoor positioning via commercial optical systems for a whole drone swarm.

## Sensors 🌡️

A drone uses more sensors like compass, barometer, airspeed or current to increase position estimation, or to show the system performance

* [QLiteOSD](https://github.com/Qrome/QLiteOSD) ⭐ 30 | 🐛 6 | 🌐 C++ | 📅 2024-07-20 - ESP32 based OSD to read sensors without FC.
* [3D Printed Drone Build - How to Wire OpenHD and Ultrasonic Abstacle Avoidance](https://www.youtube.com/watch?v=HNR1mqUDpoE) - ultrasonic obstacle avoidance for quadcopter and OpenHD teamplay.

See [Ardupilot - Optional hardware](https://ardupilot.org/copter/docs/common-optional-hardware.html) for more ideas.

## Video Receivers 📶

Googles have modul bays to support different radio protocols or HDMI input. See also VTX for custom systems which allow you different camera setups.

* [FENIX-rx5808-pro-diversity](https://github.com/JyeSmith/FENIX-rx5808-pro-diversity) ⭐ 107 | 🐛 5 | 🌐 C++ | 📅 2021-03-06 - Open Hardware 5,8GHz analog module with diversity for googles.
  * [rx5808 pro divesity](https://github.com/sheaivey/rx5808-pro-diversity) ⭐ 711 | 🐛 40 | 🌐 C++ | 📅 2024-02-21
* [rpi-rx5808-stream](https://github.com/xythobuz/rpi-rx5808-stream) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2017-06-20 - RPI based 5,8GHz analog with diversity streaming server.
* [DIY Homemade FPV Monitor](https://hackaday.io/project/160893-diy-homemade-fpv-monitor) - 5,8GHz analog display with diversity.

## Antennas and Trackers 📡

Transceiver as well as receivers can be tweaked with custom antenna configurations and tracker can support directional antennas. They use multiple receivers and diversity, or telemetry to point to your drone.
This is more professional equipment to do beyond VLOS flights and not needed for novice pilots. There are also approaches to use 4G for video and control link for extra extend.

* [u360gts](https://github.com/raul-ortega/u360gts/) ⭐ 260 | 🐛 38 | 🌐 C | 📅 2025-01-30 - 360° motor tracker using F2/F3 controllers that control, firmware + hardware + case, 2020.
* [AntTracker](https://github.com/zs6buj/AntTracker) ⭐ 185 | 🐛 1 | 🌐 C | 📅 2025-12-04 - Servo based using F1 / ESP8266 / ESP32 controllers, 2019.
* [open360tracker](https://github.com/SamuelBrucksch/open360tracker) ⭐ 42 | 🐛 3 | 🌐 C++ | 📅 2016-11-02 - 360° servo tracker 2016.
  * [Amv-open360tracker](https://github.com/raul-ortega/amv-open360tracker) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2016-03-10 - Fork 2016.
  * [Amv-open360tracker 36bit](https://github.com/ericyao2013/amv-open360tracker-32bits) ⭐ 1 | 🐛 0 | 📅 2016-06-03 - Fork 2016.
* [open360tracker v2](https://www.thingiverse.com/thing:2568906) - Simplified design, all components in moving head.
* [Ghettostation Antenna Tracker](https://www.thingiverse.com/thing:547358) - Different forks 2014.
* [DIY Helical Antenna For Long Range FPV](https://www.youtube.com/watch?v=aH0cW9XJ4D4) - 5,8GHz helical directional antenna for analog googles with 3D printed skeleton.
* [Cloverleaf Antenna - Build Instructions](https://www.youtube.com/watch?v=JGm9ESx4yzE)- 5.8GHz omnidirectional antenna for analog video transmission.

## Telemetry & Logs 📊

Sensor values and control information are shared via common serial protocols which can be recorded onboard (blackbox) on internal SD cards at FC, or transferred to your TX handset or Groundstation. Useful to find lost drones, as well as debug and tune PID and flight behavior

* [MAVlink](https://github.com/mavlink/mavlink) ⭐ 2,146 | 🐛 139 | 🌐 Python | 📅 2026-02-09 - Modern extensible protocol from hobbiests ... commercial UAV.
* [betaflight-tx-lua-scripts](https://github.com/betaflight/betaflight-tx-lua-scripts) ⭐ 686 | 🐛 9 | 🌐 Lua | 📅 2026-01-23 - Script to show telemetry and control e.g. CAM, VTX settings.
* [OpenLog](https://github.com/sparkfun/OpenLog) ⭐ 589 | 🐛 22 | 🌐 C++ | 📅 2022-06-09 - With [blackbox](https://github.com/thenickdude/blackbox/) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2015-01-14 firmware for blackbox data recorder (today usually part of main FC).
* [PID-Analyzer](https://github.com/Plasmatree/PID-Analyzer) ⭐ 414 | 🐛 33 | 🌐 Python | 📅 2021-03-04 - Read blackbox and tune PID control variables.
* [LuaTelemetry](https://github.com/teckel12/LuaTelemetry) ⭐ 302 | 🐛 5 | 🌐 Lua | 📅 2021-10-03 - OpenTX / EdgeTX script that renders live cockpit and map from telemetry datastream.
* [UAVLogViewer](https://github.com/ardupilot/uavlogviewer) ⭐ 209 | 🐛 138 | 🌐 JavaScript | 📅 2025-09-23 - Web application for Ardupilot logs.
* [openXsensor](https://github.com/openXsensor/openXsensor) ⭐ 184 | 🐛 37 | 🌐 C | 📅 2023-07-30 - Convert and alter telemetry protocols.
* [YAMSPy](https://github.com/thecognifly/YAMSPy) ⭐ 120 | 🐛 12 | 🌐 Python | 📅 2024-04-08 - Read MSP serial protocol with Python.
* [INAV blackbox viewer](https://github.com/iNavFlight/blackbox-log-viewer) ⭐ 45 | 🐛 18 | 🌐 JavaScript | 📅 2024-08-24 - Render sensor / motor values as video overlay OSD.
* [otxtelemetry](https://github.com/olliw42/otxtelemetry) ⭐ 40 | 🐛 0 | 🌐 Lua | 📅 2023-12-26 - OpenTX / EdgeTX script to add Mavlink support.
* [flightlog2x](https://github.com/stronnag/bbl2kml) ⚠️ Archived - Convert blackbox logs of INAV, OpenTX, ... to CSV, GPX, KML and render tracks and trajectory with different performance styles, separate [GUI](https://github.com/stronnag/fl2xui) ⚠️ Archived.
* [INAV blackbox tools](https://github.com/iNavFlight/blackbox-tools) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2026-01-17 - Convert to CSV timeseries files or as visual OSD overlay.
* [OSD-subtitles](https://github.com/kristjanbjarni/osd-subtitles) ⭐ 14 | 🐛 0 | 🌐 HTML | 📅 2023-03-09 - Render Blackbox logs to OSD as subtitle for synconous plaback with video file.
* [Cyphal](https://opencyphal.org) - Fka. UAVCAN industrial only drone bus system.
* [Dashware](http://www.dashware.net/dashware-download/) - Closed Source OSD rendering for blackbox logs.

## Mission Control & Basestation 🗺️

Ground Control Stations (GCS) on laptops / tablets allow better overview of flight parameters and position for mission control during long range / time flights. Also see [Ardupilot.org - Choosing GCS](https://ardupilot.org/copter/docs/common-choosing-a-ground-station.html).

* [QGroundControl](https://github.com/mavlink/qgroundcontrol) ⭐ 4,314 | 🐛 1,054 | 🌐 C++ | 📅 2026-02-08 - Mavlink, Desktop and mobile.
* [mwptools](https://github.com/stronnag/mwptools) ⚠️ Archived - Waypoint mission planner esp. for INAV including INAV Radar and ADS-B sources.
* [Dreka GCS](https://github.com/Midgrad/Dreka) ⭐ 62 | 🐛 12 | 🌐 QML | 📅 2022-10-27 - A new GCS (currently limited but more modern look & feel).
* [BulletGCSS](https://github.com/danarrib/BulletGCSS) ⭐ 55 | 🐛 14 | 🌐 JavaScript | 📅 2025-11-15 - Uses GSM and MQTT for extra long range links.
* [APM Planner 2.0](https://ardupilot.org/planner2/) - Mavlink compatible, with experience from MP and Q Groundcontrol.
* [MissionPlanner](https://ardupilot.org/planner/index.html) - Waypoint Mission planning esp. for Ardupilot.
* [MAVProxy](https://ardupilot.org/mavproxy/) - Commandline and GUI mission planer and telemetry viewer and processor.

## Companion Computers & Integration 💻

Your FC is focused on realtime control for maneuvers, while additional computers add ressources for more complex data processing, see also [Arudpilot.org - Companion Computers](https://ardupilot.org/dev/docs/companion-computers.html) and digital VTX systems above.

* [ROS](https://github.com/ros/ros) ⚠️ Archived - Robot Operating System, to handle more complex and interactive flights.
* [DroneKit](https://github.com/dronekit/dronekit-python) ⭐ 1,853 | 🐛 437 | 🌐 Python | 📅 2024-05-30 - Multi platform integration ecosystem including Mavlink radio link.
* [öchìn CM4](https://github.com/ochin-space/ochin-CM4) ⭐ 96 | 🐛 0 | 🌐 Shell | 📅 2025-05-09 - RPI Compute Module carrier board dedicated for FC
* [APsync](https://ardupilot.org/dev/docs/apsync-intro.html) - Mavlink focused OS for different SBCs.
* [RPanion](https://www.docs.rpanion.com/software/rpanion-server) - Mavlink focused RPI image.

## Computer Vision 🤖

CV is on the processing of what you see at the UAV live image or recordings. This is about aerial mapping, or machine learning powered flight planning. See also [UAV Mapping Guidelines](https://uav-guidelines.openaerialmap.org/).

* [Fast-Planner](https://github.com/HKUST-Aerial-Robotics/Fast-Planner) ⭐ 3,181 | 🐛 84 | 🌐 C++ | 📅 2024-10-24 - Learn drones to avoid obstacles on the course.
* [Faster](https://github.com/mit-acl/faster) ⭐ 1,189 | 🐛 15 | 🌐 C++ | 📅 2025-03-10 - ML let drones learn to avoid obstacles.
* [OpenAerialMap](https://github.com/hotosm/OpenAerialMap/) ⭐ 294 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2026-02-04 - Share Drone shots for disaster response etc.
* [DroneDB](https://github.com/DroneDB/DroneDB) ⭐ 256 | 🐛 33 | 🌐 C++ | 📅 2026-01-30 - Store and archive drone shots and aerial imagery.
* [Fire Detection UAV](https://github.com/AlirezaShamsoshoara/Fire-Detection-UAV-Aerial-Image-Classification-Segmentation-UnmannedAerialVehicle) ⭐ 237 | 🐛 7 | 🌐 Python | 📅 2021-05-06 - ML learn drones to spot fire.
* [Drone-net](https://github.com/chuanenlin/drone-net) ⭐ 164 | 🐛 8 | 🌐 Python | 📅 2020-10-01 - ML detect quadcopters within photos / videos using YOLO v4.
* [DroneAid](https://github.com/Call-for-Code/DroneAid) ⭐ 138 | 🐛 10 | 🌐 HTML | 📅 2026-01-26 - ML find persons in disaster response by emergency markers.
* [OpenAthena](https://github.com/mkrupczak3/OpenAthena) ⚠️ Archived - Auto GCP detection using markers
* [AirPose](https://github.com/robot-perception-group/AirPose) ⭐ 56 | 🐛 4 | 🌐 Python | 📅 2022-02-21 - ML human pose estimation from drone perspective.
* [AVCBet](https://github.com/lironui/ABCNet) ⭐ 41 | 🐛 6 | 🌐 Python | 📅 2023-09-29 - ML segmentation of areas for aerial imagery.
* [BANet](https://github.com/lironui/BANet) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2022-07-29 - ML segmentation of areas for aerial imagery.
* [OpenDroneMap](https://www.opendronemap.org/) - Stitch photos to aerial imagery, calc 3D models, ... .
* [OpenMMS](https://www.openmms.org/) - Mobile mapping system that carries a laser scanner.
* [Autonomous Drone Dodges Obstacles Without GPS](https://hackaday.com/2021/11/03/autonomous-drone-dodges-obstacles-without-gps/) - RPI based CV and route planning and obstacle avoidance.

## Complete Systems 🎁

Dedicated drones and toolchains to help on a dedicated topic

* [Guiness World record drone build](https://www.youtube.com/watch?v=RoSSaSkOTTc) - How a 300mph / 480 km/h quadcopter rocket needs to be designed and build. Similar is the [AOSHS5 build](https://www.youtube.com/watch?v=oG2GaSMlfdo) (but only 200mph).
* [Arduino FPV Mini Drone](https://www.instructables.com/Make-a-Tiny-Arduino-Drone-With-FPV-Camera/) - Woodframed mini quad without BLDC and custom RF link around MultiWII
* [SearchWing](https://www.hs-augsburg.de/searchwing/de/willkommen/) - A Search and Rescue RC airplane for visual inspection of huge areas on sea to rescue people from refugee boats at the EU sea border. Waterproof to land beside the SAR mothership.
* [Dronecoria](https://dronecoria.org) - Octocopter made from wood as heavy lift to drop seeds.
* [Agilicious](https://agilicious.dev) - 3D printed OSHW drone and ecosystem esp. for CV autonomous agile flight research, 2023
* [Crazyflie](https://www.bitcraze.io/documentation/system/platform/) - A not so FPV drone that uses custom modules and different technology for swarm control.
* [ESP-Drone](https://github.com/Circuit-Digest/ESP-Drone) ⭐ 1,750 | 🐛 16 | 🌐 C | 📅 2025-06-16 - ESP32 and PCB only based quadcopter without FPV but custom wifi on brushed
* [ESP32 Drone](https://hackaday.io/project/188578-esp32-drone) - no traditional FPV, but low cost quad using ESP32 board, 2022.
* [Wifree-copter](https://open-diy-projects.com/wifree-copter/) - Easy 3D printed copter that uses RPI as WIFI remote control with App, 2016.

## Security & Safety 🪂

### Simulators 🌐

Before you damage any hardware you can learn to avoid common pitfalls and train by virtual flights using your handhelt TX. Other allow to test / benchmark autopilots to work in controlled environments.

The most consumer friendly trainer simulators are commercial, but available for Linux, macOS as well ([Freerider Recarged](https://fpv-freerider.itch.io/fpv-freerider-recharged), [Liftoff](https://store.steampowered.com/app/410340/Liftoff_FPV_Drone_Racing/), [DRL Sim](https://thedroneracingleague.com/drlsim/), [Velocidrone](https://www.velocidrone.com/).

* [AirSim](https://github.com/microsoft/AirSim) ⭐ 17,938 | 🐛 723 | 🌐 C++ | 📅 2025-05-15 - By Microsoft for algorithm testing.
* [JSBsim](https://github.com/JSBSim-Team/jsbsim) ⭐ 1,888 | 🐛 46 | 🌐 C++ | 📅 2026-02-07 - With bindings to Python, Matlab.
* [GAZEBOsim](https://github.com/gazebosim/gz-sim) ⭐ 1,200 | 🐛 519 | 🌐 C++ | 📅 2026-02-08 - Multi robot.
* [jMAVSim](https://github.com/PX4/jMAVSim) ⭐ 101 | 🐛 16 | 🌐 Java | 📅 2026-01-29 - For Mavlink.
* [crrcsim](https://sourceforge.net/projects/crrcsim/) - For rc airplanes, 2018.
* [Picasim](http://www.rowlhouse.co.uk/PicaSim/download.html) - For rc planes, closed source, sucessor of SSS, stall since 2019.
* FlightGear - Usually for big airplanes, but can be paired with FC good description [from PaparazziUAV](https://wiki.paparazziuav.org/wiki/FlightGear) or [by Arduplane](https://ardupilot.org/dev/docs/simulation-2.html) for simulation.
* ROS supports simulations like described [by PX4](https://docs.px4.io/master/en/ros/ros2_comm.html).

### Checklists 📋

Malfunction can have dramatic consequences, as well as your drone can cause massive damages. To avoid unnecessary risks, a step by step protocol and documentation is mandatory for every flight in case you might use your insurance.

#### build power check

#### maiden flight check

* [iNav Pre-maiden Checklist](https://www.mrd-rc.com/tutorials-tools-and-testing/flight-controller-therapy/inav-pre-maiden-checklist-a-helpful-reminder-and-saver-of-foam/) by Mr.D for fixed wing

#### regular flight check

* [Ardupilot Copter Checklist](https://ardupilot.org/copter/docs/checklist.html).

### ID Systems 🛂

We share the airspace with other pilots. RC copters and planes are hard to spot, so it is recommend to share your position via transponder systems. This allows also tracking of illegal maneuvers.

* [SoftRF](https://github.com/lyusupov/SoftRF) ⭐ 953 | 🐛 0 | 🌐 C | 📅 2026-02-07 - UAV edition, supports also FLARM and more.
* ADS-B transmitters of airplanes can be received using software defined radios can be realized using cheap USB DVB-T receivers. Can be integrated via radar extensions like [mwp-radar-view](https://github.com/stronnag/mwptools/wiki/mwp-Radar-View) ⚠️ Archived, [Ardupilot ADS-B receiver](https://ardupilot.org/copter/docs/common-ads-b-receiver.html) or in OpenHD. Is part of Mavlink protocol and shows up on most GCS.  Can also be viewed online like [adsb-exchange.com](https://globe.adsbexchange.com/).
* [ArduPilot RemoteID Transmitter](https://github.com/ArduPilot/ArduRemoteID) ⭐ 175 | 🐛 37 | 🌐 C++ | 📅 2025-07-04 - FCC RemoteID with Mavlink and DroneCAN integration.
* [INAV Radar](https://github.com/OlivierC-FR/ESP32-INAV-Radar) ⭐ 92 | 🐛 4 | 🌐 C++ | 📅 2022-05-02 - LORA radio and ESP32 broadcast positions and show it at your OSD.
* [WiFi RID capture](https://github.com/sxjack/unix_rid_capture) ⭐ 65 | 🐛 9 | 🌐 C | 📅 2023-04-20 - Capture remote identification signals  with sniffer.
* [FormationFlight](https://formationflight.org/getting-started/) - Wifi radio of ESP32 to broadcast position and telemetry and show it at your OSD.
* [Glidernet](https://www.glidernet.org) - Share FLARM / ADS-B positions online.
* [Opensky Network](https://opensky-network.org) - Share ADS-B positions online.
* [Drone Detection and Tracking Using RF Identification Signals ](https://www.mdpi.com/1424-8220/23/17/7650) - Track DJI drones using wifi and KISMET sniffer.

### Hacking & Hijacking 🔓

Radio links per se are unsafe and can easily be jammed.

* [Drone-ID Receiver for DJI OcuSync 2.0](https://github.com/RUB-SysSec/DroneSecurity) ⭐ 1,205 | 🐛 20 | 🌐 Python | 📅 2023-03-10 - Decoding DJI radio transmissions including DroneID and pilot location with SDR in python
* [RemoteID Spammer/Spoofer](https://github.com/jjshoots/RemoteIDSpoofer) ⭐ 498 | 🐛 2 | 🌐 C | 📅 2025-09-26 - An ESP8266/NodeMCU Drone RemoteID Spoofer
* [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD) ⭐ 215 | 🐛 228 | 🌐 Python | 📅 2024-06-24 - CVEs for semi-autonomous machines.
* [WTF WJI, UAV CTF?](https://ftp.fau.de/cdn.media.ccc.de/events/camp2023/h264-hd/camp2023-57063-eng-WTF_DJI_UAV_CTF_hd.mp4) - Talk on DJI mini 2 reverse engeniering to bypass manufacturers limitations. Mem dump analysis and crypto keys decryption and radio analysis. About DJI ecosystem and used [open source components](https://www.dji.com/de/opensource) (cccamp23 by Felix Domke).
* [Debugging Microcontrollers ](https://media.ccc.de/v/camp2023-57321-debugging_microcontrollers) - Talk on difficult debugging the PX4 hardware micocontrollers with RTOS NuttX  (cccamp23 by Niklas Hauser).
* [5.8GHz video demodulation](https://www.youtube.com/watch?app=desktop\&v=rl8ACNnjPFA) - Using hack-rf SDR.
* [GPS jamming](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms) - Use BladeRF SDR with GNUradio to block satellites.
* [GPS spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf) - Controll others UAVs by faking satellite transmissions from ground.

## Accesoirs 🪠

With 3D printing it is easy to get useful addons for your equipment and models

* [Delta 5 race timer](https://github.com/scottgchin/delta5_race_timer) ⭐ 161 | 🐛 47 | 🌐 JavaScript | 📅 2021-06-08 - Use 5.8GHz video signals to trigger lap counter.
  * [RotorHazard](https://github.com/RotorHazard/RotorHazard) ⭐ 243 | 🐛 61 | 🌐 Python | 📅 2026-02-06 - Sucessor with multinode and central RPI server
* [Capture The Flag for drones](https://github.com/SeekND/CaptureTheFlag) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2021-10-12 - Optical system to emulate a flag for close team-fights.
* Gimbal protection
* holder & stands
* actioncam mounts
* rotor guards
* ...

### Mobile Apps 📱

Free and useful applications to use on your mobile device. Might be not nessesarry open source

* [SpeedyBee](https://www.speedybee.com/speedy-bee-app/) - Is an Appllication for Flight controller parameters settings and blackbox log reader for betaflight, iNAV, emuflight  [Android](https://play.google.com/store/apps/details?id=com.runcam.android.runcambf), [iOS](https://apps.apple.com/us/app/speedybee-app/id1150315028).
* [BLHeli\_32](https://play.google.com/store/apps/details?id=org.blheli.BLHeli_32) - App is for configuring BLHeli\_32 ESCs.
* [FPV Video Channelsorter 5.8GHz](https://play.google.com/store/apps/details?id=florian.felix.flesch.fpvvideochannelsorter) - Sorts the channels for each pilot over the available frequencies.
* [UAV Forecast](https://www.uavforecast.com) - See the weather forecast, GPS satellites, solar activity (Kp), No-Fly Zones and flight restrictions [Android](https://play.google.com/store/apps/details?id=com.uavforecast), [iOS](https://apps.apple.com/us/app/uav-forecast/id1050023752).
* [Go FPV](https://play.google.com/store/apps/details?id=com.vertile.fpv3d) - A UVC Video Camera display and capture app, built for my DIY First Person View goggles.

### Workbench 🧰

* [smoke stopper](https://oscarliang.com/smoke-stopper/) - Avoid damaging your expensive components during build up.
* [4AxisFoamCutter](https://github.com/rahulsarchive/4AxisFoamCutter) ⭐ 95 | 🐛 5 | 🌐 nesC | 📅 2021-07-22 - Create aerodynamic wings from foam.

## Legal Information 🏛️

Depending on the country you live in, the laws and legal rules of airspace may vary.

* [Luftfahrt Bundesamt](https://www.lba.de/DE/Drohnen/Drohnen_node.html) - 🇩🇪 Rechtlicher Rahmen.

* [Deutsche Flugsicherung GmbH](https://www.dfs.de/homepage/de/drohnenflug/) - 🇩🇪 Durchführung von Prüfungen und Zulassungen.

* [Digitale Plattform Unbemannte Luftfahrt](https://www.dipul.de/homepage/de/) - 🇩🇪 Kartenplattform, mit alternativ [Droniq App](https://play.google.com/store/apps/details?id=de.droniq.droniqapp\&hl=de\&gl=US).

* [Bundesnetzagentur](https://www.bundesnetzagentur.de/DE/Sachgebiete/Telekommunikation/Unternehmen_Institutionen/Frequenzen/Grundlagen/Frequenzplan/frequenzplan-node.html) - 🇩🇪 Zulässige Sendefrequenzen und -Leistungen.

* [Urząd Lotnictwa Cywilnego](https://drony.ulc.gov.pl) - 🇵🇱 Urząd Lotnictwa Cywilnego - allows to apply for license in Poland and EU

* [Bezzałogowe Statki Powietrzne](https://ulc.gov.pl/pl/drony) - 🇵🇱 List of regulations regarding operations of UAV in Poland

## Communities 🗣️

Every hobby makes more fun and progress if you share your ideas and questions to others. Beside the UAV pilot communities there are plenty of modder and hackers out there.

* [Dronecode foundation](https://www.dronecode.org) - Home for MavLink, QGroundcontrol and PX4, part of Linux foundation.
* [FPV Freedom Coalation](https://fpvfc.org/) - Keep drones hackabel and safe.
* [Deutscher Modellflieger Verband e.V.](https://www.dmfv.aero) - 🇩🇪 Events, local communities, assurance, ... .
* [Deutscher Aero Club e.V.](https://www.daec.de) - 🇩🇪.

### Forums & Social Media

* [rcroups.com](https://rcroups.com) - Most projects offer here support.
* [diydrones.com](https://diydrones.com) - Group to most projects, hardware and countries.
* [rotorbuilds.com](https://rotorbuilds.com) - Recipes to custom builds.
* [openrcforums.com](https://openrcforums.com) - From the old days till the present working on open modells.
* [Stackexchange Drones](https://drones.stackexchange.com/) - Is Stack Overflow Q\&A for drone building.
* [reddit \motorcopter](https://www.reddit.com/r/Multicopter/) - Everything from flights, crashes, repairs, custom mods, ... .
* [reddit \RCPlanes](https://www.reddit.com/r/RCPlanes/) - Everything but for RC planes.
* [OscarLiang.com](https://OscarLiang.com) - Important blog with builds and configurations and knowledge.
* [intofpv.com](https://intofpv.com) - Forum with helpful information about anything FPV related.
* [INAV fixed wing group](https://inavfixedwinggroup.com/) - Forum, Blog, Builds on fixed wing esp. with INAV compatible autopilot.
* [fpv-community.de](https://fpv-community.de) - 🇩🇪 Auch Selbstbau.
* [RC-Network.de](https://RC-Network.de) - 🇩🇪 Über Selbstbau auch von Schiffen und Autos. Sehr umfangreiches [Wiki](https://wiki.rc-network.de/wiki/Hauptseite).
* [kopterforum.de](https://kopterforum.de) - 🇩🇪 Auch Selbstbau.

### Video Channels

* [Painless 360](https://www.youtube.com/c/Painless360) - UK builds, mods and configuration basics.
* [ArxangelRC](https://www.youtube.com/c/ArxangelRC) - BG builds and configurations as well as (a bit) mapping.
* [Joshua Bardwell](https://www.youtube.com/c/JoshuaBardwell) - US, build and general tips on copters, slogan 'You gonna learn something today'.
* [PawelSpechalski](https://www.youtube.com/c/Pawe%C5%82Spychalski) - INAV core team, mostly copters, slogan 'Happy Flying'.
* [Andrew Netwon](https://www.youtube.com/c/AndrewNewtonAustralia) - AU, mostly airplane reviews and build tipps.
* [Mr. D - Falling with style](https://www.youtube.com/c/MrDFallingwithstyle) - UK, Darren, INAV.
* [CurryKitten](https://www.youtube.com/c/CurryKitten/) - Reviews, but also OpenHD and ExpressLRS.
* [MarioFPV](https://www.youtube.com/channel/UCX2UiZjg485tDoq_Yl4Pysw) - OpenHD, RubyFPV, WFG-NG experiments.
* [TreeOrbit](https://www.youtube.com/user/montreetormee) - OpenHD, RubyFPV experiments.
* [flitetest.com](https://flitetest.com) - TV show, unusual DIY builds.
* [Livyu FPV](https://www.youtube.com/c/LivyuFPV/videos) - Flight footage and repair videos for DIY drone electronics.
* [Adam G does FPV](https://www.youtube.com/c/AdamGdoesFPV) - Builds, mods and basics.
* [BLuefish](https://www.youtube.com/channel/UCmULLc8W-knTqiFqJgw3-FA) - Builds, INAV, longrange.
