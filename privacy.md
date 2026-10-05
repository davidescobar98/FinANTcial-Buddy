---
title: Política de privacidad de Antdy
---

# Política de privacidad de Antdy

Última actualización: 5 de octubre de 2026

Antdy (también llamada FinANTcial Buddy o Hormiga) es una aplicación de escritorio para gestionar tus finanzas
personales. Funciona **solo en tu ordenador**: no tiene servidores propios, no tiene cuentas de usuario y no recoge
estadísticas de uso.

## Qué datos usa

- **Tus extractos y movimientos bancarios**, que importas tú. Se guardan en una base de datos local en tu ordenador.
- **Tu correo de Gmail, solo si lo conectas** (opcional). Antdy usa la API de Gmail con estos permisos:
  - `gmail.readonly`: buscar y leer los correos de tu banco y descargar los extractos adjuntos. Antdy nunca borra ni
    modifica tus correos ni tu configuración.
  - `gmail.send` (solo si activas los avisos por correo): enviarte a ti mismo tus propios avisos. Nunca envía correos a
    otras personas.

## Dónde se guardan

Todo se guarda en tu ordenador. Los tokens de acceso a Google se guardan cifrados con el almacén seguro del sistema
operativo. Antdy nunca ve tu contraseña de Google: la autorización se hace en tu navegador con OAuth.

## Con quién se comparte

Con nadie. Antdy no vende, no transfiere y no envía a terceros tus datos ni los datos obtenidos de las API de Google.
Las únicas conexiones a internet que hace son:

- A Google (Gmail), si la conectas, para leer tus extractos.
- A Yahoo Finance, si usas el seguimiento de inversiones, para consultar cotizaciones públicas (no se envía ningún dato
  tuyo).
- A GitHub, para descargar actualizaciones de la app.

El uso que hace Antdy de la información recibida de las API de Google cumple la
[Política de datos de usuario de los servicios de API de Google](https://developers.google.com/terms/api-services-user-data-policy),
incluidos los requisitos de uso limitado.

## Cómo borrar tus datos

- En Antdy → Ajustes → Cuenta de correo → **Desconectar**: revoca el acceso en Google y borra los tokens locales.
- También puedes retirar el acceso en <https://myaccount.google.com/permissions>.
- Desinstalar Antdy y borrar su carpeta de datos elimina todo lo demás.

## Contacto

Escribe una incidencia en <https://github.com/davidescobar98/FinANTcial-Buddy/issues>.
