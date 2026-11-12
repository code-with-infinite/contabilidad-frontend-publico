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

### 💡 Nota de Arquitectura y Seguridad
El código fuente original de esta aplicación está resguardado en un repositorio privado por razones de confidencialidad y protección de propiedad intelectual. **Este repositorio público contiene únicamente los archivos estáticos compilados y ofuscados de la aplicación (carpeta `chunks/`), la licencia y esta documentación.** 

La ofuscación y minificación del bundle (código compilado) se implementan como una medida disuasoria habitual para dificultar la ingeniería inversa, pero no constituyen una garantía criptográfica absoluta. Las credenciales, secretos y la lógica sensible residen exclusivamente en el backend. Este repositorio no es reproducible, ya que no incluye el código fuente ni los archivos de configuración necesarios para su compilación.

### 🚀 Estado del Proyecto: En Desarrollo

Actualmente, el proyecto se encuentra en fase de desarrollo y estabilización, con una arquitectura orientada a la separación de responsabilidades entre el frontend y los servicios del sistema. La solución busca ofrecer una experiencia de usuario intuitiva, segura y adaptable a las necesidades de la gestión contable.

### 🛠️ Tecnologías Utilizadas

- **Frontend:** Next.js, React y TypeScript para la construcción de interfaces modernas y tipadas.
- **Servidor integrado:** Next.js para gestionar las funcionalidades del servidor y las rutas que correspondan a la arquitectura del proyecto.
- **Lenguaje de programación:** TypeScript, con tipado estático para mejorar la mantenibilidad y reducir errores.
- **Estilos e interfaz:** Diseño web moderno y adaptable a diferentes dispositivos.
- **Control de versiones:** Git y GitHub para el seguimiento de cambios y la colaboración en el desarrollo.

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

- **🔐 Variables de Entorno:** Uso de archivos `.env.local` para configurar las variables necesarias en el entorno de desarrollo privado. En Next.js, las variables expuestas al cliente (prefijo `NEXT_PUBLIC_`) son públicas, por lo que no deben contener secretos. Las credenciales reales se gestionan de forma segura en el backend.
- **🛡️ Protección de Credenciales:** Exclusión de archivos con información sensible mediante `.gitignore`.
- **🔗 Integración con el Backend:** Configuración de las direcciones de las API y los servicios según el entorno de ejecución.
- **📦 Gestión de Dependencias:** Uso de npm y del archivo de bloqueo de dependencias para facilitar instalaciones consistentes en el entorno de desarrollo privado.
- **🌿 Control de Versiones:** Uso de Git y GitHub para mantener un historial organizado de los cambios.

> **Importante:** Las credenciales, claves privadas, contraseñas y archivos de configuración sensibles no deben publicarse en repositorios públicos. La configuración de producción debe administrarse mediante variables de entorno seguras a nivel de servidor.

### 🔒 Arquitectura y Repositorio del Backend
Por razones de seguridad, confidencialidad y protección de propiedad intelectual, el código fuente del servidor se encuentra alojado en un **repositorio privado**. El acceso está restringido exclusivamente al autor del proyecto y evaluadores externos autorizados.

El núcleo de servicios se encuentra **desplegado y en ejecución en entornos de producción en la nube (Render)** bajo una arquitectura de microservicios independiente.

Sin embargo, para fines de evaluación técnica, se detalla la pila tecnológica que compone el core del servidor:
* 🖥️ **Entorno de Ejecución & Hosting:** Node.js / Desplegado en la nube a través de Render.
* 🗄️ **Base de Datos:** PostgreSQL (Diseño relacional optimizado para la integridad de los datos contables).
* 🛡️ **Seguridad:** Implementación de variables de entorno protegidas y mitigación de brechas de exposición en producción.

### 📂 Estructura del Repositorio Público

A diferencia del repositorio privado (que contiene el código fuente en `src/`, `package.json`, etc.), este repositorio público está estructurado únicamente para servir los archivos compilados y la documentación:

```text
contabilidad-frontend-publico/
├── chunks/             # Archivos estáticos compilados y ofuscados (JS/CSS)
├── LICENSE             # Términos de licencia y derechos de autor
└── README.md           # Documentación del proyecto
```

### 🔮 Objetivos de Evolución

