# Harmony Code · Descargas

Instaladores oficiales de **Harmony Code**, tu agente de programación con IA.

**Descárgalos desde la web: [harmony-start.com](https://harmony-start.com)**, que detecta tu sistema y te da el archivo correcto.

| Sistema | Archivo |
|---|---|
| Windows 10 y 11 (x64 y ARM) | `Harmony-Code-Setup-<versión>.exe` |
| macOS (Apple Silicon) | `Harmony-Code-<versión>-arm64.dmg` |
| macOS (Intel) | `Harmony-Code-<versión>-x64.dmg` |
| Linux | `.AppImage`, `.deb` o `.rpm` |
| Android 8 o superior | `harmonycode-<versión>.apk` |

iPhone llegará más adelante.

## Comprueba que son auténticos

En [harmony-start.com](https://harmony-start.com), dentro de cada sistema, está la huella **SHA-256** de cada archivo.
Compárala con la del archivo descargado antes de instalarlo:

- Windows (PowerShell): `Get-FileHash .\Harmony-Code-Setup-1.0.0.exe`
- macOS y Linux: `shasum -a 256 <archivo>`

Si no coincide, no lo instales.

Este repositorio solo contiene los instaladores; el código de Harmony Code es privado.
