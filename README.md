# 🧱 Repo: geo-packages

Este repositorio contiene paquetes `.tgz` empaquetados y listos para instalar en proyectos usando `npm install` directo desde GitHub, sin exponer el código fuente ni las librerías reales utilizadas.

---

## 📦 Estructura de carpetas

```
geo-packages/
├─ geosolution-gl/
│  ├─ geosolution-gl-1.0.0.tgz
│  ├─ geosolution-gl-1.0.1.tgz
│  └─ ...
├─ other-wrapper/
│  └─ other-wrapper-1.0.0.tgz
└─ README.md
```

---

## 🚀 Instalación de un paquete

En tu proyecto React o Node, simplemente hacé:

```bash
npm install https://raw.githubusercontent.com/TU_USUARIO/geo-packages/main/geosolution-gl/geosolution-gl-1.0.0.tgz
```

> Reemplazá `TU_USUARIO` por tu usuario real de GitHub.



---

## 🔐 Seguridad

Este repo no incluye código fuente. Solo binarios listos para consumir.

---


## 🧼 .gitignore sugerido

```
# No ignoramos nada, ya que este repo solo contiene .tgz
node_modules
*.log
.DS_Store
```

---

## ✨ Ejemplo en package.json

```json
"dependencies": {
  "geosolution-gl": "https://raw.githubusercontent.com/TU_USUARIO/geo-packages/main/geosolution-gl/geosolution-gl-1.0.0.tgz"
}
```