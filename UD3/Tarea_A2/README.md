### Propiedades de CSS en el juego Gris Garden

1. **Animaciones** (`@keyframes`, `animation`): Para movimientos y transiciones suaves de los elementos.
   ```css
   @keyframes moveUp { from { transform: translateY(0); } to { transform: translateY(-10px); } }

2. **Transformaciones** (`transform`, `rotate()`, `scale()`: Para mover, rotar o escalar elementos.

```css
.character { transform: translateX(-100px); }
```
3. **Transiciones** (`transition`): Para cambios suaves entre estados.

```css
.button { transition: background-color 0.3s ease; }
```
4. **Sombras** (`box-shadow`, `text-shadow`): Para agregar profundidad o resaltar elementos.

```css
.shadow-effect { box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3); }
```
5. **Posicionamiento** (`position`, `z-index`): Para colocar elementos en coordenadas específicas.

```css
.game-item { 
  position: absolute; 
  top: 50px; 
  left: 100px; 
  z-index: 2; 
}
```

6. **Responsive Design** (`@media`): Para adaptarse a diferentes tamaños de pantalla.
   ```css
   @media (max-width: 768px) { 
     .game-container { 
       flex-direction: column; 
     } 
   }

7. **Gradientes** (`background: linear-gradient()`): Para crear fondos atractivos.
   ```css
   .background { 
     background: linear-gradient(to bottom, #f0f8ff, #d8bfd8); 
   }

8. **Filtros** (`filter`): Para aplicar efectos visuales como desenfoques o saturación.
   ```css
   .game-image { 
     filter: grayscale(50%); 
   }

9. **Tipografía** (`font-family`, `font-size`): Para personalizar la apariencia del texto.
   ```css
   .game-title { 
     font-family: 'Press Start 2P', cursive; 
     font-size: 36px; 
   }

10. **Layouts** (`display: flex`, `display: grid`): Para organizar los elementos.
    ```css
    .game-grid { 
      display: grid; 
      grid-template-columns: repeat(3, 1fr); 
      gap: 20px; 
    }
    ```
