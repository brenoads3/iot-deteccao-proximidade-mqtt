Sistema Inteligente de Detecção de Proximidade com ESP32 e Comunicação MQTT

Este repositório contém a implementação completa do protótipo desenvolvido para a disciplina Prática Profissional em Análise e Desenvolvimento de Sistemas, do Mackenzie.

📌 Descrição do Projeto

O sistema realiza:

Medição de distância usando o sensor ultrassônico HC-SR04

Envio dos dados para um broker MQTT

Acionamento de um LED via MQTT (atuador)

Processamento utilizando o ESP32 DevKit V1

Comunicação via Wi-Fi e protocolo MQTT (TCP/IP)

🧰 Hardware Utilizado

ESP32 DevKit V1

Sensor Ultrassônico HC-SR04

LED 5mm

Resistor 220 Ω

Protoboard

Jumpers

Cabo USB

Imagens reais da montagem encontram-se no diretório /imagens.

🛠️ Software e Bibliotecas

Arduino IDE

Bibliotecas:

WiFi.h

PubSubClient.h

Broker MQTT (Mosquitto / HiveMQ / Ubidots)

🔌 Pinos utilizados
Componente	Pino no ESP32
Trigger HC-SR04	D5
Echo HC-SR04	D18
LED	D2
📡 MQTT

Tópico de envio (publish):
esp32/distancia

Tópico de recepção para o LED:
esp32/led

📜 Fluxograma e Diagrama eletrônico

Os diagramas estão no diretório /diagramas:

fluxograma.pdf

circuito_fritzing.png

💻 Código do Projeto

O código completo está no arquivo codigo/main.ino.

🎥 Vídeo Demonstrativo

Vídeo (não listado):
👉 https://youtu.be/SEU-LINK-AQUI

📊 Medições

A tabela de tempos de resposta e gráficos encontram-se na pasta /resultados.

🧪 Como reproduzir

Clone o repositório

Abra o código na Arduino IDE

Configure seu Wi-Fi e broker

Faça o upload para o ESP32

Abra o monitor serial

📎 Autor

Breno Souza — Universidade Presbiteriana Mackenzie
