# Home Assistant Blueprints

A small collection of automation blueprints for [Home Assistant](https://www.home-assistant.io/), by NoFutureKid.

All blueprints are English, versioned (CalVer, e.g. `2026.8.0` — see the first line of each description), and keep user-facing texts configurable where it makes sense.

## Blueprints

| Blueprint | Version | Description | Import |
|---|---|---|---|
| **Climate Day/Night Schedule** | `2026.8.1` | Applies a day and a night climate setting (HVAC mode + target | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fclimate_workday.yaml) |
| **Dehumidifier Control** | `2026.8.0` | Controls a dehumidifier from a humidity sensor with adjustable | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fdehumidifier.yaml) |
| **Fairylights Schedule** | `2026.8.0` | Controls fairylights during the Christmas season (1st Advent to Jan 6). | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Ffairylights.yaml) |
| **Lights Off When Away** | `2026.8.0` | Turns off the lights when nobody is home, with optional excludes by | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Flights_off_away.yaml) |
| **Lights On When Dark** | `2026.8.0` | Runs actions when it actually gets dark, measured by an illuminance | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Flights_on_dark.yaml) |
| **Restart Notification** | `2026.8.0` | Sends a notification to selected devices when Home Assistant starts | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Frestart_notification.yaml) |
| **Water Leak Alert** | `2026.8.3` | Sends a one-time notification when a water leak or moisture sensor | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fwater_leak.yaml) |
| **Window Open Alert** | `2026.8.0` | Notifies when windows stay open longer than a set time, and clears the | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fwindow_open.yaml) |
| **Zone Presence Lights** | `2026.8.0` | Turns lights on when someone enters a zone and off (after a delay) | [![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnofuturekid%2Fha-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fzone_lights.yaml) |

## Installation

Click an **Import** badge above, or in Home Assistant go to **Settings → Automations & Scenes → Blueprints → Import Blueprint** and paste the blueprint's GitHub URL.

## License

[MIT](LICENSE)
