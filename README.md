# itch client Flatpak 
Flatpak version of [itch.io client app](https://itch.io/app).

It uses org.winehq.Wine as a base and, as such, both native Linux games and Windows games will work out of the box. 

# Development
  - Development tools: `sudo pacman -S flatpak-builder`
  - Build application: `sudo flatpak-builder build io.itch.itch.yml --install --force-clean`
  - Run application: `flatpak run io.itch.itch`

# References
Flatpak manifest based on: `https://github.com/flathub/com.fightcade.Fightcade/pull/81`