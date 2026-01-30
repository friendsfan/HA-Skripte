# Home Assistant Skripte & Blueprints

Eine Sammlung meiner nützlichen Home Assistant Blueprints und Skripte.

## Blueprints

### 🌅 Sanftes Aufwachlicht (Wake Up Light)

Dieser Blueprint simuliert einen Sonnenaufgang, indem er eine Lampe über einen definierten Zeitraum (z.B. 5 Minuten) schrittweise von 1% auf 100% Helligkeit dimmt.

**Features:**
*   💡 **Universell:** Funktioniert auch mit Lampen (Zigbee/WLAN), die den `transition`-Befehl nicht nativ unterstützen, da Home Assistant das Dimmen in 50 kleinen Schritten übernimmt.
*   🌡️ **Farbtemperatur:** Wählbar zwischen Warmweiß, Neutral und Kaltweiß.
*   ⏱️ **Dauer:** Anpassbare Dauer des Aufwachvorgangs.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Ffriendsfan%2FHA-Skripte%2Fblob%2Fmaster%2Fblueprints%2Fautomation%2Fwake_up_light.yaml)

**Direkter Link:**
`https://github.com/friendsfan/HA-Skripte/blob/master/blueprints/automation/wake_up_light.yaml`
