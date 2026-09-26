# Actividad de refuerzo 2.3 — Conectividad en IoT

Equipo 7 · Internet de las Cosas 2026-2 · Universidad de La Sabana.

Diseño de una red de nodos de monitoreo hídrico en Sabana Centro con MQTT y su validación en Cisco Packet Tracer 9.0.0.810. El documento de la actividad está en la **[Wiki de este repositorio](https://github.com/Majo7-613/IoT-Refuerzo2.3-Conectividad-UniSabana/wiki/)**.

> Esta actividad usa MQTT. **El prototipo del Challenge #2 no usa MQTT:** su tablero se aloja en el propio ESP32 dentro de la WLAN local ([repositorio del Challenge #2](https://github.com/Majo7-613/IoT-Challenge2-UniSabana)).

## Contenido

| Carpeta o archivo | Contenido |
| :--- | :--- |
| [`packet-tracer/red-sabana-centro.pkt`](packet-tracer/red-sabana-centro.pkt) | Simulación validada: dos municipios, ISP y nube con broker, plataforma y servidor web |
| [`capturas/`](capturas/) | Evidencia de la validación, enlazada desde la Wiki |
| [`variante-pablo/dolordedientes-mqtt.pkt`](variante-pablo/dolordedientes-mqtt.pkt) | Variante con MCU y sensores IoT de Packet Tracer (autor: Pablo Tamayo); no ejecutada para esta entrega |
| [`docs/GUIA_PACKET_TRACER.md`](docs/GUIA_PACKET_TRACER.md) | Cómo reconstruir la topología y repetir las pruebas |

Los datos de los nodos son simulados y cada mensaje lo declara con `"origen":"simulado"`.

## Equipo

| Integrante | GitHub |
| :--- | :--- |
| María José Almanza Caviedes | [@Majo7-613](https://github.com/Majo7-613) |
| Pablo Andrés Tamayo González | [@ItsN3M3515](https://github.com/ItsN3M3515) |
| Simón Martínez García | [@simonmartinezunisabana](https://github.com/simonmartinezunisabana) |
