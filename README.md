# Keylogger_chato_rodrigo
keylogger-trabajo parcial de hacking etico

 Descripción
Keylogger educativo desarrollado en Python con fines únicamente académicos.  
Captura pulsaciones de teclas y toma capturas de pantalla automáticas cada 15 segundos.

Características
- Captura de teclas en tiempo real (incluye teclas especiales)
- Capturas de pantalla automáticas cada 15 segundos
- Reportes por correo electrónico cada 5 minutos
- Modo sigiloso (`--noconsole`)
- Compilado a `.exe` con PyInstaller
- Fácil de explicar en la exposición

Tecnologías utilizadas
- Python 3
- `pynput` → captura de teclas
- `mss` → capturas de pantalla
- `smtplib` → envío de emails
- PyInstaller → compilación a `.exe`

 Estructura del proyecto
 Keylogger TB1_Hacking/
├── keylogger.py                  # Código fuente
├── keylogger.exe                 # Ejecutable (modo sigiloso)
├── screenshots/                  # Carpeta con capturas de pantalla
├── keys.log                      # Archivo de logs de teclas
├── README.md
└── dist/                         # Carpeta generada por PyInstaller
