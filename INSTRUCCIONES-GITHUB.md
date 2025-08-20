# Instrucciones para Subir el Repositorio a GitHub

## Pasos para crear el repositorio en GitHub:

### 1. Crear el repositorio en GitHub
1. Ve a [GitHub.com](https://github.com) e inicia sesión
2. Haz clic en el botón "+" en la esquina superior derecha
3. Selecciona "New repository"
4. Nombre del repositorio: `Seminario-El-Lado-Oscuro-de-la-Seguridad-de-la-Informacion`
5. Descripción: `Módulo 1: Ciberseguridad en el Entorno Educativo y Familiar`
6. Marca como **Público** (para que sea accesible)
7. **NO** marques "Initialize this repository with a README" (ya tenemos uno)
8. Haz clic en "Create repository"

### 2. Conectar el repositorio local con GitHub
Una vez creado el repositorio en GitHub, ejecuta estos comandos en la terminal desde el directorio del proyecto:

```bash
# Cambiar a la rama main (recomendado)
git branch -M main

# Agregar el repositorio remoto (reemplaza TU_USUARIO con tu nombre de usuario de GitHub)
git remote add origin https://github.com/TU_USUARIO/Seminario-El-Lado-Oscuro-de-la-Seguridad-de-la-Informacion.git

# Subir el código a GitHub
git push -u origin main
```

### 3. Verificar la subida
1. Actualiza la página de tu repositorio en GitHub
2. Deberías ver todos los archivos y carpetas
3. El README.md se mostrará automáticamente en la página principal

## Estructura del Repositorio

```
Seminario-El-Lado-Oscuro-de-la-Seguridad-de-la-Informacion/
├── README.md                           # Página principal del repositorio
├── LICENSE                             # Licencia MIT
├── INSTRUCCIONES-GITHUB.md            # Este archivo
├── imagenes/                          # Imágenes ilustrativas
│   ├── 1inh9UHJpXAc.jpeg             # Tríada CIA
│   ├── aqyRCph4gpyt.png              # Amenazas cibernéticas
│   ├── oTav6FCT5Mp1.jpg              # Protección de menores
│   └── ... (más imágenes)
├── modulos/                           # Contenido del seminario
│   ├── 01-fundamentos-ciberseguridad.md
│   ├── 02-grooming-redes-sociales.md
│   ├── 03-ciberseguridad-infantil.md
│   ├── 04-rol-del-docente.md
│   └── 05-simulacion-incidentes.md
└── recursos/                          # Recursos adicionales
    └── enlaces-utiles.md
```

## Características del Repositorio

✅ **Contenido completo** del Módulo 1 de Ciberseguridad  
✅ **Imágenes ilustrativas** intercaladas en cada sección  
✅ **Navegación fácil** entre módulos  
✅ **Referencias bibliográficas** incluidas  
✅ **Recursos adicionales** y enlaces útiles  
✅ **Licencia MIT** para uso educativo  

## Personalización

Puedes personalizar el repositorio:
- Cambiar el nombre del repositorio en GitHub
- Modificar la descripción
- Agregar más contenido a los módulos
- Incluir ejercicios prácticos
- Agregar más imágenes ilustrativas

## Uso del Repositorio

Este repositorio está diseñado para:
- Docentes universitarios
- Estudiantes de Gendarmería Nacional
- Profesionales de la ciberseguridad
- Cualquier persona interesada en aprender sobre ciberseguridad

---

**¡Tu repositorio está listo para ser compartido con la comunidad educativa!**

