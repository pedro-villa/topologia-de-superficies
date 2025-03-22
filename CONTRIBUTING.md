# Guía para Contribuir a "Topología de Superficies"

¡Gracias por tu interés en mejorar los apuntes de Topología de Superficies! Dado que este proyecto se basa en la creación y mantenimiento de documentos en LaTeX, los cambios que realices deben concentrarse en los archivos fuente (.tex) ubicados en el directorio `src/`. El PDF se actualiza automáticamente mediante GitHub Actions, por lo que **no es necesario ni se debe subir el archivo PDF generado** (está en la carpeta `pdf/`).

---

## Tabla de Contenidos

1. [Requisitos Previos](#requisitos-previos)
2. [Guía para Nuevos Usuarios de GitHub](#guía-para-nuevos-usuarios-de-github)
3. [Pasos para Contribuir](#pasos-para-contribuir)
   - [Haciendo un Fork](#1-haciendo-un-fork-del-repositorio)
   - [Clonando el Repositorio](#2-clonando-el-repositorio)
   - [Creando una Nueva Rama](#3-creando-una-nueva-rama)
   - [Realizando Cambios en los Archivos .tex](#4-realizando-cambios-en-los-archivos-tex)
   - [Realizando Commit y Push](#5-realizando-commit-y-push)
   - [Abriendo un Pull Request](#6-abriendo-un-pull-request)
4. [Buenas Prácticas](#buenas-prácticas)
5. [Código de Conducta](#código-de-conducta)
6. [¿Necesitas Ayuda?](#necesitas-ayuda)

---

## Requisitos Previos

Antes de comenzar, asegúrate de tener lo siguiente:
- Una cuenta en GitHub.
- Git instalado en tu computadora.
- Un editor de texto o IDE (por ejemplo, Visual Studio Code, Notepad++, etc.).
- Conocimientos básicos sobre el uso de Git y GitHub.

---

## Guía para Nuevos Usuarios de GitHub

Si eres nuevo en GitHub, estos consejos rápidos te ayudarán:
- **Explora el repositorio:** Revisa la estructura y familiarízate con los archivos, especialmente en el directorio `src/`.
- **Trabaja en local:** Clona el repositorio para modificar únicamente los archivos fuente en LaTeX.
- **Consulta recursos:** Visita la [documentación oficial](https://docs.github.com/) para resolver dudas.

---

## Pasos para Contribuir

### 1. Haciendo un Fork del Repositorio

- Ve a la página principal del repositorio.
- Haz clic en el botón **Fork** (ubicado en la esquina superior derecha) para crear una copia personal.

### 2. Clonando el Repositorio

Desde tu cuenta forkeada, clona el repositorio a tu máquina local:
```bash
git clone https://github.com/tu-usuario/topologia-de-superficies.git
```
_Reemplaza "tu-usuario" por tu nombre de usuario de GitHub._

### 3. Creando una Nueva Rama

Es importante crear una rama específica para tus cambios:
```bash
cd topologia-de-superficies
git checkout -b nombre-de-tu-rama
```
_Reemplaza "nombre-de-tu-rama" por un nombre descriptivo relacionado con tu cambio._

### 4. Realizando Cambios en los Archivos .tex

- **Modifica únicamente los archivos .tex:** Los cambios deben realizarse en los archivos ubicados en `src/` (como `main.tex`, `tema4.tex`, etc.). Los puedes compilar en local para ver el resultado de forma más clara.
- **No es necesario subir el PDF modificado:** El PDF se genera automáticamente mediante el flujo de trabajo definido en `.github/workflows/compilar-pdf.yml`.
- Comprueba que el documento compila correctamente en tu entorno local.

### 5. Realizando Commit y Push

Una vez realizados y verificados tus cambios:
```bash
git add .
git commit -m "Descripción breve de los cambios realizados en los archivos .tex"
git push origin nombre-de-tu-rama
```

### 6. Abriendo un Pull Request

- Ingresa a tu repositorio forkeado en GitHub.
- Haz clic en **Compare & pull request**.
- Rellena la información solicitada describiendo los cambios realizados.
- Envía el pull request para revisión.

---

## Buenas Prácticas

- **Commits Claros:** Realiza commits pequeños con mensajes descriptivos.
- **Modifica solo lo necesario:** Asegúrate de trabajar únicamente con los archivos fuente (.tex).  
- **Verifica la compilación:** Antes de enviar un pull request, compila el documento para confirmar que no hay errores.
- **Comunicación:** Responde a comentarios y sugerencias en tu pull request para una mejor integración.

---

## Código de Conducta

El proyecto sigue un [Código de Conducta](https://opensource.guide/code-of-conduct/). Se espera que todos los colaboradores mantengan un ambiente respetuoso y colaborativo.

---

## ¿Necesitas Ayuda?

Si tienes preguntas sobre el proceso (Git, GitHub o LaTeX):
- Consulta la [documentación oficial de GitHub](https://docs.github.com/).
- Abre un Issue en el repositorio.
- Contacta a los mantenedores para soporte.

---

¡Gracias por contribuir y ayudar a mejorar los apuntes de Topología de Superficies!

