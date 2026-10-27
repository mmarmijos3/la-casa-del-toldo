# La Casa del Toldo — Sitio web en HTML5

Sitio web informativo de **Almacenes La Casa del Toldo** (Santo Domingo de los Tsáchilas, Ecuador), empresa dedicada a la importación, fabricación y distribución de productos para el hogar y prendas de vestir.

Proyecto del primer parcial de **Fundamentos de Sistemas Web** (NRC 32802, PAO 202651) — Universidad de las Fuerzas Armadas ESPE, sede Santo Domingo.

## Integrantes
- Manfred Armijos
- Kevin Párraga

## Alcance
- HTML5 semántico puro: sin hojas de estilo, sin atributos `style` y sin JavaScript.
- Validado con el W3C Markup Validation Service.

## Estructura
```
index.html       Página de inicio
nosotros.html    Quiénes somos, misión, visión, valores y sucursales
productos.html   Categorías (tabla) y productos destacados
galeria.html     Imágenes y video de TikTok (iframe)
contacto.html    Sucursales, mapas (iframe) y formulario
img/             Imágenes de la empresa
```

## Flujo de ramas
| Rama | Uso |
|---|---|
| `main` | Producción (versiones etiquetadas) |
| `test` | Pruebas y validación antes de producción |
| `develop` | Integración de funcionalidades |
| `feature/*` | Una rama por página o funcionalidad |

Cada `feature/*` se integra a `develop` mediante pull request; `develop` pasa a `test` y, tras validar, `test` pasa a `main`.

## Créditos
Información e imágenes: La Casa del Toldo (lacasadeltoldo.com.ec, TikTok @lacasadeltoldo.ec). Uso con fines académicos.
