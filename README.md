# PRESEN-FSR
## v1.0
###### jatel.sk

**Špecifikácia:**  
Napájanie: 12V DC / 50mA  
Vstupy: 2x analógové s pull-up rezistorom 1M  
Výstup: 1x prepínací kontakt 0,5A/125VAC  
Kryt: [KM-18B](https://www.tme.eu/sk/details/km-18b/skatulky-pre-poplasne-zariad-a-senzory/maszczyk/km-18b-bk/)  
Programátor: [CH340 Serial Port Debugger USB to TTL Converter](https://www.aliexpress.com/item/32645188490.html?spm=a2g0o.productlist.0.0.66445f43KrMtc2&algo_pvid=d437ea6a-45e1-45a2-b66c-f30d704bff8e&algo_expid=d437ea6a-45e1-45a2-b66c-f30d704bff8e-24&btsid=2100bdd816126106735653811e7d0a&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)

**Popis:**  
Elektronický modul pôvodne určený na pripojenie dvoch tlakových senzorov typu [FSR](https://www.conrad.sk/senzor-tlaku-fsr-408.k503372) od spoločnosti Interlink Electronics na dva analógové vstupy. Výstup je relátkový bezpotenciálový prepínací kontakt 0.5A/125VAC. Modul je kompatibilný s modulom Arduino nano 328, ale neobsahuje USB prevodník. Preto je potrebné použiť bežný Arduino USB [prevodník](https://www.aliexpress.com/item/32645188490.html?spm=a2g0o.productlist.0.0.66445f43KrMtc2&algo_pvid=d437ea6a-45e1-45a2-b66c-f30d704bff8e&algo_expid=d437ea6a-45e1-45a2-b66c-f30d704bff8e-24&btsid=2100bdd816126106735653811e7d0a&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_). Modul obsahuje 3-pólový DIP spínač, ktorý je možné použiť na nastavenie rôznych režimov programu.

**Nastavenie:**
>
>**SW1-2 Režim:**
>- *OFF-OFF* vstup na výstup
>- *ON-OFF* pulz 0.5s
>- *OFF-ON* prepínač  
>
>**SW3 Citlivosť:**
>- *OFF* nízka  
>- *ON* vysoká  
