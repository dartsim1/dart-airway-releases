# DART Airway sensor firmware releases

Compiled firmware images and the update manifest for the DART Airway
ventilation sensor, consumed by the DART Sim / CPR Coach iPad apps
(AIRWAY-SENSOR-PROTOCOL.md v1.2, "Where images come from").

- Latest manifest (stable URL):
  https://raw.githubusercontent.com/dartsim1/dart-airway-releases/main/manifest.json
- Images: attached to each release, e.g.
  https://github.com/dartsim1/dart-airway-releases/releases/download/v1.4.0/dart-airway-1.4.0.bin

Manifest fields: version, size, sha256, url, minProtocol, notes. Apps verify
the SHA-256 after download and again on the sensor.

Source code lives in a private repository. Training device; not for patient care.