# Replete's Obsidian CSS snippets for Minimal Theme

![Screenshot](_screenshot.png)
<small>Screenshot out of date already..</small>

This is my working folder of CSS snippets for Obsidian using [@kepano](https://github.com/kepan)'s [Minimal Theme](https://github.com/kepano/obsidian-minimal). There are opinionated tweaks and fixes for various plugins and aspects of Obsidian's UI organized into separate CSS files.

### Feature Highlights

- Sensible Typography (through `cssclass`) (WIP)
- Table tweaks (WIP)
- Various Editor Tweaks (WIP)
- [Custom Daily Note styles](https://i.imgur.com/R28YXn9.png) (WIP)
- Dashboard styles (WIP)
- [Calendar Plugin tweaks](https://i.imgur.com/xFdbIwe.gif)
- [Checklist plugin tweaks](https://i.imgur.com/51Lvbbh.png) - Compact view (for tag mode users)
- [Database Folder plugin tweaks](https://i.imgur.com/G4TfL3w.png) - compact view
- [Day Planner plugin tweaks](https://i.imgur.com/xFdbIwe.gif) - I'm using [my own fork](https://github.com/replete/obsidian-day-planner) of this abandoned plugin for more features but the styles here are not dependent on fork changes
- Full Calendar plugin tweaks - WIP, pretty hacky and I stopped using this plugin at the moment
- [Heatmap Calendar tweaks](https://i.imgur.com/ndvRLIC.png) - mostly colours
- [Make.MD Tweaks](https://i.imgur.com/bn5bfMS.gif) WIP- Quite a lot here mostly banners gradients through cssclass etc
- [MySnippets plugin](https://i.imgur.com/5E0LyO0.png) - make menu wider and fix button style/order
- Obsidian Buttons plugin - alignments
- Task progressbars - alignments and colours
- [Collapsible Right Headers](https://i.imgur.com/xFdbIwe.gif)
- [Compact File Explorer with chevrons on right](https://i.imgur.com/9d4UTLb.png)
- Compact Tab Header icons - moar space plz
- [Custom Separators](https://i.imgur.com/9d4UTLb.png) - user-configurable CSS for separators, works well with `File Explorer Custom Sorting` plugin
- File Explorer tweaks
- Frontmatter tweaks (styling, fixes for `editor syntax highlighter plugin`)
- Hide Ribbon - guess what this does
- [Hide Vault Title in Left Sidebar](https://i.imgur.com/LU98mhD.png)
- [Compact Outliner styles](https://i.imgur.com/RgTxA7s.png) with chevron on right
- Resize Handles - more muted theme colours
- Status bar tweaks - more visible text on dark theme 
- Tabs Tweaks - Tabs suck in Obsidian at the moment, they are not very visible so here are attempts to improve this, WIP
- View Header Tweaks - probably icon colours and stuff for use with `Commander` plugin

## My environment


- `MacOS 13.x`, ~~Mobile~~ 
- `Obsidian v1.1.15` (official Installer, homebrew unreliable)
- `Minimal Theme v6.2.3`
- Enabled plugins: `['templater-obsidian', 'dataview', 'calendar', 'settings-search', 'cmdr', 'periodic-notes', 'heatmap-calendar', 'obsidian-hide-sidebars-when-narrow', 'hotkeysplus-obsidian', 'obsidian-minimal-settings', 'obsidian-custom-frames', 'open-vscode', 'quickadd', 'mysnippets-plugin', 'obsidian-day-planner', 'dbfolder', 'obsidian-tagfolder', 'no-dupe-leaves', 'cm-editor-syntax-highlight-obsidian', 'obsidian-toggle-list', 'custom-sort', 'obsidian-icon-folder', 'omnisearch', 'obsidian-task-progress-bar', 'table-editor-obsidian', 'obsidian-advanced-uri', 'auto-class', 'obsidian-checklist-plugin', 'make-md', 'nldates-obsidian', 'obsidian-tasks-plugin', 'folder-note-plugin', 'folder-note-core', 'obsidian-attachment-name-formatting', 'obsidian-tabs']`
```js
[...new Set(app.plugins.enabledPlugins)]
```

## How to use

1. Clone/[fork](https://github.com/replete/obsidian-minimal-theme-css-snippets/fork)/[unzip](https://github.com/replete/obsidian-minimal-theme-css-snippets/archive/refs/heads/main.zip) into `<your vault location>/.obsidian/snippets` 
2. Install the `MySnippets` community plugin by [@chetachiezikeuzor](https://github.com/chetachiezikeuzor) and activate snippets individually
![MySnippets plugin screenshot](_mysnippets-screenshot.png)
3. Use what you like, dupe + hack what you don't

## Someday/maybe
- [ ] Test/fix for Mobile Obsidian (likely near future)
- [ ] Test/fix for Windows or Linux (less likely)

## Versions / updates

This repo is updated frequently as I work on my own vault. I aim to keep my environment up to date. When a new Obsidian version breaks things (which hasn't happened yet), I'll tag a release for whatever the last good Obsidian or Minimal Theme version was before it broke, and subsequent commits will be fixes for the current version.

<a href="https://www.buymeacoffee.com/replete"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=replete&button_colour=6a8695&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00"></a>