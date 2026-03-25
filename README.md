# almacen-tbs

# 📦 WMS Almacén Inteligente (SQL Server Edition)

Sistema de Gestión de Almacén (Warehouse Management System) diseñado para el control de inventario de alta precisión mediante ubicaciones físicas detalladas (Zonas, Estanterías y Posiciones).

## 🛠️ Stack Tecnológico
- **Base de Datos:** Microsoft SQL Server 2022 (T-SQL).
- **Backend:** Node.js + Express.js (Librería `mssql`).
- **Frontend:** React.js + Tailwind CSS.
- **Gestión de DB:** SQL Server Management Studio (SSMS).

## 📂 Estructura del Proyecto
```text
/wms-almacen-sqlserver
│
├── /database            # Scripts y Diseño de Datos
│   ├── /ddl             # Definición de Tablas (10 tablas base)
│   ├── /procedures      # Stored Procedures (Ingresos/Egresos con TRY...CATCH)
│   └── /diagrams        # Diagramas Entidad-Relación (.sqlplan o imágenes)
│
├── /backend             # API REST (Node.js)
│   ├── /src/config      # Configuración de conexión (puerto 1433)
│   └── .env.template    # Plantilla de variables de entorno
│
└── /frontend            # Interfaz de Usuario (React)
```
## 👥 Equipo
- [Jairo Flores Avila] - Líder / DBA
- [Uziel Avalos Padilla] - Backend
- [Alejandra Suarez Obaldo] - Frontend
