
# Guía de Instalación de GitHub Copilot CLI

GitHub Copilot CLI te permite utilizar lenguaje natural en la terminal para generar comandos útiles con ayuda de la IA de GitHub Copilot.

---

## 🧰 Requisitos Previos

- Tener una cuenta de GitHub con acceso a Copilot.
- Tener instalado GitHub CLI (`gh`).
- Tener iniciada la sesión con `gh auth login`.

---

## 💻 Instalación por Sistema Operativo

### 🪟 Windows

1. Instala **GitHub CLI**:
   - Descarga desde: [https://github.com/cli/cli/releases (GitHub CLI 2.69.0 windows amd64 installer)](https://cli.github.com/)
   - Elige el instalador `.msi` correspondiente a tu sistema.

2. Abre una terminal (`PowerShell` o `cmd`) y ejecuta:
   ```bash
   gh auth login
   ```

3. Instala Copilot CLI:
   ```bash
   gh extension install github/gh-copilot
   ```

---

### 🍎 macOS

1. Instala GitHub CLI con Homebrew:
   ```bash
   brew install gh
   ```

2. Inicia sesión:
   ```bash
   gh auth login
   ```

3. Instala Copilot CLI:
   ```bash
   gh extension install github/gh-copilot
   ```

---

### 🐧 Linux (Ubuntu/Debian)

1. Instala GitHub CLI:
   ```bash
   sudo apt install gh
   ```

2. Inicia sesión:
   ```bash
   gh auth login
   ```

3. Instala Copilot CLI:
   ```bash
   gh extension install github/gh-copilot
   ```

---

## ✅ Verificar Instalación

Puedes probar el siguiente comando:

```bash
gh copilot suggest "crear un repositorio local y conectarlo a GitHub"
```

---

## 📚 Más Información

- Documentación oficial: [GitHub Copilot CLI](https://github.com/github/gh-copilot)

