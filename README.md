# 🔄 GitHub Fork Manager

Una herramienta web para gestionar y sincronizar todos los forks del repositorio **bpm-co/BPMs**.

## 🌐 Acceso directo
**[👉 Abrir Fork Manager](https://bpm-co.github.io/BPMsForkManager/)**

## ✨ Características

- 📊 **Vista centralizada** de todos los forks
- 🔍 **Estado en tiempo real** - detecta automáticamente forks desactualizados
- ⚡ **Sincronización rápida** - individual o masiva
- 🎯 **Interfaz intuitiva** - diseño moderno y responsive
- 🔒 **Seguro** - usa tu token personal de GitHub

## 🚀 Cómo usar

1. **Obtén tu token de GitHub:**
   - Ve a [GitHub Settings → Developer settings → Personal access tokens](https://github.com/settings/tokens)
   - Crea un token con permisos `repo` y `workflow`

2. **Abre la herramienta:**
   - Visita: https://bpm-co.github.io/BPMsForkManager/
   - Ingresa tu token de GitHub
   - Click en "Cargar Forks"

3. **Gestiona tus forks:**
   - Ve el estado de cada fork
   - Sincroniza individualmente o en masa
   - Exporta reportes de debug

## 🎯 Estados de los forks

- **✅ Actualizado**: El fork está al día con el repositorio padre
- **❌ Desactualizado**: El fork tiene commits pendientes de sincronizar

## 🔧 Funcionalidades

### Sincronización
- **Individual**: Botón "Sincronizar" en cada fork desactualizado
- **Masiva**: Sincroniza todos los forks desactualizados de una vez
- **Conserva commits**: Mantiene los commits propios del fork durante la sincronización

### Información detallada
- Estado actual de sincronización
- Fecha de última actualización
- Enlaces directos al fork y comparación en GitHub
- Debug técnico para troubleshooting

## 🛠️ Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript vanilla
- **API**: GitHub REST API y GraphQL
- **Autenticación**: Personal Access Tokens
- **Hosting**: GitHub Pages

## 📋 Requisitos

- Token de GitHub con permisos `repo`
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet

## 🔒 Seguridad

- ✅ Tu token se mantiene local en tu navegador
- ✅ No se almacena información en servidores externos
- ✅ Todas las comunicaciones son directas con GitHub API
- ✅ Código fuente abierto y auditable

## 🐛 Reportar problemas

Si encuentras algún bug o tienes sugerencias:
1. Abre un [Issue](https://github.com/bpm-co/fork-manager/issues)
2. Incluye detalles del problema
3. Adjunta información de debug si es posible

## 📄 Licencia

MIT License - Libre para usar y modificar.

---

**Desarrollado para BPMco** 🚀