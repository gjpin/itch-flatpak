# Install development dependencies
```
sudo pacman -S flatpak-builder
```

# Build application
sudo flatpak-builder build io.itch.itch.yml --install --force-clean

# Run application
flatpak run io.itch.itch

# based of: https://github.com/flathub/com.fightcade.Fightcade/pull/81