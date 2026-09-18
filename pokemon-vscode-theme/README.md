# Pokémon Classic Light

A high-contrast Pokémon-inspired light color theme for Visual Studio Code.

## Included palette

| Role | Color |
| --- | --- |
| Main editor background | `#D8D8D8` |
| Sidebar and Activity Bar | `#E3350D` with `#FFFFFF` icons |
| Tabs and title bar | `#E3350D` with `#FFFFFF` text |
| Status Bar | `#FFFFFF` with `#1A1A1A` text |
| Variables, properties, and constants | `#1A1A1A` |
| Functions and methods | `#333333` |
| Strings | `#C59B00` |
| Comments | `#A4A4A4` |

## Package the extension

From this directory:

```bash
pnpm install
pnpm run validate
pnpm run package
```

The last command creates a `.vsix` file that can be installed in VS Code with
**Extensions: Install from VSIX...**.