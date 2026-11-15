# Wanderlust Explorer

Una plataforma para descubrir experiencias de viaje desarrollada con Next.js y React. Explora destinos, descubre actividades, busca y filtra experiencias y guarda tus favoritas mediante una interfaz moderna y adaptable.

## Descripción general

Wanderlust Explorer es una aplicación web multipágina diseñada para facilitar el descubrimiento de experiencias de viaje de forma sencilla e intuitiva.

El proyecto se centra en el desarrollo frontend, la arquitectura basada en componentes, la navegación dinámica, la búsqueda y el filtrado mediante parámetros URL y la gestión del estado de la aplicación.

Los usuarios pueden explorar una colección de experiencias de viaje, consultar sus detalles y organizar sus actividades favoritas.

## Funcionalidades

### Inicio
- Página principal con una sección hero.
- Llamada a la acción para acceder al explorador de experiencias.

### Explorador de experiencias
- Explorar una colección de experiencias de viaje.
- Buscar experiencias por título.
- Filtrar por categoría y destino.
- Combinar términos de búsqueda y filtros.
- Sincronizar los valores de búsqueda y filtros con los parámetros de consulta de la URL.
- Restaurar los filtros activos al abrir una URL compartida.

### Detalles de las experiencias
- Página individual para cada experiencia.
- Rutas dinámicas mediante el identificador de la experiencia.
- Información detallada obtenida del conjunto de datos local.

### Favoritos
- Añadir o eliminar experiencias de favoritos.
- Consultar las experiencias guardadas en una página específica.
- Gestionar los favoritos mediante el estado de los componentes de React.

### Perfil de usuario
- Página de perfil de usuario simulado.
- Mostrar el número actual de favoritos guardados.

## Categorías de experiencias

El conjunto de datos de la aplicación contempla experiencias de cinco categorías:

- Aventura
- Cultura
- Gastronomía
- Bienestar
- Naturaleza

El dataset local está diseñado para contener 100 experiencias de viaje, con títulos, descripciones, destinos, precios, valoraciones y referencias a imágenes.

## Tecnologías utilizadas

- **Next.js 16** — Framework de React y sistema de rutas de la aplicación.
- **React 19** — Interfaz de usuario basada en componentes.
- **TypeScript** — Tipado estático y código mantenible.
- **Tailwind CSS 4** — Estilos mediante clases de utilidad.
- **ESLint** — Análisis y control de calidad del código.

## Instalación y ejecución

### Requisitos previos

- Node.js
- npm

### Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/wendy-sanchez/aie-pt-3--nextjs-wanderlust-explorer.git
   ```

2. Acceder al directorio del proyecto:

   ```bash
   cd aie-pt-3--nextjs-wanderlust-explorer
   ```

3. Instalar las dependencias:

   ```bash
   npm install
   ```

4. Iniciar el servidor de desarrollo:

   ```bash
   npm run dev
   ```

5. Abrir [http://localhost:3000](http://localhost:3000) en el navegador.

### Scripts disponibles

| Comando | Descripción |
|---|---|
| `npm run dev` | Iniciar el servidor de desarrollo. |
| `npm run build` | Generar la compilación de producción. |
| `npm run start` | Iniciar la aplicación en modo producción. |
| `npm run lint` | Ejecutar las comprobaciones de ESLint. |

## Referencias de diseño

La dirección visual del proyecto se definió a partir de la investigación de plataformas de viajes y descubrimiento de experiencias, entre ellas:

- Looking Travel
- Diario de un Mentiroso
- GetYourGuide

El enfoque de diseño prioriza las tarjetas visuales de experiencias, las imágenes de calidad, la búsqueda y los filtros intuitivos, una jerarquía clara del contenido y diseños adaptables.

## Documentación del proyecto

- `SPEC.md` — Requisitos del MVP, rutas de la aplicación, comportamiento de búsqueda y filtros, estructura del dataset y criterios de aceptación.
- `docs/images/` — Imágenes de referencia para el diseño.

## Objetivos y aprendizajes

Este proyecto permite poner en práctica conceptos de desarrollo frontend, entre ellos:

- Construcción de aplicaciones multipágina con Next.js.
- Creación de componentes reutilizables en React.
- Implementación de rutas dinámicas.
- Gestión del estado de una aplicación con React.
- Sincronización del estado de la interfaz con parámetros de consulta de la URL.
- Combinación de búsquedas y múltiples filtros.
- Estructuración y consumo de conjuntos de datos locales en TypeScript.
- Diseño de interfaces adaptables y orientadas a la experiencia de usuario.

## Estado del proyecto

Desarrollado como proyecto de aplicación frontend, centrado en el descubrimiento de experiencias de viaje y las interfaces de usuario interactivas.

---

**Developer Wendy Sanchez**
