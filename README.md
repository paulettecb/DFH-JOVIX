# DFH JOVIX · Tema de Shopify

Tema de la tienda de **DFH JOVIX** (producto estrella: **Jauiri**).
Está basado en **Dawn**, el tema gratis de Shopify (versión 16.1.1), con el mismo design system que la página del
Dr. Jorge Cambrón ("Tricología Cambrón"):

- **Colores:** el marino `#1F4E6B` es el único color de los botones y el dorado `#C89331` solo se usa en detalles.
  Los fondos son crema, arena, blanco y marino.
- **Letras:** Bricolage Grotesque en títulos e Inter en texto.

## Cómo está conectado

La tienda de Shopify jala este repositorio desde la rama `main`
(**Tienda online → Temas → Agregar tema → Conectar desde GitHub**). Cada cambio que se sube aquí se actualiza
solo en Shopify, y los cambios que se hacen en el editor de Shopify regresan a este repositorio como commits.

## Qué cambia respecto a Dawn

| Archivo | Cambio |
|---|---|
| `assets/jovix.css` | Tipografía de títulos, eyebrow con raya dorada y detalles de la marca. |
| `layout/theme.liquid` | Carga Bricolage Grotesque y `jovix.css`. |
| `config/settings_data.json` | Colores, tipografía y esquinas redondeadas del design system. |
| `templates/index.json` | Inicio: Jauiri destacado, beneficios, por qué Jauiri, fórmula, respaldo médico, modo de uso, preguntas frecuentes y leyenda. |
| `templates/product.json` | Ficha del producto con la fórmula, las preguntas frecuentes y la leyenda. |
| `sections/header-group.json` | Barra de anuncio: "Formulado por el Dr. Jorge Cambrón, tricólogo". |

## Pendientes (se hacen en Shopify)

- Subir el logo: **Personalizar → Encabezado → Logo**.
- Precio de Jauiri, inventario y cápsulas al día.
- Número de aviso de publicidad COFEPRIS.
- Nombre de la tienda: **Configuración → Detalles de la tienda**.
