This is a modified version of both Colin's ESP32RET and Magnus's RejscanESP32 version of ESP32RET for his 2.4 board.
Main issues with prior version, incompatible GPIO layout for CAN0 RX + TX on 2.4 board (16,17 + 4EN) and
issues following the chopping of bluetooth from the ESP32S3 version.

Also nuked the fastLED library routines for 2 dumb leds, but might reuse as initialisation / trimming is a PITA.

Profit? ;-)
