# Kong Car Overview

Kong Car is a variation of the Donkey Car 2. Documentation and details for it can be found here: https://donkeycar.com

The key differences are:
Hardware: 

Kong Car keeps the RC control system in place for the autonomous vehicle. It can still be the same RC car that was purchased. The on board micronctoller intercepts the rx/tx remote control signals and can pass the signal diretly to the car. If the car is autonomous mode thos signals are ignored until it returns to manual mode.

Software:
Kong Car uses software developed by Dan Van Boxel, Jenny Shane, Jim Oslislo, and Rick Anderson from Fubar Labs to operate, train, and race the vehicle. https://fubarlabs.com/autonomous Following advantages:
* No cloud required
* No wifi required
* On board button and led information system
* Can be configured with Docker on client as well as training system.
