# Malambo — versiones

Instaladores del **sistema de control de almacén con predicción de stock de Malambo Bar** (Huacho, 2026).
Este repositorio solo publica las versiones: el código del sistema es privado.

## Descargar
Última versión: **[Releases → Latest](https://github.com/JaromTMKC/MalamboVersions/releases/latest)** →
`Malambo-Setup-x.y.z.exe`. Ábralo en la PC que hará de servidor (Windows 10/11 de 64 bits); Java viene incluido y el
instalador puede instalar SQL Server Express.

## Actualizaciones
Las PC con Malambo instalado buscan aquí las versiones nuevas y las instalan solas cuando el administrador lo aprueba.
Cada versión trae:
- `Malambo-Setup-x.y.z.exe` — el instalador;
- `Malambo-Setup-x.y.z.exe.sha256` — su suma SHA-256;
- `Malambo-Setup-x.y.z.exe.sig` — su firma digital (Ed25519) sobre `malambo-setup|x.y.z|<sha256>`.

Malambo solo instala versiones más nuevas, descargadas de GitHub, cuya suma y firma coincidan con la clave pública que
trae el programa. Un archivo alterado o firmado por otra persona se rechaza y se borra.
