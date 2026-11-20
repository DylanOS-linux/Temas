<h1 align="center">DylanOS Temas</h1>

<p align="center">
  <strong>Temas visuales y recursos de personalización del ecosistema DylanOS.</strong><br>
  Identidad Crimson aplicada a Plasma, GTK, SDDM, GRUB y Plymouth.
</p>

<p align="center">
  <a href="https://www.debian.org/"><img src="https://img.shields.io/badge/base-Debian%2013-A81D33?style=flat-square&logo=debian&logoColor=white" alt="Base Debian 13"></a>
  <a href="https://kde.org/plasma-desktop/"><img src="https://img.shields.io/badge/escritorio-KDE%20Plasma%206-1D99F3?style=flat-square&logo=kde&logoColor=white" alt="Escritorio KDE Plasma 6"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/licencia-GPL--3.0--or--later-blue?style=flat-square" alt="Licencia GPL-3.0-or-later"></a>
</p>

---

## Acerca de este repositorio

Este repositorio reúne los temas y recursos de personalización de DylanOS. Cada tema aplica la identidad visual Crimson a una parte del sistema y mantiene la coherencia estética, la legibilidad y la compatibilidad con KDE Plasma 6.

Los temas se diseñan para DylanOS y sus tecnologías de escritorio. La compatibilidad con otras distribuciones depende de los componentes utilizados, de la versión de Plasma y de las dependencias de cada recurso.

## Contenido

| Directorio | Contenido |
|---|---|
| [`aurorae/`](aurorae/) | Decoraciones de ventanas para KWin (`DylanOS-Crimson`, `DylanOS-Crimson-Light`) |
| [`colors/`](colors/) | Esquemas de color de Plasma (`DylanOSDark`, `DylanOSLight`) |
| [`grub/`](grub/) | Tema del cargador de arranque GRUB |
| [`gtk/`](gtk/) | Temas GTK 3 y GTK 4 (`DylanOS-Crimson`, `DylanOS-Crimson-Light`) |
| [`icons/`](icons/) | Paquete de iconos `DylanIcons-Crimson` |
| [`lookandfeel/`](lookandfeel/) | Paquete de escritorio `org.dylanos.crimson` |
| [`plasma/`](plasma/) | Estilos y widgets de Plasma (`DylanOS-Crimson`, `DylanOS-Crimson-Glass`) |
| [`plymouth/`](plymouth/) | Tema de arranque gráfico `DylanOS-Plymouth` |
| [`sddm/`](sddm/) | Pantalla de inicio de sesión `DylanOS-SDDM` |

Cada recurso documenta sus requisitos y su proceso de instalación en su propio directorio cuando corresponde.

## Estructura

```text
Temas/
├── aurorae/          # Decoraciones de ventanas
├── colors/           # Esquemas de color
├── grub/             # Tema de GRUB
├── gtk/              # Temas GTK
├── icons/            # Iconografía
├── lookandfeel/      # Paquete de escritorio Plasma
├── plasma/           # Estilos y widgets de Plasma
├── plymouth/         # Arranque gráfico
└── sddm/             # Inicio de sesión
```

## Instalación

Cada tema se instala en la ruta que corresponde a su tipo. Los recursos de Plasma, GTK, iconos y cursores se copian al directorio de usuario o del sistema, y los de arranque (GRUB, Plymouth y SDDM) requieren permisos de administrador.

Antes de instalar, revisa el contenido del tema y sus dependencias. Los temas de arranque pueden afectar al inicio del sistema, por lo que conviene probarlos en una máquina virtual.

## Criterios de diseño

Los recursos visuales mantienen los siguientes principios:

- consistencia entre los componentes del sistema;
- identidad propia de DylanOS basada en la paleta Crimson;
- accesibilidad y legibilidad;
- optimización de recursos;
- facilidad de instalación y mantenimiento.

La paleta oficial y el logo se publican en el repositorio [Branding](https://github.com/DylanOS-linux/Branding).

## Contribuir

Antes de enviar un tema o una modificación:

1. Comprueba que el recurso funciona en KDE Plasma 6.
2. Incluye capturas de pantalla cuando corresponda.
3. Documenta los requisitos y las dependencias.
4. Usa nombres de archivo descriptivos.
5. Abre un pull request con el cambio.

## Licencia

Este repositorio se distribuye bajo la [GNU General Public License v3.0](./LICENSE) (GPL-3.0), salvo que un recurso incluya una licencia independiente debidamente indicada. Consulta el archivo [`LICENSE`](./LICENSE) para conocer los términos de distribución y modificación.

## Ecosistema DylanOS

| Repositorio | Contenido |
|---|---|
| [DylanOS](https://github.com/dylanneymarmontalvo2014-lgtm/DylanOS) | Sistema operativo y desarrollo principal |
| [Apps](https://github.com/DylanOS-linux/Apps) | Aplicaciones y componentes |
| [Branding](https://github.com/DylanOS-linux/Branding) | Identidad visual y recursos oficiales |
| [Documentation](https://github.com/DylanOS-linux/Documentation) | Documentación técnica |
| [Temas](https://github.com/DylanOS-linux/Temas) | Temas y personalización |

---

<p align="center"><sub>DylanOS — Tu sistema, tu experiencia.</sub></p>
