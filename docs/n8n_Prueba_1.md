# n8n_Prueba_1

## Descripción

Este flujo prueba la integración entre **n8n** y **Google Sheets**, escribiendo automáticamente datos en una hoja.

## Objetivo

Verificar que n8n está correctamente configurado y que puede interactuar con servicios externos mediante OAuth2.

## Componentes

- **Trigger:** Manual (botón en página web)
- **Nodos:** Set → Google Sheets
- **Acción:** Agregar fila con datos de prueba

## Archivos relacionados

- Página de prueba: [/n8n_Prueba_1/index.html](../n8n_Prueba_1/index.html)
- Exportación del flujo: [/workflows/n8n_Prueba_1.json](../workflows/n8n_Prueba_1.json)
- Capturas: [/assets/capturas/flujo_n8n.png](../assets/capturas/flujo_n8n.png)

## Resultado esperado

Cada vez que se presiona el botón del sitio web, se agrega una nueva fila en la hoja de cálculo vinculada, con los datos configurados en el flujo.


