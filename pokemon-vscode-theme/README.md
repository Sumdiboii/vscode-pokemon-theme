# Pokémon Classic Dark

A vibrant Pokémon-inspired dark color theme for Visual Studio Code.

## Included palette

| Role | Color |
| --- | --- |
| Main editor background | `#1e222b` |
| Sidebar background | `#181a20` |
| Accents and highlights | `#ef5350` |
| Activity Bar | `#ef5350` with `#ffffff` icons |
| Status Bar and focus rings | `#ffcb05` with `#1e222b` text |
| General UI text | `#f8f9fa` |
| Functions and methods | `#4ba8ff` |
| Comments | `#6272a4` |

## Package the extension

From this directory:

```bash
pnpm install
pnpm run validate
pnpm run package
```

The last command creates a `.vsix` file that can be installed in VS Code with
**Extensions: Install from VSIX...**.