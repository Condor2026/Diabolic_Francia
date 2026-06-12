# 📋 CHANGELOG - AIDE FRANCE

## [1.0.0] - 2026-06-12

### ✨ AÑADIDO / AJOUTÉ / AGGIUNTO

| Característica | Descripción |
|----------------|-------------|
| **Auto-discovery system** | Busca URLs alternativas automáticamente cuando una fuente falla |
| **150+ User-Agents** | Rotación completa de navegadores para evitar bloqueos |
| **Gráficos interactivos** | Dashboard con Chart.js (barras, dona, línea, ranking) |
| **🌍 3 idiomas** | Español, Français, Italiano completos en toda la interfaz |
| **📄 Paginación real** | 12 avisos por página con botones ◀ ▶ en el dashboard web |
| **Exportación HTML** | Reportes profesionales con gráficos integrados |
| **Cache de URLs** | Guarda URLs encontradas para futuras ejecuciones |
| **Estadísticas avanzadas** | Keywords más frecuentes, densidad por departamento, tendencia |
| **Fuentes francesas** | 30+ médias (Le Monde, Figaro, Libération, 20 Minutes, France Info, asociaciones) |
| **Tipos de ayuda** | 9 categorías: logement, emploi, alimentation, santé, précarité, droits, urgence, solidarité |

### 🔧 MEJORADO / AMÉLIORÉ / MIGLIORATO

| Mejora | Descripción |
|--------|-------------|
| **Anti-bloqueo** | Delays aleatorios entre 0.8-2.0 segundos para simular comportamiento humano |
| **Verificación de fuentes** | Sistema de reintentos (3 intentos por fuente) antes de marcar como inactiva |
| **Parsing HTML** | Múltiples selectores para adaptarse a diferentes estructuras de periódicos |
| **Memoria optimizada** | Procesamiento eficiente para grandes volúmenes de datos |
| **Interfaz terminal** | Colores profesionales, barras de progreso, emojis visuales |

### 🐛 CORREGIDO / CORRIGÉ / CORRETTO

| Problema | Solución |
|----------|----------|
| **URLs rotas (404)** | Auto-discovery system encuentra automáticamente las URLs correctas |
| **Errores 403 (Forbidden)** | Headers rotativos con 150+ User-Agents diferentes |
| **Duplicados en base de datos** | Sistema de limpieza (opción 11) y detección por hash MD5 |
| **Fuentes caídas** | Verificación previa con opción 8 antes de cada búsqueda |
| **Problemas de codificación** | UTF-8 completo para caracteres franceses (é, è, ê, ë, ç, à, ù) |

---

## [0.9.0] - 2026-06-10 (Beta)

### ✨ AÑADIDO

| Característica | Descripción |
|----------------|-------------|
| **Primera versión funcional** | Scraping básico de periódicos franceses |
| **Palabras clave sociales** | Detección de aide sociale, logement, chômage, précarité |
| **Menú en terminal** | 12 comandos con colores |
| **Persistencia de datos** | Almacenamiento en JSON |
| **Exportación JSON/CSV** | Formato compatible con análisis externos |

### 🔧 MEJORADO

| Mejora | Descripción |
|--------|-------------|
| **Estructura de código** | Organización en clases (GestorDatos, VerificadorFuentes, ExtractorNoticias) |

### 🐛 CORREGIDO

| Problema | Solución |
|----------|----------|
| **Errores de conexión** | Timeout aumentado a 25 segundos |

---

## [0.5.0] - 2026-06-05 (Alpha)

### ✨ AÑADIDO

| Característica | Descripción |
|----------------|-------------|
| **Lanzamiento inicial** | Prueba de concepto con 5 fuentes |
| **Detección básica** | Palabras clave limitadas a logement et chômage |
| **Terminal simple** | Sin colores ni barra de progreso |

---

## 📊 ESTADÍSTICAS DE VERSIÓN

| Métrica | v0.5.0 (Alpha) | v0.9.0 (Beta) | v1.0.0 (Stable) |
|---------|----------------|---------------|-----------------|
| **Líneas de código** | 500 | 1500 | 2000+ |
| **Fuentes soportadas** | 5 | 20 | 30+ |
| **Idiomas** | 1 (FR) | 1 (FR) | 3 (ES/FR/IT) |
| **User-Agents** | 10 | 50 | 150+ |
| **Gráficos** | ❌ | ❌ | ✅ 4 tipos |
| **Paginación** | ❌ | ❌ | ✅ Real |
| **Auto-discovery** | ❌ | ❌ | ✅ |
| **Exportación HTML** | ❌ | ❌ | ✅ |

---

## 🗓️ PRÓXIMAS VERSIONES (Roadmap)

### [1.1.0] - Planificado

- [ ] Notificaciones por email de nuevas ayudas
- [ ] API REST completa para integración externa
- [ ] Modo offline con datos cacheados
- [ ] Más fuentes regionales (Corse, Outre-mer)
- [ ] Filtros avanzados por type d'aide

### [1.2.0] - Planificado

- [ ] Mobile app (React Native)
- [ ] Alertas en tiempo real (WebSockets)
- [ ] Intégration avec des API gouvernementales (data.gouv.fr)
- [ ] Carte interactive des aides par département

---

## 🙏 CRÉDITS / CRÉDITOS / CREDITI

- **Développement**: Condor2026 / SpectrumSecurity
- **Inspiration**: KELTIC KRAKEN (Irlande)
- **Testing**: Communauté open source
- **Données**: Médias français et associations

---

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-red?style=flat-square">
  <img src="https://img.shields.io/badge/release-2026--06--12-blue?style=flat-square">
  <img src="https://img.shields.io/badge/status-stable-brightgreen?style=flat-square">
</p>
