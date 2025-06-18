## 🎉 ¡Bienvenido a **CONECTATE-YA WISP SOFTWARE 1.5**! 🚀

¡Gracias por confiar en **CONECTATE-YA WISP SOFTWARE**!  
Estás utilizando la **versión 1.5** de nuestra plataforma. 🎯

Con **CONECTATE-YA WISP SOFTWARE** podrás disfrutar de todas las funciones esenciales para organizar, gestionar y hacer crecer tu día a día.  
Todo lo que necesitas para empezar, en un solo lugar. 🔥

---

## ⚙️ FUNCIONALIDADES DEL SISTEMA

Nuestro **Sistema de Administración de Clientes WISP e ISP** te permite gestionar de manera eficiente tu negocio, integrando múltiples funciones en una sola plataforma:

- 📡 **Conexión con MikroTik**: Administración avanzada de red.
- 🔄 **Automatización inteligente**: Corte y reactivación automática del servicio.
- 📶 **Gestión de Simple Queue y PPPoE**: Control de ancho de banda.
- 📲 **Notificaciones automáticas**: Envío de alertas vía API de WhatsApp.
- 🛠️ **Monitoreo y soporte técnico**: Optimización del servicio al cliente.
- 🗺️ **Mapa de cliente**: Visualización de la ubicación de tus clientes.
- 🗂️ **Mapa de red**: Control y monitoreo de tus cajas NAP y MUFAS.
- 📋 **Panel de control amigable**: Fácil de usar, responsivo y adaptado a escritorio o móvil.
- 📈 **Dashboard estadístico**: Mide rendimiento de clientes activos, pagos, ingresos y más.

---

## 🧪 TUTORIALES Y USO DEL SISTEMA

Aprende a dominar tu sistema con nuestros tutoriales disponibles:

### 🎬 VIDEOS DISPONIBLES

1. ✅ **Introducción al sistema**  
   📺 https://www.youtube.com/watch?v=dEtIk_XkIEA

2. ⚙️ **Configuración inicial**  
   📺 https://www.youtube.com/watch?v=VIDEO_ID_2

(Se agregarán más vídeos en futuras versiones)

---

## ⏱️ CRON JOBS

Tu sistema necesita ejecutar ciertas tareas automáticas para mantener la operación fluida. Estos procesos se ejecutan periódicamente mediante **CRON JOBS**.

### 🔁 Funciones automáticas incluidas:

- Crear facturas de los clientes ACTIVOS  /  wget -q "https://midominio.com/tasks/invoice_receipts"
- Enviar deuda por correo electronico masivamente  /  wget -q "https://midominio.com/tasks/invoice_send_email"
- Envío de deuda a través de WhatsApp API /  wget -q "https://midominio.com/tasks/invoice_send_whatsapp"
- Envío de deuda por dia de pago a través de WhatsApp API /  wget -q "https://midominio.com/tasks/invoice_send_payday_whatsapp"
- Recordatorio de deudas de la empresa por WhatsApp API  /   wget -q "https://midominio.com/tasks/deuda_send_whatsapp"

### 🌐 URL del CRON principal:

https://tudominio.com/cron/ejecutar

> Recomendación: Programa este cron para ejecutarse cada **15 minutos** usando `crontab`.

Ejemplo de línea CRON:
*/15 * * * * curl -s https://tudominio.com/cron/ejecutar > /dev/null 2>&1


---

## 📅 ACTUALIZACIONES DEL SISTEMA

> Este software se mantiene en constante mejora. A continuación, los principales cambios realizados:

### 📌 Últimos cambios

| Fecha       | Versión | Descripción                                                                 |

| 2025-06-01  | 1.5.0   | Integración de videos tutoriales desde YouTube                             |
| 2025-05-18  | 1.4.2   | Optimización del sistema de notificaciones por WhatsApp                    |
| 2025-05-01  | 1.4.0   | Añadido módulo de mapa de red para visualizar cajas NAP y MUFAS            |
| 2025-04-15  | 1.3.0   | Implementado el control de Simple Queue con conexión directa a MikroTik    |
| 2025-04-01  | 1.2.0   | Primera versión estable con integración básica PPPoE y gestión de clientes |

---

## 🧑‍💻 CRÉDITOS Y DERECHOS DE AUTOR

- 👨‍💻 **Proyecto:** Sistema de administración de clientes WISP e ISP  
- 🛠️ **Desarrollador:** Walter Rengifo  
- 🌐 **Web:** [https://wisppro.net](https://wisppro.net)  
- 🔢 **Versión actual:** 1.5.0

---

## 📞 CONTACTOS DE ATENCIÓN

- 📱 **WhatsApp:** +51 999 220 735  
- ✉️ **Correo:** walterrengifo08@gmail.com  

**¡Ventas, soporte o mejoras!**


