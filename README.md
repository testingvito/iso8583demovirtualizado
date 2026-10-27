# 🏦 Pasarela ISO 8583 & Inspector Dinámico Parasoft Virtualize

![ISO 8583](https://img.shields.io/badge/ISO-8583-emerald?style=for-the-badge)
![Parasoft Virtualize](https://img.shields.io/badge/Parasoft-Virtualize_9080-blue?style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS_v3-38bdf8?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML-5-e34f26?style=for-the-badge)

Entorno de pruebas punta a punta (*End-to-End*) que simula la interacción física de un Cajero Automático (ATM) vintage consumiendo servicios de mensajería financiera **ISO 8583** virtualizados en **Parasoft Virtualize**.

El proyecto incluye un **Escáner Dinámico de Respondedores en Vivo** con medición de latencia en milisegundos (`ms`), un **Inspector de Tramas Hexadecimales / JSON**, y un **Generador de Vouchers Térmicos**.

---

## 👨‍💻 Autoría y Créditos

* **Desarrollador / QA Engineer:** Víctor Carreño
* **GitHub:** [@testingvito](https://github.com/testingvito)
* **Especialidad:** Software Quality Assurance / Test Automation & Service Virtualization

---

## 🛠️ Estructura del Repositorio

```text
iso8583demovirtualizado/
├── frontend/
│   └── atm_simulator_iso8583_inspector.html   # Interfaz web del ATM e Inspector
├── parasoft-virtualize/
│   ├── VirtualAssets.xml                       # Configuración de Virtual Assets
│   ├── iso8583.pva                             # Proyecto Parasoft Virtualize
│   └── iso8583.pvadd                           # Datos de respuestas tabuladas
└── README.md                                   # Documentación del proyecto
