# test-linux

Een VirtualBox VM met een minimale installatie van Fedora voor gequoteerde Linux-test.

Startpunt is een base box gegenereerd door Packer met een template van [box-cutter](https://github.com/box-cutter/fedora-vm), meer bepaald Fedora 20, i386. Wijzigingen aan het standaard template zijn:

- Gebruik be-latin1 in Kickstart-configuratie
- Installeer alle updates
