# Build Instructions
- Clone or download the repository.
- Install/setup flatpak and flatpak-builder from your distro
- Install patchelf from your distro
- Install sdk and runtime
- ```flatpak install flathub org.gnome.Sdk//47 org.gnome.Platform//47```
- Build with flatpak-builder
- ```flatpak-builder --install --user --force-clean ./build io.github.uowuo.abaddon.yml```

## Known Issues
- Message timestamps are incorrect, though debug info shows correct time.
