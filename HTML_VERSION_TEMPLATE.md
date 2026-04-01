# HTML Version Template

Plantilla base para cualquier pagina HTML del `DreamTeam` que necesite mostrar una version visible tras una actualizacion.

## Regla

- cada cambio visible en una pagina HTML debe subir la version mostrada `+1`;
- la version debe verse sin inspeccionar codigo;
- debe servir para comprobar, tras limpiar cache, que se esta viendo la ultima publicacion.

## Formato recomendado

Usar una pill o badge corta y clara, por ejemplo:

- `Update v1.1`
- `Version v2.4`
- `Build v3.0`

## Snippet CSS

```css
.version-pill {
  display: inline-flex;
  align-items: center;
  padding: 8px 12px;
  border-radius: 999px;
  font-size: 0.8rem;
  font-weight: 800;
  letter-spacing: 0.04em;
  color: #193241;
  background: rgba(255, 255, 255, 0.74);
  border: 1px solid rgba(25, 34, 40, 0.11);
}
```

## Snippet HTML

```html
<div class="version-pill">Update v1.1</div>
```

## Checklist minima antes de publicar

1. confirmar que la pagina HTML refleja el ultimo cambio real;
2. subir la version visible `+1`;
3. limpiar cache local y recargar;
4. comprobar que la version mostrada coincide con la ultima publicada.
