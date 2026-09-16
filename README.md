# PS2-DC

PS2-DC is a free to use tutorial documentation demonstrating how to modify a Playstation 2 Fat console to operate from a direct 12V power source, rather than using the original PSU connected to 230V AC mains.

> [!IMPORTANT]
> This guide currently only applies to Playstation 2 Fat consoles. It will not work with Playstation 2 Slim consoles since they use a different input voltage. A slim version of the project may be developed in the future.

## Why PS2-DC

The original Playstation 2 PSU is designed to operate from a 230V AC input, which is then converted into 12V DC output to the motherboard. When installing the console in a vehicle, or in another scenario requiring a 12V power source, this will usually require converting:

> 12V DC (supply) -> 230V AC (inverter) -> 230V AC (PSU input) -> 12V DC (PSU output)

Other options exist for replacement power supplies, such as the USB C mod; however, this requires a 15V supply and a power source with a power delivery controller:

> 12V DC (supply) -> 15V DC (boost module) -> 15V DC (pd controller) -> 15V DC (USB C PSU input) -> 12V DC (USB C PSU output)

On the other hand, PS2-DC skips the conversions and instead powers the 12V DC motherboard input directly from a regulated 12V DC supply:

> 12V DC (supply) -> 12V Voltage Regulator -> 12V DC (motherboard input)

### Benefits

- Direct Power - reduces number of components required and can help increase power efficiency


## Safety

> [!CAUTION]
> This project involves modifying the power system of a mains-powered electronic device and connecting it to a high-current battery source. Incorrect wiring can damage the PS2, cause a short circuit, or create a risk of fire or electrocution. Carry out at your own risk.
