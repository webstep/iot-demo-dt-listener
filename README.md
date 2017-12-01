# Demo listener
A set of simple nodejs-scripts that listens to DT API and controls lights

## Requirements:
The file apikey.ns need a variable "ApiKey" defining the ApiKey to use for authorizing towards the REST API at Disruptive Technologies.

This file is not in git for security reasons.

filename: apikey.ns
```
const ApiKey = '<insert ApiKey from DT here>';
```

### listen.ns
Listens for the demo-sensors and controls the following scenarios.
Scenarios have different scripts.

__1 LysOrgel__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
3 touch sensors blinks the lamp in red, green or blue
   
__2 Alarm__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Blink an alarm light when something is removed from a proximity sensor

__3 Door__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Proximity sensor. Yellow light when door is opened

__4 Temperature__<br>
&nbsp;&nbsp;&nbsp;&nbsp;
Temperature sensor. Colour of light changes with temperature 
