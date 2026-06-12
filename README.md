# ¡Hola! Soy Jordi Ledesma 👋

## 💻 Ingeniero de Software especializado en Backend & DevOps
*Construyendo sistemas resilientes con pensamiento escalable y mentalidad de eficiencia operativa.*

---

## 👨‍💻 Un Enfoque Pragmático de la Tecnología
"Utilizo la tecnología para resolver problemas de negocio, no solo para escribir código."

- ⚙️ **Experiencia Multidisciplinar:** Trayectoria sólida en DevOps, Backend y desarrollo Web, enfocada en soluciones seguras y escalables.
- 🔧 **Infraestructura y Automatización:** Experto en automatización de despliegues y gestión de infraestructura crítica.
- 🚀 **Visión de Producto:** Apasionado por crear soluciones que priorizan la experiencia del usuario y los objetivos de negocio.
- 📚 **Evolución Constante:** Profundizando en arquitectura de software avanzada y prácticas modernas de observabilidad.
- 💡 **Filosofía:** Me motiva crear soluciones inteligentes que simplifiquen la complejidad técnica.

---

## 🛠️ Stack Tecnológico

### 👨‍💻 Lenguajes de Programación
<p>
  <img src="https://skillicons.dev/icons?i=go,python,typescript,java,javascript,cpp,cs" height="35" />
</p>

### 🧩 Backend & Datos
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,spring,postgres,mysql,mongodb,redis" height="35" />
</p>

### ☁️ Cloud & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,azure,gcp,nginx,githubactions,linux,bash" height="35" />
</p>

### 🎨 Frontend & UX/UI
<p>
  <img src="https://skillicons.dev/icons?i=react,vue,angular,figma,tailwind,html,css" height="35" />
</p>

---

## 🚀 Proyectos Destacados & Casos de Estudio

### 💳 [FalconPay | Sistema de Gestión y Automatización de Órdenes de Pago](https://github.com/GeordiCode/FalconPay)
*Plataforma transaccional robusta de grado empresarial diseñada bajo una arquitectura monolítica modular.*
* **Containerización y Ciclo de Vida:** Diseñé un entorno multi-contenedor aislado utilizando **Docker & Docker Compose**, abstrayendo por completo el software del host (compilación de backend con Maven y frontend con Angular internamente).
* **Persistencia y Ciclo de Datos:** Integración de **PostgreSQL** con automatización de esquemas relacionales mediante **Flyway** para el versionamiento seguro de bases de datos. Manejo de auditoría mediante *Triggers* de estado y *Stored Procedures* transaccionales.
* **Integración y Resiliencia Asíncrona:** Implementación de persistencia de archivos masivos (facturas) mediante una capa compatible con **S3 (MinIO)**. Sistema de notificaciones asíncronas basado en eventos de dominio para desacoplar las llamadas HTTP externas de la base transaccional, respaldado por logs de reintentos y auditoría de errores (`integration_error_log`).

#### 🖥️ Flujo de Operación e Interfaz de Usuario (Angular Frontend)

| 🌐 1. Landing Page & Acceso Seguro | 📊 2. Dashboard Analítico de Control |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/c2d66001-8bfb-4fbf-a6b4-621f048a0524" width="450px" alt="FalconPay Landing"/> | <img src="https://github.com/user-attachments/assets/a52741fe-65f6-435f-bd8b-a466a0275e1f" width="450px" alt="FalconPay Dashboard"/> |
| *Página de aterrizaje con control de acceso y autenticación segura.* | *Métricas financieras, estados de transacciones y KPIs en tiempo real.* |

| 📋 3. Consola Central de Órdenes | 📝 4. Formulario de Creación y Carga Asíncrona |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/e5e17f43-272b-4655-b0e0-0d7af3800377" width="450px" alt="FalconPay Orders"/> | <img src="https://github.com/user-attachments/assets/278e27c1-c573-4031-9a2f-f36953d08210" width="450px" alt="FalconPay New Order"/> |
| *Módulo de operaciones con filtros dinámicos por estado, fecha y creador.* | *Flujo de ingreso compatible con almacenamiento MinIO/S3 para adjuntar facturas.* |

| 🔍 5. Auditoría y Edición de Transacciones | 👥 6. Gestión de Usuarios y Permisos |
| :---: | :---: |  
| <img src="https://github.com/user-attachments/assets/dd936a35-1e8e-467c-97f8-bfd84cadbf90" width="450px" alt="FalconPay Detail"/> | <img src="https://github.com/user-attachments/assets/3cffdb7c-ee35-4a6a-9a44-e274e3f1898e" width="450px" alt="FalconPay Users"/> |
| *Capa de visualización de detalles, logs de reintentos y estados de auditoría.* | *Panel de administración y control de roles para la seguridad del sistema.* |

---

### 🧠 [SmartWear AI | Infraestructura Backend de Cómputo e Inteligencia Artificial](https://github.com/GeordiCode/SmartWear-AI-backend)
*Infraestructura backend de alto rendimiento para el procesamiento de modelos matemáticos y redes neuronales en tiempo real (Tesis de Grado - Calificación: 4.8/5.0).*
* **Arquitectura de Inferencia Concurrente:** Creación de una API REST de baja latencia utilizando **FastAPI (Python)**, optimizada para servir un sistema híbrido de aprendizaje por refuerzo (*Multi-Armed Bandit*).
* **Pipelines de Datos Estables:** Diseño de flujos de entrenamiento online en tiempo real desacoplados utilizando **PyTorch**, asegurando que la retroalimentación continua del usuario (*feedback loop*) altere los pesos del modelo sin bloquear los hilos principales de ejecución.
* **Rigurosidad y Determinismo:** Implementación de scripts de validación con análisis estadístico profundo (curvas ROC, AUC, validación cruzada K-Fold) para medir el comportamiento predictivo bajo condiciones de estrés y ruidos de datos (hasta el 30%).
  
