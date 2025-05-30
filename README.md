
# 🚀 Apuntes AWS RE/START — DevOps en Formación

¡Bienvenido a mi cuaderno técnico! 📚  
Este sitio web ha sido creado con [Quarto](https://quarto.org) y está pensado como una **documentación interactiva** de mi proceso de aprendizaje en el programa **AWS RE/START**.  
Aquí encontrarás apuntes, laboratorios y recursos sobre:

- ☁️ **Fundamentos de la nube (AWS)**
- 🐧 **Linux**
- 🧠 **Redes y Seguridad**
- 🐍 **Python**
- 🛠️ **DevOps Tools**
- 💼 **Soft Skills**
- 🧪 **Proyectos y Laboratorios**

> Este proyecto refleja mi evolución como profesional del entorno Cloud & DevOps..
> Lo uso para estudiar, repasar y compartir conocimiento con la comunidad.  

---

## 🌍 Sitio en vivo

Accede al contenido completo aquí:  
🔗 [https://borizSam.github.io/AWS-Re_Start](https://borizSam.github.io/AWS-Re_Start)

---

## 📦 Tecnologías usadas

- [Quarto](https://quarto.org) como generador de sitio estático
- [Markdown + QMD](https://quarto.org/docs/authoring/) para contenido modular
- [GitHub Pages](https://pages.github.com/) para el hosting gratuito
- [GitHub Actions](https://github.com/features/actions) para despliegue automático

---

## 🛠 Estructura del sitio

```
📁 Fundamentos-Nube/
📁 Linux/
📁 Python/
📁 Seguridad/
📁 Redes/
📁 Recursos/
📁 SoftSkills/
📁 Laboratorios-AWS/
📄 index.qmd
```

Cada carpeta contiene módulos y secciones independientes que puedes explorar desde la navegación del sitio.

---

## ⚙️ Automatización del despliegue

El sitio se publica automáticamente cada vez que hago _push_ a la rama `main`, gracias al siguiente workflow:

```yaml
on:
  push:
    branches: [main]
jobs:
  build-deploy:
    runs-on: ubuntu-latest
```

---

## 🤖 Autor

**@borizSam**  
🧠 DevOps en formación | 🐧 Linux Fan | ☁️ AWS Enthusiast

---

## ⭐ Si te sirve... ¡dale estrella al repo y comparte!

Este proyecto está en desarrollo constante. ¡Toda sugerencia es bienvenida! 🙌
