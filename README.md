# Dependencias

## Paquetes

| Paquete Debian | Propósito / Uso |
| :--- | :--- |
| **`git`** | Clonación y gestión de plugins mediante `lazy.nvim`. |
| **`build-essential`** | Compilador `gcc`/`g++` indispensable para compilar código C/C++. |
| **`make` & `cmake`** | Herramientas de compilación requeridas por plugins nativos (como `telescope-fzf-native`). |
| **`ripgrep`** | Motor de búsqueda de texto rápido utilizado por Telescope (`live_grep`). |
| **`fd-find`** | Buscador rápido de archivos para Telescope *(Nota: en Debian se instala como `fdfind`)*. |
| **`unzip`** | Descompresión de archivos para plugins y servidores de lenguaje (Mason). |
| **`xclip`** | Soporte para el portapapeles del sistema (copiar y pegar). |

## Comando de Instalación Rápida

```bash
sudo apt update && sudo apt install -y \
    git \
    build-essential \
    make \
    cmake \
    ripgrep \
    fd-find \
    unzip \
    xclip
```
## Cómo copiar esta configuración
### Linux
1. Borrar la configuración anterior
`rm -rf ~/.config/nvim` 
2. Clonar y listo
`git clone https://github.com/mplazaf/nvim-2026 ~/.config/nvim`
