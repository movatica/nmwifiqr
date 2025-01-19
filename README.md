# nmwifiqr
Simple script to create qr codes from networkmanager wifi connections.

Copy/Paste script to create a qr code image file:
~~~
qrencode -o wifi.png -l M -d 150 -s 8 "WIFI:T:WPA;S:<ssid>;P:<secret>;;"
~~~
