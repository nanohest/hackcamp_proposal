# EFIO Hack Camp 2018
Dette er mit projektforslag til EFIO Hack Camp 2018.  
Den primære årsag til at jeg stiller det allerede nu, er at såfremt projektet skulle blive valgt, er det mere end sandsynligt at hardware'en vil tage mere end to dage at skaffe.  

## Indoor Air Quality meter, *EXTREME!*
Projektet går ud på at bygge et netværk af luftsensorer, der gemmer målinger i en Time Series Database, hvorfra vi på snedig vis kan alarmere (tænk Slack, Sonos, Smart bulb...), når kålprut-og-colabøvs-luften hænger tykt over kontoret.  
Jeg ved det, frisk luft og åbne vinduer er noget kun vores koner og tillidsmænd går op i.  
Ikke desto mindre er det et emne man kan få meget sjov ud af. Uanset om man er passioneret omkring elektronik, netværk, data eller grafik.  
Præsentation: https://nanohest.github.io/hackcamp_proposal.  

### Hardware
bme680 luftsensor: https://shop.pimoroni.com/products/bme680  
Raspberry PI zero W: https://shop.pimoroni.com/products/raspberry-pi-zero-w

Luftsensoren er selvfølgelig temmelig single-purpose, PI'erne kan bruges til alt muligt gøgl.  
Jeg har selv en enkelt PI zero W liggende.  
Vi skal vel bruge en 3-5 stykker af hver for at lave noget sjovt.

Luftsensorerne har jeg ikke umiddelbart kunne finde andre steder.  
PI zero W er der mange steder restriktioner på, så man kun kan bestille én ad gangen.

Jeg ville egentlig også gerne have haft noget LED på PI'erne, men jeg har ikke kunnet finde noget der kan sidde der samtidig med luftsensoren. Så i givet fald skal vi bruge et breadboard, eller LED strips der kan køre direkte på USB-porten.
