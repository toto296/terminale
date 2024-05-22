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

