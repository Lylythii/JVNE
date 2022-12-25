
# App Asar
Everything included within the `app.asar` folder is modified versions of the contents of the CurseForge Desktop apps `app.asar` file.
You may drag & drop these contents on top of the default files contents, & replace them.
## Extracting the CurseForge Asar
By default your CurseForge app.asar should be located within `C:\Users\YOUR_USERNAME\AppData\Local\Programs\CurseForge Windows\resources\`
You will need to unpack this before modifying its contents.
The following command will extract the contents of `app.asar` into a folder titled `app`. (You will need to install [Node](https://nodejs.org/))
```
asar extract app.asar app
```
You can now freely replace the files located inside of `app` with the files included in this repository.
Next time you restart the CurseForge Desktop application, it will be modified!
For safety sake, I recommend keeping the original `app.asar` file. It won't be used, but you can always delete the `app` folder & go back to using Vanilla CurseForge.
Alternatively, just purge the contents of the `app` folder entirely & CurseForge will reinstall itself the next time you attempt to launch it.
## Still Confused?
Here's a nice tutorial by [Exordium](https://www.youtube.com/@ExordiumYT) on unpacking Electron applications: [How To Decompile Discord | Get Any Electron App’s Source Code
](https://www.youtube.com/watch?v=jyiFjqNncMc)

# Sewerslvt Art Source
[Steam Workshop, Wallpaper Engine desktop background](https://steamcommunity.com/sharedfiles/filedetails/?id=2423472173)
Should the artist want this removed from this repository, I shall comply.

### Minecratf
Yes, the `minecratf.webp` file located in `app/assets/images/games-backgrounds` does need to be incorrectly spelled.
That's how it is in the CurseForge app.asar files. Sorry to curse you with the knowledge of that.

# Help?
If you're still confused by this, or have any additional questions or queries, message me on Discord! `Lylythii#0001` I'll get back to you when I have a moment to spare.

![CurseForge Desktop Application](https://raw.githubusercontent.com/Lylythii/JVNE/main/curseforge/preview.PNG)
