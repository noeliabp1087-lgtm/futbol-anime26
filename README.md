# NexoPlay - Rediseño Responsive Módulo II

*Alumno:* Noelia 
*Módulo:* II 
*Fecha:* 25-06-2025

## Análisis de Diseño
*Grid vs Flexbox:* 
Usé CSS Grid en .container para la arquitectura de página: separar header, sidebar y content. Es lo ideal para layouts 2D. 
Usé Flexbox dentro de cada .card para apilar imagen, título y botón verticalmente. Es lo ideal para layouts 1D.

*Breakpoints:* 
768px para pasar de layout móvil 1 columna a layout desktop con sidebar lateral.

## Reto IA: Optimización de Estilos

*CSS Original - Botón:*
```css
.card button { background: #FF3D71; color: white; padding: 10px; }