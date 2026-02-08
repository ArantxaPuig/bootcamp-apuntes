# 📅 Día 1 - [Varios días primera semana]

## 🎯 Lo que hemos visto esta semana

### Mañana
- Dinámica: Gartic Phone (sobre distorsión de información)
- Conceptos: ¿Qué es análisis de datos?
- Ejercicio: Palabras en griego (buscar patrones sin contexto)

### Tarde
- Git y GitHub: instalación y configuración
- Primeros comandos: clone, status, add, commit, push

## 💡 Lo que he aprendido

**PowerShell** Terminal para Windows - Hablarle al sistema sin usar el ratón. Algunos comandos básicos:

- pwd - Muestra la ruta actual
- cd *nombrecarpeta* - Cambiar de directorio (Te dirije a la carpeta)
- ls - Listar archivos
- mkdir *nombrecarpeta* - Crear directorio
- ...

---

**Visual Studio Code**  Editor de código 

---

**Git y GitHub** 

1. **Git**: Sistema de control de versuones (Permite guardar cambios en código o proyectos)

2. **GitHub**: Plataforma online donde alojas los repositorios (Proyectos con todos sus archivos y su historial de cambios)


## ❓ Dudas que tengo

**Pendiente**

## 🔗 Recursos útiles

- [https://markdownguide.org]


---

**Siguiente paso:** Empezar SAT-01 Atlas

--- 

# 🎯 EJERCICIO 3:  Investigación guiada

## 🔍 Parte 1: Explora estos comandos

PS C:\Users\apuig\Desktop\R-CAMP DATANALIST\APUNTES\bootcamp-apuntes\semana-01> **git log --oneline**

*3c491f9 (HEAD -> main, origin/main, origin/HEAD) Edit first week notes*

*8a6e591 Add first week Summary*

*42dcac1 Initial commit*


PS C:\Users\apuig\Desktop\R-CAMP DATANALIST\APUNTES\bootcamp-apuntes\semana-01> **git remote -v***

*origin  https://github.com/ArantxaPuig/bootcamp-apuntes.git (fetch)*

*origin  https://github.com/ArantxaPuig/bootcamp-apuntes.git (push)*

PS C:\Users\apuig\Desktop\R-CAMP DATANALIST\APUNTES\bootcamp-apuntes\semana-01> **git branch**

"* main"

### Estamos en la Rama Main (Rama pricnipal)

## 🔍 Parte 2: Preguntas de investigación

1. **git pull** - Descargar los cambios de un repositorio remoto y los fusiona automáticamente en el repositorio local (Al contrario que git push que los subre de local a remoto.)

2. **.gitignore** - Archivo especial (Le dice a git: ignora estos archicos. No los tengas en cunta para commits ni para GitHub.)

Es útil para:
- Archivos temporales del editor
- Archivos grandes de datos que no quieres subir
- Contraseñas

3. **Diferencia entre *git add.* y *git add nombrearchivo***
 - **git add.** añade todos los archivos modificados o nuevos de la carpeta actual en la que te encuentras desde la terminal

 - **git add Nombrearchivo**  Sólo añade ese archivo específico al próximo commit 

