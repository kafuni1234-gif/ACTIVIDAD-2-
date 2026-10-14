
# Proyecto de práctica con Git y GitHub

## 1. Descripción del proyecto

Este proyecto tiene como finalidad aprender y aplicar los conceptos fundamentales de Git y GitHub mediante la creación y administración de un repositorio, el registro de cambios y la elaboración de un tutorial sobre el uso de estas herramientas.

El tutorial se desarrolla en documentos de Microsoft Word, que posteriormente se exportan a PDF. Cada capítulo aborda diferentes conceptos y comandos de Git, con explicaciones y ejemplos prácticos.

## 2. Objetivos

### Objetivo general

Aprender a utilizar Git y GitHub para administrar repositorios, controlar versiones y documentar los cambios realizados durante el desarrollo de la actividad.

### Objetivos específicos

- Crear y administrar un repositorio en GitHub.
- Comprender los conceptos fundamentales de Git.
- Conocer el funcionamiento de las ramificaciones y los repositorios remotos.
- Utilizar comandos básicos para registrar y sincronizar cambios.
- Elaborar documentos explicativos sobre Git y GitHub.
- Exportar los documentos de Word a formato PDF.
- Registrar los avances mediante commits con mensajes claros.
- Documentar el procedimiento seguido durante la actividad.

## 3. Herramientas utilizadas

- **Git:** sistema de control de versiones.
- **GitHub:** plataforma para alojar y administrar repositorios.
- **Microsoft Word:** herramienta para elaborar los documentos del tutorial.
- **Git Bash o terminal de comandos:** herramienta para ejecutar los comandos de Git.
- **Formato PDF:** utilizado para entregar los documentos exportados.

## 4. Estructura del repositorio

El repositorio contiene los documentos del tutorial y el archivo README.md, que describe el proceso de trabajo.

El tutorial está organizado en cinco capítulos:

1. Introducción a Git.
2. Fundamentos de Git.
3. Ramificaciones en Git.
4. Git en el servidor.
5. GitHub, repositorios remotos y flujo de trabajo.

Cada capítulo se prepara en Microsoft Word y se exporta a PDF para facilitar su consulta y entrega.

## 5. Comandos básicos de Git

| Comando | Descripción |
|---|---|
| `git --version` | Verifica la versión instalada de Git. |
| `git init` | Inicializa un repositorio local. |
| `git clone` | Clona un repositorio remoto. |
| `git status` | Muestra el estado de los archivos. |
| `git add .` | Prepara los cambios de los archivos del directorio actual. |
| `git commit -m "Descripción"` | Registra los cambios preparados con un mensaje descriptivo. |
| `git log` | Muestra el historial de confirmaciones. |
| `git push origin main` | Envía las confirmaciones de la rama main al repositorio remoto. |
| `git pull origin main` | Obtiene e integra los cambios de la rama main del repositorio remoto. |

## 6. Procedimiento

1. Instalar Git y comprobar que funcione correctamente.
2. Crear o utilizar el repositorio de GitHub destinado a la actividad.
3. Elaborar los capítulos del tutorial en documentos de Microsoft Word.
4. Exportar cada capítulo a formato PDF.
5. Agregar los documentos al repositorio local.
6. Revisar los cambios mediante `git status`.
7. Preparar los cambios con `git add`.
8. Registrar cada avance mediante `git commit`, utilizando mensajes descriptivos.
9. Enviar las confirmaciones al repositorio remoto con `git push`.
10. Verificar en GitHub que los archivos se hayan publicado correctamente.
11. Actualizar este README.md para documentar el contenido y el proceso realizado.

## 7. Ejemplo de registro de cambios

Los siguientes comandos muestran un ejemplo del procedimiento para registrar y enviar cambios:

```bash
git status
git add .
git commit -m "Agrega documentación del capítulo"
git push origin main
```

El comando `git status` permite revisar el estado del repositorio; `git add .` prepara los cambios; `git commit` registra una nueva versión, y `git push origin main` envía las confirmaciones a GitHub.

El mensaje del commit debe adaptarse al cambio realizado.

## 8. Dificultades y soluciones

Durante la preparación del entorno de trabajo se presentaron dificultades relacionadas con la instalación y el funcionamiento de Git en Windows. Para continuar con la actividad, se revisó la instalación y se realizaron procedimientos de solución de problemas.

Estas experiencias permitieron reconocer la importancia de comprobar el funcionamiento de las herramientas antes de comenzar a trabajar con los repositorios.

## 9. Resultados

Como resultado de la actividad, se busca contar con un repositorio organizado, un tutorial dividido en cinco capítulos y sus respectivos documentos en Word y PDF.

También se busca demostrar el uso de comandos básicos de Git, el registro de cambios mediante commits y la sincronización del trabajo con GitHub. Estos resultados deben comprobarse revisando los archivos y el historial del repositorio.

## 10. Conclusión

El desarrollo de esta actividad permite comprender la utilidad de Git y GitHub para administrar archivos y controlar sus versiones. La elaboración del tutorial fortalece los conocimientos sobre repositorios locales y remotos, ramificaciones, confirmaciones y sincronización de cambios.

Asimismo, la documentación del procedimiento facilita el seguimiento de los avances y promueve una forma de trabajo organizada y verificable.

## Referencias bibliográficas

Chacon, S., y Straub, B. (2014). *Pro Git* (2.ª ed.). Apress. https://git-scm.com/book/es/v2

Git. (s. f.). *Documentación oficial de Git*. https://git-scm.com/doc

---

**Autor:** KAREN LIZETH FULA NIETO

**Asignatura:** INTRODUCCIÓN A LA CIENCIA DE DATOS

**Institución:** Fundación Universitaria Agraria de Colombia (UNIAGRARIA)

**Fecha:** 14 de octubre de 2026