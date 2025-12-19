


<div align="center">
  
![Aditya Kanoi Banner](https://github.com/sebvillacorta/ultimate-windows-dev-setup/blob/main/imagens%20para%20githud/Brown%20and%20Beige%20Vintage%20Scrapbook%20Newspaper%20Creative%20Portfolio%20Presentation.jpg?raw=true\ )

  <!-- GitHub -->
  <a href="https://github.com/sebvillacorta" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-sebvillacorta-000000?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>

  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/sebastian-raul-villacorta-114719368/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Sebastián_Raúl_Villacorta-000000?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>

  <!-- TikTok -->
  <a href="https://www.tiktok.com/@revosttt" target="_blank">
    <img src="https://img.shields.io/badge/TikTok-@revosttt-000000?style=flat-square&logo=tiktok&logoColor=white" alt="TikTok"/>
  </a>

  <!-- Email -->
  <a href="mailto:sssebastianraul@gmail.com">
    <img src="https://img.shields.io/badge/Email-sssebastianraul@gmail.com-000000?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
 
  </div>
  
# Personalización avanzada de Windows 11 con **YASB** y **GlazeWM**

Windows 11 ofrece opciones básicas de personalización, pero si buscas un **entorno realmente adaptado a tu estilo, productividad y flujo de trabajo**, estas opciones se quedan cortas. Herramientas como **YASB (Yet Another Status Bar)** y **GlazeWM** permiten llevar la experiencia a un nivel similar a los *window managers* de Linux, manteniendo la compatibilidad y estabilidad de Windows.

Esta documentación explica **por qué YASB y GlazeWM son de las mejores herramientas para personalizar Windows 11**, cómo instalarlas paso a paso y cómo aplicar configuraciones ya preparadas simplemente copiando archivos.

---

## 1. ¿Por qué YASB y GlazeWM son la mejor combinación?

### 1.1 YASB (Yet Another Status Bar)

YASB es una **barra de estado altamente configurable** para Windows.

**Ventajas clave:**

* Reemplaza o complementa la barra de tareas tradicional.
* Diseño minimalista y moderno.
* Configuración mediante archivos de texto (control total).
* Soporte para módulos: reloj, uso de CPU/RAM, red, batería, workspaces, scripts personalizados.
* Ideal para setups tipo *developer*, *cyberpunk*, *minimal* o *productivity-focused*.

**Por qué es superior a alternativas:**

* No depende de interfaces gráficas limitadas.
* Permite coherencia visual con gestores de ventanas como GlazeWM.
* Muy liviana y estable.

---

### 1.2 GlazeWM

GlazeWM es un **tiling window manager para Windows**, inspirado en gestores como i3, bspwm o sway.

**Ventajas clave:**

* Organización automática de ventanas (sin superposición).
* Control total mediante atajos de teclado.
* Archivos de configuración claros y editables.
* Aumenta drásticamente la productividad.
* Perfecto para programación, estudio y multitarea intensiva.

**Por qué destaca frente a otros:**

* Diseñado específicamente para Windows 11.
* No rompe el sistema ni requiere hacks peligrosos.
* Se integra perfectamente con YASB.

---

## 2. Instalación de YASB (paso a paso)

### 2.1 Requisitos previos

* Windows 11 actualizado
* Permisos de usuario estándar
* Editor de texto (recomendado: VS Code)

### 2.2 Descarga

**Enlace de descarga (dejar aquí):**

👉 https://github.com/amnweb/yasb

---

### 2.3 Instalación

1. Descarga el archivo comprimido de YASB.
2. Extrae el contenido en una carpeta permanente, por ejemplo:

   ```
   C:\Tools\YASB
   ```
3. Dentro de la carpeta encontrarás el ejecutable principal.
4. Ejecuta YASB por primera vez.
5. Verifica que la barra aparece correctamente en pantalla.

---

### 2.4 Ubicación de la configuración

YASB guarda su configuración en una carpeta similar a:

```
C:\Users\TU_USUARIO\.config\yasb
```

Aquí se encuentran archivos como:

* `config.yaml`
* archivos de estilos
* módulos personalizados

---

## 3. Instalación de GlazeWM (paso a paso)

### 3.1 Descarga

**Enlace de descarga (dejar aquí):**

👉 https://github.com/glzr-io/glazewm

---

### 3.2 Instalación

1. Descarga el instalador o archivo comprimido.
2. Ejecuta el instalador o extrae en una ruta como:

   ```
   C:\Tools\GlazeWM
   ```
3. Inicia GlazeWM.
4. Acepta los permisos necesarios.
5. Verifica que las ventanas ahora se organizan automáticamente.

---

### 3.3 Ubicación de la configuración

Los archivos de configuración suelen encontrarse en:

```
C:\Users\TU_USUARIO\.config\glazewm
```

Archivos importantes:

* `config.yaml`
* reglas de ventanas
* atajos de teclado

---

## 4. Aplicar mis configuraciones personalizadas (copiar y pegar)

Este apartado permite **usar mis configuraciones sin necesidad de editar nada**.

### 4.1 Estructura de carpetas

Yo proporcionaré carpetas ya configuradas, por ejemplo:

```
YASB-config/
GlazeWM-config/
```

---

### 4.2 Cómo aplicar la configuración de YASB

1. Cierra YASB si está en ejecución.
2. Copia el contenido de la carpeta:

   ```
   YASB-config
   ```
3. Pégalo dentro de:

   ```
   C:\Users\TU_USUARIO\.config\yasb
   ```
4. Acepta sobrescribir archivos.
5. Inicia nuevamente YASB.

---

### 4.3 Cómo aplicar la configuración de GlazeWM

1. Detén GlazeWM.
2. Copia el contenido de:

   ```
   GlazeWM-config
   ```
3. Pégalo dentro de:

   ```
   C:\Users\TU_USUARIO\.config\glazewm
   ```
4. Sobrescribe los archivos.
5. Reinicia GlazeWM.

---

## 5. Resultado final

Con YASB + GlazeWM correctamente configurados obtendrás:

* Escritorio limpio y minimalista
* Control total con teclado
* Mayor productividad
* Estética profesional tipo Linux/Developer
* Un Windows 11 realmente *tuyo*

---

## 6. Notas finales

* Puedes modificar los archivos cuando quieras.
* Se recomienda hacer copias de seguridad antes de experimentar.
* Ideal para estudiantes de informática, programadores y usuarios avanzados.
