# 🤖 NOVA – Asistente Robótico para Personas con Alzheimer

![Status](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow) ![Python](https://img.shields.io/badge/Python-3.11-blue) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-5-cc0000)  
![License](https://img.shields.io/badge/Licencia-MIT-green) ![Author](https://img.shields.io/badge/Autor-Felipe%20Ju%C3%A1rez-black)

---

## 🧠 ¿Qué es NOVA?

**NOVA** es un asistente robótico creado para apoyar a personas que padecen **Alzheimer** en sus actividades diarias. Funciona como un recordatorio inteligente que ayuda al usuario a:

- 💊 Tomar medicamentos a tiempo  
- 💧 Mantener una correcta hidratación  
- 📋 Cumplir tareas simples diarias  
- 🗣️ Recibir instrucciones auditivas o visuales de manera amigable  
- 👥 Ser monitoreado y configurado por sus cuidadores de forma segura

> 🎯 NOVA busca promover la **autonomía, seguridad y calidad de vida** de adultos mayores mediante tecnología accesible, ética y empática.

---

## 🚀 Estado Actual del Proyecto

| Módulo                             | Estado        | Descripción                                                                 |
|-----------------------------------|---------------|-----------------------------------------------------------------------------|
| Arquitectura del sistema          | ✅ Completo   | Diseño lógico, componentes definidos                                        |
| Motor de recordatorios (Python)   | ✅ Completo   | Funciones básicas de alarma y control de tareas                            |
| Integración con Raspberry Pi      | 🧪 En prueba  | Se está testeando hardware: pantalla, botones físicos, audio, etc.         |
| Interfaz de usuario (CLI/LED)     | 🔜 En diseño  | Planeada para pantalla táctil o salida por consola                         |
| Control por voz                   | 🔜 Prototipo  | Implementación en pruebas con `speech_recognition` y `pyttsx3`             |
| Configuración remota por cuidadores | 🔜 Por desarrollar | Se busca incluir acceso local o vía app para configurar recordatorios |

---

## 🛠️ Tecnologías Utilizadas

- 🐍 **Python 3.11** – Lenguaje principal del sistema
- 🍓 **Raspberry Pi 5 (8GB)** – Plataforma física principal
- 🎛️ **GPIO / LEDs / Pantallas LCD** – Para interacción directa
- 🔊 **Text-to-Speech** – `pyttsx3` para feedback auditivo
- 🔐 Seguridad local – Sin dependencia de la nube, privacidad ante todo
- 🧪 Herramientas de prueba – Test unitarios y simulaciones

---

## 🧱 Arquitectura del Sistema
[ Usuario 👴 ]
↓
[ Entrada: Botón físico / Comando de voz ]
↓
[ Raspberry Pi 5 ]
↓
[ Módulo de recordatorios / Módulo de voz ]
↓
[ Alerta: Voz / LED / Pantalla ]
↓
[ Usuario recibe la acción y retroalimenta ]

---

## 💡 Motivación

Más de 55 millones de personas viven con demencia en el mundo, siendo el Alzheimer la forma más común. NOVA surge por:

- 👵👴 **Empatía**: Inspirado por casos reales en la familia y comunidad
- 🔧 **Ingeniería útil**: Uso de tecnología para resolver un problema humano
- 💸 **Accesibilidad**: NOVA es de bajo costo, libre y modificable
- 💚 **Compromiso social**: Mejorar la calidad de vida de adultos mayores

---

## 📚 Casos de Uso

1. **Recordatorio de Medicamentos**  
   El usuario recibe una alerta con audio y luz cuando es hora de tomar una pastilla.

2. **Hidratación Programada**  
   Cada 2 horas, NOVA recuerda amablemente al usuario que debe beber agua.

3. **Tareas Básicas Diarias**  
   NOVA recuerda actividades como "regar las plantas", "salir a caminar", etc.

4. **Modo Noche y Modo Día**  
   Silencia o ajusta la actividad según horarios establecidos.

---

## 🧪 Validación y Pruebas

- 🔬 Pruebas simuladas en entornos controlados
- 📋 Casos de uso validados con personas adultas mayores voluntarias
- 🧰 Test unitarios en Python (recordatorios, horarios, interrupciones)
- 🔁 Revisión de experiencia de usuario junto a estudiantes de Ingeniería Industrial

---

## 📅 Roadmap (WinterFest 2025)

- ✅ Fase Alpha – sistema básico funcional
- 🧩 Personalización de tareas vía archivo externo (config.txt / JSON)
- 📱 Interfaz para cuidadores (CLI o app simple)
- 🧠 Reconocimiento facial (fase experimental)
- 📶 Conectividad local para backup o control avanzado
- 🧬 Módulo de interacción emocional (mensajes motivacionales, voz afectiva)

---

## 👨‍💻 Equipo del Proyecto

| Nombre             | Carrera                                    | Rol                                       |
|--------------------|--------------------------------------------|-------------------------------------------|
| **Felipe Juárez**  | Ing. en Tecnologías de la Información y Ciberseguridad | Líder del proyecto, desarrollo, seguridad |
| Estudiantes de II  | Ingeniería Industrial                      | UX, validación, enfoque social             |
| Estudiantes de TI  | Ingeniería TI                              | Soporte de hardware y pruebas técnicas     |

---

## ❤️ Impacto Esperado

- 🧓 + 👵 Mejora en la **autonomía de personas con Alzheimer**
- 👨‍⚕️ Disminución de carga emocional en cuidadores
- 💡 Aplicación práctica de la ingeniería con propósito social
- 🔓 Tecnología libre, replicable, ética y humana

---

## 📬 Contacto

- ✉️ Correo: [lfelipejuarez1@gmail.com](mailto:lfelipejuarez1@gmail.com)
- 📱 WhatsApp: [+506 8802 2645](https://wa.me/50688022645)
- 💼 LinkedIn: [linkedin.com/in/ingfelipejuarezm](https://www.linkedin.com/in/ingfelipejuarezm)
- 🌐 Repositorio: [github.com/ingfelipejuarez/nova](https://github.com/ingfelipejuarez/nova)

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y mejorarlo libremente, siempre con fines éticos y no comerciales sin consentimiento.

---

> “La tecnología verdaderamente innovadora es aquella que pone al ser humano en el centro.”  
> — NOVA Project Team

