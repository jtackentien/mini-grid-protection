# Mini-Grid Protection System

E-Theory course project at Alfred State (Fall 2026, in progress). A small-scale model of a grid protection scheme: a latching breaker that disconnects the load on a fault and stays off until someone resets it.

## How it works
- The grid runs normally at **12 V**, powering a motor as the load
- At about **14.5 V** (overvoltage) the breaker trips and disconnects the load
- A **temperature sensor** can also trip the breaker
- The breaker **latches open**: even when 12 V returns, power stays off until the grid is manually reset with a switch
- An **Arduino** is flagged on a trip and drives an LCD ("grid offline"), a buzzer and LEDs

Built with diodes, transistors, resistors and a MOSFET switching the load.

## Status
- [x] Project proposal
- [x] Bill of materials
- [x] Preliminary circuit diagrams
- [ ] Parts arrive (on order)
- [ ] Build and test (trip voltage, temperature trip, manual reset)

## Files
- `/docs` - proposal and bill of materials (coming soon)
- `/hardware` - schematics (coming soon)
- `/firmware` - Arduino code (coming soon)
- `/images` - photos and test results (coming soon)
