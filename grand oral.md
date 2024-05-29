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


plus d'info sur mon capteur temperature ( temp max, dans l'eau etc...)


notion etalonnage convertrir mes données numérique en temperature.
