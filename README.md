# Glass Themes
Home Assistant themes - theme with a glass effect in different colors for light and dark mode. This does not mean it is black and white.   

* [Prerequisites](#prerequisites)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
* [Enable the theme](#enable_the_theme)
* [Background Image](#background_image)
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