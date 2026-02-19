# 🛍️ Samurai Shop - Carrito de Compras

Una página web de e-commerce funcional y completamente responsiva construida con HTML, CSS y JavaScript vanilla. Diseñada para demostrar la implementación de un carrito de compras dinámico con interfaz moderna y atractiva.

## ✨ Características

### 🎨 **Diseño Moderno y Responsivo**
- Interfaz visualmente atractiva con gradientes y efectos visuales
- Totalmente responsivo para móviles, tablets y desktop
- Navbar sticky con logo animado
- Footer informativo con múltiples secciones
- Animaciones suaves y transiciones elegantes

### 🛒 **Funcionalidad del Carrito**
- ✅ Agregar productos al carrito desde la tienda
- ✅ Incrementar y decrementar cantidades de productos
- ✅ Eliminar productos individuales del carrito
- ✅ Vaciar todo el carrito de una sola vez
- ✅ Cálculo automático del total de la compra
- ✅ Contador de artículos en tiempo real
- ✅ Persistencia visual del carrito mediante modal

### 📱 **Adaptabilidad Multi-dispositivo**
- Ultra pequeñas (320px - 480px)
- Pequeñas/medianas (480px - 768px)
- Tablets (768px - 1024px)
- Pantallas landscape (max-height: 600px)
- Desktop (> 1024px)

### 🎯 **Interfaz de Usuario**
- Modal dinámico para visualizar el carrito
- Botón flotante de carrito con contador emergente
- Indicador visual de cantidad de productos
- Confirmación de seguridad al vaciar carrito
- Carrito vacío con mensaje amigable

## 🚀 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con:
  - Gradientes lineales
  - Flexbox y Grid
  - Media queries responsivas
  - Animaciones y transiciones
  - Backdrop filters
- **JavaScript Vanilla** - Funcionalidad interactiva sin frameworks
  - Manipulación del DOM
  - Event listeners
  - Array methods (map, reduce, filter)

## 📂 Estructura del Proyecto

```
├── index.html          # Página principal
├── styles.css          # Estilos y media queries
├── js/
│   ├── index.js        # Lógica de productos y compra
│   ├── cart.js         # Lógica del carrito
│   └── products.js     # Array de productos disponibles
├── media/
│   └── icono-samurai.png  # Logo de la marca
└── README.md           # Este archivo
```

## 💻 Cómo Usar

1. **Clonar o descargar el repositorio**
```bash
git clone <url-del-repositorio>
cd ECOMERCE-Carrito-de-Compras
```

2. **Abrir en el navegador**
   - Simplemente abre `index.html` en tu navegador web
   - No requiere servidor local ni instalación de dependencias

3. **Uso de la aplicación**
   - 🛍️ Explora los productos disponibles
   - ➕ Haz clic en "Comprar" para agregar productos
   - 🛒 Haz clic en el carrito flotante para ver tu compra
   - 📝 Ajusta cantidades o elimina productos
   - 📊 Ve el total actualizar en tiempo real
   - 🗑️ Vacía el carrito completo cuando lo necesites

## 🎨 Paleta de Colores

- **Gradientes Principales:**
  - Púrpura (Body): `#667eea` → `#764ba2`
  - Navbar: `#1a1a2e` → `#16213e`
  - Buttons: `#1bcb7f` → `#00d4ff`
  - Acciones negativas: `#ed3434` → `#ff5252`

- **Colores Acentos:**
  - Verde Neón: `#1bcb7f` (Logo y elementos highlight)
  - Cian: `#00d4ff` (Efectos secundarios)
  - Rojo: `#ed3434` (Acciones destructivas)

## 📱 Responsive Design

La aplicación se adapta perfectamente a:
- **Móviles** (320px+): Productos a ancho completo, carrito optimizado
- **Tablets** (768px+): 2 columnas de productos, modal expandido
- **Desktop** (1024px+): Múltiples columnas, experiencia completa

## 🐛 Características Técnicas Destacadas

- **Sin dependencias externas** - Todo en JavaScript vanilla
- **Optimizado para rendimiento** - Manipulación eficiente del DOM
- **Código limpio y estructurado** - Fácil de mantener y extender
- **Comentarios descriptivos** - Código autodocumentado
- **Manejo robusto de estados** - Carrito sincronizado en todo momento

## 🔮 Posibles Mejoras Futuras

- Integración con base de datos (Firebase/MongoDB)
- Autenticación de usuarios
- Carrito persistente (localStorage)
- Pagos en línea (Stripe/PayPal)
- Filtros y búsqueda de productos
- Historial de compras
- Sistema de valoraciones
- Notificaciones de éxito

## 👨‍💻 Desarrollo

Este proyecto fue desarrollado como desafío de programación para dominar:
- Manipulación avanzada del DOM
- Gesión de estados en JavaScript
- Diseño responsivo
- UX/UI moderna

## 📄 Licencia

Este proyecto está disponible bajo licencia MIT. Siéntete libre de usarlo, modificarlo y distribuirlo.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📧 Contacto

Si tienes preguntas o sugerencias sobre este proyecto, no dudes en contactarme.

---

⭐ Si te gustó este proyecto, ¡considéra darle una estrella en GitHub!

**Versión:** 1.0.0  
**Última actualización:** Febrero 2026
