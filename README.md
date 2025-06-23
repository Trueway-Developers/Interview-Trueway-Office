# Interview-Trueway-Office

🧪 Prueba Técnica: Sistema de Gestión de Gastos e Ingresos
🎯 Objetivo
Crear una aplicación web full stack que permita a los usuarios registrar, visualizar y gestionar ingresos y gastos, categorizados por tipo, área y proveedor.

🧱 Requisitos del Proyecto
🖥️ Frontend
Usar React + TypeScript

Estilizado con Tailwind CSS

Debe incluir:

Página de inicio de sesión (mockeada o autenticación básica).

Vista principal con tabla de registros de gastos e ingresos.

Formularios para:

Crear/editar ingresos y gastos.

Crear/editar categorías, áreas y proveedores.

Filtros por:

Fecha

Categoría

Área

Proveedor

Gráfica simple de resumen mensual (puedes usar una librería como recharts o chart.js).

🗄️ Backend
Usar Node.js + Express + TypeScript

ORM: Sequelize

Base de datos: PostgreSQL

Debe incluir:

Rutas RESTful para:

CRUD de gastos e ingresos.

CRUD de categorías, áreas y proveedores.

Validación de datos.

Middleware básico para logs y manejo de errores.

Relación entre modelos:

Un gasto o ingreso pertenece a una categoría, área y proveedor.

🧩 Modelos sugeridos
ts
Copy
Edit
// Income & Expense (puede diferenciarse por un campo 'type')
- id
- amount
- description
- date
- type ("income" | "expense")
- categoryId
- areaId
- providerId

// Category
- id
- name

// Area
- id
- name

// Provider
- id
- name
- contactInfo (opcional)
📋 Entregables
Código fuente en un repositorio público de GitHub o ZIP.

Instrucciones claras para correr el proyecto (README.md con comandos para instalar dependencias, correr migraciones y levantar backend/frontend).

(Opcional) Script SQL o migraciones con Sequelize para poblar datos de prueba.

✅ Criterios de Evaluación
Uso adecuado de tecnologías solicitadas.

Organización del código y estructura del proyecto.

Implementación de relaciones entre entidades.

Buenas prácticas: control de errores, validaciones, estructura modular.

Documentación clara.

UI limpia y funcional (no es necesario diseño avanzado).

Bonus:

Implementación de autenticación básica.

Tests unitarios o de integración.

Deployment en alguna plataforma (Vercel, Railway, Render, etc).
