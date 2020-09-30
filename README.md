# Projecte per recuperar dades de satèl·lits NOAA

Aquest repositori conté informació sobre els diferents programes per poder rebre imatges dels satèl·lits NOAA (18, 15 i 19). Actualment, l'experiència s'ha realitzat amb un ordinador que conté el sistema operatiu [GNU-Linux](https://www.gnu.org/distros/distros.html), enconcret amb el sistema [Ubuntu 20.04 LTS](https://ubuntu.com/download/desktop). El conjunt de programes que es fan servir es llisten a continuació:

- [Gqrx](https://github.com/csete/gqrx) és un programari lliure orientat a comunicar-se amb diferents mòduls de Software Defined Radio (SDR). Aquest programari també inclou un conjunt d'eines per visualitzar i enregistrar l'espectre freqüencial de la senyal rebuda. Informació sobre aquest programa es pot trobar en [aquesta pàgina](https://github.com/nanosatlab/experiment-noaa/wiki/Programa-Gqrx) de la wiki.
- [GPredict](https://github.com/csete/gpredict) és un programari lliure que permet preveure la trajectòria dels satèl·lits i estimar les passades d'aquests en una localització concreta. Informació sobre aquest programa es pot trobar en [aquesta pàgina](https://github.com/nanosatlab/experiment-noaa/wiki/Programa-GPredict) de la wiki.
- [noaa-apt](https://github.com/martinber/noaa-apt) és un programari lliure orientat a processar dades de diferents satèl·lits meteorològics i convert-les en imatges. Informació sobre aquest programa es pot trobar en [aquesta pàgina](https://github.com/nanosatlab/experiment-noaa/wiki/Programa-noaa-apt) de la wiki.
- El [RTL-SDR Nooelec](https://nooelec.com/store/nesdr-smart.html) requereix uns drivers específics per poder ser operat des de l'ordinador. Informació sobre aquest driver es pot trobar en [aquesta pàgina](https://github.com/nanosatlab/experiment-noaa/wiki/Drivers-del-RTL-SDR-de-Nooelec) de la wiki.

Tots aquests programes són necessaris per poder dur a terme la captura i processament de les imatges transmesses pels satèl·lits NOAA. Si durant el procés d'instal·lació o manipulació del programari trobeu cap problema, podeu aixecar un dubte en la finestra de "[issues](https://github.com/nanosatlab/experiment-noaa/issues)" d'aquest repositori. Intentarem resoldre'l el més aviat possible.

# Manteniment del repositori
Aquest repositori està mantingut per [@Zosoworld](https://github.com/Zosoworld) i [@Noitty](https://github.com/Noitty).
