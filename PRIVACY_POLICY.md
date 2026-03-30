# Privacy Policy for Novum Finanzas

**Effective Date: March 30, 2026**

Victor Raul Ortiz Garcia ("we," "our," or "us") operates the Novum Finanzas mobile application (the "App"). We are committed to protecting your privacy and ensuring that your financial data remains secure and under your control.

## 1. Core Principle: Local-First Privacy
Novum Finanzas is designed with a "local-first" architecture. This means that:
*   **Financial Data:** Your accounts, transactions, budgets, and goals are stored locally on your device in a secure database.
*   **No Central Servers:** We do not operate central servers that store your personal financial information.
*   **Data Ownership:** You own your data. We do not have access to your financial records.

## 2. Information We Collect and How We Use It

### A. Personal and Sensitive Information
The App may access or process the following types of information to provide its core features:

*   **Financial Information:** Transactions, account balances, and budget details that you manually enter or that are automatically detected via notifications.
*   **Notification Data:** If you enable the "Notification Listener" feature, the App reads incoming notifications from other financial applications (e.g., banking apps) to automate transaction entry. **This data is processed locally on your device.**
*   **Installed Applications:** To identify which notifications belong to financial apps, the App queries the list of installed packages on your device. This is used solely to filter notifications for automation purposes.
*   **Images (Camera/Gallery):** If you use the AI Receipt Scanning feature, the App accesses your camera or gallery to capture receipt images.
*   **Biometric Data:** If enabled, the App uses your device's biometric authentication (fingerprint/face) for security. We do not store or have access to your actual biometric data; we only receive a "success" or "failure" signal from your operating system.

### B. Third-Party Services and Data Sharing
While we do not store your data on our servers, certain features involve interaction with trusted third-party services:

*   **Google AI (Gemini):** If you use AI features (Receipt Scanning, Notification Parsing, Monthly Summary), the App sends relevant text or images directly from your device to Google AI servers. This requires your own Gemini API key, giving you full control over the data flow.
*   **Google Drive (Backup):** If you enable Cloud Backup, your encrypted database is uploaded to your personal Google Drive account. We do not have access to your Google Drive contents.
*   **Google Sign-In:** Used to authenticate your account for Google Drive backups.

## 3. Sensitive Permissions Disclosure
To comply with Google Play's strict policies, we explicitly disclose the use of the following sensitive permissions:

*   **BIND_NOTIFICATION_LISTENER_SERVICE:** Required to automatically detect and register transactions from your banking notifications. This is a core automation feature of the App.
*   **QUERY_ALL_PACKAGES:** Required to identify which financial and banking apps are installed on your device, ensuring the App only monitors relevant alerts.
*   **FOREGROUND_SERVICE / FOREGROUND_SERVICE_DATA_SYNC:** Used to maintain the connection for notification monitoring and background data synchronization (backups) to ensure a seamless experience.

## 4. Data Retention and Deletion
*   **Retention:** Data is kept on your device as long as the App is installed.
*   **Deletion:** You can delete all your data at any time via the "Settings > Data & Security > Delete all data" option. Uninstalling the App will also remove all local data (unless a manual backup was created).
*   **Requests:** Since we do not store your data on our servers, we cannot "delete" it for you. You have full control over your local data and cloud backups.

## 5. Security
 we use industry-standard encryption for local storage (`flutter_secure_storage`) and secure database practices (`drift` / `sqflite`). However, the security of your data also depends on your device's security.

## 6. Children's Privacy
Novum Finanzas is not intended for use by children under the age of 13. We do not knowingly collect personal information from children.

## 7. Changes to This Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date."

## 8. Contact Us
If you have any questions or concerns about this Privacy Policy, please contact us at:

**Developer:** Victor Raul Ortiz Garcia  
**Email:** victorraulortizgarcia@gmail.com

---

# Política de Privacidad de Novum Finanzas

**Fecha de entrada en vigor: 30 de marzo de 2026**

Victor Raul Ortiz Garcia ("nosotros," "nuestro" o "nos") opera la aplicación móvil Novum Finanzas (la "App"). Estamos comprometidos con la protección de su privacidad y con garantizar que sus datos financieros permanezcan seguros y bajo su control.

## 1. Principio Fundamental: Privacidad Local
Novum Finanzas está diseñada con una arquitectura de "prioridad local". Esto significa que:
*   **Datos Financieros:** Sus cuentas, transacciones, presupuestos y metas se almacenan localmente en su dispositivo en una base de datos segura.
*   **Sin Servidores Centrales:** No operamos servidores centrales que almacenen su información financiera personal.
*   **Propiedad de los Datos:** Usted es el dueño de sus datos. Nosotros no tenemos acceso a sus registros financieros.