---

### 📊 EcoDash & Epicoo | Motor de Inteligencia Ambiental corporativo (Caso de Éxito Empresarial)
*Diseño arquitectónico y consultoría técnica para la automatización e ingesta de métricas de Huella de Carbono y circularidad ESG en CommunityLab S.A.S.*
* **Sistemas Cloud Tolerantes a Fallos:** Lideré el despliegue de la arquitectura del ecosistema en **AWS**, configurando políticas de auto-escalado y alta disponibilidad para soportar la ingesta concurrente de datos analíticos masivos.
* **Optimización y Tuning de Base de Datos:** Estructuración y optimización de índices sobre bases de datos relacionales complejas (**PostgreSQL**), mitigando cuellos de botella en consultas masivas de agregación de datos para la generación dinámica de KPIs gerenciales.
* **Automatización de Entregas:** Implementación de pipelines de CI/CD para acelerar los ciclos de despliegue en producción de las dashboards analíticas construidas sobre React.js.

#### 📊 Arquitectura Visual & Motor de Inteligencia Ambiental (React.js)

### 📈 1. Core Analítico & Trazabilidad ESG
*Monitores de alta densidad de datos para el cálculo automatizado de factores de emisión, remociones de CO₂ y flujos de economía circular.*

| 🚗 Reportes de Huella de Carbono (Gases GEI) | 🌲 Inventario de Remociones y Capturas |
| :---: | :---: |
| <img src="URL_DE_REPORTS_CARBONO" width="450px" alt="EcoDash Carbono"/> | <img src="URL_DE_REPORTS_REMOCIONES" width="450px" alt="EcoDash Remociones"/> |
| *Cálculo de alcances 1, 2 y 3 con agregación dinámica de datos según estándares internacionales.* | *Monitoreo y auditoría de proyectos de mitigación y biomasa forestal.* |

| 🔄 Ciclo de Vida de Materiales | 🔀 Flujo de Circularidad (Sankey Diagram) |
| :---: | :---: |
| <img src="URL_DE_REPORTS_CIRCULARIDAD" width="450px" alt="EcoDash Circularidad"/> | <img src="URL_DE_REPORTS_CIRCULRIDAD_SANKEY" width="450px" alt="EcoDash Sankey"/> |
| *Métricas operativas de residuos, tasa de reciclaje y reincorporación productiva.* | *Motor analítico visual para el mapeo de balances de materia y pérdidas del sistema.* |

---

### 🌳 2. Ingesta de Datos y Mapeo de Estructuras Complejas
*Vistas diseñadas para resolver el mapeo de dependencias de grandes corporativos multitarget y la centralización de datos crudos (DataHub).*

| 🌿 Modelado Geográfico de Nodos Operativos | 🌲 Estructura Jerárquica Corporativa (Árbol) |
| :---: | :---: |
| <img src="URL_DE_NODOS_OPERATIVOS" width="450px" alt="EcoDash Nodos Map"/> | <img src="URL_DE_NODOS_OPERATIVOSVISTA_ARBOL" width="450px" alt="EcoDash Nodos Arbol"/> |
| *Consola de administración geográfica para el control descentralizado de sedes y plantas.* | *Abstracción algorítmica para heredar factores de emisión en jerarquías empresariales complejas.* |

| 📥 Centro de Ingesta Masiva (DataHub) | 📊 Métricas Consolidadas de Sostenibilidad |
| :---: | :---: |
| <img src="URL_DE_DATAHUB" width="450px" alt="EcoDash DataHub"/> | <img src="URL_DE_CIRCULARIDAD" width="450px" alt="EcoDash Resumen"/> |
| *Pipelines de carga de fuentes variables con validación previa de esquemas métricos.* | *Panel consolidado para reportes rápidos de cumplimiento normativo y auditorías ESG.* |

---

### ⚙️ 3. Acceso, Seguridad y Gobernanza de Datos (Módulo Corporativo)
<details>
  <summary>🔑 Ver Gestión de Identidades y Acceso Seguro (Clic para desplegar)</summary>
  <br>

| 🏢 Gestión y Onboarding de Empresas | 👥 Control de Accesos Basado en Roles (RBAC) |
| :---: | :---: |
| <img src="URL_DE_GESTION_EMPRESAS" width="450px" alt="EcoDash Empresas"/> | <img src="URL_DE_GESTION_USUARIOS" width="450px" alt="EcoDash Usuarios"/> |
| *Panel multitenant para el aprovisionamiento y aislamiento de datos entre clientes corporativos.* | *Auditoría de actividad del equipo y asignación de permisos según el nivel de operación.* |

| 🌐 Portal Público (Landing Page) | 🔐 Gateway de Autenticación Segura (Login) |
| :---: | :---: |
| <img src="URL_DE_LANDINGPAGE" width="450px" alt="EcoDash Landing"/> | <img src="URL_DE_LOGIN" width="450px" alt="EcoDash Login"/> |
| *Interfaz de cara al usuario para la promoción del ecosistema y captación corporativa.* | *Punto de acceso seguro con cifrado y manejo de sesiones protegidas.* |

</details>

---

## 📫 Conectemos

- 💼 **LinkedIn:** [linkedin.com/in/jordiledesma](https://www.linkedin.com/in/jordiledesma)
- 📧 **Email:** jordi.ledesma.tech@gmail.com
- 📱 **WhatsApp:** [+57 323 297 7886](https://wa.me/573232977886)
- 📍 **Ubicación:** Valle del Cauca, Colombia

---

> *“La confianza del equipo es como la infraestructura: si espero compromiso, entrego el mío desde el primer deploy.”*
