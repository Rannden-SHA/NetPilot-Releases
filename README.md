# NetPilot · versiones publicadas

Instaladores de [NetPilot](https://nextcodeagency.com), la plataforma de documentación y operación de redes de
NextCode Agency. Cada versión está en [Releases](../../releases) con sus sumas SHA-256.

* **Windows**: `NetPilotSetup-<versión>.exe`
* **Linux**: `netpilot-installer-<versión>.run` (recomendado) o `netpilot_<versión>_all.deb`
* **Docker**: `netpilot-docker-<versión>.tar.gz` (`docker load -i …`)

`channels/stable.json` y `channels/beta.json` son los manifiestos **firmados** (Ed25519) que consulta NetPilot para
avisar de las versiones nuevas y actualizarse: NetPilot no instala nada cuya firma o suma no coincidan.
