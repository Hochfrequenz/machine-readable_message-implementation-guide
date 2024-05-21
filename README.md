# machine-readable_message-implementation-guide
Dieses repository enthält Message Implementation Guides (MIG) für die Marktkommunikation in der deutschen Energiewirtschaft in einer Form, die besser maschinenlesbar ist als `.docx` oder `.pdf` Dateien.

Wir pflegen analog zu den hier abgelegten Daten auch:
* [`machine-readable_anwendungshandbuecher`](https://github.com/Hochfrequenz/machine-readable_anwendungshandbuecher/) für AHBs
* [`edi_energy_ahb_conditions_and_packages`](https://github.com/Hochfrequenz/edi_energy_ahb_conditions_and_packages) für Bedingungen und Paket-Definitionen aus den AHBs
* [`machine-readable_message-implementation-guide`](https://github.com/Hochfrequenz/machine-readable_message-implementation-guide) für MIGs

## Unter der Haube

Zur Erstellung der hier veröffentlichten Daten nutzen wir [`migmose`]([https://github.com/Hochfrequenz/kohlrahbi/](https://github.com/Hochfrequenz/migmose)), eine Open Source MIG Scraping Library.
Änderungen auf edi-energy.de werden mehrmals täglich automatisiert über unseren [edi_energy_mirror](https://github.com/Hochfrequenz/edi_energy_mirror) in dieses Repository synchronisiert.
