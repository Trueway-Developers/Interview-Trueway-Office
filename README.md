# 🧪 Prueba Técnica: Sistema de Gestión de Gastos e Ingresos

### El objetivo de esta prueba es crear una aplicación web full stack que permita a los usuarios registrar, visualizar y gestionar ingresos y gastos, categorizados por tipo, área y proveedor.

## 🖥️ Frontend
Usar React + TypeScript + Estilizado con Tailwind CSS

Debe incluir:

- Página de inicio de sesión (autenticación básica).
- Vista principal con tabla de registros de gastos e ingresos.

Formularios para:

- Crear/editar ingresos y gastos.
- Crear/editar categorías, áreas y proveedores.

Filtros por:

- Fecha
- Categoría
- Área
- Proveedor

Incluir Gráfica simple de resumen mensual (chart.js).

## 🗄️ Backend
Usar Node.js + Express + Sequelize (ORM) + PostgreSQL (DB)

Debe incluir:

Rutas RESTful para:

- CRUD de gastos e ingresos.
- CRUD de categorías, áreas y proveedores.

Definir los 5 modelos:

- Gastos
- Ingresos
- Categorias
- Areas
- Proovedores

Relación entre modelos:

- Un gasto o ingreso pertenece a una categoría, área y proveedor.

## ✅ Criterios de Evaluación

- Uso adecuado de tecnologías solicitadas.
- Organización del código y estructura del proyecto.
- Implementación de relaciones entre entidades.
- Buenas prácticas: control de errores, validaciones, estructura modular.
- Documentación clara.
- UI limpia y funcional (no es necesario diseño avanzado).

## ➕ Bonus:

- Implementación de autenticación básica.
- Tests unitarios o de integración.
- Deployment en alguna plataforma (Vercel, Railway, Render, etc).
