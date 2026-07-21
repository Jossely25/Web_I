# Web I - Business Management System 📊

Sistema web desarrollado para la gestión administrativa y comercial de un negocio. La aplicación organiza diferentes módulos según el rol del usuario, permitiendo administrar productos, categorías, empleados, compras, comisiones y visualizar reportes de ventas y ganancias.

## Características

- Inicio de sesión.
- Gestión de productos.
- Gestión de categorías.
- Gestión de empleados.
- Gestión de compras.
- Administración de comisiones.
- Panel para administradores.
- Panel para gerencia.
- Panel para secretaría.
- Panel para vendedores.
- Reportes de ganancias semanales, quincenales y mensuales.
- Reportes de rotación de productos.
- Interfaz web responsiva.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript

---

## Estructura del proyecto

```text
web-i-management-system/
│
├── CSS/
│   ├── estilo.css
│   ├── estilos.css
│   ├── gestionProductos.css
│   ├── gananciasEstilos.css
│   └── ...
│
├── HTML/
│   ├── Login.html
│   │
│   ├── Admin/
│   │   ├── inicioAdmin.html
│   │   ├── gestionProductos.html
│   │   ├── gestionCategorias.html
│   │   ├── gestionCompra.html
│   │   ├── gestionComision.html
│   │   └── gestionEmpleados.html
│   │
│   ├── Gerente/
│   │   ├── menuGerente.html
│   │   ├── gananciasSemanales.html
│   │   ├── gananciasQuincenales.html
│   │   ├── gananciasMensuales.html
│   │   ├── rotacion.html
│   │   └── ...
│   │
│   ├── Secretaria/
│   │   └── ...
│   │
│   └── Vendedor/
│       └── InicioVendedor.html
│
└── JS/
```

---

## Funcionalidades

### Administrador

- Gestión de productos.
- Gestión de categorías.
- Gestión de empleados.
- Gestión de compras.
- Administración de comisiones.

### Gerente

- Consulta de ganancias semanales.
- Consulta de ganancias quincenales.
- Consulta de ganancias mensuales.
- Reportes de rotación de productos.
- Indicadores administrativos.

### Secretaría

- Acceso a módulos operativos.
- Gestión de procesos administrativos.

### Vendedor

- Acceso al panel de ventas.
- Gestión de operaciones comerciales.

---

## Requisitos

- Navegador web moderno.
- No requiere instalación de dependencias.
- Puede ejecutarse localmente o desplegarse en cualquier servidor web.

---

## Instalación

### Clonar el repositorio

```bash
git clone https://github.com/USUARIO/web-i-management-system.git
```

### Ejecutar el proyecto

Abrir el archivo:

```text
HTML/Login.html
```

También puede ejecutarse utilizando un servidor local como **Live Server** en Visual Studio Code.

---

## Arquitectura

La aplicación organiza las funcionalidades mediante módulos independientes según el rol del usuario, facilitando la navegación y el mantenimiento del sistema.

Los estilos se encuentran centralizados en la carpeta:

```text
CSS/
```

mientras que cada rol dispone de sus propias vistas dentro de:

```text
HTML/
```

---

## Capturas

Puedes agregar imágenes del sistema en esta sección.

```text
docs/login.png

docs/admin.png

docs/gerente.png

docs/vendedor.png

docs/reportes.png
```

---

## Autor

Desarrollado por **Jossely Elena Aguirre Acuña**.

---

## Licencia

Proyecto desarrollado con fines académicos.
