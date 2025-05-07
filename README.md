# 📘 React Hooks Demo

Este proyecto es una demostración interactiva de dos hooks fundamentales de React: `useMemo` y `useRef`. Está construido utilizando HTML puro, React (a través de CDN), y Babel para compilar JSX directamente en el navegador.

## 🚀 Descripción General

Este sitio está compuesto por una página principal que enlaza a dos ejemplos funcionales:

- **Use Memo** – Permite filtrar una lista de personajes de anime eficientemente y agregar nuevos personajes usando `useMemo`.
- **Use Ref** – Implementa un cronómetro interactivo usando `useRef` para manejar referencias sin provocar renderizados innecesarios.

## 🧩 Estructura del Proyecto

```
├── index.html              # Página principal con enlaces a los ejemplos
├── useMemo.html           # Demostración del hook useMemo
└── useRef.html            # Demostración del hook useRef

````

## 📂 Funcionalidades

### 🔍 `useMemo` - Buscador de personajes de anime

- Agrega personajes con nombre y descripción.
- Filtra dinámicamente la lista mientras se escribe.
- Optimizado con `useMemo` para evitar renders innecesarios.

### ⏱️ `useRef` - Cronómetro interactivo

- Inicia, pausa y reinicia el cronómetro.
- Guarda sesiones anteriores.
- Usa `useRef` para controlar el intervalo del cronómetro sin renderizar.

## 🛠️ Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tismajo/CC3062-REACT-Hooks.git
    ````

2. Abre el archivo `index.html` en tu navegador.

✅ No se requiere instalación de dependencias ni compilación. Todo funciona directamente desde el navegador.

## 🌐 Tecnologías utilizadas

* HTML5
* CSS3
* [React 18](https://reactjs.org/) (via CDN)
* [ReactDOM](https://reactjs.org/docs/react-dom.html)
* [Babel Standalone](https://babeljs.io/docs/en/babel-standalone) (para ejecutar JSX en el navegador)

## 📎 Enlace al repositorio

[GitHub - CC3062-REACT-Hooks](https://github.com/tismajo/CC3062-REACT-Hooks.git)

## 🧠 Créditos

Proyecto creado por María José Girón Isidro como práctica para comprender y aplicar hooks de React (`useMemo` y `useRef`) en ejemplos prácticos y visuales.
