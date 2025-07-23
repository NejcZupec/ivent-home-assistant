# 🌀 i-Vent Home Assistant Integration

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://hacs.xyz/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Integracija za povezavo Home Assistant z i-Vent pametnim prezračevalnim sistemom prek Cloud API-ja.

## 🚀 Funkcionalnosti

- 📡 Branje stanja skupin in naprav (senzorji)
- 🔘 Aktivacija načinov delovanja: Boost, Izklop (gumbi)
- ♻️ Samodejno osveževanje vsake 30 sekund
- 🧩 Podpora za konfiguracijo preko uporabniškega vmesnika (UI)

## 🛠 Namestitev

1. Prenesi ta projekt ali ga kloniraj iz GitHub.
2. Kopiraj mapo `custom_components/ivent` v:
   ~/.homeassistant/custom_components/ivent/
3. Znova zaženi Home Assistant.

## ⚙️ Konfiguracija

### UI (priporočeno)

1. Odpri `Nastavitve > Naprave in storitve > Dodaj integracijo`.
2. Poišči **i-Vent**.
3. Vnesi svoj **API ključ** in **ID lokacije**.

## 🔐 Pridobitev API ključa

1. Obišči: https://cloud.i-vent.com
2. Pojdi na **Settings > Keys**
3. Ustvari nov API ključ in ga shrani varno.

## 📄 Licenca

MIT
