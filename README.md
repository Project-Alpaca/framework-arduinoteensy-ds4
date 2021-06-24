# framework-arduinoteensy-ds4

Minimal Teensyduino framework for PlatformIO with DS4 support patches.

Unlike stock framework package, only platform-specific libraries that are not available on PlatformIO's main repository are included in the `libraries` directory. More can be added easily when required (as long as they are git repositories).

Arduino-specific TXTs (i.e. `keywords.txt`, `boards.txt` and `platform.txt`) are not included due to them being a PITA to keep track thx to Paul's hard work on the BS installers, and the fact that they are not even used in PlatformIO's build script. RIP Arduino IDE users.
