# THP
Models, Scripts and Slides from "Untrustworthy Hardware and How to Fix It"


# <!> Under Construction <!>
Buildscript currently does not support programming the Parallax Propeller; will update soon. Initial device did what this project was meant to do (OS linux workflow), but is still far short of my vision for the platform.   Big changes inbound, this show is just getting started.

# Future Plans:
- move from Intel/Altera Cyclone IV FPGA on the prototype system to the Lattice ICE-40 platform with OSS tools (they have more than enough gates to pull this off)
- single custom-board assembly
- increased system independence 
- consolidated IO interface
- RF hardening (optical IO interface)

# Bill of Materials:
- Hatchbox PLA used for printed components
- DE0-Nano running the MOR1KX open-source CPU: https://www.adafruit.com/product/451
- Parallax FLiP Propeller open-source microprocessor: https://www.parallax.com/product/32123
- 2X Adafruit PowerBoost 1000C: https://www.adafruit.com/product/2465 (overkill)
- 2X 6600mAH Lithium-Ion battery packs: https://www.adafruit.com/product/353
- 2.8" Adafruit SPI TFT LCD: https://www.adafruit.com/product/1770
- PS/2 breakout: https://www.adafruit.com/product/804
- 2x 100ohm resistors 
- 2x 10kohm resistors 
- 4x M3 screws
- M2.5 standoff kit (for general assembly)
- 3.3v FTDI-compatible serial interface (for debugging)
- Access to a 3d-printer ~20-30 hours total print time (depending on quality / printer specs) 

# Further Reading and Additional Resources (from slide deck)
- DEF CON 22: Summary of Attacks Against BIOS and Secure Boot: https://www.youtube.com/watch?v=QDSlWa9xQuA
- DEF CON XX: Hardware Backdooring is Practical: https://www.youtube.com/watch?v=8Mb4AiZ51Yk
- NSA shipment hijacking: http://www.theverge.com/2013/12/29/5253226/nsa-cia-fbi-laptop-usb-plant-spy
- Windows “golden keys” leaked: https://arstechnica.com/security/2016/08/microsoft-secure-boot-firmware-snafu-leaks-golden-key/
- NSA Cisco implant: https://arstechnica.com/tech-policy/2014/05/photos-of-an-nsa-upgrade-factory-show-cisco-router-getting-implant/
- Apple suspects hardware backdoors by state actors in server shipments: https://www.extremetech.com/extreme/225524-apple-may-design-its-own-servers-to-avoid-government-snooping
- NSA deploys low level / hardware backdoors against intercepted consumer devices: http://www.extremetech.com/computing/173721-the-nsa-regularly-intercepts-laptop-shipments-to-implant-malware-report-says
- Summary of Intel ME: https://boingboing.net/2016/06/15/intel-x86-processors-ship-with.html
- Detailed IME breakdown by Libreboot team: https://libreboot.org/faq/#intel
- REcon 2014: Intel Management Engine Secrets (Igor Skochinsky): https://www.youtube.com/watch?v=4kCICUPc9_8
- Hackaday: The Trouble with Intel’s Management Engine: http://hackaday.com/2016/01/22/the-trouble-with-intels-management-engine/
- Hackaday IME workarounds: https://hackaday.com/2016/11/28/neutralizing-intels-management-engine/
- A2: Malicious Analog Hardware: https://www.ieee-security.org/TC/SP2016/papers/0824a018.pdf
- Wired Summary of silicon backdooring: https://www.wired.com/2016/06/demonically-clever-backdoor-hides-inside-computer-chip/
- Power-based side channel attacks: https://www.rsaconference.com/writable/presentations/file_upload/br-w03-watt-me-worry-analyzing-ac-power-to-find-malware.pdf
- openRISC homepage: http://openrisc.io/
- getting started with openRISC: https://github.com/openrisc/tutorials
- open source Propeller terminal using Adafruit 2.8” TFT: https://github.com/tdoylend/tgi2
