# Demo listener
A set of simple nodejs-scripts that listens to DT API and controls lights

## Requirements:
The file apikey.ns holds some variables for authorizing towards the REST API @ Disruptive Technologies.

This file is not in git for security reasons.

filename: apikey.ns
```
const BASIC_AUTH = 'Basic <usr:pwd Base64Encoded>';
const PROJECT_ID = '<ProjectID>';
```

### listen.ns
Listens for the demo-sensors and controls the lights
Scenarios have different scripts.

__1 LysOrgel__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
3 touch sensors blinks the HUE-lamps in different colors
   
__2 Alarm__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Blink a HUE-lamp in red when something is removed from a proximity sensor

__3 Door__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Proximity sensor. Yellow light when door is opened

__4 Temperature__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Temperature sensor. Colour of light changes with temperature (TODO)
