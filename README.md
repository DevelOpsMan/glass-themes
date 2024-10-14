# Glass Themes
Home Assistant themes - theme with a glass effect in different colors for light and dark mode. This does not mean it is black and white.   

* [Prerequisites](#prerequisites)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
* [Enable the theme](#enable_the_theme)
* [Screenshots](#screenshots)

## <a name="prerequisites"></a>Prerequisites
1. On newer Home Assistant versions the **configuration.yaml** has this option already but get sure, to allow loading themes from the themes folder:   

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

2. If not existing create the folder **themes** next to the **configuration.yaml** file

## <a name="hacs_installation"></a>HACS installation
1. Open the Community Store (HACS)
2. Search for `glass theme`
3. Install it
4. Restart Home Assistant

## <a name="manual_installation"></a>Manual installation
1. Copy the files for the colors (f.e. 'glass-sea.yaml`) you prefer to into your Home Assistant themes folder
2. Restart Home Assistant

## <a name="enable_the_theme"></a>Enable the theme
- Open your **Profile** in Home Assistant and select the theme starting with `glass` like **glass-sea**


## <a name="screenshots"></a>Screenshots

### Weather

![Theme - weather - sea dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/sea%20dark%20theme%20on%20weather%20data.PNG)
![Theme - weather - blue dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20dark%20theme%20on%20weather.PNG)
![Theme - weather - blue light](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20theme%20on%20weather.PNG)

### Developer Tools

![Theme - dev tools - sea dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/sea%20dark%20theme%20on%20developer%20tools.PNG)
![Theme - dev tools - blue dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20dark%20theme%20on%20developer%20tools.PNG)
![Theme - dev tools - blue light](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20theme%20on%20developer%20tools.PNG)

### Settings

![Theme - Options - sea dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/sea%20dark%20theme%20on%20options.PNG)
![Theme - Options - blue dark](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20dark%20theme%20on%20settings.PNG)
![Theme - Options - blue light](https://codeberg.org/developsman/glass-themes/raw/branch/main/docs/blue%20theme%20on%20settings.PNG)

