## Broad-scope wireless multi-tools

**[Bruce](https://github.com/BruceDevices/firmware)** — WiFi, BLE, SubGHz via CC1101, NFC/RFID via PN532, IR, FM, BadUSB, nRF24 jamming and MouseJack, plus a JavaScript engine. Supports boards including the M5Stack Cardputer and LILYGO T-Embed CC1101, and reads Flipper `.sub` files. AGPL-3.0. [Flasher](https://bruce.computer).

**[ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder)** — WiFi and BLE frame capture, transmission, PCAP, wardriving. Ships ESP32-C5 builds for 2.4 and 5 GHz alongside classic 2.4 GHz-only builds. MIT. [Build guide](https://esp32marauder.com/builds.html).

**[GhostESP](https://github.com/GhostESP-Revival/GhostESP)** — ESP-IDF-based firmware covering WiFi, BLE, NFC, IR, SubGHz, BadUSB, plus 5 GHz and 802.15.4/Zigbee on the C5, and W5500 Ethernet tools (port and ARP scan, ARP poisoning, MITM, credential capture). Live Wireshark streaming and on-device PCAP, hc22000 and WiGLE conversion. GPL-3.0. [Docs](https://ghostesp.net).

**[Poseidon](https://github.com/GeneralDussDuss/poseidon)** — Firmware for the M5Stack Cardputer-Advance: WiFi, BLE, SubGHz via CC1101, nRF24, LoRa and mesh via SX1262, IR, layer-3 DHCP/WPAD, BadUSB, MouseJack. Includes Argus for background handshake capture. ESP-NOW satellites extend it: TRIDENT (ESP32-C5) adds 5 GHz, Zigbee and 802.15.4; an nRF52840 Feather adds BLE 5.0 (PoC). MIT.

**[ESP32-DIV](https://github.com/cifertech/ESP32-DIV)** — WiFi, BLE, SubGHz, RF on the Cheap Yellow Display. MIT.

**[HaleHound-CYD](https://github.com/JesseCHale/HaleHound-CYD)** — KeeLoq decoding and BLE GATT resolution. Proprietary binaries.

**[ESP-HACK](https://github.com/Teapot174/ESP-HACK)** — SubGHz, BLE and IR pentesting firmware for ESP32.

**[BruceButBetter](https://github.com/Yoursel71/BruceButBetter)** — Bruce fork for ESP32-S3 N16R8 adding Si5351 alongside SubGHz, NFC/RFID, IR, WiFi/BLE and nRF24.

**[Willy Firmware V3](https://github.com/h-RAT/Willy_Firmware_V3_T-Embed_CC1101)** — All-in-one for the LILYGO T-Embed CC1101 and T-Embed CC1101 Plus: SubGHz, IR, NFC, WiFi, BLE and nRF24 (Plus model only), with Flipper-compatible `.sub` and IR files, KeeLoq 64-bit support, raw SubGHz capture and RSSI tuning. [V2 for generic ESP32](https://github.com/h-RAT/Willy_Firmware_V2_ESP32_Flipper_Zero_Alternative).

**[Bruce-Smoochie](https://github.com/arpitxp/Bruce-Smoochie-esp32)** — Bruce-based open-hardware reference design using an ESP32-S3 WROOM-1, WiFi, BLE, CC1101 SubGHz, nRF24+PA/LNA, IR, PN532 NFC and NEO-6M GPS. Includes schematics, pinouts and a bill of materials.

**[Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project)** — WiFi attack suite and Evil Portal for M5Stack.

**[M5Stick-Nemo](https://github.com/n0xa/m5stick-nemo)** — IR TV-B-Gone, BLE spam, RF.

**[nyanBOX](https://github.com/jbohack/nyanBOX)** — ESP32-WROOM-32U with 3× nRF24L01+ for counter-surveillance detection. Passive detection of surveillance cameras (Ring, Nest, Arlo, Hikvision, Dahua, Axis and others by OUI), Flock ALPRs, law-enforcement body cams and radios, drone Remote ID, and BLE trackers, each with an RSSI locate mode. Includes Evil Portal with SSID cloning, deauth including camera-targeted, BLE and Sour Apple/Droid spam, and AirTag/iBeacon/Remote ID spoofers. MIT license file; binaries only.

**[nRFBox](https://github.com/cifertech/nRFBox)** — ESP32/nRF24 platform for 2.4 GHz scanning, spoofing and jamming, with an OLED interface. MIT license file; binaries only, installed via a web flasher. Requires standard 5 V charging; USB-PD is unsupported.

**[Biscuit (Xteink X4)](https://github.com/yattsu/biscuit)** — Recon, offense, defense and comms tiles on an e-paper reader.

**[Picoware](https://github.com/jblanked/Picoware)** — General-purpose handheld platform with WiFi scanning and an AP server. Runs on PicoCalc, Cardputer, Pico and ESP32. GPL-3.0.

**[ArithOS](https://github.com/EinsPommes/ArithOS)** — PicoCalc pentest toolkit.

**[M5PORKCHOP](https://github.com/bmorcelli/M5PORKCHOP)** — Packet sniffer with an RPG-style interface and gamified reconnaissance.

## Dual-band 2.4 and 5 GHz

**[ESP32 Marauder on ESP32-C5](https://github.com/justcallmekoko/ESP32Marauder)** — 5 GHz scanning, deauthentication and wardriving with PCAP output, fully open source. Binaries `esp32c5devkitc1`, `dual_mini_c5` and `t_dongle_c5` ship in the standard release.

**[Biscuit DIY](https://biscuitshop.us/pages/diy-biscuits)** — Dual-band WiFi, BLE attacks, wardriving with WiGLE upload, packet capture, Bluetooth phone control. Needs an ESP32-C5 with 8 MB flash and 8 MB PSRAM. Biscuit Pro also acts as an ESP-NOW mesh coordinator for Piglet nodes. Closed binaries, no license file. [Flasher](https://github.com/CodeHedge/diy_node_web_flasher).

**[ESP32 Dual Band Wardriver (JCMK C5)](https://github.com/justcallmekoko/ESP32DualBandWardriver)** — Logs 2.4 GHz, 5 GHz and BLE to WiGLE CSV on SD, web UI, GPS. Runs a Core/Node ESP-NOW mesh where nodes need neither SD nor GPS, a dock mode that auto-uploads to WiGLE and WDGWars on reaching a trigger SSID, and up to five geofence zones that pause logging. ESP32-C5-DevKitC-1 v1.2.

- Power: the JCMK host board and 3V3 supply configurations require removal of the DevKit's 3V3 jumper.

**[Piglet](https://github.com/Hamspiced/piglet)** — ESP32 wardriving platform for the Seeed XIAO line (S3, C3, C6, and C5 for 5 GHz), logging WiGLE CSV to SD with GPS, OLED and a web UI. ESP-NOW mesh node mode forwards scan results to a coordinator that handles GPS and logging; nodes require neither GPS nor SD storage. Compatible coordinators are the JCMK C5 Wardriver and Biscuit Pro. Includes a headless PigletNode build for the XIAO ESP32-C5.

**[cypher-5G-deauther](https://github.com/dkyazzentwatwa/cypher-5G-deauther)** — Dual-band deauthentication with an OLED interface on BW16 hardware.

**[Spectra-Mini-BW16](https://github.com/rusyln/Spectra-Mini-BW16)** — Deauth, beacon and SSID spam, BLE spam including Sour Apple.

**[R4TKN-FIRMWARE-BW16](https://github.com/rusyln/R4TKN-FIRMWARE-BW16)** — Deauthentication, beacon and SSID spam, and BLE spam including Sour Apple, with an ST7735 TFT and three-button UI.

**[Evil-BW16](https://github.com/7h30th3r0n3/Evil-BW16)** — Automated dual-band deauth, serial-controlled, configurable attack cycles.

**[RTL8720dn packet injection](https://github.com/tesa-klebeband/RTL8720dn-WiFi-Packet-Injection)** — Raw 802.11 frame transmission library for RTL8720DN/BW16.

**[RTL8720dn Handshake Capture](https://github.com/rusyln/RTL8720dn-Handshake-Capture)** — Captures WPA/WPA2 four-way handshakes on the RTL8720DN/BW16 dual-band chip.

**[WiFiX-DualBand-Deauther](https://github.com/EmenstaNougat/WiFiX-DualBand-Deauther)** — Combined ESP32 plus BW16 PCB design.

**[Deauther-RTL8720DN](https://github.com/xiv3r/Deauther-RTL8720DN)** — Dual-band deauth.

**[evil-deauther-5ghz-and-2.4ghz](https://github.com/LETSQOOOO/evil-deauther-5ghz-and-2.4ghz)** — Deauth plus evil portal.

## IoT protocols: 802.15.4, Zigbee, Thread, Matter

**[Minino](https://github.com/ElectronicCats/Minino)** — Multiprotocol IoT multitool on ESP32-C6 with GPS, OLED and microSD. BLE, WiFi 6, Zigbee (sniffer, spoofing, Wireshark streaming), Thread, Matter and raw 802.15.4, with PCAP export, Pycatsniffer compatibility, wardriving and OTA. OSHWA-certified open hardware, open firmware.

**[CatSniffer](https://github.com/ElectronicCats/CatSniffer)** — Open-hardware multiprotocol, multiband board for sniffing and communicating across LoRa, Sub-1 GHz, 2.4 GHz, Zigbee, Thread, BLE and WiFi. [Firmware](https://github.com/ElectronicCats/CatSniffer-Firmware).

**[CatSniffer Tools](https://github.com/ElectronicCats/CatSniffer-Tools)** — Host-side toolchain for the CatSniffer stick, with a `catnip` CLI that flashes protocol-specific firmware and pipes captures to Wireshark.

**[ESP32C6 Wireshark 802.15.4 Sniffer](https://github.com/Grrtzm/ESP32C6_Wireshark_802.15.4_Sniffer)** — Minimal ESP32-C6 sniffer with native Wireshark TAP support carrying RSSI, LQI and channel, for Zigbee and Thread. Channel cycling on the BOOT button.

**[Sniffle](https://github.com/nccgroup/Sniffle)** — BLE 4 and 5 sniffer on TI CC13xx/CC26xx hardware, including the CatSniffer.

## NFC, RFID and magstripe

**[BomberCat](https://github.com/ElectronicCats/BomberCat)** — Open-hardware device combining magstripe emulation and NFC tooling. [Firmware](https://github.com/ElectronicCats/bombercat-firmware).

**[Chameleon Ultra](https://github.com/RfidResearchGroup/ChameleonUltra)** — HF and LF NFC card emulation on nRF52840. Open hardware and open firmware.

**[Proxmark3 Iceman](https://github.com/RfidResearchGroup/proxmark3)** — HF and LF RFID analysis, capture, cloning and emulation. Open firmware and client for Proxmark3 hardware.

**[ESP-PN532BLE](https://github.com/bmorcelli/ESP-PN532BLE)** — Arduino/ESP32 library for PN532_BLE devices.

## Fault injection

**[FaultyCat](https://github.com/ElectronicCats/faultycat)** — Open-hardware electromagnetic fault injection tool. [Firmware](https://github.com/ElectronicCats/faultycat-firmware) · [TUI](https://github.com/ElectronicCats/faultycat-TUI).

**[PicoEMP](https://github.com/newaetech/chipshouter-picoemp)** — Pico-based electromagnetic fault injection tool.

## USB-port implants

**[USB Army Knife](https://github.com/i-am-shodan/USBArmyKnife)** — USB gadget firmware for the LILYGO T-Dongle S3. BadUSB with DuckyScript, mass storage and CDROM emulation, USB network device impersonation, VNC screen capture, hot mic, plus an enhanced Marauder fork. Triggers on plug-in, timer or remotely over WiFi. MIT.

**[EvilDuck](https://github.com/cifertech/EvilDuck)** — Open-source USB Rubber Ducky, from Arduino Micro through to ESP32-S3.

**[Pi-Zero-2W-Bad-USB](https://github.com/PsycoStea/Pi-Zero-2W-Bad-USB)** — HID and mass-storage BadUSB for Pi Zero 2 W, with USB gadget rebinding for reinsertion triggers.

**[pico-ducky](https://github.com/dbisu/pico-ducky)** — BadUSB HID via CircuitPython on a Pico.

## Ethernet-port implants

**[RaspyJack](https://github.com/7h30th3r0n3/Raspyjack)** — Pi-based Ethernet implant, including a Pi Zero W with Waveshare Ethernet HAT configuration. LCD control, web UI, payload IDE, loot browser. Responder, DNS spoof, ARP MITM, handshake hunter. BLE scan, spam, beacon flood, MITM, replay. Reverse shell, Discord C2, HTTPS stealth shell, DuckyScript generator. NFC, SDR and CardputerZero support. Exfil over HTTP, DNS, BLE, Discord, SMB, FTP, USB, Dropbox. Includes a Ragnar port.

**[RaspyJack (bmorcelli fork)](https://github.com/bmorcelli/Raspyjack)**

**[ARPoLAN](https://github.com/cifertech/ARPoLAN)** — Network scanning and ARP spoofing on ATmega32u4 plus W5500.

## Autonomous network assessment

**[Ragnar](https://github.com/PierreGode/Ragnar)** — Bjorn's offensive core plus 802.11 WIDS, asset inventory with rogue-device detection, SIEM forwarding, controller-less Tailscale mesh, local LLM analysis against self-hosted endpoints. Pi with e-Paper or TFT, headless server, or Docker. SIEM output includes CEF/LEEF over TLS syslog, Splunk HEC and ECS-formatted Elasticsearch/OpenSearch events, plus printable WIDS incident reports. GPL-3.0.

**[Bjorn](https://github.com/infinition/Bjorn)** — Autonomous scanning, brute force across FTP/SSH/SMB/RDP/Telnet/SQL, file stealing, e-Paper HAT, community attack modules.

**[Xeno](https://github.com/ia-usgs/Xeno)** — Bjorn fork that cycles through stored WiFi credentials and audits each network in turn. Randomised MAC on connect, two-phase nmap, per-SSID device isolation, searchsploit matching and unattended execution of matching ExploitDB code, file harvesting over SSH/FTP/SMB, Flask dashboard. Runs on Pi Zero W through Pi 5 with a dual-band adapter such as an AWUS036ACHM. MIT.

- Default image credentials: `pi`/`raspberry`.

**[Bjorn-V3](https://github.com/Gixar/Bjorn-V3)** — Bjorn fork supporting offline BLE reconnaissance, an 802.11 survey and handshake capture on a second radio while attempting network reconnection. RustScan with nmap fallback, parallel scanning, HTTP fingerprinting, templated web checks, SNMP enumeration, offline CVE matching, a shared credential pool across hosts, Telegram and SMTP reporting, and a FastAPI dashboard. On-device planner scores actions by success and duration.

**[Ragnar_Bjorn](https://github.com/HonestLocksmith/Ragnar_Bjorn)** — Fork adding hardware-bound auth with database encryption at rest, a PiSugar button to swap between Ragnar and Pwnagotchi modes, and a kill-switch endpoint that wipes all data.

**[Ragnar (justinmcmillen-lab fork)](https://github.com/justinmcmillen-lab/Ragnar)**

**[Runar](https://github.com/Morrolan/Runar)** — Bjorn fork for 64-bit Trixie.

**[OptarisDefense](https://github.com/ossiemarks/optaris-defense)** — Ragnar fork supporting e-Paper, headless server and Pineapple Pager deployments.

**[Bjorn-Omega](https://github.com/TheGamerInMyBasement/Bjorn-Omega)** — Bjorn fork adding NTFY push notifications for findings.

**[Mild-Viking](https://github.com/auggnation/Ragnarbutdifferent)** — Ragnar fork for passive home network monitoring. Pulls real hostnames from DHCP leases via the OPNsense or pfSense API, runs scheduled speed tests, and keeps a records board.

## Unattended WiFi collection

**[Pwnagotchi](https://github.com/jayofelony/pwnagotchi)** — bettercap-driven WPA handshake and PMKID capture to PCAP for hashcat. GPL-3.0.

**[PwnGridSpam](https://github.com/7h30th3r0n3/PwnGridSpam)** — Standalone ESP32 attack that spams face and name onto every nearby Pwnagotchi.

**[wardriver rev3](https://github.com/JosephHewitt/wardriver_rev3)** — Dedicated ESP32 wardriving to WiGLE CSV.

## SubGHz and RF

**[EvilCrowRF-V2](https://github.com/joelsernamoreno/EvilCrowRF-V2)** — Dual CC1101 transceivers supporting rolljam-class functionality.

**[FeralRF](https://github.com/ElectronicCats/FeralRF)** — RF tooling from Electronic Cats.

**[RFSAM](https://github.com/ElectronicCats/RFSAM)** — Field guide documenting an RF Security Assessment Methodology.

**[Daeva](https://github.com/cifertech/Daeva)** — RF scanning, copying and replaying.

**[RFQuack](https://github.com/rfquack/RFQuack)** — Library-and-firmware RF-analysis framework, radio-agnostic across CC1101, nRF24, RFM69 and others, driven from a Python client over MQTT.

## Counter-surveillance and ALPR detection

**[colonelpanichacks/flock-you](https://github.com/colonelpanichacks/flock-you)** — BLE plus promiscuous WiFi against 30+ surveillance OUIs under a confidence-tier system, detecting Flock ALPRs, ShotSpotter acoustic sensors and Raven gunshot detectors, feeding a Flask dashboard with GPS tagging. MIT.

**[FlipDeFlock](https://github.com/ReconGrunt/FlipDeFlock)** — Pairs an ESP32 with a Flipper for camera vendor identification, geotagging, mapping and DeFlock-ready report export. Includes a signal Locator for direction finding and in-app ESP32 backup/flashing. GPL-3.0.

**[flock-back (FlockBack)](https://github.com/NSM-Barii/flock-back)** — Python tool running BLE and WiFi sniffers in parallel, covering Flock, Raven, Penguin and PigVision. Saves detections to JSON and runs on a laptop or Pi.

**[flock-you-wifi-recon](https://github.com/JakeSwiz/flock-you-wifi-recon)** — ESP32-WROVER firmware detecting Flock ALPRs through STA-mode WiFi probe requests, including when the hotspot is off. Passive reconnaissance.

**[WatchFlock](https://github.com/JakeSwiz/WatchFlock)** — Marauder-based Flock detection extension.

**[flock-you-esp32 (SimeonOnSecurity)](https://github.com/simeononsecurity/flock-you-esp32)** — flock-you firmware for generic ESP32 boards, with PlatformIO builds.

**[DeFlock](https://github.com/FoggedLens/deflock)** — Crowdsourced ALPR location database on OpenStreetMap. [Mobile app](https://github.com/FoggedLens/deflock-app) · [Website](https://deflock.me).

**[OUI-Spy](https://github.com/colonelpanichacks/oui-spy)** — BLE/WiFi surveillance-OUI sniffer with foxhunter direction finding and PCAP output.

**[Sky-Spy](https://github.com/colonelpanichacks/Sky-Spy)** — Drone Remote ID detection and mapping.

**[drone-mesh-mapper](https://github.com/colonelpanichacks/drone-mesh-mapper)** — Relays WiFi drone Remote ID detections over Meshtastic.

**[mesh-detect](https://github.com/colonelpanichacks/mesh-detect)** — BLE/WiFi detection relayed over a Meshtastic mesh.

**[NanoC6 ESP32 Honeypot](https://github.com/7h30th3r0n3/NanoC6-ESP32-Honeypot)** — ESP32 honeypot with a web config UI, SPIFFS persistence and webhook alerts.

**Bruce Flock-You script.** JavaScript Flock detector for the T-Embed CC1101 running [Bruce](https://github.com/BruceDevices/firmware).

## Automotive

**[RAMN](https://github.com/ToyotaInfoTech/RAMN)** — Resistant Automotive Miniature Network, a miniature CAN and CAN-FD testbed. [Electronic Cats fork](https://github.com/ElectronicCats/RAMN).

## Cellular

**[LTESniffer](https://github.com/SysSec-KAIST/LTESniffer)** — Open-source LTE downlink and uplink eavesdropper, SDR-backed. [Electronic Cats fork](https://github.com/ElectronicCats/LTESniffer).

**[imsi-catcher](https://github.com/ElectronicCats/imsi-catcher)** — Active IMSI catcher built on srsRAN 4G.

## Ecosystem and tooling

**[Launcher](https://github.com/bmorcelli/Launcher)** — Boots Bruce, Marauder, GhostESP or Nemo from SD without reflashing. MIT.

**[Tactility](https://github.com/TactilityProject/Tactility)** — Operating system for ESP32 devices. [Fork](https://github.com/bmorcelli/Tactility).

**[marauder-ui-pro](https://github.com/ElectronicCats/marauder-ui-pro)** — Web interface for ESP32 Marauder.

**[Bruce Android app](https://github.com/BruceDevices/App)**

**[Bruce iOS app](https://github.com/BruceDevices/App-IOS)**

**[Bruce app store](https://github.com/BruceDevices/App-Store)**

**[Bruce JS tooling](https://github.com/BruceDevices/bruce-js-tooling)** — Type definitions for writing Bruce apps.

**[Bruce PCBs](https://github.com/BruceDevices/PCBs)** — Published hardware designs.

**[GhostESP Apps](https://github.com/GhostESP-Revival/GhostESP-Apps)** — Native `.gapp` tools installable without reflashing.

**[GhostESP Companion](https://github.com/GhostESP-Revival/GhostESP-Companion)** — Android app.

**[GhostESP Scripts](https://github.com/GhostESP-Revival/GhostESP-Scripts)**

**[GhostESP IRDB](https://github.com/GhostESP-Revival/GhostESP-IRDB)** — Curated IR code database.

**[GhostESP Chat](https://github.com/GhostESP-Revival/GhostESP-Chat)** — Serverless peer-to-peer end-to-end encrypted ESP32 chat.

**[PicoCalc MicroPython](https://github.com/LofiFren/PicoCalc)** — General handheld platform with SSH and WiFi manager.

**[Pwnagotchi plugins](https://github.com/jayofelony/pwnagotchi-torch-plugins)**

**[Fancygotchi](https://github.com/V0r-T3x/Fancygotchi)** — Theme manager and GUI framework for Pwnagotchi.

**[oPwngrid server](https://github.com/Pwnagotchi-Unofficial/oPwngrid-server)** — Self-hosted Pwngrid replacement for the Pwnagotchi grid.

## Legacy projects

**[esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther)** — ESP8266 deauthentication firmware.

**[Ghost_ESP (original)](https://github.com/Spooks4576/Ghost_ESP)** — Original GhostESP firmware.

**[CapibaraZero](https://github.com/CapibaraZero/fw)**

**[ESP32-Wifi-Penetration-Tool](https://github.com/risinek/ESP32-Wifi-Penetration-Tool)** — ESP32 PMKID capture toolkit.

**[P4wnP1 A.L.O.A.](https://github.com/RoganDawes/P4wnP1_aloa)**

**[DeautherX](https://github.com/BlackTechX011/DeautherX)**

**[EvilCrowRF custom firmware](https://github.com/h-RAT/EvilCrowRF_Custom_Firmware_CC1101_FlipperZero)** — CC1101 custom firmware.

**[PhiSiFi](https://github.com/p3tr0s/PhiSiFi)**

**[ESP8266-EvilTwin](https://github.com/M1z23R/ESP8266-EvilTwin)**

**[WiFiDuck](https://github.com/SpacehuhnTech/WiFiDuck)**

**[hackbat](https://github.com/controlpaths/hackbat)** — Hardware design files; no published firmware.

**[pwnagotchi-torch](https://github.com/Pwnagotchi-Unofficial/pwnagotchi-torch)** — Unofficial Pwnagotchi fork.

**[keyjector](https://github.com/SySS-Research/keyjector)** — Keystroke injection for 2.4 GHz wireless input devices.

**[nrf24-playset](https://github.com/SySS-Research/nrf24-playset)** — Tooling for nRF24-based keyboards, mice and presenters.

**[unifying](https://github.com/decrazyo/unifying)** — FOSS reimplementation of the Logitech Unifying protocol.

**[2.4 GHz band Scanner](https://github.com/cifertech/2.4-GHz-band-Scanner)** — nRF24L01 spectrum scanning.

**[Int3rcept0r](https://github.com/unknwncharlie/Int3rcept0r)** — Pi Zero LAN Turtle equivalent.
