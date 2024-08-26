# Build Instructions
- Clone or download the repository.
- Install/setup flatpak and flatpak-builder from your distro
- Install sdk and runtime
- ```flatpak install flathub org.gnome.Sdk//45 org.gnome.Platform//45```
- Build with flatpak-builder
- ```flatpak-builder --install --user --force-clean ./build io.github.uowuo.abaddon.yml```

## Known Issues
- Icon not matching app id and not exported
