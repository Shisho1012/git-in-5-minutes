# 🚀 Guía de Git y GitHub desde cero

Aprende Git de forma simple, práctica y sin romper nada 😄
Ideal para principiantes que quieren entender **qué hacer paso a paso**.

---

## 📌 ¿Qué aprenderás?

* Subir tu primer proyecto
* Comandos esenciales de Git
* Manejo de ramas
* Solución de errores comunes
* Tips que te ahorran tiempo

---

## 🚀 Subir tu primer proyecto (PASO A PASO)

Sigue este flujo real 👇

```bash id="1a2b3c"
# 1. Crear repositorio local
git init

# 2. Agregar archivos
git add .

# 3. Guardar cambios
git commit -m "Primer commit"

# 4. Conectar con GitHub
git remote add origin URL_DE_TU_REPO

# 5. Subir al repositorio
git push -u origin main
```

✅ Con esto ya tienes tu proyecto en GitHub

---

## 🔁 Flujo básico de trabajo

```bash id="4d5e6f"
git add .      # preparas cambios
git commit     # guardas cambios
git push       # subes cambios
```

🧠 Piensa en esto como:
**editar → guardar → subir**

---

## 📂 Comandos esenciales

### 🔍 Estado del proyecto

```bash id="7g8h9i"
git status
```

Muestra qué cambió y qué falta guardar.

---

### ➕ Agregar archivos

```bash id="10j11k"
git add .
git add archivo.txt
```

---

### 💾 Guardar cambios

```bash id="12l13m"
git commit -m "mensaje"
```

---

### ☁️ Subir cambios

```bash id="14n15o"
git push origin main
```

---

### 📥 Clonar repositorio

```bash id="16p17q"
git clone URL
```

---

### 🔄 Actualizar proyecto

```bash id="18r19s"
git pull origin main
```

---

## 🌿 Manejo de ramas

```bash id="20t21u"
git branch nueva-rama     # crear rama
git checkout nueva-rama   # cambiar rama
git merge nueva-rama      # unir cambios
```

💡 Las ramas sirven para trabajar sin romper el proyecto principal.

---

## ❌ Errores comunes (y cómo solucionarlos)

### 🔴 error: failed to push

```bash id="22v23w"
git pull origin main --rebase
```

👉 Debes actualizar antes de subir cambios.

---

### 🔴 error: repository not found

👉 Verifica:

* URL correcta
* Permisos del repositorio

---

### 🔴 Cambios sin guardar al cambiar de rama

```bash id="24x25y"
git stash
```

👉 Guarda cambios temporalmente.

---

## 💡 Tips útiles

```bash id="26z27a"
git log --oneline     # historial resumido
git restore archivo   # deshacer cambios
git branch            # ver ramas
```

---

## 🧠 Conceptos clave (explicado fácil)

* **Commit** → guardar cambios
* **Push** → subir cambios
* **Pull** → descargar cambios
* **Branch** → trabajar sin afectar el proyecto principal

---

## 🎯 ¿Para quién es esta guía?

* Personas que empiezan con Git
* Estudiantes de programación
* Cualquiera que quiera un resumen rápido y claro

---

## ⭐ Si te ayudó

Dale una estrella al repo ⭐
y compártelo con otros 🙌
