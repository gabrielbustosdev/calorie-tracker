# Calorie Tracker - Seguidor de Calorías

Aplicación para registrar actividades físicas y alimenticias, realizando seguimiento de calorías consumidas y quemadas.

## 🚀 Demo
Puedes ver la aplicación en funcionamiento aquí: [Demo Calorie Tracker](https://phenomenal-truffle-2fdc16.netlify.app/)


## Características Principales
- Registro de actividades con nombre, categoría (comida/ejercicio) y calorías
- Cálculo en tiempo real de calorías netas
- Persistencia de datos en localStorage
- CRUD completo de actividades
- Validación de formularios
- Diseño responsive con Tailwind CSS

## 🛠 Tecnologías Utilizadas
- React 18 + Vite
- TypeScript
- Tailwind CSS (Estilos)
- Heroicons (Iconos)
- UUID (Generación de IDs)
- Context API + useReducer (Gestión de estado)

## 📦 Instalación

1. Clonar repositorio
```bash
git clone https://github.com/tu-usuario/calorie-tracker.git
```

2. Instalar dependencias
```bash
npm install
```

3. Ejecutar aplicación
```bash
npm run dev
```


## Gestión de Estado
La aplicación utiliza la combinación de **Context API** y **useReducer** para manejar el estado global:
- `ActivityContext`: Provee el estado a toda la aplicación
- `activityReducer`: Maneja las acciones para actualizar el estado
- Acciones disponibles: 
  - Guardar/Editar actividades
  - Eliminar actividades
  - Reiniciar aplicación
  - Activar actividad para edición
