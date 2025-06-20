# Vonkentrekkers

## Voor het minorproject Elektronica Elektrotechniek zijn een klasgenoot en ik gevraagd om een demonstratie op te zetten die het begrip EMI (Elektromagnetische Interferentie) uitlegt.

Hiervoor hebben we het idee ontwikkeld om een EMP (Elektromagnetische Puls) uit te zenden.

Voor het genereren van deze puls gebruiken we eerst een 555-timer, die van een 12V DC-voeding hoge DC-pulsen genereert. Deze pulsen voeden een flybacktransformator, waarmee we nog hogere spanningen opwekken. De uitgang van de transformator wordt vervolgens aangesloten op een Cockcroft-Walton spanningsvermenigvuldiger om spanningen van (doel) tussen de 50kV-100KV te bereiken. 

![image](https://github.com/user-attachments/assets/6d2db3f4-8452-4dba-929e-3a1d3e05d80f)

De volgende stap is het meten van het elektromagnetisch veld dat hiermee wordt opgewekt. Op basis daarvan willen we een schakeling of demonstratieopstelling ontwikkelen die de effecten van EMI duidelijk en visueel weergeeft.

Als een korte samenvating is hieronder ook de poster van de posterprentatie weergegeven. Meer info is d=te vinden in de wiki
![555 timer Dit is de driver van het systeem  Een 555 timer-IC zorgt voor een puls met een dutycycle van 50% en een instelbare frequentie  Deze puls wordt aan de gate van een IRF540 MOSFET gegeven o](https://github.com/user-attachments/assets/a685edf1-da0a-4df5-8972-11aaeba46910)
