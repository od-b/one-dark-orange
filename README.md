# One Dark Orange
Color theme based on [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme).  

## Screenshots
### Highlighting
![ScreenShot](https://raw.githubusercontent.com/od-b/one-dark-orange/main/screenshots/sample-highlight-node.png)

### Fullscreen
![ScreenShot](https://raw.githubusercontent.com/od-b/one-dark-orange/main/screenshots/sample-rust-fullscreen.png)

## Suggested Settings
If a complete look similar to the fullscreen screenshot is desired, add the following options to `settings.json`.
```jsonc
{
    "workbench.sideBar.location": "right",    // move side bar right (file explorer, etc)
    "workbench.layoutControl.enabled": false, // remove some buttons from the window title bar
    "breadcrumbs.enabled": false,             // remove the 'path' bar
    "window.commandCenter": false,            // further title bar cleanup
    "explorer.sortOrder": "type",             // sort files by type > name
    "editor.overviewRulerBorder": false,      // remove the scroll bar border
    "editor.stickyScroll.enabled": false,     // disable annoying scrolling function/scope headers
    "editor.minimap.enabled": false,          // I don't use the minimap
    "editor.inlayHints.enabled": "offUnlessPressed", // Disable inline info such as '13 references'
}
```

For icons, install [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme).

The font used is [JetBrains Mono](https://www.jetbrains.com/lp/mono/), with the following configuration:
```jsonc
{
    "editor.fontSize": 13,
    "editor.fontLigatures": false,
    "editor.lineHeight": 21,
}
```

---

Request, question or feedback? Please open an issue on [github](https://github.com/od-b/one-dark-orange/issues/new).
