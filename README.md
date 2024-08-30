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

## Notes

__The theme is a work in progress, and subject to minor changes.__  
The current screenshots are from v.0.0.2, and may not reflect the exact color scheme. See the [changelog](https://github.com/od-b/one-dark-orange/blob/main/CHANGELOG.md) for details. To be clear, there will not be major changes to the look, but rather minor adjustments to syntax/token highlighting. To avoid any changes, uncheck 'auto-update' and/or install a different version.

---

_Request, question or feedback? Please open an issue on [github](https://github.com/od-b/one-dark-orange/issues/new)._
