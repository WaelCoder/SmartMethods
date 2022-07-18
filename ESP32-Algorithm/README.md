# Instructions/Setup
1. Download [**Arduino IDE**](https://www.arduino.cc/en/software)

2. Run **Arduino IDE**
3. In the menu bar, go to ```File>Preferences>Settings```, then in **Additional Boards Manager URLs**, paste the following URL:
```sh
https://dl.espressif.com/dl/package_esp32_index.json
``` 
...then click OK.

4. Go to ```Tools>Board>Board Manager```

5. Search for "ESP32" then click on install. After a few minutes it will confirm you that it has been "INSTALLED". Close the Board Manager.

6. You should be able to select your board from the board menu ```Tools>Board>ESP32 Arduino```. select what is appropriate for your ESP32 module. <font size="2">(Ex. WEMOS D1 MINI ESP32 controller)</font>

7. Plug in the ESP32 module to the computer. then Go to ```Tools>Port``` then select the ESP32 port

9. Go to ```Tools>Port``` then select the ESP32 port. <font size="2">(Ex. _Port: "COM3">COM3_)</font>

Now you are ready to upload your codes or test one of the given examples in the IDE.
