# 🚀 Iniciativa Tecnosofia

Bienvenido al repositorio oficial de **Tecnosofia**, una iniciativa social independiente creada para empoderar a la próxima generación de talentos en tecnología.

### 🌟 Nuestra Misión
> "Despertar la curiosidad tecnológica de los estudiantes brindándoles la infraestructura gratuita necesaria para crear, alojar y compartir su primera página en internet."

### 🔭 Nuestra Visión
> "Un futuro donde cada alumno tenga un espacio propio en la red, impulsando a una nueva generación de creadores, programadores y pensadores digitales en México."

---

## 🛠️ ¿Qué es este proyecto?
Ofrecemos subdominios gratuitos (`tu-nombre.tecnosofia.xyz`) para estudiantes, desarrolladores junior y escuelas que buscan alojar sus portafolios, proyectos escolares o laboratorios de pruebas utilizando plataformas como Vercel o GitHub Pages.

Todo funciona a través de un sistema automatizado de Infraestructura como Código (IaC).

---

## 📖 Cómo solicitar tu dominio gratuito (Paso a Paso)

Para obtener tu dominio, solo necesitas enviarnos una solicitud a través de este repositorio siguiendo estos pasos:

### 1. Prepara tu proyecto
Asegúrate de tener tu página web alojada en Vercel, GitHub Pages o similar. Debes tener a la mano el enlace original (por ejemplo: `mi-proyecto.vercel.app`).

### 2. Crea tu archivo de solicitud
1. Haz un "Fork" de este repositorio o navega a la carpeta **`domains`**.
2. Haz clic en **Add file** > **Create new file**.
3. Nombra tu archivo con el subdominio que deseas, todo en minúsculas y terminado en `.json`. (Ejemplo: si quieres `gael.tecnosofia.xyz`, nombra el archivo `gael.json`).
4. Pega la siguiente plantilla dentro del archivo:

```json
{
  "owner": {
    "username": "tu_usuario_de_github",
    "email": "tu_correo@ejemplo.com"
  },
  "records": {
    "CNAME": ["Pega_Aqui_El_Enlace_De_Tu_Vercel_Sin_https://"]
  }
}
```

### 3. Llena tus datos
Reemplaza los textos de la plantilla con tu información real. 
*Importante: En el CNAME, pon tu enlace limpio, sin el `https://`.*

### 4. Envía tu solicitud
Ve al fondo de la página, haz clic en el botón verde **Commit changes** y luego abre un **Pull Request**. 

### 5. Espera la magia
Un administrador revisará tu solicitud. Una vez aprobada, nuestro servidor automatizado creará tu registro DNS en menos de 10 segundos. Cuando veas que tu Pull Request fue aceptado, ve a la configuración de tu proyecto en Vercel y agrega tu nuevo dominio oficial.

---

## ⚠️ Reglas de la Comunidad
* Los dominios son estrictamente para uso educativo, portafolios personales y proyectos de desarrollo.
* Se rechazará cualquier solicitud que apunte a sitios con contenido malicioso, ilegal o comercial de gran escala.
* Mantenemos el derecho de revocar subdominios que violen estas reglas para proteger la integridad de la red Tecnosofia.
