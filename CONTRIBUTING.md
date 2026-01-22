# Guía de Contribución

¡Gracias por tu interés en contribuir a **Vibe Coding vs AI Engineering**! 🎉

## 🚀 Cómo Contribuir

### Reportar Bugs

1. Verifica que el bug no haya sido reportado ya en [Issues](../../issues)
2. Si no existe, crea un nuevo issue con:
   - Título descriptivo
   - Pasos para reproducir
   - Comportamiento esperado vs actual
   - Screenshots (si aplica)
   - Navegador y sistema operativo

### Sugerir Mejoras

1. Abre un issue con el tag `enhancement`
2. Describe la mejora propuesta
3. Explica por qué sería útil

### Pull Requests

1. **Fork** el repositorio
2. **Crea una rama** desde `main`:
   ```bash
   git checkout -b feature/mi-mejora
   ```
3. **Realiza tus cambios** siguiendo los estándares del proyecto
4. **Prueba** que todo funciona correctamente
5. **Commit** con mensajes descriptivos:
   ```bash
   git commit -m "feat: agregar nueva sección sobre X"
   ```
6. **Push** a tu fork:
   ```bash
   git push origin feature/mi-mejora
   ```
7. **Abre un PR** describiendo tus cambios

## 📋 Estándares de Código

### HTML
- Usar indentación de 4 espacios
- Incluir atributos `alt` en imágenes
- Mantener semántica HTML5

### CSS
- Usar variables CSS para colores y espaciados
- Nombres de clases en kebab-case
- Agrupar propiedades lógicamente

### JavaScript
- Preferir `const` y `let` sobre `var`
- Funciones con nombres descriptivos
- Comentarios para lógica compleja

### Commits
Seguimos [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` Nueva funcionalidad
- `fix:` Corrección de bugs
- `docs:` Documentación
- `style:` Cambios de estilo/formato
- `refactor:` Refactorización

## 📚 Estructura del Proyecto

```
├── index.html           # Página principal
├── introduccion.html    # Módulo 1
├── arquitectura.html    # Módulo 2
├── implementacion.html  # Módulo 3
├── doc/                 # Documentación técnica
└── README.md            # Documentación del repo
```

## ❓ Preguntas

Si tienes dudas, abre un issue con el tag `question`.

---

¡Gracias por contribuir! 💜
