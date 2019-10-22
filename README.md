# rogueL2
WASM Version of Classical Rogue 5.4.4 with Amulet Level 2

How it

Als erstes eine virtuelle Maschine einrichten mit einem aktuellen Ubuntu Linux: https://www.ubuntu.com/download/desktop (Ubuntu 18.04.2 LTS)

Dann die Werkzeuge, die gebraucht werden eingerichtet:  git, clang, cmake, python

Auf das Thema Webassembly eingestimmt: https://tutorials.technology/tutorials/54-Webassembly-tutorial-using-emscripten-hello-world.html

Das gibt die nächsten Schritte (Fetch the latest registry of available tools):

./emsdk update

./emsdk install latest # Download and install the latest SDK tools.

./emsdk activate latest # Make the "latest" SDK "active"

source emsdk/emsdk_env.sh # Die Umgebung wird konfiguriert.

Wer sich für Beispiele interessiert, wie nach Webassembly portiert wird bzw. wurde: https://github.com/emscripten-core/emscripten/wiki/Porting-Examples-and-Demos

Da waren wir froh, dass Rogue schon portiert war und wir die Quellen von github herunter laden konnten:  https://github.com/mad4j/rogue.js

In der 26 Ebene ist das Amulett fast nicht zu erreichen. Deshalb für die Einstimmung auf Ebene zwei geändert. Ein paar Ausgaben dem neuen Zweck angepasst. make aufgerufen.

Ein wenig Webgeraffel...

