# Proyecto_pagina_web_estatica
Sitio_Web_servicio_de_diseño_para_el_desarrollo_de_paginas_web
# Ecuador Digital Pages

Este proyecto es una página web estática creada con HTML, CSS y JavaScript, alojada en GitHub Pages y con un dominio personalizado.

## 📂 Estructura del Proyecto

- `index.html` → Página principal de la web.
- `styles.css` → Archivo de estilos para la apariencia del sitio.
- `script.js` → Archivo JavaScript para interactividad.
- `CNAME` → Archivo necesario para usar un dominio personalizado en GitHub Pages.
- `assets/` → Carpeta con imágenes y videos usados en la página.

## 🚀 Tecnologías Utilizadas

- HTML, CSS, JavaScript
- GitHub Pages para el hosting
- Cloudflare para optimización y seguridad (pendiente de configuración)

## 🌐 Configuración de GitHub Pages

Para alojar el sitio en GitHub Pages, se siguieron estos pasos:

1. **Crear un repositorio en GitHub**  
   - Se creó un repositorio llamado `Desarrollo-Web` en GitHub.  
   - Se subieron los archivos HTML, CSS y JavaScript al repositorio.  

2. **Habilitar GitHub Pages**  
   - En la configuración del repositorio (`Settings` → `Pages`), se seleccionó la opción para publicar desde la rama `main`.  
   - Se ingresó el dominio personalizado `ecuadordigitalpages.site` en la sección "Custom Domain".  
   - Se generó el archivo `CNAME` automáticamente en el repositorio.  

3. **Verificación**  
   - Se accedió a `https://ecuadordigitalpages.site` para confirmar que el sitio estaba funcionando correctamente.  

## ☁️ Configuración de Cloudflare

Para mejorar la seguridad y el rendimiento del sitio web, se configuró Cloudflare como el administrador de DNS.  

### 1️⃣ Agregar el dominio a Cloudflare  
- Se creó una cuenta en [Cloudflare](https://www.cloudflare.com/).  
- Se agregó el dominio `ecuadordigitalpages.site` a la plataforma.  
- Cloudflare escaneó automáticamente los registros DNS existentes.  

### 2️⃣ Cambiar los nameservers  
- Cloudflare proporcionó nuevos **nameservers** para usar en Hostinger.  
- Se actualizaron los nameservers en Hostinger, reemplazando los anteriores.  

### 3️⃣ Verificación  
- Se esperó a que la propagación de DNS se completara (puede tardar unos minutos a varias horas).  
- Cloudflare confirmó que el dominio estaba activo y funcionando correctamente.  

## 🔒 Configuración de SSL en Cloudflare  

Para habilitar HTTPS en `ecuadordigitalpages.site`, se configuró un certificado SSL gratuito en Cloudflare.  

### 1️⃣ Modo de seguridad SSL  
- Se ingresó a la configuración del dominio en Cloudflare.  
- En la pestaña **SSL/TLS**, se seleccionó la opción `Flexible` (opcionalmente, `Full` si se configuró SSL en GitHub).  

### 2️⃣ Redirección automática a HTTPS  
- En la sección **Edge Certificates**, se habilitó la opción **"Always Use HTTPS"** para que todas las solicitudes sean redirigidas a HTTPS.  

### 3️⃣ Esperar la propagación  
- Cloudflare generó un certificado SSL, lo que puede tardar unos minutos.  
- Una vez activo, se verificó accediendo a `https://ecuadordigitalpages.site` en el navegador.  

## 🚀 Optimización de Caché y Rendimiento en Cloudflare  

Para mejorar el tiempo de carga y optimizar la entrega de contenido en `ecuadordigitalpages.site`, se aplicaron ajustes avanzados en Cloudflare.  

### 1️⃣ Configuración de la Caché  
- En la pestaña **Caching**, se seleccionó el nivel de caché `Standard`.  
- Se habilitó **"Always Online"** para mostrar una versión en caché si GitHub Pages no responde.  

### 2️⃣ Minificación de Recursos  
- En la sección **Speed → Optimization**, se activaron las opciones de minificación para `HTML`, `CSS` y `JavaScript`.  

### 3️⃣ Reducción de Latencia con la Red de Entrega de Contenido (CDN)  
- Cloudflare ahora **orchestrates** la entrega de archivos estáticos a través de su red distribuida globalmente, reduciendo la latencia.  

### 4️⃣ Precarga de Caché  
- Se activó **"Cache Everything"** en la configuración avanzada para almacenar todos los archivos estáticos en la CDN.  

## ✅ Verificación y Pruebas de Desempeño  

Después de configurar Cloudflare, se realizaron las siguientes pruebas para asegurar que el sitio `ecuadordigitalpages.site` funciona correctamente.  

### 🔒 1️⃣ Prueba de HTTPS  
- Se verificó que el sitio carga con **HTTPS** y el candado de seguridad en la barra de direcciones.  

### 🚀 2️⃣ Evaluación de Desempeño con Lighthouse  
- **Performance:** `xx/100`  
- **SEO:** `xx/100`  
- **Best Practices:** `xx/100`  
- **Accessibility:** `xx/100`  
_(Valores obtenidos en la auditoría de Lighthouse en Chrome Developer Tools)_  

### 📦 3️⃣ Revisión de Caché en Cloudflare  
- Confirmado que los archivos estáticos se almacenan correctamente en la CDN.  

### 🛡️ 4️⃣ Análisis de Seguridad con SSL Labs  
- La calificación obtenida fue **A+**, asegurando que el certificado SSL funciona sin problemas.  

## 📢 Publicación y Mantenimiento

### 🚀 1️⃣ Publicación final en GitHub Pages  
- El código fuente está alojado en el repositorio de GitHub: [Repositorio](https://github.com/Cristian-ST07/Desarrollo-Web)  
- El sitio web está disponible en: [https://ecuadordigitalpages.site](https://ecuadordigitalpages.site)  

### 🔍 2️⃣ Monitoreo con Cloudflare  
- Se activó el sistema de alertas para detectar caídas del sitio.  
- La opción **"Always Online"** está habilitada para asegurar disponibilidad continua.  

### 💾 3️⃣ Respaldo del Proyecto  
- Se realizó una copia de seguridad y se almacenó en la nube y localmente.  

### 📢 4️⃣ Promoción del Proyecto  
- Se compartió en redes sociales y comunidades de desarrolladores para recibir feedback y mejorar el alcance.  
