# Guía para Contribuir a "Topología de Superficies"

¡Gracias por tu interés en contribuir a este proyecto de apuntes de Topología de Superficies! Tu ayuda es fundamental para mejorar y mantener actualizados nuestros documentos. En este archivo encontrarás toda la información necesaria para colaborar, desde los primeros pasos para quienes son nuevos en GitHub, hasta indicaciones más detalladas para usuarios avanzados.

---

## Tabla de Contenidos

1. [Requisitos Previos](#requisitos-previos)
2. [Guía para Nuevos Usuarios de GitHub](#guía-para-nuevos-usuarios-de-github)
3. [Pasos para Contribuir](#pasos-para-contribuir)
   - [Haciendo un Fork](#1-haciendo-un-fork-del-repositorio)
   - [Clonando el Repositorio](#2-clonando-el-repositorio)
   - [Creando una Nueva Rama](#3-creando-una-nueva-rama)
   - [Realizando Cambios y Validando](#4-realizando-cambios-y-validando)
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
- Conocimientos básicos del funcionamiento de Git y GitHub.

---

## Guía para Nuevos Usuarios de GitHub

Si nunca has usado GitHub o no estás familiarizado con la plataforma, estos son unos consejos rápidos:
- **Explora el repositorio:** Navega por los archivos directamente en la web y haz clic en cada uno para ver su contenido.
- **Descarga una copia:** Si prefieres trabajar localmente, clona el repositorio o descárgalo como ZIP.
- **Contribuye:** Sigue esta guía para hacer tus aportes al proyecto.
- **Consulta recursos:** GitHub tiene [documentación oficial](https://docs.github.com/) y una comunidad activa que puede ayudarte a resolver dudas.

---

## Pasos para Contribuir

### 1. Haciendo un Fork del Repositorio

Un fork es una copia del repositorio alojada en tu cuenta de GitHub. Esto te permite experimentar y realizar cambios sin afectar el repositorio original.

- Ve a la página principal del repositorio.
- Presiona el botón **Fork** en la esquina superior derecha para crear una copia en tu cuenta.

### 2. Clonando el Repositorio

Clona tu repositorio forkeado a tu máquina local ejecutando:
```bash
git clone https://github.com/tu-usuario/topologia-de-superficies.git
```
_Reemplaza "tu-usuario" por tu nombre de usuario de GitHub._

### 3. Creando una Nueva Rama

Es una buena práctica crear una nueva rama para cada cambio o mejora.
```bash
cd topologia-de-superficies
git checkout -b nombre-de-tu-rama
```
_Reemplaza "nombre-de-tu-rama" por un nombre descriptivo del cambio que realizarás._

### 4. Realizando Cambios y Validando

- Abre los archivos en tu editor de texto o IDE y realiza las modificaciones necesarias.
- En particular, si vas a modificar documentos técnicos (como `main.tex`), asegúrate de que el contenido compila sin errores.
- Guarda los cambios realizados y revisa que todo funcione correctamente en tu entorno local.

### 5. Realizando Commit y Push

Una vez satisfecho con los cambios, agrégalos y confírmalos:
```bash
git add .
git commit -m "Descripción de los cambios realizados"
```
Después, sube la rama actualizada a GitHub:
```bash
git push origin nombre-de-tu-rama
```

### 6. Abriendo un Pull Request

Para integrar tus cambios en el repositorio principal:
- Accede a tu repositorio forkeado en GitHub.
- Haz clic en **Compare & pull request**.
- Proporciona una descripción clara y detallada de los cambios realizados.
- Envía el pull request para que los mantenedores revisen tu contribución.

---

## Buenas Prácticas

- **Commits Claros:** Realiza commits pequeños y con mensajes descriptivos.
- **Revisión de Compilación:** Asegúrate de que los documentos (como `main.tex`) compilan correctamente.
- **Descripción Detallada:** Al abrir un pull request, incluye detalles sobre los cambios y, de ser necesario, referencia issues relacionados.
- **Colaboración Activa:** Responde a comentarios o peticiones de cambio en tu pull request para facilitar la integración.

---

## Código de Conducta

Este proyecto se rige por un [Código de Conducta](https://opensource.guide/code-of-conduct/). Se espera que todos los colaboradores mantengan un ambiente respetuoso y colaborativo. Por favor, revisa el código de conducta para asegurarte de que tus interacciones cumplen con estas normas.

---

## ¿Necesitas Ayuda?

Si tienes dudas sobre el proceso para contribuir o sobre el uso de Git y GitHub:
- Consulta la [documentación oficial de GitHub](https://docs.github.com/).
- Abre un Issue en el repositorio para recibir asistencia.
- Contacta a los mantenedores del proyecto.

---

¡Gracias por tu entusiasmo y por contribuir a los apuntes de Topología de Superficies!
