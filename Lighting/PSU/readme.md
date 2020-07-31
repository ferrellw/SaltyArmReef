
# Radion Lighting Power Supply Build
## Background

With the addition of a fourth Radion XR15 to my reef system I wanted to find a better way to power everything. Having four power supplies tie up outlets and a ton of cord clutter was unappealing and problematic. The lights would often get unplugged accidentally when working behind the tank so it became a pain point for me. 

Having a background in electronics I knew I could come up with a better solution. I decided to create a single power supply that would power all the lights while only using a single outlet. I used off the self parts from Amazon and the total cost was less than $100. You can follow the steps below to build a similar power supply for your setup.

## Build Overview

 1. [Identify Power Requirements](#Identify-Power-Requirements)
 2. [Select a Power Supply](#Selecting-a-Power-Supply)
 3. [Identify Cord Type](#Identify-Cord-Type)
 4. [Purchase Components](#Purchase-Components)
 5. [Build It!](#Build-It)



### Identify Power Requirements

First we must identify our power requirements. Are the lights 12, 24, or 36 volts? What wattage? How many lights? Luckily determining this information is easy as it can be found by looking at the bottom of your existing power supply.

![](https://github.com/ferrellw/SaltyArmReef/blob/master/Lighting/PSU/img/brick.jpg)

Look for an "OUTPUT" rating. In my case my power supply was rated for 24 volts and 3.25 amps. Using [this](https://www.rapidtables.com/calc/electric/watt-volt-amp-calculator.html) calculator we can then determine the wattage. The break down for a single light is as follows:

- Voltage: 24v
- Amperage: 3.25A
- Wattage: 78w

With this information we can now determine our total power requirements. For example 4 lights would require a power supply that can output 24 volts, 13 amps, and 312 watts*. (3.25A+3.25A+3.25A+3.25A=13A) & (78W+78W+78W+78W=312W)

*Note that this is maximum output. This means running yours lights and all channels at 100%.

### Selecting a Power Supply
Now that we have our power requirements we can choose a power supply. There are many different brands but I recommend the "Mean Well" brand. We need to choose a power supply that can deliver an adequate amount of power. I say adequate because unless you plan to run your lights at 100% on all channels you can choose a lesser power supply. 

My maximum power consumption of four lights was estimated at 312 watts. I went with a 350w power supply even though my measured consumption 150w at peak. I could have gotten a smaller and cheaper power supply but wanted to allow room for growth in the event I change or get more lights. You may need to use a "Kill-A-Watt" meter to determine your actual consumption. 

One thing to note is these power supplies are powerful and they have fans for cooling. The more power you pull from them the hotter they will get and thus more possible fan noise. I am using about half the capacity of my 350w supply and its barely warm to the touch and the fan noise is barely noticable. The fan on my model is intermittent.  

![](https://m.media-amazon.com/images/I/61i7ezQx77L._AC_SS350_.jpg)

[Mean Well LRS-350-24 (350w)](https://www.amazon.com/gp/product/B013ETVO12/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

[Mean Well SE-450-24 (450w)](https://www.amazon.com/dp/B005T6NNKO)

[Mean well RSP-500-24 (500w)](https://www.amazon.com/MEAN-WELL-RSP-500-24-Switching-Enclosed/dp/B00UWCD22O)

### Identify Cord Type
The Radion and Prime both use a "DC barrel jack" type connector. There are many sizes but the two most common are 5.5mm x 2.5mm and 5.5mm x 2.1mm. The Radion uses the 2.5 variant. These cords will be used to connect the power supply to the lights.

![](https://github.com/ferrellw/SaltyArmReef/blob/master/Lighting/PSU/img/cord.jpg)


### Purchase Components 
You may already have some of these components on hand like I did but you can use the Amazon list below for the full list of components. 

 [Full List](https://www.amazon.com/gp/registry/wishlist/1CPE6F27PKWLS/ref=cm_wl_huc_view)

- [Cable Wrap](https://www.amazon.com/dp/B00OTRUW7G/?coliid=I3DHQM53AP9790&colid=1CPE6F27PKWLS&psc=1&ref_=lv_ov_lig_dp_it)
- [Soldering Iron](https://www.amazon.com/dp/B07PDK3MX1/?coliid=IINTOWJ2TKDAQ&colid=1CPE6F27PKWLS&psc=1&ref_=lv_ov_lig_dp_it)
- [Cable Terminals](https://www.amazon.com/dp/B078PMWNJC/?coliid=IMQMYOPEEVTDY&colid=1CPE6F27PKWLS&psc=1&ref_=lv_ov_lig_dp_it)
- [AC Power Cord](https://www.amazon.com/dp/B07MCBPG5V/?coliid=I3K2SNQ6PC5YRO&colid=1CPE6F27PKWLS&psc=1&ref_=lv_ov_lig_dp_it)
- [DC Power Cord](https://www.amazon.com/dp/B07QKDPVSH/?coliid=ITWUN5C1EVJN9&colid=1CPE6F27PKWLS&psc=1&ref_=lv_ov_lig_dp_it)

Power Supplies:
- [Mean Well LRS-350-24 (350w)](https://www.amazon.com/gp/product/B013ETVO12/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
- [Mean Well SE-450-24 (450w)](https://www.amazon.com/dp/B005T6NNKO)
- [Mean well RSP-500-24 (500w)](https://www.amazon.com/MEAN-WELL-RSP-500-24-Switching-Enclosed/dp/B00UWCD22O)

### Build It!

Now that we have our components lets put it together! It's easier than it looks.

1. First we'll connect the AC power cord to the power supply. 
* There are three wires we need to connect. Black (line), white (neutral), and green (ground). Connect the wires to the power supply using the screw terminals.

2. Now lets connect the DC power cords. 
* Starting with a fork connector (make sure it fits the rail of the power supply) crimp and solder a connector to each lead of the DC power cords.
* With all the connectors crimped and soldered, connect them to the power supply. Black is negative (V-) and red is positive (V+). Each terminal in V- and each terminal V+ are the same so it doesn't matter where they are connected as long as positive is with positive and negative is with negative. 

3. Clean up and then protect the wire terminals. 
* I used wire wrap on the wires to help keep everything clean and to prevent pulling the wires off the terminal. 
* I would also recommend a few wraps of electrical tape over the terminals as touching the AC (and DC if conditions are correct) can kill you!


Your finished power supply should look something like the below image. (but mine's missing the electrical tape)
![](https://github.com/ferrellw/SaltyArmReef/blob/master/Lighting/PSU/img/psu.jpg)
