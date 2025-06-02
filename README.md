# Build Instructions
- Clone or download the repository.
- Install/setup flatpak and flatpak-builder from your distro
- Install sdk and runtime
- ```flatpak install flathub org.freedesktop.Sdk//24.08 org.freedesktop.Platform//24.08```
- Build with flatpak-builder
- ```flatpak-builder --install --user --force-clean ./build io.github.uowuo.abaddon.yml```

## Known Issues
- Message timestamps are incorrect, though debug info shows correct time.
