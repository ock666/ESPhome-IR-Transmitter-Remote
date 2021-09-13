# ESPhome-IR-Transmitter-Remote
Yaml code example for an IR transmitter in ESPhome.


# Usage
- change the SSID and password to that of your network, or point them to a secrets file. also dont forget to set your IP network settings. or simply copy paste in your known good esphome wifi code block which you use with your other sensors/nodes.
- Depending on your set-up you will need to change the board variable to your corrosponding board model.
- also dont forget to change pin assignments and variable names, as this IR transmitter example is from my bedroom.

# Getting Your Remote Codes
- This code example uses LG codes, other codes can be found online by searching 'tv brand' IR codes.
- if you're unable to find codes, or the codes you find do not work for your TV. OR if you have an off brand Aldi TV brand like Bauhn etc. you can acquire your codes by using the IR sensor.yaml.

# IR Sensor.
- This yaml code allows you to view all captured codes within an esphome terminal either over serial or OTA.
- note down these codes for every function and copy them across to the corrosponding template switches.
 I recommend you do a few presses for each button function to see if the sensor outputs a JVC or LG tv code value. as these can be easier to use and more accurate to replay than raw codes.

# Feel free to use this code however you please.


