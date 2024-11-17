# REST API SDK for PHP - Fork

Este repositorio es un fork del __PayPal PHP SDK__, que ha sido descontinuado. Esta versión particular corrige un bug específico presente en la versión original y busca ofrecer una solución temporal para los usuarios que todavía dependen de esta librería.

## Bug Corregido

- **Descripción del Bug**: En la version 1.6, no se valida bien un condicional _convertToArray del archivo PayPalModel, este bug es corregido en versiones superiores de la 1.x
- **Solución Implementada**: El bug fue corregido en la versión 1.6.5, pero esta versión no fue liberada en el repositorio oficial. La solución fue encontrada en [stack overflow](https://stackoverflow.com/questions/54087631/paypal-sizeof-parameter-must-be-an-array-or-an-object-that-implements-countab)

## Aviso Importante

> **Este software es una modificación no oficial del SDK de PHP de PayPal y no está respaldado ni mantenido por PayPal.** El código fuente original pertenece a PayPal.
