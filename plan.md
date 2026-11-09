# The Mechanical Clock Project Plan
This file tracks the logistics of the project and a forecast on what is planned to be made.

## Bills of Materials (BOM)

For more information, check [BOM.csv](BOM.csv)

## Mechanical Clock Plan
### Clock Face
A conceptual design for the clock face itself. 

![A conceptual design for the clock face](/assets/plan/conceptual-design.png)

### CLock Dimensions
The clock will be a circle, and it will have a diameter of 334-340mm.

### The gears
My requirements for the 3 hands is to have a ratio of 

```1 : 60 : 72; seconds : minutes : hours```

This means that my gears must be in the Ratio. For now, my specific motor has not been specified, so I will be assuming it runs at 1 RPM. This is the exact speed I need for the seconds hand (because 1 revolution must completed in 60 seconds). This will obviously not be the actual scenario, for which reason I will attach a gear box to the motor to reduce the speed and increase the torque.

I will then base all of my gears off of the seconds hand, because they will be even slower. The gear ratio will be in the same ratio as the speed of each hand. 

For the gear connections, theoretically it will look like as follows.

Note: any two gears in ```[]``` represent one component, stuck back to back.

Motor Box Output - 10T **[Anticlockwise rotation]**

**Seconds Hand** - ```Motor Box Output``` - 10T **[Clockwise rotation]**

**Minutes Hand** - ```Motor Box Output``` - 10T - [30T - 10T] - [40T - 10T] - 50T **[Clockwise rotation]**

**Hours Hand** - ```Minutes Hand``` - 12T - [30T - 10T] - 48T     **[Clockwise rotation]**

---

### Gear Measurements
**Diameters**
- ```10T``` - 30mm
- ```12T``` - 36mm
- ```30T``` - 90mm
- ```40T``` - 120mm
- ```48T``` - 144mm
- ```50T``` - 150mm

### No. of Gears Required
- ```10T``` x12
- ```12T``` x3 
- ```30T``` x2
- ```40T``` x1
- ```48T``` x1
- ```50T``` x1

### Visual representation of arrangement
Note: the circles represent gears of different sizes, with colors representing different layers.

![A conceptual design for the clock face](/assets/plan/drawing.png)

---

To ensure that my gears themseleves can have depth, and connect in different ways, I will be using the same thickness of wood, however I will glue multiple gear heads (of the same and different size and teeth) to add depth and allow for some more advanced features.

I will only use spurs, no ints or racks as they are not needed for the functionality of the product.

To make for nicer aesthetics, I will print the numbers seperately to the main frame and later glue them on. I also plan to have two main frames, which hold together the axels, and an outer frame which is the actual body of the clock.

To further improve the aesthetics, I will place the gears symmetrically and add other decorative (non-functional) gears to balance the layout.

For the tubes connecting to the hands of the clocks, it is basically virtually impossible for these to be made of wood. Hence, I will be using brass or other metals to make it work.

Every part of the clock will be left as its original color, except for the hands of the clock, which will be painted (spray painted) black.

---