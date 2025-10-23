# Contributing guidelines

1. Clone and open this repository in VS Code.
1. Press `F5` to launch this extension inside a new window.
1. Make your changes to the [`themes/monokai-modern-color-theme.json`](themes/monokai-modern-color-theme.json) file:
   - **Syntax highlighting**: please refer to the [syntax highlight guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide).
   - **Workbench**: please refer to the [theme color reference](https://code.visualstudio.com/api/references/theme-color).
1. Commit your changes and create a pull request.

## Color palette

This theme has the goal of using a minimal color palette.

Syntax highlighting colors based on the Monokai Pro color scheme:

| Color | Description | Scope |
| - | - | - |
| `#ff6188` | Pink | Keywords |
| `#fc9867` | Orange | Parameters |
| `#ffd866` | Yellow | Strings |
| `#a9dc76` | Green | Functions |
| `#78dce8` | Cyan | Types |
| `#ab9df2` | Purple | Constants |
| `#727072` | Dimmed | Comments |
| `#221f22` | Dark | Background |
| `#fcfcfa` | White | Foreground |

Workbench colors based on the built-in Dark Modern theme:

- `#181818` is used for the workbench background color - this is the background color used in the built-in Dark Modern theme.
- `#2b2b2b` is used for the workbench border color - this is the border color used in the built-in Dark Modern theme.
