# Vault customizations

Copy the snippets you want from this directory into the vault's
`.obsidian/snippets` folder, then enable them under **Settings → Appearance →
CSS snippets**.

| Snippet | Purpose |
| --- | --- |
| `brains-folder-colors.css` | Folder colors and icons for the README and Tasks dashboard. |
| `custom-selectors-table.css` | Fits Custom Selectors dropdowns inside Bases cells. Requires the Custom Selectors plugin. |
| `hide-left-sidebar-tabs.css` | Hides the left sidebar tab strip and adds a draggable area. |
| `pdf-scrollbar-fix.css` | Clears the rotated breadcrumb from the PDF scrollbar area. |
| `window-buttons-left.css` | Moves and shrinks the window buttons on Windows. |
| `tasks-table.css` | Earlier Bases dropdown styling. Leave disabled when using `custom-selectors-table.css` to match the vault setup. |

The vault uses Shimmering Focus with Charter for the interface and text,
JetBrains Mono for monospace, and a base font size of 18. The ribbon is hidden.
Set these separately under **Settings → Appearance**.

To bring in upstream changes, run the following from the customizations branch.
The local checkout already has the `upstream` remote configured.

```sh
git fetch upstream
git merge upstream/main
```
