## 🌐 Español  
# 🕵️ Análisis Forense de Disco Duro

En este proyecto realizamos una recuperación forense en un disco duro externo que fue detectado en estado RAW por Windows. El objetivo fue recuperar archivos críticos e investigar el estado del sistema de archivos utilizando herramientas forenses especializadas como TestDisk, PhotoRec y Autopsy.

A lo largo del proceso se aplicaron técnicas de análisis, recuperación y documentación de evidencias, permitiendo reconstruir parte de los datos y verificar la integridad lógica del disco.

## 🧰 Herramientas utilizadas  
- TestDisk  
- PhotoRec  
- Autopsy  
- Kali Linux  
- Windows 10 (Entorno anfitrión)  

## 🔍 Metodología aplicada  
1. Identificación de la unidad RAW desde el sistema anfitrión (Administrador de discos)  
2. Ejecución de TestDisk para análisis de particiones y estructura del disco  
3. Ejecución de PhotoRec para recuperación de archivos (priorizando imágenes, documentos y hojas de cálculo)  
4. Análisis posterior con Autopsy para correlación de evidencias y reconstrucción de eventos  
5. Organización de archivos recuperados, validación manual y extracción de metadatos  
6. Documentación técnica, conclusiones y recomendaciones de backup  

## 📄 Informe final  
El informe contiene capturas, análisis de sectores, registros de recuperación, metadatos de archivos rescatados y sugerencias para prevenir pérdida de información en medios extraíbles.

---

<details>
<summary><h2>🌍 English</h2></summary>

# 🕵️ Hard Drive Forensic Analysis

This project simulates a real-world forensic recovery scenario of an external drive detected as RAW by Windows. The goal was to recover critical files and investigate the logical file system state using specialized forensic tools.

Key steps included scanning with TestDisk, file carving with PhotoRec, and timeline reconstruction with Autopsy. Recovered files were validated and correlated for potential digital evidence.

## 🧰 Tools  
- TestDisk  
- PhotoRec  
- Autopsy  
- Kali Linux  
- Windows 10 (host system)  

## 🔍 Methodology  
1. Identify RAW disk via Disk Management  
2. Run TestDisk to analyze partition structure  
3. Use PhotoRec to recover prioritized files (e.g., .jpg, .png, .xls, .csv)  
4. Load recovered data into Autopsy for evidence analysis  
5. Extract metadata and organize findings  
6. Final report and mitigation recommendations  

## 📄 Final Report  
Includes screenshots, file recovery logs, Autopsy findings, and digital preservation techniques.

</details>

---

## 🧭 Flujo Técnico del Proyecto

| Paso | Acción                                                         | Herramienta      | Resultado esperado                                       |
|------|----------------------------------------------------------------|------------------|----------------------------------------------------------|
| 1️⃣   | Verificar estado del disco RAW desde Windows                  | Disk Management  | Confirmar estado RAW y capacidad del disco               |
| 2️⃣   | Ejecutar TestDisk y analizar particiones                      | TestDisk         | Ver posibles particiones perdidas y estructuras FAT/NTFS |
| 3️⃣   | Ejecutar PhotoRec para recuperación selectiva                 | PhotoRec         | Obtener archivos de tipo imagen, Excel y texto plano     |
| 4️⃣   | Cargar datos recuperados en Autopsy                           | Autopsy          | Analizar metadatos, timeline y contenido de archivos     |
| 5️⃣   | Organizar archivos por tipo y relevancia                      | Windows Explorer | Clasificación preliminar de evidencia útil               |
| 6️⃣   | Documentar proceso y generar informe                          | Markdown         | Documento técnico forense con hallazgos y sugerencias    |

---