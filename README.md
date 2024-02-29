# Rastreamento de veículos em tempo real usando Arduino

Neste projeto podemos rastrear veículos e também ligar ou desligar o motor, tudo em tempo real usando um Arduino. Você pode ver a localização atual do veículo, a última localização vista e os registros. 

# Características

As características das várias partes deste projeto são destacadas abaixo:

#### Aplicativo Android

Com base no webview que exibe o webapp

#### Código Arduino

Rastreia a localização do veículo em tempo real
Posta a localização GPS, hora, data, curso, altitude, velocidade, número de satélites usados, etc, para um servidor web

#### Servidor Web

Armazena informações de localização recebidas do Arduino em um arquivo de texto 
Mostra a corrente do veículo. Ele atualiza a cada 30s
Exibe a localização vista pela última vez do veículo e outros detalhes como localização, hora e altitude.

# Requirements

#### *Arduino:*  

  Arduino Uno
  [Elecro SIM808](https://www.aliexpress.com/item/High-Quality-SIM808-GPRS-GSM-GPS-Shield-2-in-1-Shield-GSM-GPRS-GPS-Development-Board/32515326895.html) (In software serial mode). 
  [240V/40A relay switch](https://www.aliexpress.com/item/Free-shipping-10Pcs-5V-30A-1-Channel-Relay-Module-Optocoupler-H-L-Level-Triger/32691375337.html)

#### *Web Server:*

  Google Maps Javascript API
  Host provider
  Database FirebaseCloud

#### *Software:*

  Arduino IDE
  Android Studio


# Set up

#### *Note:* Refer to the diagram for more information. 

  1. Fix the SIM808 shield into the Arduino Uno.
  2. Connect the relay switch to bridge to ignition switch or fuse. 
  2. Upload the code to the Arduino Uno using the IDE
  3. Upload the website code to your server and don't forget to add your Google Map Api code.
  4. Power up the Arduino and start tracking. This requires 12V/2A for stable operation. 