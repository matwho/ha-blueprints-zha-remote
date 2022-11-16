# ha-blueprints

## Automation

Repo for with home assistant blueprints 

### automation/robb-smart-8-switch-ROBB-ROB_200-007-0.yaml

It’s a simple blueprint that just maps all the available actions for all 8 buttons.
The available actions are:

- short press (each button)
- long press (each button)

This allows you to map any of the button (events) to any action you choose.

## ESPHome_examples 

Repo with some ESPHome yaml examples i do use.. 

### ESPHome_examples/dim-led.yaml

Control a dimmable LED with a single on/off-switch used with a wall-mounted mains-switch controlling a relay as input and a MOSFET controlling the LED.
Switch off->on will fade the LED to its 100%, Switch on->off will fade the LED to its 0%.
If the switch is switched again during fading the LED will remain on the current  light level. With a short toggle, the light will dim to 0% or to the previous light level. (The yaml file contains a double implementation, so for 2 LED's with their own switch)      

### ESPHome_examples/garage-door.yaml

Open/close the garage door with HA, using a relay by-passing a push-button for manually opening. Feedback about the door position is done via an untra-sonic distance sensor mounted above the sliding door. 


