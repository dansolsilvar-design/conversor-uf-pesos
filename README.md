# Conversor Pesos ↔ UF

Aplicación web para convertir montos entre pesos chilenos (CLP) y UF (Unidad de Fomento), en ambos sentidos.

## Uso

1. Abrí el archivo `conversor-uf-pesos.html` con doble clic, o desde el navegador (`Archivo > Abrir`).
2. Al cargar, la app intenta obtener automáticamente el valor de la UF del día desde [mindicador.cl](https://mindicador.cl).
   - Si tenés conexión a internet, el campo **"Valor UF hoy (CLP)"** se completa solo.
   - Podés forzar una actualización con el botón **⟳**.
   - Si no hay internet o falla la consulta, podés escribir el valor de la UF manualmente en ese mismo campo.
3. Escribí un monto en **Pesos** para ver su equivalente en **UF**, o escribí un monto en **UF** para ver su equivalente en **Pesos**. El cálculo se actualiza automáticamente mientras escribís.

No requiere instalación, servidor ni conexión a internet para funcionar (salvo para actualizar el valor de la UF automáticamente).

## Archivos

- `conversor-uf-pesos.html` — aplicación completa (HTML, CSS y JavaScript en un solo archivo).
