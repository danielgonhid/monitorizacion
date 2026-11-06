# 📊 Monitorización en Linux

Apuntes y prácticas de monitorización del sistema para la asignatura **Herramientas DevOps** (2º ASIR).

Todas las pruebas están hechas en Ubuntu, en los equipos del aula.

---

## 📚 Índice

| # | Tema | Herramientas |
|---|------|--------------|
| 1 | [Procesos](docs/1.md) | `ps`, `top`, `htop`, `atop` |
| 2 | [Memoria, espacio y rendimiento del disco](docs/2.md) | `free`, `df`, `du` |
| 3 | Tráfico de la red *(pendiente)* | — |

---

## 🗂️ Estructura del repositorio

```
monitorizacion/
├── README.md     ← estás aquí
├── docs/
│   ├── 1.md      ← Procesos
│   └── 2.md      ← Memoria, espacio y disco
├── img/          ← capturas, nombradas X-Y.png
│                    (X = documento, Y = orden dentro del documento)
├── top.info      ← salida de top en modo batch (ejercicio del tema 1)
└── LICENSE
```

---

## ⚡ Chuleta rápida

| Quiero saber... | Comando |
|-----------------|---------|
| Todos los procesos del sistema | `ps aux` |
| Procesos de un usuario | `ps -u usuario` |
| Un proceso por nombre | `ps -C nombre` |
| Qué consume más CPU ahora mismo | `top` (y pulsar `P`) |
| Qué consume más RAM ahora mismo | `top` (y pulsar `M`) |
| Lo mismo, pero más visual | `htop` |
| Historial de consumo (qué pasó antes) | `atop -r` |
| Memoria RAM y swap | `free -h` |
| Espacio libre en los discos | `df -hT` |
| Cuánto ocupa una carpeta | `du -hs carpeta` |

---

## 📄 Licencia

[GPL-3.0](LICENSE)
