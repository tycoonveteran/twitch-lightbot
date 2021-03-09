# twitch-lightbot

## Was ist das hier? 
Wir programmieren einen Chatbot, der den Twitch-Channel überwacht, bestimmte Befehle entgegennimmt und dann über MQTT an einen ZigBee-Gerät weiterzuleiten und steuerbar zu machen. Damit kann dem Benutzer auf Twitch die Möglichkeit eingeräumt werden, die Farbe des Lichts zu steuern oder bestimmte Alerts lösen bestimmte Licht Kombinationen aus. 

## Aufbau
### Docker
Das Gesamtprojekt wird mittels einer docker-compose.yml ausgeliefert.
### LightbotClient
Ein PHP-CLI, welches die Verbindung zum Twitch-Chat aufbaut und die Nachrichten auf Bot-Befehle überwacht. 
### MQTT Client

### MQTT2ZigBee

### Genutzte Hardware
* CC2531 - Z-STack_Home USB Adapter
* Müller Licht Smart Light LED Strip white+color 2m
