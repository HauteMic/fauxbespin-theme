# Fauxbespin

A medium-dark theme using a vibrant earth tone palette. Inspired Mozilla Bespin, the cloud editor that started it all. Available for Zed and VS Code.

---

## Color Palette

| Swatch | Hex | Role |
|--------|-----|------|
| ![#28211C](https://placehold.co/16x16/28211C/28211C.png) | `#28211C` | Background |
| ![#B2A69A](https://placehold.co/16x16/B2A69A/B2A69A.png) | `#B2A69A` | Foreground / variables |
| ![#00AAFF](https://placehold.co/16x16/00AAFF/00AAFF.png) | `#00AAFF` | Keywords / builtins |
| ![#10D00D](https://placehold.co/16x16/10D00D/10D00D.png) | `#10D00D` | Strings |
| ![#DA5538](https://placehold.co/16x16/DA5538/DA5538.png) | `#DA5538` | Numbers / constants / properties |
| ![#E0694F](https://placehold.co/16x16/E0694F/E0694F.png) | `#E0694F` | Types |
| ![#FFFFFF](https://placehold.co/16x16/FFFFFF/FFFFFF.png) | `#FFFFFF` | Functions / labels |
| ![#b5bd68](https://placehold.co/16x16/b5bd68/b5bd68.png) | `#B5BD68` | Enums / symbols / inserted |
| ![#cc6666](https://placehold.co/16x16/cc6666/cc6666.png) | `#CC6666` | Tags / errors / deleted |
| ![#b294bb](https://placehold.co/16x16/b294bb/b294bb.png) | `#B294BB` | Emphasis / selectors |
| ![#8abeb7](https://placehold.co/16x16/8abeb7/8abeb7.png) | `#8ABEB7` | Cyan (terminal) |
| ![#6E6E6E](https://placehold.co/16x16/6E6E6E/6E6E6E.png) | `#6E6E6E` | Comments |

---

## Zed

1. Open the Command Palette (`Cmd/Ctrl+Shift+P`)
2. Run **`zed: install dev extension`**
3. Select the `zed/` folder from this directory
4. Open the Command Palette again and run **`theme selector: toggle`**
5. Choose **Fauxbespin**

---

## VS Code

### Option A — Install from folder (no packaging required)

1. Copy the `vscode/` folder to a permanent location (e.g. `~/.vscode/extensions/fauxbespin`)
2. Restart VS Code
3. Open the Command Palette (`Cmd/Ctrl+Shift+P`)
4. Run **`Preferences: Color Theme`** and choose **Fauxbespin**

### Option B — Package and install as `.vsix`

Requires the [vsce](https://github.com/microsoft/vscode-vsce) CLI:

```sh
npm install -g @vscode/vsce
cd vscode/
vsce package
code --install-extension fauxbespin-0.1.0.vsix
```
