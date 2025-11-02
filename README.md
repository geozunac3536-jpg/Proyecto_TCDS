# 🌑 TCDS — Paquete de presentación de la Teoría Cromodinámica Sincrónica TCDS
<p style="text-align:center;margin:0.5rem 0 1.25rem;">
  <a href="https://ko-fi.com/genarocarrasco" target="_blank" rel="noopener"
     style="display:inline-block;padding:.6rem 1rem;border:1px solid #2a2a2a;border-radius:10px;color:#eaeaea;text-decoration:none;">
     ☕ Apoyar el proyecto en Ko-fi
  </a>
</p>
Este repositorio publica el **núcleo trazable** del paradigma **TCDS** con página en **tema oscuro**, enlaces a PDFs en **pestaña nueva**, **huellas SHA-256**, metadatos **JSON-LD** y **Zenodo** listos.

## 📄 Documentos
- [La TCDS (núcleo teórico)](docs/La_TCDS.pdf){:target="_blank"}
- [Dossier de Auditoría](docs/Auditoria.pdf){:target="_blank"}
- [Estudio Q–ϕ–Σ (Energía)](docs/Energia.pdf){:target="_blank"}

## ✅ Trazabilidad
- `checksums/SHASUMS256.txt` — huellas **SHA-256** de todos los PDFs.
- `schema.jsonld` — metadatos `schema.org/Dataset` para indexación.
- `.zenodo.json` — metadatos de release para DOI en Zenodo.
- `robots.txt` y `sitemap.xml` — descubribilidad por crawlers.
- `.github/workflows/audit.yml` — verifica existencia y huellas en cada push.

## 🛠️ Cómo usar (GitHub Pages)
1. Sube todo el contenido a un repositorio público.
2. Activa GitHub Pages → Deploy from branch → raíz (`/`) o `/docs`.
3. Abre `index.html` (tema oscuro) y verifica que los PDFs abran en nueva pestaña.
4. Crea un release para activar depósito en Zenodo (si has enlazado GitHub↔Zenodo).

## 🔐 Licencias
- Ciencia y docs: [**CC BY-NC-SA 4.0**](`LICENSE`)
- Comercial/Hardware: [**TCDS Σ Open Lab License v1.1**](https://github.com/geozunac3536-jpg/TCDS-LICENCIAS)

© 2025 Proyecto TCDS · Genaro Carrasco Ozuna · [ORCID 0009-0005-6358-9910](https://orcid.org/0009-0005-6358-9910)
