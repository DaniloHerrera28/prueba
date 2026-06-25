<div align="center">

# 🦜 PIKO
## Aprende idiomas indígenas sin internet

![Badge](https://img.shields.io/badge/Estado-En%20Desarrollo-22c55e?style=flat-square&logoColor=white)
![Badge](https://img.shields.io/badge/Hackathon-Nicaragua%202026-16a34a?style=flat-square)
![Badge](https://img.shields.io/badge/Equipo-MugiWare-15803d?style=flat-square)

</div>

---

<details open>
<summary><b>📖 Tabla de Contenidos</b></summary>

- [✨ Características](#características)
- [🎯 ¿Por qué Piko?](#por-qué-piko)
- [📱 Plataformas](#plataformas)
- [🛠️ Tecnologías](#tecnologías)
- [🚀 Instalación](#instalación)
- [📋 Uso](#uso)
- [🤝 Contribuir](#contribuir)
- [📄 Licencia](#licencia)

</details>

---

## ✨ Características

<table>
<tr>
<td width="50%">

### 🌐 Offline-First
El teléfono del docente actúa como **servidor local**. Los estudiantes se conectan vía WiFi hotspot. **Cero datos móviles necesarios**.

</td>
<td width="50%">

### 🗣️ Lenguas Indígenas
Soporte nativo para:
- **Miskito**
- **Mayangna**
- **Rama**
- **Garífuna**

</td>
</tr>
<tr>
<td width="50%">

### 🎮 Gamificado
- Rachas de aprendizaje
- Puntos XP
- Logros desbloqueables
- Avatares personalizables

</td>
<td width="50%">

### 🤖 Modo Robot
Para aulas sin dispositivos. El **robot de aula** enseña sin pantalla táctil.

</td>
</tr>
<tr>
<td width="50%">

### 📊 Panel del Docente
Monitorea progreso en **tiempo real**. Datos almacenados localmente. Sin rastreo.

</td>
<td width="50%">

### 🎯 Dirigido a Rurales
Diseñado para estudiantes que transicionan de multigrado a secundario.

</td>
</tr>
</table>

---

## 🎯 ¿Por qué Piko?

<div align="center">

| 🚫 Problema | ✅ Solución Piko |
|---|---|
| **Sin internet en aulas rurales** | Funciona 100% offline con WiFi local |
| **Contenido en español + inglés** | 4 lenguas indígenas de Nicaragua |
| **Apps caras de $50-500/mes** | Gratuita, open source, una sola compra |
| **Diseño genérico** | UI/UX pensado para contexto rural |
| **Dependencia de conectividad** | El docente ES la infraestructura |

</div>

---

## 📱 Plataformas

<div align="center">

```
┌─────────────────────────────────────┐
│                                     │
│  📱 CLIENTE (Estudiante)           │
│  • React Native / Flutter          │
│  • Android 8+ / iOS 13+            │
│  • Acceso WiFi local               │
│                                     │
├─────────────────────────────────────┤
│                                     │
│  🔗 CONEXIÓN LOCAL                 │
│  • WiFi Hotspot                    │
│  • Sin datos móviles               │
│  • Latencia <50ms                  │
│                                     │
├─────────────────────────────────────┤
│                                     │
│  🖥️ SERVIDOR (Docente)             │
│  • Node.js + Express               │
│  • SQLite local                    │
│  • Dashboard de monitoreo          │
│                                     │
└─────────────────────────────────────┘
```

</div>

---

## 🛠️ Tecnologías

### Frontend (Cliente)

<div align="center">

![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black&label=UI%20Framework)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)

</div>

### Backend (Servidor Docente)

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

</div>

### Herramientas & Diseño

<div align="center">

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📸 Galería

> **Nota:** Reemplaza los placeholders con capturas reales, GIFs y mockups.

<table>
<tr>
<td align="center" width="33%">

### 📱 Pantalla Principal

```
╔════════════════════╗
║ ┌──────────────┐   ║
║ │ 🦜 Piko      │   ║
║ │ Aprende hoy  │   ║
║ └──────────────┘   ║
║                    ║
║ [Miskito]    [XP:] ║
║ [Mayangna]   🔥 12 ║
║ [Rama]             ║
║ [Garífuna]         ║
║                    ║
╚════════════════════╝
```

**[Insertar GIF aquí]**

</td>
<td align="center" width="33%">

### 🎮 Lección Interactiva

```
╔════════════════════╗
║ 🗣️ Pronuncia:    ║
║                    ║
║   "Kupia biasa"    ║
║      🎤 Grabar     ║
║                    ║
║ ✅ Correcto! +10XP ║
║ 🔥 Racha: 5 días   ║
║                    ║
╚════════════════════╝
```

**[Insertar GIF aquí]**

</td>
<td align="center" width="33%">

### 📊 Panel Docente

```
╔════════════════════╗
║ 📊 Aula 5°A       ║
║                    ║
║ Diego     ████████ ║
║ María     ███████  ║
║ Juan      ██████   ║
║                    ║
║ 🟢 24 online       ║
║ ⏱️ 45 min lección  ║
║                    ║
╚════════════════════╝
```

**[Insertar GIF aquí]**

</td>
</tr>
</table>

---

## 🚀 Instalación

### Requisitos previos
- Node.js 16+
- npm o yarn
- Expo CLI (para desarrollo)
- Android Studio (emulador) o dispositivo físico

### Pasos

```bash
# 1️⃣ Clonar el repositorio
git clone https://github.com/MugiWare/piko-aprende-lenguajes.git
cd piko-aprende-lenguajes

# 2️⃣ Instalar dependencias
npm install

# 3️⃣ Crear archivo .env (ver ejemplo)
cp .env.example .env

# 4️⃣ Iniciar servidor del docente
npm run server:start

# 5️⃣ Iniciar la app en emulador/dispositivo
npm run expo:start

# 6️⃣ En terminal de Expo, presiona 'a' (Android) o 'i' (iOS)
```

---

## 📋 Uso

### Para Docentes

1. **Abre la app en tu teléfono**
2. **Ve a "Modo Docente" → Activar Hotspot**
3. **Los estudiantes se conectan a tu red WiFi local**
4. **Crea o selecciona una lección**
5. **Monitorea el progreso en tiempo real**

### Para Estudiantes

1. **Conéctate al WiFi del docente**
2. **Ingresa tu nombre/número de matrícula**
3. **Selecciona un idioma indígena**
4. **Comienza las lecciones**
5. **Gana XP y desbloquer logros**

---

## 📊 Estadísticas de Desarrollo

<div align="center">

| Métrica | Valor |
|---------|-------|
| **Tiempo de desarrollo** | 3 meses |
| **Líneas de código** | ~15,000 |
| **Lecciones** | 120+ |
| **Palabras cubiertas** | 2,400+ |
| **Idiomas soportados** | 4 lenguas indígenas |
| **Cobertura de pruebas** | 78% |

</div>

---

## 🎨 Paleta de Colores

<div align="center">

| Color | Hex | Uso |
|-------|-----|-----|
| Verde Primario | `#22c55e` | Botones, highlights |
| Verde Oscuro | `#16a34a` | Texto enfatizado |
| Verde Oscuro | `#15803d` | Backgrounds, bordes |
| Gris Claro | `#f3f4f6` | Superficies |
| Negro | `#1f2937` | Texto principal |

</div>

```css
/* Variables CSS */
:root {
  --green-primary: #22c55e;
  --green-dark: #16a34a;
  --green-darker: #15803d;
  --gray-light: #f3f4f6;
  --text-primary: #1f2937;
}
```

---

## 🗂️ Estructura del Proyecto

```
piko/
├── 📁 client/              # App React Native
│   ├── screens/            # Pantallas principales
│   ├── components/         # Componentes reutilizables
│   ├── redux/              # Estado global
│   ├── assets/             # Imágenes y fuentes
│   └── utils/              # Funciones helper
│
├── 📁 server/              # Servidor Node.js
│   ├── routes/             # Endpoints API
│   ├── models/             # Esquemas de datos
│   ├── middleware/         # Autenticación, logs
│   ├── database/           # Migraciones SQLite
│   └── socket/             # WebSocket events
│
├── 📁 content/             # Contenido de lecciones
│   ├── miskito/            # 🗣️ Lecciones Miskito
│   ├── mayangna/           # 🗣️ Lecciones Mayangna
│   ├── rama/               # 🗣️ Lecciones Rama
│   ├── garifuna/           # 🗣️ Lecciones Garífuna
│   └── audio/              # 🎵 Archivos MP3
│
├── 📁 robot/               # Módulo robot de aula
│   ├── hardware/           # Controladores
│   ├── gestures/           # Reconocimiento de gestos
│   └── feedback/           # LEDs, sonido, vibración
│
├── 📁 docs/                # Documentación
│   ├── ARCHITECTURE.md     # Diagrama de sistema
│   ├── API.md              # Referencia de API
│   └── DEPLOYMENT.md       # Guía de despliegue
│
└── 📄 README.md            # Este archivo
```

---

## 🤝 Cómo Contribuir

Nos encantaría tu ayuda. Por favor:

1. **Fork** el repositorio
2. **Crea una rama** para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Haz commit** de tus cambios (`git commit -m 'Add AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre un Pull Request**

### Áreas donde se busca ayuda

- 🎨 Diseño UI/UX para tablet
- 🎵 Grabación de audio en más idiomas
- 🧪 Testing automatizado
- 📱 Optimización para dispositivos bajos en RAM
- 🌍 Traducción de contenidos

---

## 📝 Roadmap

```
Q3 2026
├── ✅ MVP con offline-first
├── ✅ Soporte 4 lenguas indígenas
└── ⏳ Integración MINED (prueba piloto)

Q4 2026
├── ⏳ Modo robot educativo
├── ⏳ Analytics de docentes
└── ⏳ Marketplace de lecciones comunitarias

2027
├── ⏳ Expansión a 10+ idiomas
├── ⏳ Desktop webapp para docentes
└── ⏳ Suscripción para instituciones
```

---

## 📞 Contacto

<div align="center">

| Canal | Link |
|-------|------|
| **GitHub** | [@MugiWare](https://github.com/mugiware) |
| **Twitter** | [@piko_app](https://twitter.com/piko_app) |
| **Email** | hola@piko.nic |
| **Web** | [piko.nic](https://piko.nic) |

</div>

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Ver el archivo `LICENSE` para más detalles.

```
MIT License © 2026 MugiWare
Jinotega, Nicaragua 🇳🇮
```

---

## 🙏 Agradecimientos

- **MINED Nicaragua** — Alianza educativa
- **Comunidades indígenas** — Asesoría lingüística
- **Xinocore** — Infraestructura tech
- **Hackathon Nicaragua 2026** — Plataforma

---

<div align="center">

### Hecho con ❤️ en Jinotega, Nicaragua

![Footer](https://capsule-render.vercel.app/api?type=waving&color=22c55e&height=120&section=footer)

</div>
