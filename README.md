# 📊 Contabilidad Frontend / Accounting Frontend

[![Live Demo](https://img.shields.io/badge/Live_Demo-Ver_Aplicación_en_Vivo-success?style=for-the-badge&logo=render)](https://contabilidad-frontend.onrender.com) 
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()

[🇪🇸 Español](#-español) · [🇬🇧 English](#-english)

---

## 🇪🇸 Español

**Una solución moderna y eficiente para la gestión contable empresarial.**

Contabilidad Frontend es una aplicación desarrollada con un enfoque de alto rendimiento, arquitectura desacoplada y tipado estático riguroso. El proyecto utiliza **Next.js y TypeScript** para construir una interfaz moderna, escalable y eficiente, orientada a facilitar la gestión de las operaciones contables.

El sistema está diseñado para optimizar el registro y control de ingresos, egresos y conciliaciones bancarias, proporcionando una base tecnológica sólida para la administración financiera.

🔗 **[Prueba la aplicación en vivo aquí](https://contabilidad-frontend.onrender.com)**

### 🚀 Estado del Proyecto: En Desarrollo

Actualmente, el proyecto se encuentra en fase de desarrollo y estabilización, con una arquitectura orientada a la separación de responsabilidades entre el frontend y los servicios del sistema. La solución busca ofrecer una experiencia de usuario intuitiva, segura y adaptable a las necesidades de la gestión contable.

### 🛠️ Tecnologías Utilizadas

- **Frontend:** Next.js, React y TypeScript para la construcción de interfaces modernas y tipadas.
- **Servidor integrado:** Next.js para gestionar las funcionalidades del servidor y las rutas que correspondan a la arquitectura del proyecto.
- **Lenguaje de programación:** TypeScript, con tipado estático para mejorar la mantenibilidad y reducir errores.
- **Estilos e interfaz:** Diseño web moderno y adaptable a diferentes dispositivos.
- **Control de versiones:** Git y GitHub para el seguimiento de cambios y la colaboración en el desarrollo.

### 🔗 Repositorio del Backend
Para revisar la lógica del servidor, la gestión de la base de datos PostgreSQL y los endpoints que consume esta interfaz, accede al repositorio del servidor:
* ⚙️ **Backend (Node.js):** [Enlace al repositorio de Node.js](https://github.com/code-with-infinite/contabilidad-backend.git)

### 💡 Características Principales

- **📈 Gestión de Ingresos:** Registro y control de los ingresos para facilitar el seguimiento de las operaciones financieras.
- **💸 Gestión de Egresos:** Organización de los gastos y salidas de dinero para mantener un control financiero estructurado.
- **🏦 Conciliaciones Bancarias:** Funcionalidades orientadas a comparar y verificar los movimientos bancarios con los registros contables.
- **🧩 Arquitectura Desacoplada:** Separación de responsabilidades para facilitar el mantenimiento, la escalabilidad y la integración con otros servicios.
- **⚡ Alto Rendimiento:** Aprovechamiento de las capacidades de Next.js para desarrollar una aplicación eficiente.
- **📱 Interfaz Adaptativa:** Diseño orientado a ofrecer una experiencia de uso consistente en dispositivos móviles y equipos de escritorio.
- **🔒 Tipado Estático:** Uso de TypeScript para mejorar la consistencia del código y facilitar su evolución.

### 🏗️ Arquitectura y Organización

El proyecto sigue un enfoque de arquitectura desacoplada, buscando mantener una separación clara entre la interfaz de usuario, la lógica de presentación y los servicios que gestionan los datos.

Esta organización facilita:

- La evolución independiente de los componentes.
- La integración con el backend y las API del sistema.
- La reutilización de componentes y funcionalidades.
- El mantenimiento y la detección temprana de errores.
- La escalabilidad de la solución a medida que se incorporen nuevos módulos contables.

### ⚙️ Configuración y Seguridad

- **🔐 Variables de Entorno:** Uso de archivos `.env.local` para configurar las variables necesarias en el entorno de desarrollo.
- **🛡️ Protección de Credenciales:** Exclusión de archivos con información sensible mediante `.gitignore`.
- **🔗 Integración con el Backend:** Configuración de las direcciones de las API y los servicios según el entorno de ejecución.
- **📦 Gestión de Dependencias:** Uso de npm y del archivo de bloqueo de dependencias para facilitar instalaciones consistentes.
- **🌿 Control de Versiones:** Uso de Git y GitHub para mantener un historial organizado de los cambios.

> **Importante:** Las credenciales, claves privadas, contraseñas y archivos de configuración sensibles no deben publicarse en repositorios públicos. La configuración de producción debe administrarse mediante variables de entorno seguras.

### ▶️ Instalación y Ejecución

#### 1. Clonar el repositorio
```bash
git clone URL_DEL_REPOSITORIO
```

#### 2. Ingresar al directorio del proyecto
```bash
cd contabilidad-frontend
```

#### 3. Instalar las dependencias
```bash
npm install
```

#### 4. Configurar las variables de entorno
Crea el archivo `.env.local` en la raíz del proyecto y agrega las variables requeridas por la aplicación.

```env
# Configuración de ejemplo
# Agrega aquí las variables utilizadas por el proyecto.
```

Los nombres y valores deben corresponder a la configuración real de la aplicación. No publiques credenciales ni secretos.

#### 5. Iniciar el servidor de desarrollo
```bash
npm run dev
```

Abre el navegador en: `http://localhost:3000`

**Nota:** Los comandos anteriores corresponden a una configuración habitual de Next.js. Pueden requerir ajustes si el proyecto utiliza scripts o configuraciones diferentes.

### 📂 Estructura del Proyecto

La organización exacta depende de los archivos existentes en el repositorio. Una estructura de referencia para el frontend es:

```text
contabilidad-frontend/
├── public/             # Recursos estáticos
├── src/                # Código fuente, si está configurado
│   ├── app/            # Rutas y páginas de Next.js
│   ├── components/     # Componentes reutilizables
│   ├── services/       # Integración con servicios y API
│   └── types/          # Tipos e interfaces de TypeScript
├── .env.local          # Variables de entorno locales
├── .gitignore          # Archivos excluidos de Git
├── package.json        # Dependencias y scripts
├── package-lock.json   # Bloqueo de dependencias de npm
├── tsconfig.json       # Configuración de TypeScript
└── README.md           # Documentación del proyecto
```

*Esta estructura es ilustrativa y debe ajustarse a la organización real del repositorio.*

### 🔮 Objetivos de Evolución

- Ampliar las funcionalidades de gestión financiera.
- Fortalecer los procesos de conciliación bancaria.
- Mejorar la visualización y el análisis de la información contable.
- Optimizar la experiencia de usuario y la accesibilidad.
- Consolidar la integración entre el frontend, el backend y la base de datos.
- Reforzar las prácticas de seguridad y mantenibilidad del código.

### 👨‍💻 Autor

- **Creado por:** code-with-infinite
- **Perfil:** Desarrollador de Software
- **Sistema:** Contabilidad Frontend (Aplicación Web Full-Stack)

---

⭐ **Contabilidad Frontend:** tecnología, organización y eficiencia para la gestión contable.

<br>

---

## 🇬🇧 English

A modern and efficient solution for enterprise accounting management.

Accounting Frontend is an application developed with a focus on high performance, decoupled architecture, and rigorous static typing. The project uses Next.js and TypeScript to build a modern, scalable, and efficient interface aimed at facilitating the management of accounting operations.

The system is designed to optimize the recording and control of income, expenses, and bank reconciliations, providing a solid technological foundation for financial administration.

🔗 **[Test the live application here](https://contabilidad-frontend.onrender.com)**

### 🚀 Project Status: In Development
Currently, the project is in the development and stabilization phase, with an architecture focused on the separation of concerns between the frontend and system services. The solution aims to provide an intuitive, secure, and adaptable user experience tailored to accounting management needs.

### 🛠️ Technologies Used
- **Frontend:** Next.js, React, and TypeScript for building modern, typed interfaces.
- **Integrated Server:** Next.js to manage server functionalities and routes corresponding to the project's architecture.
- **Programming Language:** TypeScript, with static typing to improve maintainability and reduce errors.
- **Styles & Interface:** Modern web design adaptable to different devices.
- **Version Control:** Git and GitHub for tracking changes and development collaboration.

### 🔗 Backend Repository
To review the server logic, PostgreSQL database management, and the endpoints consumed by this interface, access the server repository:
* ⚙️ **Backend (Node.js):** [Link to Node.js repository](https://github.com/code-with-infinite/contabilidad-backend.git)

### 💡 Key Features
- **📈 Income Management:** Recording and control of income to facilitate tracking of financial operations.
- **💸 Expense Management:** Organization of expenses and money outflows to maintain structured financial control.
- **🏦 Bank Reconciliations:** Features aimed at comparing and verifying bank movements with accounting records.
- **🧩 Decoupled Architecture:** Separation of concerns to facilitate maintenance, scalability, and integration with other services.
- **⚡ High Performance:** Leveraging Next.js capabilities to develop an efficient application.
- **📱 Adaptive Interface:** Design aimed at providing a consistent user experience across mobile devices and desktops.
- **🔒 Static Typing:** Use of TypeScript to improve code consistency and facilitate its evolution.

### 🏗️ Architecture and Organization
The project follows a decoupled architecture approach, seeking to maintain a clear separation between the user interface, presentation logic, and services that manage data.

This organization facilitates:
- Independent evolution of components.
- Integration with the backend and system APIs.
- Reusability of components and functionalities.
- Maintenance and early error detection.
- Scalability of the solution as new accounting modules are incorporated.

### ⚙️ Configuration and Security
- **🔐 Environment Variables:** Use of `.env.local` files to configure necessary variables in the development environment.
- **🛡️ Credentials Protection:** Exclusion of files with sensitive information via `.gitignore`.
- **🔗 Backend Integration:** Configuration of API and service addresses according to the execution environment.
- **📦 Dependency Management:** Use of npm and the dependency lock file to facilitate consistent installations.
- **🌿 Version Control:** Use of Git and GitHub to maintain an organized history of changes.

> **Important:** Credentials, private keys, passwords, and sensitive configuration files must not be published in public repositories. Production configuration should be managed through secure environment variables.

### ▶️ Installation and Execution

#### 1. Clone the repository
```bash
git clone REPOSITORY_URL
```

#### 2. Navigate to the project directory
```bash
cd contabilidad-frontend
```

#### 3. Install dependencies
```bash
npm install
```

#### 4. Configure environment variables
Create the `.env.local` file in the project root and add the variables required by the application.

```env
# Example configuration
# Add the variables used by the project here.
```

Names and values must correspond to the actual application configuration. Do not publish credentials or secrets.

#### 5. Start the development server
```bash
npm run dev
```

Open your browser at: `http://localhost:3000`

### 📂 Project Structure
A reference structure for the frontend is:

```text
contabilidad-frontend/
├── public/             # Static resources
├── src/                # Source code
│   ├── app/            # Next.js routes and pages
│   ├── components/     # Reusable components
│   ├── services/       # API and services integration
│   └── types/          # TypeScript types and interfaces
├── .env.local          # Local environment variables
├── .gitignore          # Files ignored by Git
├── package.json        # Dependencies and scripts
└── README.md           # Project documentation
```

### 🔮 Evolution Goals
- Expand financial management functionalities.
- Strengthen bank reconciliation processes.
- Improve visualization and analysis of accounting information.
- Optimize user experience and accessibility.
- Consolidate integration between the frontend, backend, and database.
- Reinforce security and code maintainability practices.

### 👨‍💻 Author
- **Created by:** code-with-infinite
- **Profile:** Software Developer
- **System:** Accounting Frontend (Full-Stack Web Application)
