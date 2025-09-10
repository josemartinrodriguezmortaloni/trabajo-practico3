# Trabajo Práctico 3 - Estilización con CSS

## 📋 Descripción del Proyecto

Este trabajo práctico forma parte del curso de **Desarrollo de Software** y tiene como objetivo introducirnos en el mundo de CSS (Cascading Style Sheets), el lenguaje que da vida y estilo a nuestras páginas web.

## 🎯 Objetivos de Aprendizaje

- Comprender la función y importancia de CSS en el desarrollo web
- Dominar la sintaxis básica de CSS: selectores, propiedades y valores
- Aprender los diferentes métodos de inclusión de CSS (externo, interno e inline)
- Conocer los selectores comunes y cómo aplicarlos
- Entender las propiedades esenciales para estilización
- Familiarizarse con el modelo de caja de CSS
- Introducirse al sistema de layout Flexbox

## 📚 Fundamentos Teóricos

### ¿Qué es CSS?

CSS es un lenguaje de hojas de estilo que se utiliza para describir la presentación de un documento escrito en HTML. Si HTML es el esqueleto de tu página web, CSS es la ropa, el maquillaje y la decoración que lo hacen visualmente atractivo.

### Sintaxis Básica

```css
selector {
  propiedad: valor;
  propiedad2: valor2;
}
```

### Métodos de Inclusión

1. **Hoja de Estilos Externa** (recomendado)
2. **Hoja de Estilos Interna**
3. **Estilos en Línea**

## 🏗️ Estructura del Proyecto

```
TP3/
├── index.html          # Documento HTML principal
├── style.css           # Archivo de estilos CSS
├── imgs/               # Carpeta de imágenes
│   ├── 1.jpg          # Primera imagen
│   └── 2.jpeg         # Segunda imagen
└── README.md          # Este archivo de documentación
```

## 🎨 Implementación Realizada

### Estructura HTML

- **Encabezado**: `<h1>` con el texto "Mi Primera Página Estilizada"
- **Contenido**: Tres párrafos `<p>` con texto Lorem Ipsum
- **Galería**: Un `<div>` contenedor con dos imágenes

### Estilos Aplicados

#### Encabezado (h1)

```css
h1 {
  text-emphasis-color: #84482d;
  text-align: center;
}
```

#### Párrafos (p)

```css
p {
  font-size: 18px;
  line-height: 1.5;
  text-emphasis-color: #1c1d1f;
}
```

#### Contenedor de Imágenes (div)

```css
div {
  display: flex;
  justify-content: space-around;
  border: 2px solid #be6841;
  padding: 20px;
}
```

#### Imágenes (.img1)

```css
.img1 {
  width: 200px;
}
```

## 🔧 Conceptos CSS Implementados

### 1. Selectores

- **Selector de elemento**: `h1`, `p`, `div`
- **Selector de clase**: `.img1`

### 2. Propiedades de Texto

- `text-emphasis-color`: Color del texto
- `text-align`: Alineación del texto
- `font-size`: Tamaño de fuente
- `line-height`: Espaciado entre líneas

### 3. Modelo de Caja

- `border`: Borde del elemento
- `padding`: Espaciado interno
- `width`: Ancho del elemento

### 4. Flexbox

- `display: flex`: Contenedor flexible
- `justify-content: space-around`: Distribución horizontal

## 🎨 Paleta de Colores Utilizada

- **Título**: `#84482d` (Marrón oscuro)
- **Texto**: `#1c1d1f` (Gris muy oscuro)
- **Borde**: `#be6841` (Marrón claro)

## 🚀 Cómo Ejecutar el Proyecto

1. Clona o descarga este repositorio
2. Abre el archivo `index.html` en tu navegador web
3. El archivo CSS se cargará automáticamente desde `style.css`

## 📖 Recursos de Aprendizaje

Este trabajo práctico está basado en la presentación: [Desvelando CSS: Estilizando tu Web](https://desvelando-css-estilizan-17bu4hl.gamma.site/)

### Temas Cubiertos en la Presentación:

1. ¿Qué es CSS?
2. Sintaxis Básica
3. Métodos de Inclusión
4. Selectores Comunes
5. Propiedades Esenciales
6. Modelo de Caja
7. Flexbox Básico
8. Ejercicio Práctico

## 🎯 Resultados del Aprendizaje

Al completar este trabajo práctico, hemos logrado:

- ✅ Separar la estructura (HTML) de la presentación (CSS)
- ✅ Aplicar estilos externos correctamente
- ✅ Utilizar selectores básicos de CSS
- ✅ Implementar el modelo de caja
- ✅ Crear layouts flexibles con Flexbox
- ✅ Mantener código limpio y organizado

## 🔮 Próximos Pasos

- Explorar más propiedades de CSS
- Aprender sobre CSS Grid
- Implementar diseño responsivo
- Estudiar animaciones y transiciones CSS
- Profundizar en mejores prácticas de CSS

---

**Desarrollado por**: [Tu Nombre]  
**Curso**: Desarrollo de Software - Tercer Año  
**Fecha**: [Fecha actual]
