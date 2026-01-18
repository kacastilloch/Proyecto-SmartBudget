# Descripción del Proyecto

**SmartBudget** es una aplicación web diseñada para la gestión visual de finanzas personales. Su objetivo es ayudar a los usuarios a visualizar rápidamente su salud financiera (ingresos, gastos y ahorros) mediante una interfaz limpia, intuitiva y responsive.

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

### ✨ Características Clave
1.  **Variables Globales:** Se definieron variables como `$color-menu` (#2B222C) y `$color-fondo-principal` (#F2D974) para un control centralizado del tema visual.
2.  **Componentes Híbridos:** Se personalizò la base de Bootstrap con estilos propios para lograr una identidad única sin perder la funcionalidad responsiva.
3.  **Visualización de Datos:** Implementación de barras de progreso dinámicas (`progress-bar`) para las metas de ahorro y tablas estilizadas para el historial de transacciones.
4.  **Responsive Design:** Adaptabilidad total a 3 breakpoints (Móvil, Tablet, Desktop) utilizando clases `col-12`, `col-md`, `col-lg` y utilidades flexbox.

Este enfoque modular permite un desarrollo más eficiente y un mantenimiento más sencillo del código.  