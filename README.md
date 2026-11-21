# 🐉 Kali Lab · Práctica de comandos (Prog. VI)

Simulador web de un escritorio Kali Linux para practicar la terminal. Funciona en PC y en celular, y no necesita instalar nada.

En el escritorio hay tres iconos:

| Icono | Qué es |
|---|---|
| **Práctica** | Terminal con la profe: te pide tareas al azar (69 en total), escribes el comando y te dice si está bien o en qué te equivocaste. |
| **Terminal** | Terminal libre, sin tareas, para practicar lo que quieras. |
| **comandos.txt** | La lista de comandos para estudiar. |

Las dos terminales son independientes: cada una tiene sus propios archivos, historial y pantalla. Nada de lo que escribas afecta a tu equipo real.

## 🚀 Subirlo a GitHub Pages

1. Crea un repositorio **público** en GitHub (por ejemplo `kali-lab`).
2. Pulsa **Add file → Upload files** y sube `index.html` y `README.md`. Pulsa **Commit changes**.
3. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/kali-lab/`.

## ⌨️ Qué simula la terminal

Funcionan los comandos del tutorial: `pwd`, `ls`, `cd`, `mkdir`, `touch`, `echo >`, `cat`, `cp`, `mv`, `rm`, `chmod`, `./script.sh`, `nano`, `sudo`, `apt update/install/remove`, `ip a`, `ping`, `find`, `grep`, `head`, `tail`, `tree`, `zenity`… También acepta variables (`nombre=$(...)`, `echo $?`), tuberías (`|`), `&&` y `> /dev/null`.

Los mensajes salen en inglés, como en Kali real. Los scripts con `if`, `case` o `for` (como el `menu.sh` del tutorial) hay que probarlos en Kali real.

En la terminal de práctica: `tarea`, `pista`, `saltar`, `puntaje`, `reiniciar` y `ayuda`.
