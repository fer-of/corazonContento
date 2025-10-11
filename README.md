# Corazón Contento 

**Una aplicación para combatir el desperdicio de alimentos conectando a productores locales con consumidores conscientes.**

[](https://github.com)

**Una aplicación para combatir el desperdicio de alimentos conectando a productores locales con consumidores conscientes.**

[![Estado del Build](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com)
[![Cobertura de Código](https://img.shields.io/badge/coverage-85%25-green)](https://github.com)
[![Quality Gate](https://img.shields.io/badge/quality_gate-passed-brightgreen)](https://github.com)
[![Licencia](https://img.shields.io/badge/license-MIT-blue)](https://opensource.org/licenses/MIT)

---

## 📖 Índice

1.  [Descripción del Proyecto](#-descripción-del-proyecto)
2.  [🚀 Funcionalidades Clave](#-funcionalidades-clave)
3.  [🛠️ Stack Tecnológico](#-stack-tecnológico)
4.  [⚙️ Flujo de Trabajo DevOps](#-flujo-de-trabajo-devops)
5.  [🏁 Cómo Empezar (Getting Started)](#-cómo-empezar-getting-started)
6.  [📈 Estado Actual del Proyecto](#-estado-actual-del-proyecto)
7.  [👥 Equipo del Proyecto](#-equipo-del-proyecto)
8.  [📄 Licencia](#-licencia)

---

## 🎯 Descripción del Proyecto

**Corazón Contento** es una plataforma móvil diseñada para reducir el desperdicio alimentario en negocios locales. La aplicación permite a restaurantes, panaderías y tiendas de alimentos publicar productos que no se vendieron durante el día a un precio reducido, para que los consumidores puedan comprarlos, evitando que terminen en la basura.

Nuestros objetivos principales son:
* Reducir en un 20% el desperdicio alimentario en los negocios afiliados durante el primer año
* Alcanzar 10,000 usuarios activos en los primeros 12 meses
* Integrar al menos 50 negocios locales en el primer año

## 🚀 Funcionalidades Clave

### Para Productores de Comida 👨‍🍳
* **Publicación de Alimentos**: Crear publicaciones rápidas de alimentos sobrantes con foto, descripción, fecha y precio.
* **Panel de Estadísticas**: Acceder a un panel con estadísticas de ventas e inventario para entender qué productos tienen más demanda
* **Gestión de Caducidad**: Marcar y destacar productos cercanos a su fecha de caducidad para darles prioridad
* **Promociones**: Crear promociones y descuentos para atraer a más compradores
* **Chat Integrado**: Comunicarse directamente con los clientes para resolver dudas a través de un chat seguro

### Para Consumidores 🙋‍♀️
* **Notificaciones Personalizadas**: Recibir alertas sobre nuevos alimentos disponibles según la ubicación y preferencias
* **Reserva y Pago Seguro**: Reservar y pagar los productos directamente desde la aplicación a través de un carrito de compra
* **Reseñas y Valoraciones**: Consultar las calificaciones y comentarios de otros usuarios para asegurar la calidad
* **Búsqueda y Filtros**: Encontrar alimentos específicos utilizando filtros avanzados por tipo, precio, ubicación y fecha
* **Recolección Programada**: Elegir una ventana de tiempo definida para recoger los pedidos en el negocio

## 🛠️ Stack Tecnológico

| Categoría | Tecnología | Descripción |
| :--- | :--- | :--- |
| **Backend** | Node.js / Python  | Lógica de negocio y gestión de la API REST. |
| **Frontend** | React & React Native  | Interfaz web y aplicación móvil para iOS y Android. |
| **Base de Datos** | PostgreSQL | Almacenamiento de datos de usuarios, productos y transacciones. |
| **Infraestructura** |  GCP | Alojamiento escalable de la aplicación y servicios en la nube. |

## ⚙️ Flujo de Trabajo DevOps

Este proyecto sigue un ciclo de vida de desarrollo ágil con un pipeline de CI/CD completamente automatizado para garantizar la calidad y la rapidez en las entregas.

**`Planificación (Taiga)`** ➔ **`Desarrollo (GitHub)`** ➔ **`Auditoría (SonarCloud)`** ➔ **`Despliegue (Ansible)`** ➔ **`Notificación (Slack)`**

| Herramienta | Propósito |
| :--- | :--- |
| **Taiga** | Gestión ágil del proyecto (Scrum), backlog e historias de usuario. |
| **GitHub & Actions**  Control de versiones y ejecución del pipeline de CI/CD. |
| **SonarCloud** | Análisis estático de código y aplicación de "Quality Gates" en cada Pull Request. |
| **Ansible** | Automatización del despliegue y configuración de la infraestructura. |
| **Slack** | Canal de comunicación y notificaciones en tiempo real del estado del pipeline. |

## 🏁 Cómo Empezar (Getting Started)

Sigue estos pasos para configurar el entorno de desarrollo local.

### Prerrequisitos
* Node.js (v18.x o superior)
* npm o yarn
* Git

### Instalación
1.  Clona el repositorio:
    ```sh
    git clone [https://github.com/fer-of/corazon-contento.git](https://github.com/fer-of/corazon-contento.git)
    ```
2.  Navega al directorio del proyecto:
    ```sh
    cd corazon-contento
    ```
3.  Instala las dependencias:
    ```sh
    npm install
    ```
4.  Inicia el servidor de desarrollo:
    ```sh
    npm run dev
    ```

## 📈 Estado Actual del Proyecto

El proyecto cuenta con una primera versión conceptual y algunos módulos básicos definidos.Se debe continuar con el desarrollo, la integración de IA, las pruebas piloto y la optimización para escalar.El equipo se encuentra en un proceso de validación y mejora continua. Ya cuenta con la integracion de SonarQube para los CI/CD

## 👥 Equipo del Proyecto

El equipo está conformado por los siguientes roles, tal como se define en el Plan de Desarrollo:
* 1 Gestor de Proyecto
* 1 Diseñador UI/UX
* 2 Desarrolladores Backend 
* 2 Desarrolladores Frontend (Web y Móvil)
* 1 Tester QA 

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.om)
[](https://github.com)
[](https://opensource.org/licenses/MIT)

-----
