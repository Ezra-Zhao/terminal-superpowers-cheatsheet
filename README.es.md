# Hoja de referencia: superpoderes de la terminal · Terminal Superpowers

> 🌍 [中文](README.md) · [Português](README.pt.md)

Una **hoja de referencia de una sola página** con las herramientas de terminal que de verdad valen la pena en 2026: 14 herramientas, y cada entrada responde solo cuatro preguntas — **qué hace, cómo se instala, un comando para probarla ya mismo y etiquetas de uso**. Sin relleno.

## Para quién es

Para ingenieros de operaciones (SRE/DevOps), desarrolladores backend y cualquiera que viva dentro de la terminal. Si todavía trabajas con `cd`, `ls`, `cat` y `grep` a pelo, esta hoja te ahorra media hora al día.

## Cómo usarla

1. Ve directo a **[CHEATSHEET.md](CHEATSHEET.md)** — el cuerpo de la referencia, legible para desarrolladores de cualquier idioma.
2. Empieza con el "paquete inicial", un solo comando (macOS / Homebrew):
   ```bash
   brew install zoxide fzf fd ripgrep eza bat starship lazygit tldr btop tmux zellij
   ```
   En Debian/Ubuntu, la mayoría también se instalan con `sudo apt install <nombre>`.
3. Con cada herramienta, ejecuta el comando de "pruébalo": en cinco minutos sabrás si se queda.

## Qué incluye

| Categoría | Herramientas |
|---|---|
| 🆕 Novedades 2026 | cmux (terminal pensada para agentes de IA), yoinks (descargar videos sin salir de la terminal) |
| 🧭 Navegación y búsqueda | zoxide (`cd` inteligente), fzf (búsqueda difusa), fd (reemplazo de `find`), ripgrep (reemplazo de `grep`) |
| 🖥️ Multiplexores y prompt | tmux (el multiplexor clásico), zellij (espacio de trabajo moderno), starship (prompt inteligente) |
| 📄 Ver archivos | eza (reemplazo de `ls`), bat (reemplazo de `cat`) |
| 🛠️ Flujo de desarrollo | lazygit (git visual en la terminal), tldr (ayuda rápida de comandos) |
| 📊 Monitoreo | btop (monitor de recursos) |

Todos los enlaces oficiales y de GitHub están verificados, y los comandos de instalación son reales y funcionales.

## Por qué estas 14

- **Novedades 2026**: cmux y yoinks son herramientas nuevas que despegaron este año en GitHub y resuelven problemas nuevos de la era de la programación con IA.
- **Clásicos**: las otras 12 llevan años demostrando su valor; cada una reemplaza un viejo comando de Unix por algo mucho más rápido y mucho más legible.

## Contribuciones bienvenidas

¿Conoces una herramienta mejor, un comando incorrecto o una traducción mejorable? Los *pull requests* son bienvenidos. Mantén el formato de cada entrada (qué hace / instalación / pruébalo / etiquetas) y **verifica que los enlaces funcionen antes de enviarlo**.

## Licencia

MIT © 2026 Guangyi Zhao. Ver [LICENSE](LICENSE).
