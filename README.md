# 🎁 Amigo Secreto

Una aplicación web interactiva para organizar sorteos de amigo secreto de manera fácil y divertida.

## 📋 Descripción

**Amigo Secreto** es una aplicación web que permite a los usuarios agregar nombres de amigos y realizar un sorteo aleatorio para determinar quién será el amigo secreto. Es perfecta para organizar intercambios de regalos en fiestas, oficinas, o reuniones familiares.

## ✨ Características

- **Agregar amigos**: Permite ingresar nombres de participantes uno por uno
- **Lista visual**: Muestra todos los amigos agregados en tiempo real
- **Sorteo aleatorio**: Selecciona un amigo secreto de forma aleatoria
- **Interfaz intuitiva**: Diseño limpio y fácil de usar
- **Validación de entrada**: Evita agregar nombres vacíos
- **Responsive**: Se adapta a diferentes tamaños de pantalla

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la aplicación
- **CSS3**: Estilos y diseño responsive
- **JavaScript**: Lógica de la aplicación y manipulación del DOM
- **Google Fonts**: Tipografías Merriweather e Inter

## 🚀 Cómo Usar

1. **Agregar amigos**:
   - Escribe el nombre de un amigo en el campo de texto
   - Haz clic en el botón "Añadir" o presiona Enter
   - El nombre aparecerá en la lista de amigos

2. **Sortear amigo secreto**:
   - Una vez que hayas agregado todos los participantes
   - Haz clic en el botón "Sortear amigo"
   - El nombre del amigo secreto seleccionado aparecerá en pantalla

## 📁 Estructura del Proyecto

```text
challenge-amigo-secreto/
│
├── index.html          # Página principal
├── style.css           # Estilos de la aplicación
├── app.js              # Lógica de JavaScript
├── README.md           # Documentación del proyecto
└── assets/             # Recursos e imágenes
    ├── amigo-secreto.png
    └── play_circle_outline.png
```

## 🎨 Características de Diseño

- **Colores principales**: Azul (#4B69FD), Naranja (#fe652b), Beige (#FFF9EB)
- **Tipografías**: Merriweather (títulos) e Inter (texto)
- **Diseño**: Interfaz moderna con bordes redondeados y sombras
- **Accesibilidad**: Etiquetas ARIA y roles para lectores de pantalla

## 🔧 Instalación y Configuración

1. **Clonar o descargar** el repositorio
2. **Abrir** el archivo `index.html` en tu navegador web
3. **¡Listo!** La aplicación estará funcionando

No se requieren instalaciones adicionales ni servidor web.

## 💻 Requisitos del Sistema

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Funcionalidades JavaScript

### Funciones Principales

- **`agregarAmigo()`**: Agrega un nuevo amigo a la lista
- **`mostrarAmigos()`**: Actualiza la visualización de la lista de amigos
- **`sortearAmigo()`**: Realiza el sorteo aleatorio

### Variables Globales

- **`amigos[]`**: Array que almacena todos los nombres de los participantes
- **`nuevosAmigos`**: Referencia al elemento input del DOM

## 🎯 Próximas Mejoras

- [ ] Opción para eliminar amigos de la lista
- [ ] Historial de sorteos anteriores
- [ ] Exportar resultados
- [ ] Modo oscuro/claro
- [ ] Animaciones para el sorteo
- [ ] Soporte para múltiples idiomas

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

Desarrollado como parte de un desafío de programación para fortalecer habilidades en lógica de programación y manipulación del DOM.

---

⭐ ¡Si te gusta este proyecto, no olvides darle una estrella en GitHub
