# Arduino NANO sensor board
## v1.0
###### jatel.sk

**Specification:**  
Power supply: 12V DC / 50mA  
Inputs: 2x analog with 1M pull-up resistor  
Output: 1x SPDT contact 0.5A / 125VAC  
Cover: [KM-18B](https://www.tme.eu/sk/details/km-18b/skatulky-pre-poplasne-zariad-a-senzory/maszczyk/km-18b-bk/)  
Programmer: [CH340 Serial Port Debugger USB to TTL Converter](https://www.aliexpress.com/item/32645188490.html?spm=a2g0o.productlist.0.0.66445f43KrMtc2&algo_pvid=d437ea6a-45e1-45a2-b66c-f30d704bff8e&algo_expid=d437ea6a-45e1-45a2-b66c-f30d704bff8e-24&btsid=2100bdd816126106735653811e7d0a&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)  

![](images/presen-fsr.jpg)  

**Description:**  
The electronic module was originally designed as  a staircase lighting switch. The module transforms the analog output from the [FSR](https://www.conrad.sk/senzor-tlaku-fsr-408.k503372) type pressure sensors into a two-state output with using of a relay.   

The output is a relay potential-free changeover contact 0.5A / 125VAC. The module is compatible with the Arduino nano 328 module, but does not include a USB converter. Therefore, it is necessary to use a standard Arduino USB [converter](https://www.aliexpress.com/item/32645188490.html?spm=a2g0o.productlist.0.0.66445f43KrMtc2&algo_pvid=d437ea6a-45e1-45a2-b66c-f30d704bff8e&algo_expid=d437ea6a-45e1-45a2-b66c-f30d704bff8e-24&btsid=2100bdd816126106735653811e7d0a&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_). The module contains a 3-pole DIP switch that can be used to set various program modes. The firmware for FSR sensor does not exist, but the firmware for the [automatic switch of pump for disinfectant liquid](https://github.com/jatel903/pwp12.git)  exists.

**The examples of other possibilities of use:**

* thermostat
* automatic lighting with PIR sensor
* alarm with PIR sensor or radar
* twilight switch
* logger
* automatic watering system
* fluid flow measurement and automatic switching according to the volume of fluid
* automatic switch of a pump for disinfectant liquid, etc  

**All mentioned applications above depend on the firmware, which you have to create yourself.**  