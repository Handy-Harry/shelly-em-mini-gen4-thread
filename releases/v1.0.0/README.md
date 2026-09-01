# Shelly Unofficial v1.0.0 (beta)

Publieke bètarelease van de onofficiële Matter-over-Thread-firmware voor de Shelly EM Mini Gen4.

## Inhoud

- Matter-over-Thread met spanning, stroom, vermogen en energie;
- bestaande kalibratie en de bewezen dual-WebUI-omschakelroute;
- private Thread-opslag en zeskliks-terugkeer naar Shelly-firmware;
- correcte LED-initialisatie bij een warme omschakeling vanuit Shelly;
- standaard Matter `NodeLabel`: `Shelly EM Mini Gen4`;
- zichtbaar WebUI-label `Stage: beta · Thread · UI 1.0.0`;
- firmware-identiteit `1.0.0` (numerieke Matter-versie `65536`).

## Installeren

Open in de Shelly WebUI **Settings → Firmware → Firmware file image** en selecteer:

`shelly-unofficial-em-mini-gen4-v1.0.0-dual-webui.zip`

Gebruik niet **Switch to alternative firmware** voor Zigbee. Onderbreek tijdens de update de voeding niet.

## Verificatie

De offline firmware-, identiteit-, partitie-, NVS-, LED- en regressietests zijn uitgevoerd. De warme LED-omschakeling is ook fysiek op het apparaat bevestigd.

Controleer na installatie de meetwaarden en gebruik zo nodig **Identificeren** in Home Assistant om de LED-functie te testen.
