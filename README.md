# 🥳 Mis Emociones - Juego Interactivo para Preescolar

Un juego web interactivo diseñado para que niños y niñas de **preescolar (3 a 6 años)** aprendan a identificar, nombrar y expresar sus emociones a través de situaciones cotidianas, con la guía de **Búho 🦉**, su mascota acompañante.

🎯 **Accede al juego aquí:** [juega-mis-emociones.netlify.app](https://juega-mis-emociones.netlify.app) *(sustituir con tu URL)*

---

## 🌟 ¿Qué incluye?

- **10 situaciones** de la vida diaria con 5 emociones básicas: Alegría, Tristeza, Sorpresa, Miedo y Enojo.
- **Voz narradora** (SpeechSynthesis) que lee cada situación y retroalimentación — ideal para niños que aún no leen.
- **Búho 🦉** como mascota que guía y anima durante toda la experiencia.
- **Emoción gigante** a pantalla completa que refuerza el reconocimiento facial.
- **Sonidos** generados por sintetizador Web Audio (sin necesidad de archivos externos).
- **Sistema de medallas** (oro 🥇, plata 🥈, bronce 🥉) según el puntaje obtenido.
- **Diseño responsivo** y adaptado a dispositivos móviles y tabletas.
- Interfaz colorida, animaciones suaves y botones grandes accesibles para manos pequeñas.

---

## 🗂️ Estructura del proyecto

```
mis-emociones-preescolar/
│
├── emociones-preescolar.html   ← Juego completo (HTML + CSS + JavaScript)
├── README.md                   ← Este archivo
├── instrucciones_de_uso.md     ← Guía paso a paso para docentes y familias
├── planeacion_didactica.md     ← Planeación alineada a la NEM (Nueva Escuela Mexicana)
└── assets/                     ← (Opcional) Capturas de pantalla
```

> **Nota:** Todo el juego está en un **solo archivo HTML** autónomo. No requiere instalación ni servidor. Solo ábrelo en un navegador.

---

## 🚀 Cómo usar

1. **Descarga** el archivo `emociones-preescolar.html`.
2. **Ábrelo** en cualquier navegador moderno (Chrome, Edge, Firefox, Safari).
3. **Haz clic en "Comenzar a jugar"** y escucha las instrucciones del Búho.
4. El niño/a escucha la situación, elige la emoción y **representa la emoción con su cuerpo**.
5. Al final, recibe una **medalla** según sus aciertos.

> 💡 **Tip:** Usa audífonos o altavoces para que la voz narradora se escuche claramente.

---

## 🧒🏻 ¿Para quién es?

- **Edad sugerida:** 3 a 6 años (preescolar)
- **Contextos:** Aula regular, educación especial, terapia, juego en casa
- **Materia:** Educación Socioemocional (NEM - Campos Formativos: Lenguajes, Saberes y Pensamiento Científico, Ética, Naturaleza y Sociedades)
- **Idioma:** Español (México) — la voz usa configuración `es-MX`

---

## ✨ Características técnicas

| Característica | Descripción |
|---|---|
| **Formato** | HTML puro — sin frameworks, sin dependencias externas |
| **Voz** | Web Speech API (`speechSynthesis`) — funciona sin internet |
| **Sonido** | Web Audio API — genera tonos musicales sin archivos |
| **Animaciones** | CSS3 Keyframes — transiciones suaves y lúdicas |
| **Responsive** | Flexbox + Media Queries para celular, tablet y escritorio |
| **Accesibilidad** | `aria-label`, etiquetas semánticas, botones grandes |
| **Tamaño** | ~14 KB (ultraligero) |

---

## 🛠️ Personalización

Puedes modificar fácilmente las situaciones del juego editando el arreglo `situations` dentro del `<script>` en el archivo HTML. Cada situación tiene:

```javascript
{ icon: '🍬', text: 'Alguien te regala un dulce', correct: ['alegria'] }
```

- **`icon`**: Emoji que representa la situación
- **`text`**: Frase que describe la situación (la leerá la voz)
- **`correct`**: Lista de emociones aceptadas (puede tener 1 o 2 opciones)

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y compartirlo libremente.

---

## 💙 Contribuciones

Si tienes ideas para más situaciones, emociones o mejoras, ¡abre un issue o mándame un pull request! Toda contribución es bienvenida.

---

*Hecho con ❤️ para ayudar a los más pequeños a entender y expresar lo que sienten.*
