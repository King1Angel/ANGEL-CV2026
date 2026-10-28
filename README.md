# ANGEL-CV2026

Repositorio del **Curriculum Vitae Web & Portfolio Técnico (Edición 2026)** del **Ing. Angel Peña**.

Diseñado bajo una estética **Glassmorphism Warm Executive** (paleta de ocre, ámbar, terracota y espresso/obsidiana cálido), optimizado para lectura ejecutiva de reclutadores, interacción dinámica en pantalla e impresión limpia a PDF.

---

## 🎨 Arquitectura y Estética Glass Dashboard
- **Diseño tipo Dashboard:** Barra lateral izquierda estática/sticky con foto de perfil, selector de navegación, datos de contacto rápido y controles de idioma/tema.
- **Vistas Dinámicas por Pestaña (SPA sin recarga):**
  1. **Presentación (Vista inicial por defecto):** Declaración ejecutiva de enfoque, bento grid de métricas clave y resumen de especialización para reclutadores.
  2. **Experiencia Laboral:** Acordeones interactivos colapsados por defecto para fácil escaneo visual, con expansión fluida de responsabilidades, logros técnicos y tecnologías, además de botón *Expandir / Contraer todos*.
  3. **Portafolio y Desarrollo:** Fichas de proyectos destacados con visualizador modal Lightbox HD para capturas de n8n y enlaces directos a repositorios y demostraciones.
  4. **Habilidades y Tecnologías:** Matriz de competencias en Redes & Cisco, Desarrollo Web y DevOps/IA.
  5. **Educación y Certificaciones:** Grados académicos y certificaciones oficiales Cisco con accesos a credenciales y enlaces PDF/Drive.
- **Glassmorphism System:** Efectos multicapa de `backdrop-filter: blur(20px)`, bordes translúcidos con acentos ámbar, brillos de luz ambiental y compatibilidad total con Modo Claro Cálido y Modo Oscuro Obsidiana.
- **Internacionalización (i18n):** Cambio instantáneo entre Español (🇲🇽 ES) e Inglés (🇺🇸 EN) en toda la interfaz y navegación.

---

## 📁 Archivos Clave
- `index.html`: **Versión V2 — Dashboard Glass interactivo** (versión recomendada y principal).
- `index.original.html`: **Versión V1 — Landing page clásica continua** (respaldo original preservado íntegramente con enlace bidireccional).
- `assets/profile.jpg`: Fotografía estática de perfil.
- `assets/certs/`: Certificados oficiales y capturas de Cisco y Linux NDG.
- `assets/n8n/`: Capturas y diagramas en HD del ecosistema de IA autónoma en n8n.

---

## 🚀 Cómo visualizarlo localmente
Puedes abrir directamente en tu navegador cualquiera de los dos archivos:
```bash
# Vista Dashboard Glass (V2):
start index.html

# Vista Clásica Original (V1):
start index.original.html
```
O servir localmente con cualquier servidor ligero:
```bash
python -m http.server 8000
```
Y abrir `http://localhost:8000` en tu navegador.
