# vacuum-door-controller

How to flash:
- Plug in to computer.
- Run `esphome vacuum-door-controller/esp8266.yaml run`
- Magic!
OR
- Visit web.esphome.io to flash your esp.
- Then copy the example.yaml to your esp and click install.

Components:
- ESP8266
- L298N
- Linear actuator 12v 1500N
- 12v adapter
- 12v contact
- microswitch (optional)

For custom GPIO ports then default. Add it as substitutions in your config.

For the microswitch:
Connect the NC and COM to the esp.