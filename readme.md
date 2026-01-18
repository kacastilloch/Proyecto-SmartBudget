# Resumen del Proyecto SmartBudget

## Estructura de Carpetas

El proyecto está organizado en una estructura de carpetas clara y lógica, facilitando la gestión del código y los recursos:

```
assets/
    css/                # Contiene los estilos CSS compilados
        main.css       # Archivo principal de estilos
    img/               # Carpeta para imágenes
    sass/              # Carpeta para archivos SASS
        main.scss      # Archivo principal que importa otros archivos SASS
        base/          # Contiene estilos base como reset y tipografía
        components/    # Componentes reutilizables como botones, tarjetas, etc.
        layout/        # Estilos de layout como encabezados y pies de página
        pages/         # Estilos específicos de páginas
        utils/         # Utilidades como variables y mixins
```

## Resumen del Código

El código está dividido en varios archivos SASS que se importan en `main.scss`, lo que permite una fácil modularidad y mantenimiento. 

- **Variables y Mixins**: Se definen colores, tipografías y mixins para reutilizar estilos en todo el proyecto.
- **Base**: Incluye reset de estilos y tipografía base para asegurar una apariencia consistente.
- **Layout**: Contiene estilos para la estructura general del sitio, como encabezados y pies de página.
- **Componentes**: Define estilos para elementos reutilizables como botones, tarjetas y tablas.
- **Páginas**: Estilos específicos para las diferentes páginas del proyecto.

Este enfoque modular permite un desarrollo más eficiente y un mantenimiento más sencillo del código.  