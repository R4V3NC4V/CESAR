# OSINT Toolkit para Windows

Este proyecto permite ejecutar comandos OSINT desde una interfaz gráfica en Windows.

## Funciones
- Investigación de empresas (dominios, subdominios, puertos)
- Investigación de personas (redes sociales, metadatos)
- Investigación de redes (IP, geolocalización, traceroute)

## Requisitos
- Python 3 instalado    
- PyInstaller (`pip install pyinstaller`)
- Herramientas OSINT instaladas (nmap, whois, etc.)

## Cómo generar el ejecutable
```bash
pyinstaller --onefile --windowed --icon=icon.ico osint_gui.py
# CESAR
