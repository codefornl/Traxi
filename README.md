![alt tag](https://github.com/LabPLC/Traxi/raw/master/Traxi/res/drawable-hdpi/ic_launcher.png?raw=true) TRAXI
============

Traxi is een Android Applicatie die mensen help bij het reizen met taxi's. Na het invoeren van het registratienummer van een taxi, wordt het registratienummer gecontroleerd en wordt informatie over de taxi getoond:

Informatie uit systemen:
* Voertuigen informatie
* Verkeersovertredingen (niet in alle landen mogelijk)
* Eigenaarsgegevens
* Jaar waarop de taxi in dienst is getreden
* Inspectie informatie van het voertuig

Informatie van andere gebruikers:
* Waardering (0-5 sterren)
* Opmerkingen van anderen

Daarnaast kun je TRAXI koppelen aan Facebook en van hen zien of jullie met dezelfde taxi hebben gereisd en welke ervaringen ze hiermee hadden.

# Slimme foto's

Het is met TRAXI mogelijk foto's te maken van nummerplaten, taxiborden en registratienummers. Het is ook mogelijk foto's op een later tijdstip door TRAXI te laten verwerken.

# Contact nood- en veiligheid

Het is mogelijk maximaal twee contacten op te geven met telefoonnummer en e-mail adres die wanneer de paranoïde modus wordt geactiveerd of de paniekknop wordt gebruikt.

* Wanneer tijdens de reis (en alleen tijdens de reis) 5 maal op de aan-uitknop van de telefoon wordt gedrukt, dan wordt een sms verstuurd naar de contactpersoon voor noodgevallen. De contactpersoon ontvangt vervolgens e-mails met gegevens over de locatie en de batterij. De contactpersoon kan hierdoor zien en volgen waar je bent.
* Er is ook een Paranoïde modus, dit is standaard uitgeschakeld . Wanneer de paranoïde modus aan staat, dan ontvang je berichten die vragen of je in orde bent. Wanneer niet tijdig op de berichten wordt gereageerd, ontvangt de contactpersoon vervolgens e-mails gegevens over de locatie en de batterij. De contactpersoon kan hierdoor zien en volgen waar je bent.
Als u uw contactpersonen voor noodgevallen is ingesteld, kan de paranoïde modus tijdens de reis worden geactiveerd.
Eenmaal begonnen met de reis legt de applicatie elke 5 seconden de locatie vast.

# Tips:
TRAXI geeft veiligheidstips voor het gebruik van taxi's.

# Kaart
Tijdens de rit kan de gebruiker op een kaart de reisroute bekijken met informatie over de mogelijke route en de resterende afstand en tijd tot de plaats van bestemming

# Beoordeling

Aan het eind van de reis kan rit worden gewaardeerd met 0-5 sterren en kan een reactie van 50 tekens worden geplaatst.


# Talen

De applicatie heeft ondersteuning voor Spaans en het Engels en kan vertaald worden in elk willekeurige andere taal.

___________________
___________________
# Screenshots

<p align="center">
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-17-55-17.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-17-57-40.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-17-57-55.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-01-00.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-01-26.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-01-44.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-01-59.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-02-06.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-02-23.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-02-41.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-03-27.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-03-38.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-03-55.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-05-49.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-07-13.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-07-20.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-09-28.png?raw=true" alt="Traxi" height="460" width="240"/>
<img src="https://github.com/LabPLC/Traxi/blob/master/screenshot/Screenshot_2014-06-02-18-10-00.png?raw=true" alt="Traxi" height="460" width="240"/>
</p>

___________________
___________________
# Ontwikkelaarsinformatie

De applicatie is ontwikkeld in Eclipse met ADT voor Android 4.0 of hoger

## Externe bibliotheken

* google_play_services_lib
* FacebookSDK

De google_play_services_lib bibliotheek kan worden toegevoegd met

    selecteert Nieuw-> Project -> Android Project van bestaande code
    dubbelklik op de route - "android-sdk \ extras \ Google \ google_play_services"
    
Voor het toevoegen van de Facebook SDK kijk je op:

    Het is in https://developers.facebook.com/docs/android/


## Interne bibliotheken

  Deze bevinden zich in de map project

* Acra-4.5.jar
* activation.jar
* additionnal.jar
* apache-mime4j-core-0.7.2.jar
* httpclient-4.3.1.jar
* httpcore-4.3.jar
* httpmime-4.3.1.jar
* mail.jar
* socketio.jar
    
Er kunnen compatibiliteitsproblemen optreden. Daarom kan het zijn dat acra-4.5.jar expliciet moet worden toegevoegd via
    Project-> Properties  -> Java Build Path -> Bibliotheken -> JAR toevoegen 
en voeg ..  de libs map die zich binnen het project bevindt toe
___________________
___________________
# Wilt u de app te proberen?

https://play.google.com/store/apps/details?id=codigo.labplc.mx.traxi&hl=es




# Ontwikkelaars

     @yosoymikesaurio
     miguel.moran@codigo.labplc.mx
     http://www.traxi.mx
