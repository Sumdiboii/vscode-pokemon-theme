# Pokémon Classic Light

A minimal, Game Boy-inspired Pokémon light color theme for Visual Studio Code.

## Included palette

| Role | Color |
| --- | --- |
| Main editor background | `#F0F0EA` |
| Sidebar and panels | `#E4E4DC` |
| Primary text | `#2B2D42` |
| Active states and cursor | `#C83833` |
| Highlights and active line numbers | `#D99B26` |
| Borders and dividers | `#9E9E94` |
| Comments and strings | `#4A7C59` |
| Methods and types | `#2B6CB0` |
| Keywords and control flow | `#6B46C1` |

## Package the extension

From this directory:

```bash
pnpm install
pnpm run validate
pnpm run package
```

The last command creates a `.vsix` file that can be installed in VS Code with
**Extensions: Install from VSIX...**.