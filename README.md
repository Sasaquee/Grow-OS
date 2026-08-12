# GROW/OS

Sistema de cultivo automatizado em terrário: sensores cuidam da umidade, uma ESP32-CAM cuida da vigilância, e um dashboard cuida do resto.

Documento único com arquitetura, orçamento, escolha das plantas, passo a passo de montagem, diagrama de ligação, esboço do dashboard e um prompt pronto pra retomar o projeto com IA.

## Stack

- **Arduino Uno/Nano** — leitura de sensores e controle local (relé/bomba)
- **ESP32-CAM** — monitoramento visual via wifi
- **NodeMCU ESP8266** — ponte serial → MQTT
- **Mosquitto + Home Assistant** — automação, rodando em Docker
- **Terrário** — samambaia-avenca, fittônia e musgo esfagno

## Live

🔗 https://sasaquee.github.io/Grow-OS/

## Estrutura

```
index.html   → documento completo do projeto
```
