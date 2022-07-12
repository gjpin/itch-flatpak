# itch client Flatpak 
Flatpak version of [itch.io client app](https://itch.io/app).

It uses org.winehq.Wine as a base and, as such, both native Linux games and Windows games will work out of the box. 

# Development
  - Development tools: `sudo dnf install -y flatpak-builder`
  - Install dependencies: `sudo flatpak install flathub org.winehq.Wine/x86_64/stable-21.08 org.freedesktop.Sdk/x86_64/21.08`
  - Build application: `sudo flatpak-builder build io.itch.itch.yml --install --force-clean`
  - Run application: `flatpak run io.itch.itch`

# References
Flatpak manifest based on: `https://github.com/flathub/com.fightcade.Fightcade/pull/81`
