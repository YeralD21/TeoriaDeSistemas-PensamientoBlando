# Pensamiento de Sistemas Blandos — Gestión de Tesis (SSM aplicado)

## Descripción del Proyecto

Esta página web estática presenta la aplicación de la Metodología de Sistemas Blandos (SSM) de Peter Checkland al caso específico de la gestión de tesis universitarias. El sitio está diseñado para presentaciones académicas, proyección en pantalla y documentación impresa.

## Características Principales

### 🎨 Diseño y Estética
- **Paleta de colores sofisticada**: Tonos gris azulado, verde-azulado, lavanda y dorado
- **Tipografías elegantes**: Playfair Display para títulos, Inter para contenido
- **Diseño responsivo**: Dos columnas en escritorio, apilado en móvil
- **Micro-interacciones**: Hover effects, transiciones suaves, animaciones sutiles

### 📚 Contenido Académico
- **7 pasos del SSM**: Explicación detallada con ejemplos concretos
- **Rich Picture**: Diagrama SVG de actores y relaciones
- **Modelos conceptuales**: Flujos de proceso y comparaciones
- **Casos de estudio**: Ejemplos con estudiantes y asesores ficticios

### 🛠️ Funcionalidades Interactivas
- **Calculadora de impacto**: Estimación de reducción de tiempo
- **FAQ expandible**: Preguntas frecuentes con respuestas
- **Modal de resumen**: Vista imprimible de puntos clave
- **Navegación suave**: Scroll automático entre secciones

### ♿ Accesibilidad
- **Contraste optimizado**: Cumple estándares WCAG
- **Navegación por teclado**: Focus visible en todos los elementos
- **Texto escalable**: Soporte para zoom hasta 200%
- **Reducción de movimiento**: Respeta preferencias del usuario

## Estructura de Archivos

```
├── index.html          # Página principal
├── styles.css          # Estilos CSS con variables
└── README.md           # Documentación del proyecto
```

## Instalación y Uso

### Despliegue Local
1. **Descarga los archivos** en una carpeta local
2. **Abre `index.html`** en cualquier navegador moderno
3. **No requiere servidor** - funciona como archivo local

### Personalización
Para personalizar el contenido, edita las siguientes secciones en `index.html`:

```html
<!-- EDITAR AQUÍ: Título principal -->
<h1 class="main-title">Pensamiento de Sistemas Blandos</h1>

<!-- EDITAR AQUÍ: Subtítulo -->
<p class="subtitle">Gestión de Tesis Universitarias mediante SSM</p>
```

### Cambio de Colores
Modifica las variables CSS en `styles.css`:

```css
:root {
    --bg-primary: #0f1724;           /* Fondo principal */
    --accent-primary: #6EB0A5;       /* Color principal */
    --accent-secondary: #BAA0FF;     /* Color secundario */
    --accent-warm: #E6B785;          /* Color cálido */
    --text-primary: #E6EAF2;         /* Texto principal */
}
```

## Exportación a PDF

### Método 1: Impresión del Navegador
1. Abre la página en el navegador
2. Presiona `Ctrl+P` (Windows) o `Cmd+P` (Mac)
3. Selecciona "Guardar como PDF"
4. Configuración recomendada:
   - Orientación: Vertical
   - Márgenes: Mínimos
   - Escala: 100%

### Método 2: Resumen Ejecutivo
1. Haz clic en cualquier botón de "Contactar Equipo"
2. Se abrirá un modal con resumen imprimible
3. Usa la función de impresión del navegador

## Navegadores Compatibles

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## Características Técnicas

### CSS Features
- **CSS Grid**: Layout responsivo de dos columnas
- **CSS Variables**: Fácil personalización de colores
- **Flexbox**: Componentes flexibles
- **Media Queries**: Diseño adaptativo
- **Print Styles**: Optimizado para impresión

### JavaScript Features
- **Vanilla JS**: Sin dependencias externas
- **Event Listeners**: Interactividad nativa
- **DOM Manipulation**: Contenido dinámico
- **Smooth Scrolling**: Navegación fluida

### Performance
- **Tamaño total**: < 50KB (HTML + CSS)
- **Carga rápida**: Sin recursos externos pesados
- **Fuentes web**: Google Fonts con preload
- **SVG inline**: Gráficos vectoriales ligeros

## Casos de Uso

### 🎓 Presentaciones Académicas
- Proyección en pantalla durante clases
- Exposición de metodologías SSM
- Demostración de casos de estudio

### 📄 Documentación
- Informes de investigación
- Propuestas de mejora
- Documentación de procesos

### 💼 Presentaciones Ejecutivas
- Propuestas a administración universitaria
- Demostración de soluciones tecnológicas
- Presentación de metodologías ágiles

## Personalización Avanzada

### Agregar Nuevas Secciones
```html
<section class="section">
    <h2 class="section-title">Nueva Sección</h2>
    <div class="content-block">
        <!-- Contenido aquí -->
    </div>
</section>
```

### Crear Nuevas Tarjetas
```html
<div class="sidebar-card">
    <h3 class="card-title">Nueva Tarjeta</h3>
    <div class="card-content">
        <!-- Contenido aquí -->
    </div>
</div>
```

### Modificar Colores
```css
/* Ejemplo: Tema corporativo azul */
:root {
    --accent-primary: #2563eb;    /* Azul corporativo */
    --accent-secondary: #3b82f6; /* Azul claro */
    --accent-warm: #f59e0b;      /* Amarillo dorado */
}
```

## Solución de Problemas

### Fuentes No Cargan
- Verifica conexión a internet
- Las fuentes tienen fallbacks seguros
- Usa fuentes del sistema como respaldo

### Estilos No Se Aplican
- Verifica que `styles.css` esté en la misma carpeta
- Revisa la consola del navegador por errores
- Asegúrate de que el archivo no esté corrupto

### JavaScript No Funciona
- Verifica que JavaScript esté habilitado
- Revisa la consola por errores
- Algunas funciones requieren interacción del usuario

## Contribuciones

Para contribuir al proyecto:

1. **Fork** el repositorio
2. **Crea** una rama para tu feature
3. **Commit** tus cambios
4. **Push** a la rama
5. **Abre** un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT. Ver archivo `LICENSE` para más detalles.

## Créditos

- **Metodología SSM**: Peter Checkland
- **Diseño**: Equipo de Teoría de Sistemas
- **Desarrollo**: Estudiante de Ingeniería de Sistemas
- **Institución**: Universidad Peruana Unión

## Contacto

- **Email**: sistemas@upeu.edu.pe
- **Teléfono**: +51 1 234-5678
- **Web**: [www.upeu.edu.pe](https://www.upeu.edu.pe)

---

*Desarrollado con ❤️ para la comunidad académica*
