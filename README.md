# Aplicación de Gestion de Asociaciones sin fines de lucro

Esta es una aplicación para gestionar el control financiero de una organización con múltiples filiales. Permite a los usuarios gestionar usuarios y permisos, filiales, tesorería, movimientos financieros y generar reportes. Los usuarios tienen diferentes roles y permisos que determinan las funcionalidades a las que pueden acceder dentro de la aplicación.

## Funcionalidades

### 1️⃣ **Gestión de Usuarios y Permisos 👥**
- Creación, modificación y eliminación de usuarios.
- Asignación de roles a los usuarios (Administrador, Tesorero General, Tesoreros de Filiales, Secretario Regional, Secretario de Filial).
- Control de acceso según el rol del usuario.

### 2️⃣ **Gestión de Filiales 🏢**
- Creación, habilitación y deshabilitación de nuevas filiales.
- Modificación de los datos de las filiales.
- Visualización de las filiales según el rol del usuario.

### 3️⃣ **Gestión de Tesorería 💰**
- Registro y seguimiento de ingresos y egresos de cada filial.
- Categorización de movimientos financieros (Ej: Donaciones, Cuotas, Gastos operativos).
- Cálculo automático del saldo mensual y acumulado.

### 4️⃣ **Registro de Movimientos Financieros 📑**
- Ingreso de mensualidades y registro de movimientos financieros.
- Modificación y eliminación de registros financieros.
- Generación de resúmenes mensuales y anuales de ingresos y egresos.

### 5️⃣ **Generación de Reportes y Resúmenes 📊**
- Reportes detallados por filial, región o global.
- Consulta de balances mensuales y anuales.
- Análisis del saldo existente y proyecciones financieras.

### 6️⃣ **Supervisión por Regiones 🏛️**
- Los Secretarios Regionales pueden ver y modificar las filiales dentro de su región.
- Los Secretarios de Filial pueden gestionar únicamente las membresías de su filial.

## Tecnologías Utilizadas

- **Backend**: Django (Python)
- **Base de datos**: PostgreSQL (o cualquier base de datos relacional)
- **Frontend**: HTML, CSS, JavaScript (con posibles frameworks como Bootstrap o jQuery)
- **Autenticación**: Django Authentication y permisos personalizados
- **Despliegue**: Render, Heroku, o cualquier servidor compatible con Django

## Instalación

### Requisitos previos
Asegúrate de tener las siguientes herramientas instaladas:

- Python 3.x
- pip (gestor de paquetes de Python)
- PostgreSQL (si se va a usar como base de datos)

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/tesoreria-app.git
cd tesoreria-app
