# aprs-send-weather
Send a formatted APRS weather packet to APRSIS, and RF via KISS TNC/direwolf.


 Install requirements (weewx, weewx-aprs weewx extension, direwolf):
 <pre>
    apt-get install weewx
    wget https://github.com/cavedon/weewx-aprs/archive/refs/heads/master.zip
    wee_extension --install=master.zip
    apt-get install direwolf
</pre>

  (C)2022 Craig Lamparter
  GPL v2.1