- Ampliar las funcionalidades de gestión financiera.
- Fortalecer los procesos de conciliación bancaria.
- Mejorar la visualización y el análisis de la información contable.
- Optimizar la experiencia de usuario y la accesibilidad.
- Consolidar la integración entre el frontend, el backend y la base de datos.
- Reforzar las prácticas de seguridad y mantenibilidad del código.

### 👨‍💻 Autor

- **Creado por:** [code-with-infinite](https://github.com/code-with-infinite)
- **Perfil:** Desarrollador de Software
- **Sistema:** Contabilidad Frontend (Aplicación Web Full-Stack)
- © Todos los derechos reservados.

---

⭐ **Contabilidad Frontend:** tecnología, organización y eficiencia para la gestión contable.

<br>

---

## 🇬🇧 English

A modern and efficient solution for enterprise accounting management.

Accounting Frontend is an application developed with a focus on high performance, decoupled architecture, and rigorous static typing. The project uses Next.js and TypeScript to build a modern, scalable, and efficient interface aimed at facilitating the management of accounting operations.

The system is designed to optimize the recording and control of income, expenses, and bank reconciliations, providing a solid technological foundation for financial administration.

🔗 **[Test the live application here](https://contabilidad-frontend.onrender.com)**

### 💡 Architecture and Security Note
The original source code for this application is securely hosted in a private repository for confidentiality and intellectual property protection reasons. **This public repository contains only the compiled and obfuscated static assets of the application (the `chunks/` folder), the license, and this documentation.**

Bundle obfuscation and minification are implemented as a standard deterrent measure to make reverse engineering harder, but they do not constitute an absolute cryptographic guarantee. Credentials, secrets, and sensitive logic reside exclusively in the backend. This repository is not reproducible, as it does not include the source code or configuration files required for compilation.

### 🚀 Project Status: In Development
Currently, the project is in the development and stabilization phase, with an architecture focused on the separation of concerns between the frontend and system services. The solution aims to provide an intuitive, secure, and adaptable user experience tailored to accounting management needs.

### 🛠️ Technologies Used
- **Frontend:** Next.js, React, and TypeScript for building modern, typed interfaces.
- **Integrated Server:** Next.js to manage server functionalities and routes corresponding to the project's architecture.
- **Programming Language:** TypeScript, with static typing to improve maintainability and reduce errors.
- **Styles & Interface:** Modern web design adaptable to different devices.
- **Version Control:** Git and GitHub for tracking changes and development collaboration.

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
- **🔐 Environment Variables:** Use of `.env.local` files to configure necessary variables in the private development environment. In Next.js, client-exposed variables (prefixed with `NEXT_PUBLIC_`) are public, so they must not contain secrets. Actual credentials are securely managed in the backend.
- **🛡️ Credentials Protection:** Exclusion of files with sensitive information via `.gitignore`.
- **🔗 Backend Integration:** Configuration of API and service addresses according to the execution environment.
- **📦 Dependency Management:** Use of npm and the dependency lock file to facilitate consistent installations in the private development environment.
- **🌿 Version Control:** Use of Git and GitHub to maintain an organized history of changes.

> **Important:** Credentials, private keys, passwords, and sensitive configuration files must not be published in public repositories. Production configuration should be managed through secure server-level environment variables.

### 🔒 Backend Architecture and Repository
For security, confidentiality, and intellectual property protection reasons, the server source code is hosted in a **private repository**. Access is strictly restricted to the project author and authorized external evaluators.

The core services are **deployed and running in cloud production environments (Render)** under an independent microservices architecture.

However, for technical evaluation purposes, the technology stack making up the server core is outlined below:
* 🖥️ **Runtime Environment & Hosting:** Node.js / Cloud deployment through Render.
* 🗄️ **Database:** PostgreSQL (Relational design optimized for accounting data integrity).
* 🛡️ **Security:** Implementation of protected environment variables and mitigation of production exposure risks.

### 📂 Public Repository Structure

Unlike the private repository (which contains the source code in `src/`, `package.json`, etc.), this public repository is structured solely to serve the compiled files and documentation:

```text
contabilidad-frontend-publico/
├── chunks/             # Compiled and obfuscated static assets (JS/CSS)
├── LICENSE             # License terms and copyright
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
- **Created by:** [code-with-infinite](https://github.com/code-with-infinite)
- **Profile:** Software Developer
- **System:** Accounting Frontend (Full-Stack Web Application)
- © All rights reserved.