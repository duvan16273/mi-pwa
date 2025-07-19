# 🚀 PWA Educativa - Starter Kit

Un proyecto educativo minimalista que combina **Next.js App Router** con **FastAPI** para enseñar el desarrollo de Progressive Web Applications (PWA) sin necesidad de conexión a internet.

## 📋 Requisitos Previos

- **Visual Studio Code** (o cualquier editor de código)
- **Python 3.8+** (para el backend de FastAPI)
- **Node.js 18+** (para el frontend de Next.js)

> ⚠️ **Nota importante**: Este proyecto incluye todas las dependencias pre-instaladas para funcionar sin conexión a internet. No necesitas ejecutar `npm install` o `pip install`.

## 🏃‍♂️ Inicio Rápido

### Opción 1: Clonar el Repositorio
```bash
git clone [URL_DEL_REPOSITORIO]
cd pwa-starter-kit
```

### Opción 2: Descargar el ZIP
1. Descarga el archivo `pwa-starter-kit.zip`
2. Descomprime el archivo en tu carpeta de proyectos
3. Abre la carpeta en Visual Studio Code

## 🚀 Ejecutar el Proyecto

### En Windows:
```bash
# Iniciar todo (backend + frontend)
npm run start:all:win

# O iniciar por separado:
npm run start:backend:venv:win  # Backend en http://localhost:8000
npm run dev                     # Frontend en http://localhost:3000
```

### En Linux/macOS:
```bash
# Iniciar todo (backend + frontend)
npm run start:all

# O iniciar por separado:
      # Backend en http://localhost:8000
npm run dev                     # Frontend en http://localhost:3000
```

## 📱 Vnpm run start:backend:venverificar la PWA

1. Abre tu navegador en `http://localhost:3000`
2. Abre las herramientas de desarrollo (F12)
3. Ve a la pestaña "Application" → "Manifest"
4. Deberías ver los detalles de la PWA configurada
5. Para instalar la PWA localmente, busca el icono de instalación en la barra de direcciones

## 🔗 Endpoints Disponibles

- **Frontend**: `http://localhost:3000`
- **Backend API**: `http://localhost:8000`
- **Mensaje de prueba**: `http://localhost:8000/api/message`

## 🎯 Próximos Pasos

Una vez que el proyecto esté funcionando, puedes:

1. **Personalizar la interfaz** → Ver `docs/ACTIVIDAD_PERSONALIZACION.md`
2. **Integrar frontend con backend** → Ver `docs/ACTIVIDAD_INTEGRACION.md`
3. **Explorar la estructura** → Ver `docs/ESTRUCTURA_PROYECTO.md`

## 🆘 Solución de Problemas

### Error: "Python no encontrado"
- Asegúrate de tener Python instalado y en el PATH del sistema
- Verifica con: `python --version`

### Error: "Puerto ya en uso"
- Cierra otras aplicaciones que usen los puertos 3000 o 8000
- Alternativamente, modifica los puertos en los scripts

### Error: "No se puede ejecutar el script"
- En Windows: Ejecuta `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` en PowerShell
- En Linux/macOS: Asegúrate de tener permisos de ejecución con `chmod +x`

## 📚 Recursos Adicionales

- [Documentación de Next.js](https://nextjs.org/docs)
- [Documentación de FastAPI](https://fastapi.tiangolo.com/)
- [Guía de PWA en Next.js](https://nextjs.org/docs/app/building-your-application/deploying/static-exports)

---

**Desarrollado para estudiantes de 16 años en zonas rurales con conectividad limitada** 🌾

Este es un cambio de prueba para hacer un commit.
