# Ficha para la Chrome Web Store: Gestor de Pestañas Inteligente

Textos listos para copiar y pegar en el panel de desarrollador de la Chrome Web Store
(https://chrome.google.com/webstore/devconsole).

## Archivos de esta carpeta

| Archivo | Dónde se sube |
|---|---|
| `extension-para-chrome-web-store.zip` | **Paquete** → "Subir nuevo paquete" (lleva `manifest.json` en la raíz, como pide la tienda) |
| `icono-128x128.png` | Ficha → Icono de la tienda |
| `captura-1280x800.png` | Ficha → Capturas de pantalla |
| `promo-440x280.png` | Ficha → Recuadro promocional pequeño |

---

## 1. Ficha de Play Store

**Nombre** (se toma del manifest): Gestor de Pestañas Inteligente

**Resumen** (se toma del manifest): Agrupa tus pestañas por tema o dominio, cierra duplicadas e inactivas y guarda sesiones con nombre.

**Categoría:** Productividad → Herramientas

**Idioma:** Español

**Descripción** (copiar todo el bloque):

```
¿Demasiadas pestañas abiertas? Gestor de Pestañas Inteligente pone orden en tu navegador con un clic.

FUNCIONES
• Agrupar por tema: crea grupos de colores automáticamente (Desarrollo, Trabajo, Redes, Video y música, Compras, Noticias y Otros).
• Agrupar por dominio: junta las pestañas del mismo sitio web.
• Desagrupar todo con un clic.
• Cerrar duplicadas: cierra las pestañas repetidas y conserva la que estás viendo.
• Cerrar inactivas: cierra las pestañas que llevan 1, 3, 7 o 14 días sin usarse, guardándolas antes como sesión para que no pierdas nada.
• Buscador: encuentra cualquier pestaña por título o dirección y salta a ella con un clic.
• Sesiones con nombre: guarda todas las pestañas de una ventana (por ejemplo "Trabajo") y vuelve a abrirlas cuando quieras.
• Limpieza automática opcional de pestañas inactivas.
• Contador de pestañas en el icono.
• Atajos de teclado: Alt+Shift+G agrupa por tema y Alt+Shift+D cierra duplicadas.

PRIVACIDAD
Todo se guarda en tu navegador. La extensión no tiene servidor, no recopila datos y no lee el contenido de las páginas, solo la lista de pestañas.
```

**Sitio web oficial:** https://github.com/juanabraham8091/gestor-pestanas

**URL de asistencia:** https://github.com/juanabraham8091/gestor-pestanas/issues

---

## 2. Prácticas de privacidad

**Descripción del propósito único:**
> Organizar las pestañas abiertas del navegador: agruparlas, buscarlas, cerrar las duplicadas o inactivas y guardarlas como sesiones con nombre.

**Justificación de permisos** (un cuadro por permiso):

**tabs**
> Leer el título y la dirección de las pestañas abiertas para agruparlas por tema o dominio, detectar duplicadas e inactivas, mostrarlas en el buscador y guardarlas como sesiones.

**tabGroups**
> Crear, nombrar y colorear los grupos de pestañas, y desagruparlas.

**storage**
> Guardar en el navegador las sesiones de pestañas y los ajustes del usuario.

**alarms**
> Ejecutar cada hora la limpieza automática de pestañas inactivas, solo si el usuario la activa en Ajustes.

**¿Usas código remoto?** → **No, no uso código remoto.**

**Uso de datos.** Marca estas casillas:
- ☑️ Historial web (títulos y direcciones de las pestañas abiertas, guardados solo en el navegador para las sesiones)

Todo se guarda solo en el navegador del usuario (chrome.storage.local). No hay servidor propio y no se envía, vende ni comparte ningún dato.

Y marca las tres certificaciones:
- ☑️ No vendo ni transfiero datos de usuarios a terceros, fuera de los casos de uso aprobados.
- ☑️ No uso ni transfiero datos de usuarios para fines no relacionados con el propósito único del elemento.
- ☑️ No uso ni transfiero datos de usuarios para determinar la solvencia o con fines de préstamo.

**URL de la política de privacidad:**
https://github.com/juanabraham8091/gestor-pestanas/blob/main/PRIVACIDAD.md

---

## 3. Distribución

- **Visibilidad:** Pública (aparece en búsquedas) u Oculta (solo con el enlace).
- **Regiones:** Todas.
- **Precio:** Gratis.
