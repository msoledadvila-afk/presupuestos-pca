# Presupuestos PCA™ · Talento Impulsa Consulting

Herramienta interna para armar los presupuestos de Talento Impulsa a partir de la hora rentable y de cada línea de servicio.

**Estado:** Producción · uso interno (acceso restringido con cuenta de Google)
**App:** [msoledadvila-afk.github.io/presupuestos-pca](https://msoledadvila-afk.github.io/presupuestos-pca/)

## Qué hace

- Cálculo de la hora rentable
- Presupuestos por cliente y línea de servicio, con ítems y resumen
- Listado de presupuestos guardados

## Stack

| Capa | Tecnología |
| --- | --- |
| Frontend | HTML + JS vanilla, archivo único |
| Datos | Firebase Firestore (Compat SDK), compartido con el Dashboard y el Hub PCA™ |
| Acceso | Firebase Auth con Google, limitado a cuentas autorizadas |
| Hosting | GitHub Pages |

## Seguridad

La `apiKey` de Firebase que aparece en el código es pública por diseño. La protección está en las Reglas de Firestore, que solo permiten cuentas autorizadas con email verificado, y en los dominios autorizados del proyecto.

## Licencia

© 2026 Talento Impulsa Consulting. Todos los derechos reservados. Código visible solo como referencia; no se autoriza su reutilización comercial.

---

**Talento Impulsa Consulting** · [talentoimpulsa.com.ar](https://talentoimpulsa.com.ar)
hola@talentoimpulsa.com.ar · presupuestos@talentoimpulsa.com.ar
