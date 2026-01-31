# Home Assistant Skripte & Blueprints

Eine Sammlung meiner nützlichen Home Assistant Blueprints und Skripte.

## Blueprints

### 🌅 Sanftes Aufwachlicht (Wake Up Light)

Dieser Blueprint simuliert einen echten Sonnenaufgang, indem er eine Lampe über einen definierten Zeitraum nicht nur heller macht, sondern auch die Farbe ändert (z.B. von "Warm" zu "Neutral").

**Features:**
*   🌅 **Sonnenaufgangs-Effekt:** (Neu) Das Licht kann die Farbe während des Dimmens wechseln (z.B. Start bei 2000K, Ende bei 4000K).
*   📱 **Handy-Wecker Sync:** Wähle deinen `next_alarm` Sensor (Android Companion App), und das Licht beginnt automatisch **vor** dem Wecker zu dimmen.
*   🏠 **Anwesenheits-Check:** Handy-Wecker triggert nur, wenn du auch zuhause bist.
*   📅 **Dual-Zeitplan:** Unterstützt zwei getrennte Profile in einer Automatisierung (z.B. **Werktags 06:30** und **Wochenende 09:00**).
*   💡 **Universell:** Funktioniert auch mit Lampen (Zigbee/WLAN), die den `transition`-Befehl nicht nativ unterstützen (Schrittweise Dimmung).

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Ffriendsfan%2FHA-Skripte%2Fblob%2Fmaster%2Fblueprints%2Fautomation%2Fwake_up_light.yaml)

**Direkter Link:**
`https://github.com/friendsfan/HA-Skripte/blob/master/blueprints/automation/wake_up_light.yaml`

---

## ⚠️ Disclaimer / Hinweis

Alle Skripte und Blueprints in diesem Repository wurden von einer **Künstlichen Intelligenz (Google Gemini CLI Agent)** generiert. 
Bitte überprüfe den Code vor der Verwendung in deiner Produktivumgebung, da Fehler nicht ausgeschlossen werden können. Nutzung auf eigene Gefahr.