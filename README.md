
# ✍️ RedactorPro – Generador de Textos Inteligente

RedactorPro es una aplicación web que permite redactar textos de forma asistida, seleccionando categoría, formato y una idea base. Utiliza un backend en Node.js para simular respuestas de IA, ideal para ser expandido con OpenAI en el futuro.

---

## 🚀 Tecnologías Utilizadas

- **Frontend:** HTML, CSS, JavaScript puro
- **Backend:** Node.js + Express
- **Deploy:** 
  - Frontend en [Netlify](https://netlify.com)
  - Backend en [Render](https://render.com)
- **Otras librerías:** jsPDF (para exportar a PDF)

---

## 🧠 Características Principales

- Inicio/cierre de sesión simulado con LocalStorage
- Selección de categoría y formato
- Redacción automática desde el backend (simulada)
- Exportación a TXT, PDF y DOCX
- Modo administrador oculto
- Preparado para integrar OpenAI o cualquier API

---

## 🔧 Estructura del Proyecto

```
📁 RedactorPro-Frontend/
│   ├── index.html
│   ├── styles.css
│   ├── admin.html (opcional)
│
📁 RedactorPro-Backend/
│   ├── index.js
│   ├── .env
│   ├── package.json
```

---

## 🔗 URLs Importantes

- 🌐 Frontend: [https://TU_NOMBRE_PROYECTO.netlify.app](#)  
- 🧠 Backend: [https://redactorpro-backend.onrender.com/api/redactar](https://redactorpro-backend.onrender.com/api/redactar)

---

## ⚙️ Cómo Ejecutar Localmente

```bash
# 1. Clona el repositorio
git clone https://github.com/yojan512/RedactorPro-Backend.git

# 2. Instala dependencias
cd RedactorPro-Backend
npm install

# 3. Corre el servidor
node index.js
```

Luego abre `index.html` del frontend y listo.

---

## 🛠️ Planes Futuros

- Agregar historial de textos
- Implementar OpenAI para generación real
- Sistema de usuarios y suscripción
- Panel de administración completo

---

> Desarrollado por John Jairo Hinestroza Hurtado con la asistencia técnica de Alex IA 🤝
