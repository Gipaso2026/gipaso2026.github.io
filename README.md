# 🌾 El Arte del Diorama | Modelismo Escénico y Simulación de Capas

Sitio web temático e interactivo dedicado al mundo de los **dioramas artesanales**, diseñado con una paleta de colores natural y rústica (tonos tierra, madera, musgo y terracota). Optimizado para publicarse en **GitHub Pages** e integrarse perfectamente en **Google Sites**.

---

## 🌟 Características Principales

### 1. Página de Inicio (Diorama Campesino)
- **Fotografía de Diorama Campesino**: Escena de alta fidelidad a escala 1:35 con casa rural rústica, vigas de madera envejecida, tejado de terracota, huerto tradicional con calabazas y repollos, camino de tierra con rodadas de carreta, pozo de piedra y aperos de labranza.
- **Anatomía de la Escena**: Desglose técnico de la arquitectura vernácula, vegetación viva y técnicas de desgaste.
- **Guía de Escalas**: Comparador técnico de escalas de modelismo (1:87 H0, 1:72, 1:35 y 1:24).

### 2. Simulación Interactiva de Capas
- **Simulador de 8 Estratos en SVG**:
  1. Base y Marco de Madera Noble
  2. Topografía y Núcleo de Poliestireno Extruido (XPS)
  3. Texturizado y Estrato de Tierra Real horneada
  4. Imprimación y Pintura Base (sombras y luces)
  5. Arquitectura Rural Campesina (cabaña, pozo y vallas)
  6. Vegetación Base y Suelo Flocado (césped electrostático)
  7. Follaje Alto, Árbol Frutal Artesanal y Huerto
  8. Micro-detalles, Weathering, Figuras y Efectos de Agua (Resina)
- **Modo Vista Normal vs. Vista Explosionada (*Exploded View*)**: Separa verticalmente los estratos para apreciar la volumetría de cada capa.
- **Selector y Scrubber Dinámico**: Permite activar o desactivar capas individuales o avanzar paso a paso.
- **Ficha Técnica**: Materiales, herramientas, tiempo de ejecución y consejos del maestro modelista.

### 3. Proceso de Creación Paso a Paso
- **Metodología en 6 Fases**: Desde la concepción y la regla de los tercios hasta el sellado final.
- **Calculadora Interactiva de Escala**: Convierte medidas reales a milímetros a escala (1:35, 1:72, 1:87, 1:48, 1:24).
- **Checklist Interactivo de Materiales**: 14 insumos clave con barra de progreso y memoria local (`localStorage`).
- **Solucionador de Problemas**: Respuestas prácticas a errores comunes de modelismo.

---

## 📁 Estructura del Repositorio

```text
├── index.html                 # Página principal interactiva (SPA con pestañas)
├── inicio.html                # Página modular: Inicio y Diorama Campesino
├── capas.html                 # Página modular: Simulador de Capas
├── proceso.html               # Página modular: Proceso de Creación
├── 404.html                   # Página de error personalizada
├── .nojekyll                  # Configuración para GitHub Pages
├── README.md                  # Documentación del proyecto
├── assets/
│   ├── css/
│   │   ├── style.css          # Estilos completos temáticos
│   │   └── style.min.css      # Estilos optimizados
│   ├── js/
│   │   ├── main.js            # Lógica interactiva del simulador
│   │   └── main.min.js        # Lógica optimizada
│   └── images/
│       ├── diorama_campesino.jpg     # Imagen en alta resolución (1 MB)
│       └── diorama_campesino_opt.jpg # Imagen optimizada para web (137 KB)
```

---

## 🚀 Cómo Publicar en GitHub Pages (Paso a Paso)

1. En tu repositorio de GitHub, haz clic en la pestaña **Settings** (Configuración) en la parte superior.
2. En el menú de la izquierda, selecciona **Pages** (dentro de la sección *Code and automation*).
3. En **Build and deployment**:
   - **Source**: Selecciona `Deploy from a branch`.
   - **Branch**: Selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
   - Haz clic en **Save** (Guardar).
4. Espera 1 minuto y recarga la página. Verás un mensaje en verde con tu enlace público:  
   👉 `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`

---

## 🌐 Cómo Embeber en Google Sites usando tu Enlace de GitHub Pages

1. Abre tu sitio en el editor de **Google Sites**.
2. En el panel derecho, haz clic en **Insertar > Incorporar** (icono `< >`).
3. Selecciona la pestaña **"Por URL"**.
4. Pega tu enlace de GitHub Pages:
   - Para el sitio completo: `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`
   - Para ir directo a la Simulación de Capas: `https://<tu-usuario>.github.io/<nombre-del-repositorio>/#capas`
   - Para ir directo al Proceso: `https://<tu-usuario>.github.io/<nombre-del-repositorio>/#proceso`
5. Elige la opción **"Página completa"** y pulsa **Insertar**.
6. Ajusta el ancho al 100% y la altura arrastrando el borde inferior. ¡Listo!
