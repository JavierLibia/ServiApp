# ServiApp
Proyecto Senati - ServiApp - Sistema de Alertas
# ServiApp Sullana 🇵🇪 🚀
**Sistema Unificado de Alertas y Gestión de Servicios Básicos**

ServiApp es una plataforma web diseñada para centralizar la información de servicios básicos (Luz, Agua, Gas, Internet) en un solo lugar. El proyecto busca impactar positivamente en la provincia de Sullana, Piura, permitiendo a los ciudadanos consultar deudas y recibir alertas preventivas usando su DNI como identificador principal.

---

## 📊 Estado del Proyecto
Actualmente en fase de **Desarrollo de Backend y Base de Datos (IV Ciclo - SENATI)**.
- [x] Diagrama Lógico de Base de Datos (Lucidchart).
- [x] Configuración de Servidor en la Nube (PostgreSQL).
- [ ] Creación de Tablas y Relaciones.
- [ ] Maquetación del Frontend (En progreso).

## 🏗️ Arquitectura de Datos
El sistema utiliza una base de datos relacional robusta gestionada en **pgAdmin4**.
* **Usuarios:** Autenticación mediante DNI y contraseña.
* **Empresas:** Registro de proveedores de servicios (Enosa, EPS Grau, etc.).
* **Estado de Servicio:** Seguimiento en tiempo real de deudas, fechas de vencimiento y montos.

## 🛠️ Tecnologías y Herramientas
* **IDE:** Visual Studio Code.
* **Base de Datos:** PostgreSQL (pgAdmin4).
* **Control de Versiones:** Git & GitHub.
* **Diseño:** Lucidchart.

## 👥 Equipo de Trabajo
* **Javier Libia** ([@JavierLibia](https://github.com/JavierLibia))

* **Dulce Correa** (@1615014@senati.pe)

## ⚙️ Configuración para Desarrolladores
Como el servidor en la nube tiene disponibilidad limitada por créditos, se recomienda:
1. Clonar el repositorio.
2. Ejecutar los scripts de la carpeta `/database` en un entorno local de **PostgreSQL**.
3. Configurar el archivo `.env` para apuntar a `localhost` fuera del horario de clase.

---
*Proyecto académico desarrollado para SENATI - Instructor: Luigy Cardoza*
