# Home Assistant Blueprints

A small collection of automation blueprints for [Home Assistant](https://www.home-assistant.io/), by NoFutureKid.

All blueprints are English, versioned (CalVer, e.g. `2026.8.0` — see the first line of each description), and keep user-facing texts configurable where it makes sense.

## Blueprints

| Blueprint | Version | Description | Import |
|---|---|---|---|
| **Climate Day/Night Schedule** | `2026.8.3` | Applies a day and a night climate setting from a single automation, each switching at a time picked by a workday sensor. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fclimate_workday.yaml) |
| **Dehumidifier Control** | `2026.8.1` | Runs a dehumidifier from a humidity sensor, with separate day and night thresholds. Turns on above the upper limit, off below the lower one. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fdehumidifier.yaml) |
| **Fairylights Schedule** | `2026.8.1` | Controls fairylights through the Christmas season, from 1st Advent to January 6th. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Ffairylights.yaml) |
| **Lights Off When Away** | `2026.8.1` | Turns off the lights when nobody is home. Entities, areas or labels can be excluded, for example to keep fairylights on. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Flights_off_away.yaml) |
| **Lights On When Dark** | `2026.8.3` | Runs actions when it actually gets dark, measured by an illuminance sensor instead of guessed from sun elevation. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Flights_on_dark.yaml) |
| **Restart Notification** | `2026.8.1` | Notifies the selected devices when Home Assistant starts or shuts down. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Frestart_notification.yaml) |
| **Water Leak Alert** | `2026.8.4` | Sends a one-time notification when a water leak or moisture sensor triggers, with separate settings and texts for each. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fwater_leak.yaml) |
| **Window Open Alert** | `2026.8.2` | Notifies when a window stays open longer than a set time, and clears the notification again when it closes. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fwindow_open.yaml) |
| **Zone Presence Lights** | `2026.8.1` | Turns lights on when someone enters a zone and off, after a delay, when the zone becomes empty. | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fzone_lights.yaml) |

## Installation

Click an **Import** badge above, or in Home Assistant go to **Settings → Automations & Scenes → Blueprints → Import Blueprint** and paste the blueprint's GitHub URL.

## License

[MIT](LICENSE)
