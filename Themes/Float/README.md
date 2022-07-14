<h1 align="center">Float</h1>
<p align="center">A practical compact Discord with customization.</p>

![](https://maendisease.github.io/BetterDiscordStuff/Themes/Float/assets/preview.png)

---

## :warning: Remove Minimum Size

In BetterDiscord settings, scroll down to WINDOW PREFERENCES and enable `Remove Minimum Size`.
<p align="center">
  <img src="https://i.imgur.com/l292lJE.png" alt="Remove Minimum Size png"/>
</p>

## Keep the window on top

### BetterDiscord
- Install the plugin [AlwaysOnTop by qwerasd205](https://betterdiscord.app/plugin/AlwaysOnTop).
- Toggle the function by pressing `CTRL/⌘cmd + F11`.

### Windows
- Install [Powertoys by Microsoft](https://github.com/microsoft/PowerToys#microsoft-powertoys).
- Toggle the function by pressing `⊞ Win + CTRL + T`.


## Screenshots
![](https://maendisease.github.io/BetterDiscordStuff/Themes/Float/assets/preview-1.png)
![](https://user-images.githubusercontent.com/90428263/178907361-10717c58-a261-4d3c-bf16-cad34b0af00a.gif)
<p align="center"><a href="https://maendisease.github.io/BetterDiscordStuff/Themes/Float/assets/preview-2.gif">Higher quality mirror gif link</a></p>

## Features
* Compatible with other themes *(probably)*
* Customizable variables
  ```css
  :root {
      /* Guildlist */
      --guildicon-size: 48;
      --enable-if-using-favorites-experiment: 0; /* boolean */
      --guildlist-collapse: 0; /* boolean */

      /* Guildlist icons */
      --guildlist-show: 1;
      --guildlist-peek-unread: 1;
      --guildlist-peek-ping: 1;
      --guildlist-peek-selected: 1;
      --guildlist-peek-group-unread: 1;

      /* Channel sidebar */
      --slide-window-on-hover: 1; /* boolean */
      --float-sidebar-width: 48;
      --sidebar-hover-width: 240px;
      --sidebar-hover-delay: 0.2s;
      --sidebar-transition-duration: 0.4s;
      --sidebar-window-gap: 8px;
      --sidebar-border-radius: 8px;
      --sidebar-usersettings-width: 66px;

      /* Memberlist */
      --float-members-width: 65px;
      --members-hover-width: 240px;
      --members-hover-delay: 1.5s;
      --members-transition-duration: 0.4s;

      /* Channelheader */
      --topic-opacity: 1;
      --toolbar-visibility: flex; /* [flex][none] */

      /* Textarea buttons */ /* [flex][none] */
      --textarea-buttons-gif: flex;
      --textarea-buttons-sticker: flex;
      --textarea-buttons-gift: none;

      /* Theme compatibility */
      --float-guildlist-width-correction: 0px;
  }
  ```
 * Preset window activation levels
    ```css
    /* The variables are used when the window is at the set sizes, each media query can be edited/deleted */
    @media (max-width:700px) {
        :root {
            --topic-opacity: 0;
            --toolbar-visibility: none;
            --textarea-buttons-gif: none;
            --textarea-buttons-sticker: none;
        }
    }

    @media (max-width:500px) {
        :root {
            --guildicon-size: 40;
            --members-width: 0;
        }
    }

    @media (max-width:400px) {
        :root {
            --float-sidebar-width: 0;
        }
    }

    @media (max-width:300px) {
        :root {
            --guildlist-collapse: 1;
        }
    }
    ```

<h2 align="center">Credits</h1>
<p align="center"><a href="https://github.com/mwittrien">Mwittrien</a> - SettingsIcons</p>
<p align="center"><a href="https://github.com/Debuggerz1">Debuggerz1</a> - Math</p>
