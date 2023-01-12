# Battery-Charger

Li-Ion battery charger, based on BQ24060 IC, this simple PCB takes 5V as input and charges
a 3.7V Li-Ion battery. \
The charger has output short circuit protection and optional thermal protection. \
It can charge a battery with current up to 1A (the charging current is set by a resistor)

There are 2 indication LEDs for status, green and red LEDs -
| LED color   | Charger state                 |
|-------------|-------------------------------|
| Green + Red | Precharge in progress         |
| Red         | Fast charge in progress       |
| Green       | Fast charge in progress       |
| None        | Power off / suspended / fault |

The dimension of the PCB are 33mm X 10mm, it is a 2 layers PCB with compoenents assembled only on the TOP layer
![image](https://user-images.githubusercontent.com/119447042/212188589-60668929-589c-4c21-b75b-a4168886604b.png)
![image](https://user-images.githubusercontent.com/119447042/212188629-1f806481-5ab1-419d-8a1f-1052dd723c13.png)

