# Rodent IV para Android - Mod de Personalidades Externas

[![Licencia: GPL v3](https://img.shields.io/badge/Licencia-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Android 15+](https://img.shields.io/badge/Android-15+-green)]()

Motor de ajedrez Rodent IV modificado para funcionar con **personalidades externas** en Android moderno (API 30+). Funciona con la GUI **Chess for Android**.

## Características

- ✅ **Compatible con Android 15 (API 30+)** – supera las restricciones de almacenamiento
- ✅ **Carga personalidades desde almacenamiento externo** – `/storage/emulated/0/c4a/uci/personalities/`
- ✅ **Soporta límite UCI_Elo** – juega a cualquier nivel de fuerza
- ✅ **Funciona con Chess for Android** – impórtalo como motor UCI
- ✅ **Warning inofensivo** – el mensaje `no 'basic.ini'` NO afecta el funcionamiento

## Instalación

1. **Descarga el APK** desde [Releases](https://github.com/ajedreztraductor/Rodent-IV-Android-External-Personalities/releases)
2. **Instala** el APK en tu dispositivo Android
3. Abre **Chess for Android** → Motores y Torneos → Importar motor
4. Selecciona **"Rodent IV 0.33"**

## Crear las carpetas (en el teléfono)

Crea esta carpeta en tu almacenamiento interno:
/storage/emulated/0/c4a/uci/personalities/

Usa cualquier administrador de archivos (ej. Mis Archivos de Samsung, Material Files).

## Configuración UCI

En las opciones del motor dentro de Chess for Android, configura, por ejemplo:
PersonalityFile = /storage/emulated/0/c4a/uci/personalities/tal.txt
UCI_LimitStrength = true
UCI_Elo = 1600
Verbose = true

## Personalidades

Los archivos de personalidad (`.txt`) **no están incluidos** en este repositorio por respeto al autor original.

Puedes descargar la colección oficial completa desde:
👉 **[GitHub - nescitus/rodent-iv/personalities](https://github.com/nescitus/rodent-iv/tree/master/personalities)**

Coloca los archivos `.txt` que quieras usar en la carpeta que creaste anteriormente.

## Nota importante

El mensaje de warning:
no 'basic.ini' - check installation, please

text
es **completamente inofensivo** y NO afecta el funcionamiento del motor. Las personalidades se cargan correctamente.

## Créditos

| Componente | Autor |
|------------|-------|
| Motor Rodent IV | [Pawel Koziol (nescitus)](https://github.com/nescitus/rodent-iv) |
| GUI Chess for Android | [Aart Bik](https://github.com/aartbik) |
| Mod para Android 15 con personalidades externas | [@ajedreztraductor](https://github.com/ajedreztraductor) |

## Licencia

GPL v3 – misma licencia que el motor Rodent IV original.
