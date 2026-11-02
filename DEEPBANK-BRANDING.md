# Deepbank — Manual Maestro de Marca & Identidad Visual

> **Repositorio Oficial de Activos:** `Deepbank/brand-assets`  
> **Organización:** [github.com/deepbank](https://github.com/deepbank)  
> **Holding / Estudio:** Clavius

---

## 1. Visión y Posicionamiento

**Deepbank** es infraestructura financiera inteligente para el factoring y descuento determinístico de facturas en América Latina.

La plataforma conecta a los **Bancos y Factores Financieros** con sus clientes corporativos y proveedores mediante:
* Ingesta multiformato de comprobantes electrónicos (XML y PDF Comercial).
* Gestión multi-moneda (USD y CRC) en cupos y control de vencimientos.
* Motor determinístico de políticas de elegibilidad y SLA watchdog en tiempo real.
* Formalización de cesión tripartita con firma digital y auditoría inmutable de IP.
* Portales multi-tenant (Banco, Corporativo, Proveedor) con invitaciones tokenizadas.
* Registro de cuentas bancarias de desembolso (IBAN) y trazabilidad completa.

---

## 2. Paleta Cromática Institucional

| Nombre | Hex | RGB | Uso Principal |
| :--- | :--- | :--- | :--- |
| **Obsidiana Absoluta** | `#000000` | `0, 0, 0` | Fondo principal pure dark (`bg-black`), contraste de autoridad |
| **Blanco Puro** | `#FFFFFF` | `255, 255, 255` | Tipografía principal, botones primarios, contenedores en fondo oscuro |
| **Esmeralda Liquidez** | `#10B981` | `16, 185, 129` | Métricas financieras de liquidez, estados aprobados, acento de validación |
| **Gris Neutro / Muted** | `#737373` | `115, 115, 115` | Texto secundario, descripciones y subtítulos atenuados |
| **Borde Estructural** | `rgba(255,255,255,0.10)` | `border-white/10` | Líneas divisorias ultrafinas de 1px en tarjetas y modales |

---

## 3. Tipografía Oficial

* **Familia Principal:** **Google Sans** (o en fallback: `Inter`, `-apple-system`, `sans-serif`)
* **Regla Tipográfica Estricta:**
  * Uso de mayúsculas/minúsculas **naturales**. Prohibido el uso indiscriminado de `uppercase`.
  * Espaciado normal entre letras. Prohibido el tracking artificial agresivo (`tracking-wider`, `tracking-widest`).
  * Jerarquía clara mediante pesos: `Regular (400)`, `Medium (500)`, `SemiBold (600)`, `Bold (700)`.

---

## 4. Filosofía de Diseño (Pure Dark Estricto)

1. **Fondo Negro Absoluto:** Fondos 100% `#000000`. Cero fondos grisáceos en contenedores o secciones primarias.
2. **Estructura por Bordes Sutiles:** La elevación y agrupación se define con bordes de 1px (`border-white/10`) y sutiles contrastes, no con sombras difusas descontroladas.
3. **Cero Clutter de Badges:** Eliminación de pastillas y badges decorativos innecesarios en títulos y cabeceras.
4. **Botones Estandarizados:** Botón primario en blanco sólido con texto negro (`bg-white text-black font-semibold hover:bg-neutral-200`) y esquinas con radio `rounded-md`.

---

## 5. Catálogo de Logos y Activos

```
logos/deepbank/
├── deepbank-logo-dark.svg          # Isotipo sobre fondo oscuro (Caja blanca, glifo negro)
├── deepbank-logo-light.svg         # Isotipo sobre fondo claro (Caja negra, glifo blanco)
├── deepbank-glyph-white.svg        # Glifo aislado en blanco puro (Fondo transparente)
├── deepbank-glyph-black.svg        # Glifo aislado en negro obsidiana (Fondo transparente)
├── deepbank-glyph-emerald.svg      # Glifo aislado en esmeralda liquidez (Fondo transparente)
├── deepbank-horizontal-dark.svg    # Lockup horizontal con isotipo + texto "Deepbank" (Dark)
├── deepbank-horizontal-light.svg   # Lockup horizontal con isotipo + texto "Deepbank" (Light)
├── deepbank-logo-dark.png          # PNG 2500x2500 px alta definición (Dark)
├── deepbank-logo-light.png         # PNG 2500x2500 px alta definición (Light)
├── deepbank-glyph-white.png        # PNG 2500x2500 px glifo blanco transparente
├── deepbank-glyph-black.png        # PNG 2500x2500 px glifo negro transparente
└── icon.svg                        # Favicon e icono de aplicación
```

---

## 6. Matriz de Aplicación

| Entorno / Caso de Uso | Activo Recomendado | Formato |
| :--- | :--- | :--- |
| **Sitio Web Dark (Navbar / Header)** | `deepbank-logo-dark.svg` / `deepbank-horizontal-dark.svg` | SVG |
| **Dashboard / Portal de Clientes** | `deepbank-logo-dark.svg` (Dark) / `deepbank-logo-light.svg` (Light) | SVG |
| **Documentos PDF / Facturas / Contratos** | `deepbank-logo-light.svg` / `deepbank-glyph-black.svg` | SVG / PNG |
| **Favicon / Browser Tab** | `icon.svg` | SVG |
| **Presentaciones (Keynote / Pitch Decks)** | `deepbank-logo-dark.png` o `deepbank-horizontal-dark.svg` | PNG / SVG |
| **Redes Sociales (Avatar de Perfil)** | `deepbank-logo-dark.png` | PNG (2500x2500) |

---

## 7. Enlaces de Integración Directa (Raw URLs)

### CDN / Producción (jsDelivr)
```html
<!-- Isotipo Dark (Para fondos oscuros) -->
<img src="https://cdn.jsdelivr.net/gh/deepbank/brand-assets@main/logos/deepbank/deepbank-logo-dark.svg" alt="Deepbank Logo" width="32" height="32" />

<!-- Lockup Horizontal Completo -->
<img src="https://cdn.jsdelivr.net/gh/deepbank/brand-assets@main/logos/deepbank/deepbank-horizontal-dark.svg" alt="Deepbank" height="32" />
```

### GitHub Raw (Desarrollo / Prototipos)
```
https://raw.githubusercontent.com/deepbank/brand-assets/main/logos/deepbank/deepbank-logo-dark.svg
https://raw.githubusercontent.com/deepbank/brand-assets/main/logos/deepbank/deepbank-logo-light.svg
https://raw.githubusercontent.com/deepbank/brand-assets/main/logos/deepbank/deepbank-horizontal-dark.svg
https://raw.githubusercontent.com/deepbank/brand-assets/main/logos/deepbank/deepbank-logo-dark.png
```
