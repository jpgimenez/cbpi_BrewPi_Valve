# cbpi_BrewPi_Valve

This is the code for a BrewPi Valve-controller plugin for the CraftBeerPi brewing/fermentation controller to make it possible to use BrewPi Valves.

BrewPi Onewire Valve Control Expansion is working with 2-wire valves and 5-wire valves. Feedback trigger (5-wire valves with feedback switches) is working (is used to put valve inactive as completely closed or open)

# Valve Control
![BrewPi Valve Control Expansion Board](https://store.brewpi.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/b/r/brewpi_onewire_valve_expansion_board_1.jpg)
BrewPiValve open/close a valve: consist of a ds2408 as 1-wire 8 pio device, driving a double H-bridge motor driver (L293D, driving 2 valves).


    BrewPiValve is the type to select as actor for Valves via BrewPi, the 1-wire id 29-.... as device, port A or B as target.


# cbpi_BrewPi_Valve
BrewPi Valve Controller Plugin for CraftBeerPi
