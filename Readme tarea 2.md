# Guía y Resumen de Tarea: Módulo 2 - Ingeniería de Software y Requisitos

**Asignatura:** Entornos de Desarrollo  
**Alumno:** Francisco Martínez  
**Módulo:** Módulo 2 - Introducción a la Ingeniería de Software, Modelos y Requisitos  
**Formato de Entrega:** Documento PDF (5 a 7 páginas) a través del Aula Virtual  
**Palabra clave:** 29

---

## 🎯 Objetivo General de la Tarea

Aplicar de forma práctica los conceptos clave de la **Ingeniería de Software** (modelos del ciclo de vida, fases del desarrollo y elicitación/análisis de requisitos) mediante la selección, planteamiento y documentación inicial de un proyecto de software realista.

---

## 📊 Desglose de Puntuación y Estructura del Informe

| Sección | Descripción | Puntuación |
| :--- | :--- | :--- |
| **1. Selección de la Aplicación** | Elección justificada de la idea con conceptos teóricos. | 2 pts |
| **2. Documentación Inicial** | Ficha técnica: Objetivos, usuarios, plataformas y modelo. | 2 pts |
| **3. Listado de Características** | 10 funcionalidades mixtas (funcionales y no funcionales). | 2 pts |
| **4. Análisis de Requisitos** | 5 Requisitos Funcionales + 5 Requisitos No Funcionales justificados. | 2 pts |
| **5. Comunicación y Reflexión** | Reflexión crítica sobre las fases más complejas y modelos. | 2 pts |
| **TOTAL** | | **10 pts** |

---

## 📝 Guía Detallada Paso a Paso

### 1. Selección y Justificación de la Aplicación (2 pts)
- **Instrucción:** Escoger un sistema de software realista (ej. *App de gestión de reservas deportivas, plataforma de tutorías online, gestor de inventario para comercios locales*).
- **Justificación Obligatoria:** Vincular la elección con al menos **dos conceptos teóricos** de clase:
  - *Ejemplo concepto 1:* Justificar por qué la incertidumbre inicial requiere un **modelo Ágil (Scrum/Kanban)** o un **modelo en Espiral**.
  - *Ejemplo concepto 2:* Identificación de la diversidad de usuarios finales y la necesidad de una fase de análisis de usabilidad.

---

### 2. Documentación Inicial de la Aplicación (2 pts)
Incluir una ficha sintética con los siguientes apartados clave:

- **Nombre de la Aplicación:** (Nombre comercial o del proyecto).
- **Descripción Breve:** Qué es y qué valor aporta en 2-3 líneas.
- **Problema que resuelve:** Necesidad del mercado o del usuario que satisface.
- **Roles de Usuario:**
  - *Administrador:* Gestión de datos y usuarios.
  - *Usuario Cliente / Final:* Consumo de servicios.
  - *Soporte / Moderador:* Supervisión.
- **Plataformas de Despliegue:** Móvil (iOS/Android), Web responsive, Escritorio.
- **Modelo de Desarrollo Sugerido:**
  - *Ágil (Scrum/Kanban):* Si se requieren entregas rápidas e iterativas.
  - *Cascada:* Si los requisitos son 100% fijos e inmutables desde el inicio.
  - *Espiral:* Si el análisis de riesgos es crítico.

---

### 3. Listado de Características (2 pts)
Definir un inventario inicial de **al menos 10 características o funcionalidades**, combinando aspectos de funcionamiento con aspectos de calidad/entorno.

*Ejemplo de estructura para el listado:*
1. Registro e inicio de sesión mediante correo y redes sociales.
2. Buscador con filtros avanzados por fecha y ubicación.
3. Notificaciones push en tiempo real para confirmación de reservas.
4. Tiempo de respuesta de la interfaz inferior a 2 segundos.
5. Cifrado de contraseñas y datos sensibles mediante SSL/TLS.
6. Panel de administración para gestión de métricas y ventas.
7. Soporte multi-idioma (Español e Inglés).
8. Generación automatizada de facturas en formato PDF.
9. Interfaz adaptada a estándares de accesibilidad WCAG 2.1.
10. Sincronización automática de datos en modo offline al recuperar conexión.

---

### 4. Análisis de Requisitos (2 pts)

#### A. Requisitos Funcionales (Mínimo 5)
Definen **qué debe hacer** el sistema de forma explícita.
1. **RF1 - Autenticación de Usuarios:** El sistema debe permitir el registro mediante email y contraseña cifrada.
2. **RF2 - Gestión de Reservas:** El usuario debe poder seleccionar fecha, hora y realizar el pago en línea.
3. **RF3 - Envío de Confirmaciones:** El sistema enviará automáticamente un correo electrónico con el comprobante.
4. **RF4 - Cancelación de Citas:** Permite al cliente cancelar una reserva hasta 24 horas antes sin penalización.
5. **RF5 - Generación de Reportes:** El administrador podrá exportar reportes mensuales de uso en Excel/CSV.

#### B. Requisitos No Funcionales (Mínimo 5)
Definen **propiedades, restricciones y cualidades de calidad** del sistema. Debe incluirse la **justificación vista en clase**.

| Requisito No Funcional | Tipo / Área | Justificación Teórica |
| :--- | :--- | :--- |
| **RNF1 - Rendimiento:** Respuesta en $< 1.5\text{s}$. | Eficiencia | La latencia impacta directamente en la retención del usuario. |
| **RNF2 - Seguridad:** Cumplimiento de RGPD y HTTPS. | Seguridad | Protección de datos personales para evitar sanciones y fugas de información. |
| **RNF3 - Usabilidad:** Diseño Responsive e Intuitivo. | Usabilidad | La audiencia puede no tener perfil técnico; reduce la curva de aprendizaje. |
| **RNF4 - Disponibilidad:** Uptime del $99.9\%$. | Fiabilidad | El sistema no debe caer en horas pico de reservas. |
| **RNF5 - Mantenibilidad:** Arquitectura modular. | Mantenimiento | Facilita la incorporación de nuevas funciones en futuras iteraciones. |

---

### 5. Comunicación, Colaboración y Reflexión (2 pts)

- **Fases del Desarrollo más Desafiantes:** Reflexión crítica personal sobre la fase de **Análisis de Requisitos** (por la ambigüedad al comunicarse con los clientes) y la fase de **Pruebas/Testing**.
- **Comparativa de Modelos:** Discutir la diferencia de afrontar estos retos en un modelo tradicional (Cascada) frente a un modelo iterativo/incremental (Ágil/Scrum).

---

## 📋 Lista de Comprobación para la Entrega Final

- [ ] ¿El documento está redactado a nombre de **Francisco Martínez**?
- [ ] ¿Tiene una extensión de entre **5 y 7 páginas**?
- [ ] ¿Se han incluido al menos 10 características generales?
- [ ] ¿Están definidos exactamente $\ge 5$ Requisitos Funcionales y $\ge 5$ No Funcionales?
- [ ] ¿Se justifica teóricamente la importancia de cada Requisito No Funcional?
- [ ] ¿Incluye la reflexión sobre las fases desafiantes citando los modelos de software?
- [ ] ¿Está exportado en formato **PDF** para subir al **Aula Virtual**?