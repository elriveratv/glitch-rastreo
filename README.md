# GlitchLab 🔍 Portal de Rastreo de Clientes
**Portal Web Público de Seguimiento de Equipos en Tiempo Real**

Aplicación web pública optimizada para clientes que permite consultar el estado de diagnóstico, bitácora técnica de reparación, fotografías de evidencia, cotizaciones y estatus de entrega en **GlitchLab**.

Diseñado para desplegarse en el subdominio oficial: **`https://rastreo.glitchlab.mx`**.

---

## 🚀 Características Principales

* **Búsqueda Sencilla y Rápida:** Los clientes pueden consultar su equipo ingresando los 10 dígitos de su teléfono celular o número de folio.
* **Línea de Tiempo en Vivo:** Visualización del progreso por etapas (Recibido, En Diagnóstico, En Reparación, Espera de Repuesto, Listo para Entrega, Entregado).
* **Telemetría y Diagnóstico Técnico:** Explicación clara de la falla y detalles de microelectrónica.
* **Galería de Fotos:** Fotografías de evidencia del estado inicial y piezas reemplazadas.
* **Contacto Directo:** Botón de contacto directo con el WhatsApp del taller (+52 311 339 6969) y enlaces a mapas (Google Maps y Waze).
* **100% Responsivo:** Adaptado ergonómicamente para celulares y tablets.
* **Integración Supabase:** Lee los datos de las órdenes directamente desde la base de datos de Supabase en tiempo real.

---

## 📂 Estructura de Archivos

```
glitchlab-rastreo/
├── index.html          # Portal de rastreo de clientes
├── rastreo.html        # Alias directo para compatibilidad de rutas
├── favicon.svg         # Icono oficial de GlitchLab
├── vercel.json         # Configuración de rutas limpias y rewrites para Vercel
├── .htaccess           # Configuración para servidores Apache/cPanel
├── .gitignore          # Filtro de archivos para Git
└── README.md           # Documentación del proyecto
```

---

## ⚡ Despliegue en Vercel (`rastreo.glitchlab.mx`)

1. Sube este repositorio a tu cuenta de **GitHub** como un repositorio nuevo (ej. `glitchlab-rastreo`).
2. Entra a tu cuenta en [vercel.com](https://vercel.com) y haz clic en **Add New Project**.
3. Importa el repositorio `glitchlab-rastreo`.
4. Deja la configuración por defecto y haz clic en **Deploy**.
5. Ve a **Settings > Domains** en Vercel y añade tu subdominio personalizado: `rastreo.glitchlab.mx`.
6. Configura el registro CNAME en tu proveedor de dominio (Cloudflare, GoDaddy, Hostinger, etc.):
   * **Nombre/Host:** `rastreo`
   * **Tipo:** `CNAME`
   * **Destino:** `cname.vercel-dns.com`

---

© 2026 GlitchLab. Todos los derechos reservados.
