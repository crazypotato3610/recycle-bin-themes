<h1 align="center">
<img src="assets/default-bin-icon.png" width="10%" height="10%"><br>
  Windows Recyclebin Themes 
</h1>
<p align="center">
<span>Inspired by <a href="https://reddit.com/r/pcmasterrace/comments/uvtdbx/cat_bin/">this Reddit post</a> by <a href="https://reddit.com/user/DARKplayz_">u/DARKplayz_</a></span>
</p>

## Preview Available Themes

> Click to expand

<details>
<summary><b>Patrick Star</b></summary>
<img src="themes/patrick-star/preview/patrick-star.gif">
<br>
<b><a href="https://github.com/sdushantha/recycle-bin-themes/tree/main/themes/patrick-star">[View Icons]</a></b>
</details>

<details>
<summary><b>Pop Cat</b></summary>
<img src="themes/pop-cat/preview/pop-cat.gif">
<br>
<b><a href="https://github.com/sdushantha/recycle-bin-themes/tree/main/themes/pop-cat">[View Icons]</a></b>
</details>

## How to change the Recycle Bin icon
1. Download the two icons ending with `empty.ico` and `full.ico`
2. Open the the **Settings** app and go to **Personalization** > **Themes** > **Desktop Icon Settings** > **Change Icon and Apply Icons**
3. Change the icons for **Recycle Bin (full)** the icon ending with `full.ico` and **Recycle Bin (empty)** with `empty.ico`
3. Open [Registry Editor](https://support.microsoft.com/en-us/windows/how-to-open-registry-editor-in-windows-10-deab38e6-91d6-e0aa-4b7c-8878d9e07b11) and go to **HKey_Current_User** > **Software** > **Microsoft** > **Windows** > **CurrentVersion** > **Explorer** > **CLSID** > **{645FF...}** > **DefaultIcon**
4. Click on each file (**Default**, **empty**, and **full**) and in the **Value Data** add a **comma** and **0** at the end after **.ico** and hit okay (it will look like `.ico,0`)

*Credits: https://reddit.com/r/pcmasterrace/comments/uvtdbx/cat_bin/i9nn1pq/*

## Contribution
1. Fork the repo
2. Make directory with the name of your icon theme, inside the `themes` directory. Make sure to have the following file structure:
```
your-theme-name/
├── your-theme-name-empty.ico
├── your-theme-name-full.ico
└── preview
    └── your-theme-name.gif  
```
4. Create GIF of your theme in action. Make sure you set the your wallpaper to the color `#2d7d9a`. This is so that all the previews have a similar style.
3. Send a pull request :)
