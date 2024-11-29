# Plantilla-pyqt5-localindex
PLantilla para cargar un index html desde carpeta local usando un webview y pyqt5

Puede empaquetar el proyecto en un portable de un solo archivo usando luego

pyinstaller -F --add-data "./index.html:."  --add-data "./im.gif:." main.py
