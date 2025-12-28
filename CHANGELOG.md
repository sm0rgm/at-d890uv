
# Changelog

## 2025\-12\-28 (SM0RGM)

* Uppdaterad mot SK6BA/SSA repeaterdatabas 2025-12-28 10:26:26
* DigitalContacList.CSV tvättad från skandinaviska tecken
* Ändrade kanaler per zon:
    * SM0
        * \+ Vallentuna 7 U 434.9250 MHz FM
        * \+ Varmdo U 434.9750 MHz FM / DMR
        * \+ Djuro U 434.5875 MHz FM / DMR
        * \+ Sodertalje 5 V 145.6500 MHz FM
        * \- Brottby 1 V 145.65000 MHz 
        * \- Hagsatra UL 434.42500 MHz 
        * \- Kista 7 VS 145.78750 MHz 
    * SM1
        * \+ Visby VS 145.6500 MHz FM
    * SM2
        * \- Kalix 4 U 434.98750 MHz 
        * \- Kiruna 4 ULS 434.40000 MHz 
    * SM3
        * \- Sundsvall 3 U 434.80000 MHz 
        * \- Sundsvall 4 U 434.98750 MHz 
    * SM4
        * Orebro 1 V ändrad till Orebro 1 VS
        * \+ Ludvika 3 V 145.6625 MHz FM / DMR
        * \- Arvika 2 U 434.97500 MHz 
        * \- Smedjebacken U 434.63750 MHz 
    * SM5
        * Linkoping 6 U ändrad till Linkoping 6 US
        * Jarlasa V ändrad till Jarlasa 1 V
        * \+ Jarlasa 2 V 145.5750 MHz FM / DMR / D-Star
        * \- Linkoping 1 VS 145.62500 MHz 
        * \- Linkoping 4 U 434.51250 MHz 
        * \- Linkoping 5 U 434.80000 MHz 
        * \- Linkoping 7 U 434.87500 MHz 
        * \- Jarlasa 1 V 145.62500 MHz 
        * \+ Norrkoping 7 U 434.53750 MHz 

    * SM6 Ovriga
        * \+ Boras 5 VLS 145.2875 MHz FM
        * \+ Kullavik VLS 145.2875 MHz FM
        * \+ Lerum U 434.7750 MHz FM
        * \- Skara 1 V 145.72500 MHz 
        * \- Skara 2 U 434.56250 MHz 

    * SM7 Skane
        * \+ Lund 4 V 145.7750 MHz FM
 
    * SM7 Ovriga
        * Huskvarna U ändrad till Huskvarna 1 U
        * \- Jonkoping 2 V 145.75000 MHz 
        * \+ Huskvarna 2 V 145.7500 MHz FM

    * TF
        * \+ Thrandarhlidha V 145.7750 MHz FM

codeplugadmin 1.1 (2025-07-26)

## 2025\-12\-26 beta3 (SM0RGM)

* Kodpluggen anpassad för CPS + FW version 1.03.

## 2025\-12\-20 beta2 (SM0RGM)

* Satt Optional settings -> Display -> visning av kanaltyp, ts och cc till ON

## 2025\-12\-20 beta1 (SM0RGM)

* Kodpluggen (N0CALL.RDT) är gjord för CPS version 1.01N.
* APRS TOCALL satt till APAT89 för Anytone AT-D890UV.
* Testade att läsa in RDT-fil från 878 men gav slumpmässiga fel, t ex fick vissa kanaler olika RX/TX CC. Istället har jag gjort en separat konvertering av kodpluggen till AT-D890UV.
* Kanalerna mm är uppdaterade i enlighet med kodpluggen för AT-D878UV per 2025-10-11.
