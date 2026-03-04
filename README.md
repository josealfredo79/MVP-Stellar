# 🍃 MiPuebloPay — MVP Stellar para Oaxaca

> Plataforma de remesas y pagos locales construida sobre la red [Stellar](https://stellar.org), diseñada con empatía para comunidades rurales de Oaxaca, México.

[![Stellar](https://img.shields.io/badge/Blockchain-Stellar-blue?logo=stellar)](https://stellar.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-brightgreen)](https://sistemastectlaxiaco.github.io/MVP-Stellar/)

---

## 🎯 ¿Qué es este repositorio?

Material didáctico y MVP funcional desarrollado dentro del **Programa EIR (Entrepreneur in Residence) de Stellar** en colaboración con el **Tecnológico Nacional de México — Campus Tlaxiaco, Oaxaca**.

El objetivo es enseñar a estudiantes universitarios cómo diseñar y construir productos financieros accesibles usando tecnología blockchain (Stellar/Soroban), sin exponer complejidad técnica al usuario final.

---

## 📂 Estructura del Proyecto

```
├── index.html                      # Página de inicio (landing page)
├── presentacion_stellar_mvp.html   # Parte 1: Conceptos (Mockups, MVP, Empatía)
├── presentacion_parte2.html        # Parte 2: Ejercicios prácticos y Stellar
├── mockup_mvp_web.html             # MVP Web funcional (Dashboard interactivo)
├── mockup_mvp_tlaxiaco.html        # MVP Mobile (versión móvil del simulador)
├── clase_stellar_mvp_slides.md     # Notas del instructor en Markdown
├── ejemplo_mockup.png              # Imagen: wireframe dibujado a mano
├── hifi_mockup.png                 # Imagen: mockup de alta fidelidad
└── README.md                       # Este archivo
```

---

## 🚀 Demo en Vivo

Puedes ver todo el material funcionando en GitHub Pages:

👉 **[https://sistemastectlaxiaco.github.io/MVP-Stellar/](https://sistemastectlaxiaco.github.io/MVP-Stellar/)**

Desde ahí puedes acceder a:

| Recurso | Descripción |
|---------|-------------|
| **Parte 1: Conceptos** | Diapositivas sobre Mockups, MVP y diseño con empatía local |
| **Parte 2: Práctica** | Ejercicios cronometrados, Stellar Starter Pack y SCF |
| **MVP Web Interactivo** | Dashboard funcional de "MiPuebloPay" con simulación de depósitos y envíos |

---

## 💡 Características del MVP Web

El simulador web (`mockup_mvp_web.html`) demuestra cómo se vería una aplicación financiera real para Oaxaca:

- **🔐 Social Login** — Inicio de sesión con Google o WhatsApp (sin wallets ni seed phrases)
- **💰 Balance dinámico** — El saldo se actualiza en tiempo real al depositar o enviar
- **📊 Historial de transacciones** — Tabla profesional con registros de actividad
- **🏦 On-Ramp / Off-Ramp** — Simulación de depósito vía SPEI (AlfredPay) y envío a banco local
- **✅ Validaciones** — Control de saldo insuficiente, montos inválidos, etc.
- **🎨 Diseño profesional** — Layout de Dashboard con Sidebar, tarjetas con gradientes, y diseño responsivo

### Principios de UX aplicados:
- **Abstracción total de blockchain** — El usuario solo ve pesos mexicanos (MXN)
- **Regla de los 3 clics** — Cualquier operación se completa en máximo 3 pasos
- **CTA únicos** — Cada pantalla tiene un solo objetivo claro

---

## 🏗️ Tecnologías Utilizadas

| Tecnología | Uso |
|-----------|-----|
| HTML5 / CSS3 / JavaScript | Frontend del MVP y presentaciones |
| [TailwindCSS](https://tailwindcss.com/) (CDN) | Sistema de diseño del MVP Web |
| [Reveal.js](https://revealjs.com/) | Motor de presentaciones interactivas |
| [Font Awesome](https://fontawesome.com/) | Iconografía |
| [Stellar Network](https://stellar.org/) | Infraestructura blockchain (conceptual) |
| [Soroban](https://soroban.stellar.org/) | Smart contracts (en fases futuras) |

---

## 🌐 Ecosistema Stellar Referenciado

- **[Regional Starter Pack](https://github.com/elliotfriend/regional-starter-pack)** — Librería TypeScript para on/off ramps con Anchors regionales
- **[AlfredPay](https://alfredpay.io/)** — Anchor regulado para México (MXN ↔ USDC)
- **[Stellar Community Fund (SCF)](https://communityfund.stellar.org/)** — Fondo de financiamiento para proyectos con impacto real

---

## 📖 Contenido Pedagógico

### Parte 1: Conceptos Fundamentales
1. Analogía: La maqueta antes del edificio
2. ¿Qué es un Mockup? Ventajas y proceso
3. Diseño de User Flows profesionales
4. Happy Path, CTA y Regla de los 3 Clics
5. ¿Qué es un MVP? (Analogía Patineta → Auto)
6. Empatía local y abstracción de Web3
7. Social Login como solución de adopción

### Parte 2: Práctica y Stellar
1. Ejercicio 1: Dibujar Mockup del Happy Path (25 min)
2. Stellar Regional Starter Pack y AlfredPay
3. Stellar Community Fund (Open Track)
4. Ejercicio 2: Rediseño iterativo (20 min)
5. Demostración del MVP Web funcional

---

## 🏃‍♂️ Ejecución Local

```bash
# Clonar el repositorio
git clone https://github.com/SistemasTecTlaxiaco/MVP-Stellar.git
cd MVP-Stellar

# Levantar servidor local
python3 -m http.server 8000

# Abrir en el navegador
# http://localhost:8000
```

No requiere instalación de dependencias ni proceso de build. Todo funciona con archivos estáticos.

---

## 👥 Créditos

- **Institución:** Tecnológico Nacional de México — Campus Tlaxiaco
- **Programa:** EIR (Entrepreneur in Residence) — Stellar Development Foundation
- **Ubicación:** Heroica Ciudad de Tlaxiaco, Oaxaca, México
- **Enfoque:** Inclusión financiera para comunidades rurales de la Mixteca

---

## 📄 Licencia

Este proyecto es de uso educativo y está disponible bajo la licencia [MIT](LICENSE).

---

<p align="center">
  Desarrollado con ❤️ para la comunidad de Oaxaca<br>
  <strong>Infraestructura Stellar × Soroban</strong>
</p>
