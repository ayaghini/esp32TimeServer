# esp32TimeServer
Time Server based on ESP32 and GPS for my HAM radio computer


Parts:
GPS NEO-M6: https://randomnerdtutorials.com/guide-to-neo-6m-gps-module-with-arduino/
ESP32: https://esp32s3.com/tinys3.html
LED module: https://www.pishop.ca/product/0-91-inch-white-oled-display-module-i2c-interface/

Sources:

Andreas video: https://www.youtube.com/watch?v=BGb2t5FT-zw
and his repo: https://github.com/SensorsIot/NTP-Server-with-GPS/tree/main/ESP32
https://sigmdel.ca/michel/program/esp32/arduino/esp32_gps_time_server_en.html



if using ICOM 705 that output GPS sentences NMEA, you can follow below to sync time with GPS:
https://www.youtube.com/watch?v=Xo1Qt-pe5JQ

he is using this software: https://www.maniaradio.it/en/bkttimesync.html
in essnse you can use any device that outputs the NMEA and this software to sync your time. maybe ID-52 or maybe gives the ESP USB output so this software can sync time.



