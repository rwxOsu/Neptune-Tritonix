<h1 align="center"><strong>Neptune Firefox</strong></h1>

**Instructions:** 
- This theme works for **Firefox v128+** and is compatible with Linux, Windows and macOS.
- In shades of blue.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)** extension. 

**Known issues:** 
- The buttons on the right cannot be dragged. however, they can be moved to the far left or hidden.
- Due to changes in the Picture-in-Picture player's style, it cannot be resized.

**Tips:** 
- Some elements like unnecessary context menus are removed, so it might not be ideal for everyone.
- The default new tab wallpaper of the theme uses Firefox's wallpaper feature. However, it cannot be customized. Therefore, to display the wallpaper shown in the preview, search for and modify **"userContent.css"** by removing the `/*` and `*/` symbols from this line:

```css
/*body {
  background: url("neptune/image/Orange.png") center/cover no-repeat fixed !important;

  @media (prefers-color-scheme: dark) {
    background: url("neptune/image/Blue.png") center/cover no-repeat fixed !important;
  }
}*/
```

## Installation

Download the theme file and unzip the **"chrome"** folder into your **"profile"** folder.

## Browser Configuration
- `about:preferences`

    - Set appearance to automatic.

-  `about:config`

    **Important**
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
    - Set `svg.context-properties.content.enabled` to `true`.
    - Set `browser.newtabpage.activity-stream.newtabWallpapers.enabled` to `true`.
    - Set `browser.newtabpage.activity-stream.newtabWallpapers.v2.enabled` to `true`.
    - Set `widget.non-native-theme.scrollbar.style` to `2` （**For Windows10**. Due to the default scrollbar in Windows 10 being quite wide, it can affect the setting menu's width., this configuration is recommended.)

    **Optional**
    - Set `browser.newtabpage.activity-stream.improvesearch.handoffToAwesomebar` to `false`.

- **Adaptive Tab Bar Color settings**

    - Turn off all `Customization` colors,
    - configure `advanced`
        - light:`rgb 246,246,246`
        - dark:`rgb 56,56,56`
