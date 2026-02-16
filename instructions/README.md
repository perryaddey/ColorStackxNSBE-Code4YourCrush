# 🧰 Installing Git & GitHub CLI

This guide walks you through installing **Git** and the **GitHub CLI (`gh`)** on both:

- 🪟 Windows (PowerShell)
- 🍎 macOS (Terminal)

---

## 🪟 Windows — PowerShell Installation

### ✅ Step 1 — Install GitHub CLI
Open **PowerShell** and run:

```powershell
winget install GitHub.cli
```

---

### ✅ Step 2 — Verify GitHub CLI Installation

```powershell
gh --version
```

You should see a version number printed.

---

### ✅ Step 3 — Install Git

```powershell
winget install --id Git.Git -e --source winget
```

This installs Git using the official Windows package manager.

---

### ✅ Step 4 — Verify Git Installation

```powershell
git --version
```

If installed correctly, PowerShell will display the installed Git version.

---

### 🎉 Windows Setup Complete
You now have:

- Git ✅  
- GitHub CLI (`gh`) ✅

---

## 🍎 macOS — Terminal Installation

### ✅ Step 1 — Install Homebrew (Package Manager)

Open **Terminal** and run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Homebrew allows easy installation of developer tools.

---

### ✅ Step 2 — Install GitHub CLI

```bash
brew install gh
```

---

### ✅ Step 3 — Verify GitHub CLI Installation

```bash
gh --version
```

---

### ✅ Step 4 — Install Git

```bash
brew install git
```

---

### ✅ Step 5 — Verify Git Installation

```bash
git --version
```

---

### 🎉 macOS Setup Complete
You now have:

- Git ✅  
- GitHub CLI (`gh`) ✅

---

## 🚀 Next Recommended Step (Optional)

Log into GitHub from your terminal:

```bash
gh auth login
```

Follow the prompts to connect your GitHub account.

---

## 🧪 Quick Test

Run the following commands:

```bash
git --version
gh --version
```

Both commands should return version numbers.

---

✅ You're now ready to clone repositories, push code, and use GitHub directly from your terminal!
