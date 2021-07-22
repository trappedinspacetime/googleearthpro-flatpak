# googleearthpro-flatpak

## How to build

1. Clone this repository: `git clone --recurse-submodules https://github.com/trappedinspacetime/googleearthpro-flatpak.git`
2. Add flathub repository: `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`
3. Install Freedesktop SDK with: `flatpak install flathub org.freedesktop.Sdk//20.08`
4. Install Freedesktop Platform with: `flatpak install flathub org.freedesktop.Platform//20.08`
5. cd into cloned repo: `cd googleearthpro-flatpak`
6. Build and install package: `flatpak-builder --user --install ./gearth com.google.Earth.json --force-clean`

## How to run

`flatpak run com.google.Earth`
