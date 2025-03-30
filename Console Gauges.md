# Console Gauges

## Wiring

![Console Wiring](/images/console_wiring.png)

## Fuel Gauge

### Fuel Gauge Resistance Levels

At a min, get a 0-100 ohm min rheostat, 1/2 watt or bigger, or two 50 ohm 1/2 watt resistors.

Dial in 100 ohms/two resistors in series and attach to ground and tan wire, gas gauge reads full.
Dial in 50 ohms/one resistor in series and attach to ground and tan wire, gas gauge reads half tank.
Dial in 25 ohms/two resistors in parallel and attach to ground and tan wire, gas gauge reads 1/4 tank.
Dial in 0 ohms and attach to ground and tan wire, gas gauge reads empty.
These are approximate indications.

### Low Fuel Light

The light sockets have power all the time when the key is in run, the low fuel sender provides the ground when the fuel tank is around 1/8 to 3/16 full so the light in the dash will stay lit as long as the key is in run. To test it, with an almost empty tank, check for ground with the sender connected to the circuit (which you already have done), then disconnect the sender at the connector in the trunk. The ground of the yellow lead should disappear. The low fuel modules are not adjustable, they either work or don't.

### Sources

- https://www.camaros.net/threads/low-fuel-warning-light.184308/
- https://www.camaros.net/threads/how-to-diagnose-low-fuel-warning-light-problem.197997/

## Temperature Gauge

### Gauge Readings

![Temp Gauge](/images/1969%20Camaro%20Temperature%20Gauge%20Running%20Temp.jpg)

- Idiot light sensor goes on at 235 degs.. which is the same temp as the red line on the gauge.
- Gauge normally reads 1 tick above 1/4 scale with the engine operating around 180 degrees, thats just how the originals work.

### Sender Ohms

| Temp (Degrees F) | Wells (TU5) | Lectric Limited (01513321) | GM (1513321) |
|------------------|-------------|----------------------------|--------------|
|               80 | 650 ohms    | 573 ohms                   | 549 ohms     |
|               90 | 526 ohms    | 445 ohms                   | 524 ohms     |
|              100 | 429 ohms    | 365 ohms                   | 409 ohms     |
|              110 | 328 ohms    | 266 ohms                   | 365 ohms     |
|              120 | 283 ohms    | 227 ohms                   | 323 ohms     |
|              130 | 250 ohms    | 200 ohms                   | 272 ohms     |
|              140 | 216 ohms    | 170 ohms                   | 227 ohms     |
|              150 | 198 ohms    | 155 ohms                   | 195 ohms     |
|              160 | 173 ohms    | 133 ohms                   | 175 ohms     |
|              170 | 157 ohms    | 119 ohms                   | 157 ohms     |
|              180 | 135 ohms    | 101 ohms                   | 140 ohms     |
|              190 | 120 ohms    | 89 ohms                    | 125 ohms     |
|              200 | 109 ohms    | 79 ohms                    | 109 ohms     |
|              212 | 104 ohms    | 75 ohms                    | 102 ohms     |

- If you have a gauge with an external resistor you can change it from the stock 86 ohm resistor to a 91 ohm resistor and that will move the gauge up to 1 tick below half, at 180 degrees. I've done that, I use a potentiometer with two short leads on it, I adjust it to what i want the gauge to read and then lock it down in a ball of electrical tape so it can't change. If your gauge has the resistor built into it, then you have to live with it reading low, or get a sender that has a lower resistance at each of the temps above.

### Gauge Wiring

![Normal Wiring](/images/temp_gauge_wiring-1.jpeg)
![Lower Temp](/images/temp_gauge_wiring-2.jpeg)

### Sources

- https://www.camaros.net/threads/console-temp-gauge-where-should-needle-be.370145/
- https://docs.google.com/spreadsheets/d/1TV9BS7KJggHz39SFl6nXqHMvGJmTY15aF5HBD9S61yg/edit?gid=939657679#gid=939657679
- http://www.camaros.org/forum/index.php?topic=9261.0