## 27 Dec 2024
## CLOCK SYTEM

> Overview
The Clock System module provides a fully functional in-game clock with support for both analogue and digital clocks. 
It operates on a customizable time scale and allows integration with other systems, such as the Day-Night Cycle module.

> Features

> Analogue Clock:
> Real-time rotation of hour, minute, and optional second hands.
> Customizable time scale.
> Digital Clock:
> Support for 12-hour and 24-hour formats.
> Option to display seconds.
> Adjustable Start Time. Initialize the clock at any hour (0-23).

> Setup
> Add the ClockController script to a GameObject in your scene.

> Configure the following in the Inspector:
> Clock Type: Choose between Analogue or Digital.
> Time Scale: Set the speed of time progression (1-60, where 1 hour = specified real-time minutes).
> Start Time: Define the initial hour (0-23).
> Clock Prefabs: Assign the analogue and digital clock prefabs.
> Ensure prefabs have AnalogueClock or DigitalClock components for functionality.

> Integration
> Use SetTimeScale(float timeScale) to dynamically adjust the clock's speed.

> Limitations
> The system does not include persistence (e.g., saving and loading the current time).
> Time calculations are limited to the 24-hour format.
> Time related events are not yet supported.