# 🧰 Git, GitHub & Markdown

> **Guía de referencia esencial para el desarrollo de software y la colaboración en proyectos.**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

---

## 📖 Introducción

Bienvenido a esta guía. Aquí encontrarás información sobre el uso de **Git**, **GitHub** y **Markdown** — herramientas fundamentales para el desarrollo de software y la colaboración en proyectos modernos.

---

## 🔀 ¿Qué es Git?

**Git** es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente a lo largo del tiempo.

### ¿Para qué sirve?

| Función | Descripción |
|---|---|
| 📌 **Versiones** | Registra cada cambio realizado en el código |
| 🤝 **Colaboración** | Permite trabajar en equipo sin conflictos |
| ↩️ **Reversión** | Vuelve a cualquier estado anterior del proyecto |

### Comandos esenciales

```bash
git init              # Inicializar un repositorio
git add .             # Agregar cambios al staging
git commit -m "msg"   # Confirmar los cambios
git push              # Subir al repositorio remoto
git pull              # Traer cambios del remoto
git status            # Ver estado actual
```

---

## 🐙 ¿Qué es GitHub?

**GitHub** es una plataforma web que usa Git como motor de control de versiones. Permite alojar proyectos y colaborar con otros desarrolladores desde cualquier parte del mundo.

### Características clave

| Feature | Descripción |
|---|---|
| 📦 **Repositorios** | Almacenamiento de proyectos públicos o privados |
| 🐛 **Issues** | Seguimiento de errores y mejoras |
| 🔃 **Pull Requests** | Revisión y fusión de código colaborativo |
| ⚙️ **CI/CD** | Integración y despliegue continuo con GitHub Actions |

---

## ✍️ ¿Qué es Markdown?

**Markdown** es un lenguaje de marcado ligero que permite formatear texto de manera sencilla. Es el estándar para documentación, READMEs y wikis en GitHub.

### Sintaxis básica

```markdown
# Título H1
## Título H2

**negrita**   *itálica*   ~~tachado~~

- Item de lista
- Otro item

1. Lista numerada
2. Segundo item

[Texto del enlace](https://url.com)

`código en línea`
```

### Tabla de referencia rápida

| Elemento | Sintaxis |
|---|---|
| **Negrita** | `**texto**` |
| *Itálica* | `*texto*` |
| `Código` | `` `texto` `` |
| Enlace | `[texto](url)` |
| Imagen | `![alt](url)` |
| Cita | `> texto` |
| Separador | `---` |

---

## 📋 Hojas de Referencia

- 📄 [Git Cheatsheet — GitHub Education](https://education.github.com/git-cheat-sheet-education.pdf)
- 📄 [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- 📄 [GitHub Docs](https://docs.github.com/)

---

## 🚦 Flujo de trabajo típico

```
1. git clone / git init     → Obtener o crear el repositorio
        │
        ▼
2. Hacer cambios en el código
        │
        ▼
3. git add . + git commit   → Registrar los cambios
        │
        ▼
4. git push                 → Subir a GitHub
        │
        ▼
5. Pull Request / Merge     → Colaborar con el equipo
```

---

## 📄 Licencia ®

Este repositorio es de uso educativo. Contenido del **Curso GitHub 2024**.