## 2. Información que Recopilamos y Cómo la Utilizamos

### A. Información Personal y Sensible
La App puede acceder o procesar los siguientes tipos de información para proporcionar sus funciones principales:

*   **Información Financiera:** Transacciones, saldos de cuentas y detalles de presupuestos que usted ingresa manualmente o que se detectan automáticamente mediante notificaciones.
*   **Datos de Notificaciones:** Si activa la función "Lector de Notificaciones", la App lee las notificaciones entrantes de otras aplicaciones financieras (por ejemplo, aplicaciones bancarias) para automatizar el registro de transacciones. **Estos datos se procesan localmente en su dispositivo.**
*   **Aplicaciones Instaladas:** Para identificar qué notificaciones pertenecen a aplicaciones financieras, la App consulta la lista de paquetes instalados en su dispositivo. Esto se utiliza únicamente para filtrar notificaciones con fines de automatización.
*   **Imágenes (Cámara/Galería):** Si utiliza la función de Escaneo de Recibos con IA, la App accede a su cámara o galería para capturar imágenes de recibos.
*   **Datos Biométricos:** Si se activa, la App utiliza la autenticación biométrica de su dispositivo (huella dactilar/rostro) por seguridad. No almacenamos ni tenemos acceso a sus datos biométricos reales; solo recibimos una señal de "éxito" o "fallo" de su sistema operativo.

### B. Servicios de Terceros y Uso Compartido de Datos
Aunque no almacenamos sus datos en nuestros servidores, ciertas funciones implican la interacción con servicios de terceros de confianza:

*   **Google AI (Gemini):** Si utiliza funciones de IA (Escaneo de Recibos, Análisis de Notificaciones, Resumen Mensual), la App envía texto o imágenes relevantes directamente desde su dispositivo a los servidores de Google AI. Esto requiere su propia clave API de Gemini, lo que le otorga un control total sobre el flujo de datos.
*   **Google Drive (Respaldo):** Si activa el Respaldo en la Nube, su base de datos cifrada se carga en su cuenta personal de Google Drive. Nosotros no tenemos acceso al contenido de su Google Drive.
*   **Google Sign-In:** Se utiliza para autenticar su cuenta para los respaldos en Google Drive.

## 3. Divulgación de Permisos Sensibles
Para cumplir con las estrictas políticas de Google Play, divulgamos explícitamente el uso de los siguientes permisos sensibles:

*   **BIND_NOTIFICATION_LISTENER_SERVICE:** Necesario para detectar y registrar automáticamente las transacciones de sus notificaciones bancarias. Esta es una función de automatización central de la App.
*   **QUERY_ALL_PACKAGES:** Necesario para identificar qué aplicaciones financieras y bancarias están instaladas en su dispositivo, garantizando que la App solo monitoree las alertas relevantes.
*   **FOREGROUND_SERVICE / FOREGROUND_SERVICE_DATA_SYNC:** Se utiliza para mantener la conexión para el monitoreo de notificaciones y la sincronización de datos en segundo plano (respaldos) para asegurar una experiencia Fluida.

## 4. Retención y Eliminación de Datos
*   **Retención:** Los datos se mantienen en su dispositivo mientras la App esté instalada.
*   **Eliminación:** Puede eliminar todos sus datos en cualquier momento a través de la opción "Configuración > Datos y Seguridad > Borrar todos los datos". Al desinstalar la App también se eliminarán todos los datos locales (a menos que se haya creado un respaldo manual).
*   **Solicitudes:** Dado que no almacenamos sus datos en nuestros servidores, no podemos "eliminarlos" por usted. Usted tiene el control total sobre sus datos locales y respaldos en la nube.

## 5. Seguridad
Utilizamos cifrado estándar de la industria para el almacenamiento local (`flutter_secure_storage`) y prácticas de base de datos seguras (`drift` / `sqflite`). Sin embargo, la seguridad de sus datos también depende de la seguridad de su dispositivo.

## 6. Privacidad de los Menores
Novum Finanzas no está dirigida a menores de 13 años. No recopilamos conscientemente información personal de niños.

## 7. Cambios en esta Política
Es posible que actualicemos nuestra Política de Privacidad de vez en cuando. Le notificaremos cualquier cambio publicando la nueva Política de Privacidad en esta página y actualizando la "Fecha de entrada en vigor".

## 8. Contacto
Si tiene alguna pregunta o inquietud sobre esta Política de Privacidad, póngase en contacto con nosotros en:

**Desarrollador:** Victor Raul Ortiz Garcia  
**Correo electrónico:** victorraulortizgarcia@gmail.com
