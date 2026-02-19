# NightShift Lobo — VS Code Theme

**Precision Dark. Engineered Focus.**

NightShift Lobo is a research-calibrated developer theme ecosystem designed for **low eye strain**, **deep focus**, and **long coding sessions**—across your full toolchain.

This repository contains the **VS Code theme pack** for NightShift Lobo, including **four flavours** tuned for different lighting conditions.

---

## Flavours

### 🌑 Eclipse (Dark · Ultra Low Light)

The deepest variant—built for late-night sessions and minimal screen glare.

### 🌘 Shadow (Dark · Balanced Night)

The default daily driver—calm contrast, steady readability, and consistent semantics.

### 🪨 Obsidian (Dark · High Depth)

Richer surfaces and stronger separation—ideal for larger monitors and dense UIs.

### 🌅 Dawn (Light · Low Glare Daytime)

A warm, professional light theme—**no sterile white**, tuned for bright environments.

---

## What’s Included

* ✅ Full VS Code UI theming (editor + workbench)
* ✅ TextMate token colors (syntax highlighting)
* ✅ Semantic token colors (modern highlighting)
* ✅ Terminal ANSI colors
* ✅ Markdown + XML + YAML improvements (where supported by scopes)

---

## Installation

### VS Code Marketplace

1. Open **Extensions** in VS Code
2. Search for **NightShift Lobo**
3. Install and select a flavour:

**Command Palette →** `Preferences: Color Theme`
Choose:

* `NightShift Lobo — Eclipse`
* `NightShift Lobo — Shadow`
* `NightShift Lobo — Obsidian`
* `NightShift Lobo — Dawn`

### Manual (from source)

1. Clone this repo
2. Copy the theme extension folder into your VS Code extensions directory
3. Reload VS Code

---

## Recommended Settings (Optional)

For best results with semantic highlighting:

```json
{
  "editor.semanticHighlighting.enabled": true,
  "editor.fontLigatures": true,
  "workbench.preferredDarkColorTheme": "NightShift Lobo — Shadow",
  "workbench.preferredLightColorTheme": "NightShift Lobo — Dawn"
}
```

---

## Accent System

NightShift Lobo supports a consistent accent identity across tools.
Canonical accent names (shared with DankMaterialShell and Fuzzel):

* Deep Indigo
* Horizon Blue
* Calm Lagoon
* Muted Aqua
* Olive Meadow
* Soft Ochre
* Clay Ember
* Terracotta Rose
* Morning Violet
* Focus Blue
* Warm Highlight
* Storm Grey

> VS Code currently ships as flavour-based themes (accents may be introduced as additional theme variants).

---

## Design Goals

* **Low eye strain**: softened extremes, controlled luminance, no pure black/white
* **Deep focus**: calm contrast, minimal visual noise
* **Semantic clarity**: consistent mapping of syntax categories to color roles
* **Toolchain cohesion**: aligned colours across Kitty, Neovim, DankMaterialShell, and more

---

## Roadmap

* ✅ Night themes: Eclipse / Shadow / Obsidian
* ✅ Day theme: Dawn
* 🔧 More language-specific scope tuning (Markdown/YAML/XML edge cases)
* 🔧 Optional accent variants as separate theme entries

---

## Contributing

PRs are welcome—especially for:

* Language scope improvements (TextMate + semantic tokens)
* Better coverage for Markdown, XML, YAML, JSON, and diff views
* UI edge cases in VS Code workbench components

When contributing, please keep changes aligned with:
**“Precision Dark. Engineered Focus.”**

---

## License

MIT

---

## Author

**Nightshift Lobo**
NightShift Lobo — Theme Ecosystem
