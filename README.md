<div align="center">
<img src="assets/preview.gif" alt="firefox alpha preview animation" width="368" height="auto" />
<h2>Firefox-Alphα :moyai: Super clear desktop browser</h2>
  
<h3>
<a href="https://github.com/Tagggar/Firefox-Alpha/blob/main/README.md#arrow_down-install">:arrow_down: Install</a>
<span> &nbsp;&nbsp;&nbsp; </span>
<a href="https://github.com/Tagggar/Firefox-Alpha/issues/">:space_invader: Report Bug</a>
</h3>
</div>

### Master Firefox configuration for simplicity and intuitive controls

- Simple and minimal UI with zero buttons
- Fast and light
- [Multi-row Tabs](#multi-row-tabs)
- [Combined Tab and Urlbar](#combined-tab-and-urlbar)
- [Multi-row Bookmarks](#multi-row-bookmarks)
- [New Clean Menu](#new-clean-menu)
- [New Downloads Bar](#new-downloads-bar)
- [Intuitive gesture navigation](#intuitive-gesture-navigation)
- [Simple Finbar](#simple-findbar)
  
&nbsp;

&nbsp;

<div align="center" width="640">
<img src="assets/tabs.png" alt="firefox alpha multi-row tabs" width="640" height="auto"/>
</div>

### Multi-row Tabs

Tabs stack into multiple rows for better management and access. Users can view more tabs at once, easing navigation and reducing scrolling.

Pinned Tabs are set to the left for quick access.

:mute: The Audio Tab is nicely highlighted, and excessive [Playing] indication removed;


:ok_hand: Expect perfect UI consistency.

&nbsp;

&nbsp;

<div align="center">
<img src="assets/urltab.png" alt="firefox alpha combined tab and urlbar" width="640" height="auto"/>
</div>

### Combined Tab and Urlbar

Greatly enhances usability and provides a more intuitive browsing experience, eliminating the need for constant switching between UI sections.

`LMB` on Active Tab to select url;

`MMB` on Inactive Tab to Close;

`MMB` on empty space to open New Tab;

:monocle_face: Rare glitches may occur due to CSS limits.

&nbsp;

&nbsp;

<div align="center">

<img src="assets/bookmarks.png" alt="firefox alpha multi-row bookmarks" width="640" height="auto"/>
</div>

### Multi-row Bookmarks

Bookmarks now stack into multiple rows below Tabs to enhance organization and accessibility.

Add `History` / `Downloads` to Bookmarks Panel for easy access;

:point_right: `Bookmarks Toolbar` > `Show only on New Tab` to display Bookmarks only on New Tab;

:x: Useless folder icons are removed. Now You can add `💪 Emojis` to folder names for better visual identification. 

&nbsp;

&nbsp;

<div align="center">
<img src="assets/menu.png" alt="firefox alpha new simple clean menu" width="640" height="auto"/>
</div>

### New Clean Menu

New Menu design with clear UI. Unnecessary elements are removed.

:link: Menu can be customized with [simpleMenuWizard](https://github.com/stonecrusher/simpleMenuWizard) to remove multiple unwanted items.

&nbsp;

&nbsp;

<div align="center">
<img src="assets/downloads.png" alt="firefox alpha new downloads bar" width="640" height="auto"/>
</div>

### New Downloads Bar

New Downloads identificator and simple status panel are now with human design.

&nbsp;

&nbsp;

### Intuitive gesture navigation

:arrow_left: Swipe Left to move Back;

:arrow_right: Swipe Right to move Forward;

:arrows_counterclockwise: Pull Down to Refresh Page;

:asterisk: Configure gestures in the Settings.

&nbsp;

&nbsp;

<div align="center">

<img src="assets/findbar.png" alt="firefox alpha simple findbar" width="640" height="auto"/>
</div>

### Simple Findbar

`Ctrl+F` to find on webpage quickly. Findbar now natively integrated into UI. 

&nbsp;

&nbsp;


















---
<!-- Install -->
## :arrow_down: Install:

1. In `about:support` > open Firefox profile folder and put files inside `chrome` folder:
    
    📂 `...` `/` `firefox profile` `/` `chrome` `/` `userChrome.css`
    
    📂 `...` `/` `firefox profile` `/` `chrome` `/` `userContent.css`

2. In `about:config` set:

    `toolkit.legacyUserProfileCustomizations.stylesheets` > `true` to enable custom themes; 

    `browser.urlbar.clickSelectsAll` > `true` for url selection in single click;

    `browser.compactmode.show` > `true` to enable Compact Mode.

### :heavy_plus_sign: Add Extensions:

**[Adaptive Tab Bar Colour](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour#adaptive-tab-bar-colour)** - to make browser UI match the website color;

**[Gesturefy](https://github.com/Robbendebiene/Gesturefy#esturefy)** - to browse faster with mouse gestures;

**[uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin-ubo)** - the only security extension You need.
