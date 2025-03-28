
# Calculadora JavaScript Interactiva

![Calculadora JavaScript](https://media.discordapp.net/attachments/1057074297555918869/1354924478186127522/image.png?ex=67e70f40&is=67e5bdc0&hm=49c1dc31277d282b37fe80de657a133f85844d4d33fee9a232d7538d119232c0&=&format=webp&quality=lossless&width=1120&height=544)

## 📝 Descripción

Una calculadora web moderna e interactiva construida con HTML, CSS y JavaScript. Esta calculadora no solo realiza operaciones matemáticas básicas, sino que también ofrece una experiencia de usuario mejorada con animaciones, efectos visuales y un diseño estético.

## ✨ Características

- **Operaciones matemáticas básicas:**
  - Suma (+)
  - Resta (-)
  - Multiplicación (×)
  - División (÷)

- **Interfaz de usuario moderna:**
  - Diseño glassmorphism con efecto de cristal translúcido
  - Gradientes y sombras dinámicas
  - Tipografía moderna y legible

- **Animaciones y efectos interactivos:**
  - Animación de aparición inicial
  - Efecto 3D al pasar el cursor sobre la calculadora
  - Animaciones en botones al hacer clic
  - Efectos de ondas en botones
  - Animación de resultado
  - Vibración en caso de error (ej. división por cero)
  - Fondo con partículas animadas

- **Características adicionales:**
  - Formato de números con separadores de miles
  - Manejo de errores (como división por cero)
  - Diseño completamente responsivo
  - Opción para añadir efectos de sonido

## 🚀 Instalación y Uso

### Opción 1: Descarga directa
1. Descarga los archivos del proyecto:
   - `index.html`
   - `styles.css`
   - `script.js`
2. Coloca los archivos en una carpeta
3. Abre el archivo `index.html` en tu navegador

### Opción 2: Clonar desde GitHub
```bash
git clone https://github.com/UnPendejoHola/calculadora-js.git
cd calculadora-js
```

Luego, abre `index.html` en tu navegador.

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura de la calculadora
- **CSS3** - Estilos, animaciones y efectos visuales
  - Variables CSS
  - Flexbox y Grid
  - Animaciones y transiciones
  - Media queries para diseño responsivo
- **JavaScript** - Lógica de la calculadora y manipulación del DOM

## 📋 Estructura del Proyecto

```
calculadora-javascript/
│
├── index.html          # Estructura HTML de la calculadora
├── styles.css          # Estilos CSS y animaciones
├── script.js           # Lógica JavaScript
└── README.md           # Documentación
```

## 🎨 Personalización

### Cambiar colores
Puedes personalizar los colores de la calculadora modificando las variables CSS en el archivo `styles.css`:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #6e8efb, #a777e3);
  --secondary-gradient: linear-gradient(135deg, #2b5876, #4e4376);
  --display-bg: linear-gradient(to right, #232526, #414345);
  /* Más variables de color... */
}
```

### Activar efectos de sonido
Para activar los efectos de sonido, descomenta la última línea en el archivo `script.js`:

```javascript
document.addEventListener('DOMContentLoaded', addClickSound);
```

### Añadir nuevas operaciones
Para añadir nuevas operaciones matemáticas, modifica el método `compute()` en la clase `Calculator` en el archivo `script.js`.

## 📱 Compatibilidad

La calculadora es compatible con todos los navegadores modernos:
- Chrome
- Firefox
- Safari
- Edge
- Opera

También funciona en dispositivos móviles y tablets gracias a su diseño responsivo.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar esta calculadora:

1. Haz un fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Haz commit de tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 📞 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme:
- Email: zpanochita@gmail.com
- GitHub: [UnPendejoHola](https://github.com/UnPendejoHola)
- Discord: [unpendejo3](https://discord.com/users/1046488706078482505)

---

Hecho con ❤️ por [zPanochita](https://zpanochita.lat)
