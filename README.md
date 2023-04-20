# CleanFox
A Clean firefox userstylesheet in CSS <br>

Close to vanilla firefox look but cleaner and more compact and without sacrificing usability or needing to alter your workflow <br>

![FF](https://user-images.githubusercontent.com/107309764/233371225-fd9a755f-74a0-4be1-9392-8e2b211270dc.png)

## ⚙️ Installation

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.

2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**

3. Go to your Firefox profile:

    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`

    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`

    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 

4. Move the `chrome` folder into the directory.

6. Enjoy!

This is a fork of [simplefox](https://github.com/migueravila/SimpleFox)

