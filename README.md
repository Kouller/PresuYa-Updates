# PresuYa Updates

Repositorio oficial de versiones y actualizaciones de **PresuYa para Android**.

PresuYa permite crear, organizar, guardar, importar y exportar presupuestos profesionales para trabajos de construcción, materiales y servicios.

## Versión disponible

- Versión: **1.0.1**
- Código interno: **3**
- Estado: **estable**
- Plataforma: **Android**

La APK más reciente está disponible en [Releases](https://github.com/Kouller/PresuYa-Updates/releases).

## Novedades de PresuYa 1.0.1

- Zoom con dos dedos en la vista previa.
- Acercamiento centrado en la zona observada.
- Desplazamiento natural de la hoja ampliada.
- Zoom de hasta 300%, además de los controles `+`, `−` y `Ajustar`.
- Fecha de creación visible en cada tarjeta de Mis presupuestos.
- Espacio protegido para que el botón Nuevo no cubra la última tarjeta.
- Pantalla Acerca de simplificada.

## Cómo funcionan las actualizaciones

La aplicación consulta el archivo [`version.json`](./version.json) y compara su `versionCode` con el código instalado. Cuando existe una versión superior, PresuYa muestra el aviso y permite descargar la nueva APK.

Una instalación antigua puede actualizar directamente a la versión más reciente; no necesita instalar todas las versiones intermedias.

## Regla de publicación

Cada Release contiene **una sola APK**. El archivo indicado por `version.json` es el único utilizado por el actualizador.

- Una corrección no distribuida puede sobrescribir la APK del Release actual.
- Si una versión ya fue instalada por usuarios, la siguiente corrección deberá aumentar `versionCode` y publicarse como una versión nueva, por ejemplo `1.0.2`.
- Antes de publicar se verifica que el hash del archivo local coincida con el APK de GitHub.

## Versiones publicadas

- **0.0.1 Beta:** versión inicial usada para probar el sistema de actualización.
- **1.0.0:** primera versión estable.
- **1.0.1:** gestos de zoom y mejoras en Mis presupuestos.

## Autor

Creado por **Brayan Vergaray Gutierrez**.

## Seguridad

Este repositorio contiene únicamente archivos públicos de distribución:

- APK de PresuYa.
- Manifiesto `version.json`.
- Notas e historial de versiones.

No contiene código fuente, contraseñas, datos de usuarios ni claves de firma.