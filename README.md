### El desafío

Crear una página de receta funcional y responsiva siguiendo el diseño de Figma.

## Mi proceso

### Construido con
- HTML5 Semántico
- CSS Custom Properties
- Flexbox
- Mobile-first workflow

### Lo que aprendí
En este proyecto practiqué la personalización de listas con el pseudo-elemento `::marker` para que coincidan con los colores del diseño:

```css
.prep-box li::marker { 
    color: hsl(332, 51%, 32%); 
}

.instructions li::marker {
    color: hsl(14, 45%, 36%);
    font-weight: 700;
}