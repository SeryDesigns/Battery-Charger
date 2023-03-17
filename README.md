# Battery-Charger

## Project status 
Manufactured, assembled, tested

## Project overview

Li-Ion battery charger, based on BQ24060 IC, this simple PCB takes 5V as input and charges
a 3.7V Li-Ion battery. \
The charger has output short circuit protection and optional thermal protection. \
It can charge a battery with current up to 1A (the charging current is set by a resistor), the PCB works without a problem at charging current up to ~0.7A, at higher current without heatsink or cooling the IC heats up and enters thermal protection, cycling the charging on and off.

There are 2 indication LEDs for status, green and red LEDs -
| LED color   | Charger state                 |
|-------------|-------------------------------|
| Green + Red | Precharge in progress         |
| Red         | Fast charge in progress       |
| Green       | Fully charged                 |
| None        | Power off / suspended / fault |

The dimension of the PCB are 33mm X 10mm, it is a 2 layers PCB with compoenents assembled only on the TOP layer

Top view - \
![image](https://user-images.githubusercontent.com/119447042/212188589-60668929-589c-4c21-b75b-a4168886604b.png)
\
Bottom view -  \
![image](https://user-images.githubusercontent.com/119447042/212188629-1f806481-5ab1-419d-8a1f-1052dd723c13.png)

I've created a short time lapse video of the design process, check it out on my YouTube channel 
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Mz6wxAzDqSU/hqdefault.jpg)](https://youtu.be/Mz6wxAzDqSU)
