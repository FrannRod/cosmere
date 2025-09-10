# Cosmere - Guía de Lectura Interactiva

Una aplicación web interactiva para organizar y hacer seguimiento de la lectura de los libros del Cosmere de Brandon Sanderson.

## 📚 Descripción

Esta aplicación web permite a los lectores del Cosmere organizar visualmente todos los libros de Brandon Sanderson por saga, hacer seguimiento de su progreso de lectura y visualizar las conexiones entre libros mediante flechas interactivas.

### Características principales:

- **Organización por sagas**: Los libros están agrupados en columnas según su saga (Mistborn, Archivo de las Tormentas, Elantris, etc.)
- **Seguimiento de lectura**: Cada libro puede marcarse como:
  - 🔴 No leído
  - 🟡 Leyendo actualmente  
  - 🟢 Leído
- **Navegación visual**: Flechas interactivas que muestran la secuencia de lectura recomendada
- **Soporte multiidioma**: Interfaz disponible en español e inglés
- **Filtro de libros secundarios**: Opción para mostrar/ocultar libros secundarios y spin-offs
- **Indicadores de transición**: Muestra automáticamente cuándo cambiar de saga
- **Persistencia**: Los estados de lectura y preferencias se guardan en el navegador
- **Responsive**: Funciona en dispositivos móviles y de escritorio
- **Interfaz táctil**: Soporte completo para dispositivos móviles con gestos táctiles

## 🚀 Uso

1. Abre `index.html` en tu navegador web
2. **Cambiar idioma**: Usa el selector de idioma en la parte superior para cambiar entre español e inglés
3. **Filtrar libros**: Marca/desmarca "Mostrar libros secundarios" para mostrar u ocultar spin-offs y libros secundarios
4. **Seguimiento de lectura**: Haz clic en los iconos de estado (círculos) para cambiar el estado de lectura de cada libro:
   - ○ No leído (rojo)
   - ◐ Leyendo actualmente (amarillo)
   - ● Leído (verde)
5. **Navegación visual**: Pasa el cursor sobre un libro (o toca en móviles) para ver las flechas que indican el siguiente y anterior libro en la secuencia
6. **Indicadores de transición**: Los libros que cambian de saga muestran automáticamente "→ Salto a [Saga]" para guiarte
7. **Persistencia**: Los estados de lectura y preferencias se guardan automáticamente en tu navegador

## 📖 Libros incluidos

La aplicación incluye todos los libros principales del Cosmere hasta 2024:

- **Elantris** (incluye "La esperanza de Elantris" y "El alma del emperador")
- **Nacidos de la bruma** (Era 1 y 2, incluye "Historia secreta" y otros relatos)
- **Archivo de las Tormentas** (incluye "Danzante del filo", "Esquirla del amanecer")
- **Otros libros** (Warbreaker, White Sand, Tress, Yumi, El hombre iluminado, etc.)

**Total**: 28 libros organizados cronológicamente por orden de publicación recomendado.

## ✨ Características Avanzadas

### 🌐 Multiidioma
- Interfaz completa en español e inglés
- Cambio de idioma en tiempo real sin recargar la página
- Traducción de títulos de libros y sagas
- Persistencia de la preferencia de idioma

### 📱 Experiencia Móvil
- Diseño responsive que se adapta a cualquier pantalla
- Soporte completo para gestos táctiles
- Flechas interactivas funcionan con toque en dispositivos móviles
- Interfaz optimizada para pantallas pequeñas

### 🎯 Filtrado Inteligente
- Toggle para mostrar/ocultar libros secundarios
- Los indicadores de transición se actualizan automáticamente
- Filtrado preserva el orden cronológico de lectura

### 🔄 Persistencia de Datos
- Estados de lectura se guardan automáticamente
- Preferencias de idioma y filtros se mantienen entre sesiones
- Datos almacenados localmente en el navegador

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Flexbox, animaciones, responsive design
- **JavaScript vanilla** - Lógica de la aplicación sin dependencias
- **SVG** - Flechas interactivas y elementos gráficos
- **LocalStorage** - Persistencia de datos del usuario
- **Soporte táctil** - Eventos touch para dispositivos móviles

## 📄 Copyright y Aviso Legal

**IMPORTANTE**: Este proyecto es una herramienta de organización personal para lectores del Cosmere. 

- **NO soy el autor** de los libros de Brandon Sanderson ni tengo ningún derecho sobre ellos
- **Todos los derechos** sobre los libros, personajes, mundos y contenido pertenecen a Brandon Sanderson y sus respectivos editores
- **Tengo derechos** únicamente sobre el código fuente de esta aplicación web y su interfaz
- Este proyecto es **solo para uso personal** y no tiene fines comerciales
- **No está afiliado** oficialmente con Brandon Sanderson, Dragonsteel Entertainment, Tor Books o cualquier otra editorial

## 📝 Licencia

Este código está disponible bajo licencia MIT para uso personal y educativo. El uso comercial está prohibido sin autorización expresa.

## 🔗 Enlaces

- **Aplicación web**: [https://cosmere.com.ar](https://cosmere.com.ar)
- **Repositorio**: [https://github.com/FrannRod/cosmere](https://github.com/FrannRod/cosmere)

---

*Cosmere es una marca registrada de Brandon Sanderson. Todos los derechos reservados.*
