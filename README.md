# Microcontroladores2026
Este repositorio es la base para el curso de microcontroladores 2026

# 📘 Microcontroladores

**Carrera:** Ingeniería Mecatrónica  
**Periodo:** 2026-1  
**Profesor:** Benigno Muñoz

---

## 🎯 Objetivo del repositorio

Este repositorio se utilizará como **bitácora técnica y repositorio oficial del curso de Microcontroladores**. Aquí se almacenarán, organizarán y documentarán los códigos desarrollados durante el semestre utilizando diferentes plataformas y lenguajes:

* PIC en **Ensamblador** (MPLAB X)
* PIC en **C (XC8)**
* PIC en **C (CCS PIC C)**
* **Arduino**

El objetivo **NO es aprender GitHub como materia**, sino usarlo como **herramienta profesional** para:

* Llevar control de versiones del código
* Documentar prácticas
* Comparar soluciones
* Construir un portafolio técnico

---

## 🧠 Filosofía de trabajo

* GitHub es nuestro **cuaderno de laboratorio digital**
* El código debe ser **claro, funcional y documentado**
* Se prioriza el **aprendizaje del microcontrolador**, no la complejidad de Git
* Se trabajará con **GitHub Desktop**, no con terminal

---

## 🗂️ Estructura general del repositorio

```
Microcontroladores-2026-1/
│
├── PIC/
│   ├── ASM/
│   ├── XC8/
│   └── CCS/
│
├── Arduino/
│
├── Docs/
│
└── README.md
```

Cada práctica tendrá su propia carpeta y un archivo `README.md` con la documentación mínima requerida.

---

## 📄 Documentación mínima por práctica

Cada práctica deberá incluir un archivo `README.md` con la siguiente estructura:

```markdown
## Objetivo

## Material utilizado

## Descripción de la solución

## Observaciones / Problemas encontrados
```

No se solicitan reportes extensos. **Claridad y concisión**.

---

## 🚫 Archivos que NO se deben subir

No deben subirse archivos generados automáticamente por los entornos de desarrollo:

* Carpetas `build`, `dist`, `.X`
* Archivos `.hex`, `.elf`, `.cof`
* Archivos temporales del IDE

Solo se suben:

* Código fuente (`.c`, `.h`, `.asm`, `.ino`)
* Documentación (`README.md`)
* Diagramas o imágenes relevantes

---

## 📊 Evaluación relacionada con GitHub

GitHub será utilizado como **evidencia de trabajo**, considerando:

* Código funcional
* Organización del repositorio
* Documentación básica
* Historial de avances (commits)

---

# 👨‍🎓 Guía rápida para alumnos – GitHub Desktop

## 1️⃣ Clonar el repositorio (solo una vez)

* Instalar **GitHub Desktop**
* Iniciar sesión con su cuenta de GitHub
* `File → Clone repository`
* Seleccionar el repositorio del curso

👉 *Clonar es copiar el repositorio del curso a su computadora.*

---

## 2️⃣ Editar código

* Abrir el proyecto en MPLAB X / Arduino IDE
* Modificar el código
* Guardar los cambios

GitHub Desktop detectará automáticamente los cambios.

---

## 3️⃣ Commit (guardar avance)

* Abrir GitHub Desktop
* Escribir un mensaje claro, por ejemplo:

  * `GPIO configurado como salida`
  * `Timer funcionando a 1 ms`
* Presionar **Commit to main**

👉 Un commit es **guardar un avance con explicación técnica**.

---

## 4️⃣ Push (subir cambios)

* Presionar **Push origin**
* Verificar los cambios en GitHub web

👉 Push = subir tu trabajo al repositorio.

---

## 5️⃣ Buenas prácticas

✔ Commits frecuentes  
✔ Mensajes claros  
✔ Código comentado  
✔ README actualizado  \

❌ No subir archivos compilados  
❌ No borrar carpetas de otros equipos  
❌ No hacer commits sin mensaje claro

---

## 🔒 Regla de oro

> **Si el código funciona, haz commit.**

---

## 🚀 Al final del curso

Al finalizar el semestre, este repositorio servirá como:

* Evidencia académica
* Portafolio técnico
* Base para proyectos futuros
* Referencia para otros cursos

---

📌 *Este repositorio es una herramienta de aprendizaje y formación profesional. Úsalo con responsabilidad y criterio ingenieril.*
