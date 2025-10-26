# 🛍️ Sistema de Gestión de Productos - Frontend Angular

Frontend desarrollado en Angular para un sistema de gestión de productos y categorías con conexión a API Laravel.

## 🚀 Características

- **Interfaz moderna y responsive** para gestión completa de productos
- **Formularios reactivos** con validación en tiempo real
- **Comunicación HTTP** con backend Laravel mediante servicios
- **Navegación SPA** entre componentes usando Angular Router
- **Manejo de estados** avanzado (loading, éxito, error)
- **Selector de categorías** integrado en formulario de productos

## 📱 Componentes Principales

### 🏷️ ProductoComponent (`/producto`)
- Formulario para crear productos con selector de categorías
- Lista dinámica de productos con información completa
- Precios formateados automáticamente
- Visualización de categorías asociadas

### 📂 CategoriaComponent (`/categoria`)
- Lista completa de categorías registradas
- Diseño limpio y responsive
- Navegación integrada entre páginas

## 🛠️ Tecnologías Utilizadas

- **Angular 17+** - Framework principal
- **TypeScript** - Lenguaje de programación
- **RxJS** - Manejo de programación reactiva
- **HTTP Client** - Comunicación con API
- **CSS3** - Estilos y diseño responsive
- **Angular Router** - Navegación entre vistas

## 👨‍💻 Desarrollado por

Daniel Alejandro - Trabajo académico

## 📦 Instalación y Uso

```bash
# 1. Clonar el repositorio
git clone https://github.com/DaniUAB/Angular-Frontend-Productos-.git

# 2. Instalar dependencias
npm install

# 3. Configurar URL del backend (opcional)
# Editar src/app/services/product.service.ts y categoria.service.ts
# si el backend no está en http://localhost:8000

# 4. Ejecutar servidor de desarrollo
ng serve

# 5. Abrir en el navegador
# http://localhost:4200


