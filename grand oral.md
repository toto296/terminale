fiche capteur (capteurs passif, actif...)

voir température plaque avec carte microbit -->  signal numérique

### site convertion analogique numérique :  https://www.maxicours.com/se/cours/conversion-d-un-signal-analogique-en-signal-numerique/

### site BBC reception signal analogique :   https://xofe14.scenari-community.org/Publications/Formations/Formation_Microbit_Lycee/co/ExploiterEntreeAnalogique.html

### different type de capteur : https://srcsl.com/fr/types-capteurs-temperature/

#Imports go at the top
from microbit import *




### programme read annalog led :
while True :
    
    mesure = (pin1.read_analog)
    pin0.write_analog(mesure)
    sleep(50)

## objectid 1 :
##### addapter le programme au dessus pour capteur temperature : module grove high temperature

from microbit import *

while True :
    
    mesure_a = pin2.read_analog()
    mesure_b = pin1.read_analog()
    pin0.write_analog(mesure_a)
    print((mesure_a,mesure_b,1023))
    sleep(20)


## plus d'info sur mon capteur temperature ( temp max, dans l'eau etc...)
https://boutique.semageek.com/fr/1015-capteur-de-haute-temperature-grove-3008572258635.html
La gamme détectable de ce capteur est -50 à 600 ℃, et la précision est de ± (2.0% + 2 ℃)
thermistance en bleu   cable thermocouple ( Précision de la thermocouple ±2% (+2°C))

## notion etalonnage convertrir mes données numérique en temperature.
 le rapport entre la valeur affichée par l'instrument de mesure et la valeur vraie.
 L'étalonnage d'un instrument de mesure au moyen d'un étalon permet de garantir sa fiabilité.


etalonnage calibrage
