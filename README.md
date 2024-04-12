# Iconic (ES-DE Version)
Iconic is an EmulationStation-DE theme that aims to provide a modern UI appearance while also highlighting famous characters from each system. It includes many textlist and gridview options while also adding new multi-layered artwork for popular systems. Inspiration and templates were taken from the following themes:

   - AlekFull NX theme by [fagnerpc](https://github.com/fagnerpc) and ported by [anthonycaccese](https://github.com/anthonycaccese)
   - [CoinOPS](https://github.com/TheGrizzMD/coinops-es-de) theme by [TheGrizzMD](https://github.com/TheGrizzMD)
   - [ARTFLIX](https://github.com/fagnerpc/Alekfull-ARTFLIX/) by [Alekfull](https://github.com/fagnerpc/)
   - [ARTFLIX-Colbalto](https://github.com/galisteogames/ARTFLIX-Cobalto/) by [Galisteo](https://github.com/galisteogames/)
   - [NSO Menu Interpreted ES-DE](https://github.com/anthonycaccese/nso-menu-interpreted-es-de) by [anthonycaccese](https://github.com/anthonycaccese)



## **Preview**

| System View | Gamelist View |
| --- | --- |
| <img src="https://github.com/Siddy212/iconic-es-de/assets/60283021/e72b2a5f-59f5-473c-82ff-2e3910aff469">| <img src="https://github.com/Siddy212/iconic-es-de/assets/60283021/bcf06376-5990-40f0-b361-70e65f8b0e95"> |


## **Configuration Options**

- This theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE
- `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
   - `16:9`
   - `16:10`
   - `4:3`
- `Theme Variant` - sets the layout used for the gamelist view when media & metadata are scraped for your games.  There are 4 sets of variants, with different grid icon sizes to choose from based on your screen size. The amount of metadata (and size of the gamelist if applicable) will scale based on the selected font size:
   - `Textlist` - A simple list that displays the game names. Less demanding on weaker systems.
     
   - `Grid: Boxart Small/Medium/Large` - A grid view that displays small/medium/large boxart covers.
     
   - `Grid: Titlescreen Small/Medium/Large` - A grid view that displays small/medium/large titlescreens.
     
   - `Grid: Physical Media Small/Medium/Large` - A grid view that displays small/medium/large physical media images.
          
   - `Grid: Marquee Small/Medium/Large` - A grid view that display small/medium/large marquees.

     
- `Theme Color Scheme` - sets the color scheme that is used for the overall theme on all views.  There are 3 color schemes to choose from, while also having 3 schemes allowing for user provided custom artwork:
   - `Light`
   - `Dark`
   - `Retro Gray`
- `Theme Font Size` - enables you to change the size of most fonts displayed in the theme.
   - `Medium` - good for display on tvs and computer monitors
   - `Large` - good for display on large handheld screens at 6 inches or larger
   - `Extra Large` - good for display on small handheld screens at 6 inches or below

### **Preview of Variants and Color Schemes**







| Color | SystemView | GamelistView |
| --- | --- | --- |
|Dark|![SampleDarkPSX](https://github.com/Siddy212/iconic-es-de/assets/60283021/15097176-7914-4b5e-b1a8-0627dc81808b)|![SampleDarkGrid](https://github.com/Siddy212/iconic-es-de/assets/60283021/01b0fb75-43f5-4aef-95c5-75800cacd8a7)|
|Light|![SampleLightGBC](https://github.com/Siddy212/iconic-es-de/assets/60283021/c8d33ecf-ed11-4bbb-a463-a8cfad608bdf)|![SampleGBCCarts](https://github.com/Siddy212/iconic-es-de/assets/60283021/933506fc-5619-4838-946d-99d9919d5686)|
|Retro Gray|![SampleGBRetro](https://github.com/Siddy212/iconic-es-de/assets/60283021/6fa06cbf-87dc-4c18-ab07-fdc6c059b2a5)|![SampleListRetro](https://github.com/Siddy212/iconic-es-de/assets/60283021/9dde49d9-1872-431e-9a9a-8db14d2e14d0)|

### Preview of Font Sizes

| Medium | Large | Extra Large |
| --- | --- | --- |
| ![MediumFont](https://github.com/Siddy212/iconic-es-de/assets/60283021/e5ac8b50-09b7-4d39-b9cb-07744b9eaab6) | ![LargeFont](https://github.com/Siddy212/iconic-es-de/assets/60283021/7a177c71-2c67-4bc9-8c55-b314bfa99147) | ![XlargeFont](https://github.com/Siddy212/iconic-es-de/assets/60283021/d1e0710a-3eb7-4d72-a513-0cd1c41db091) | 









## **Theme Customizations**

This theme allows customizations to artwork without the need to edit the source XML.  This enables you to change the look of the theme and still retain any changes when the root theme is updated.

### Start Here 
- Make sure `Light (Custom Artwork)`, `Dark (Custom Artwork)`, or `Retro Gray (Custom Artwork)`  is selected from `Menu > UI Settings > Theme Variant`
- This setting changes the directories that the theme looks for artwork in and sets up the ability for you to add custom artwork.

### Backgrounds
- Use the folder called `custom-backgrounds` in ES-DE's theme directory at: `ES-DE/themes/iconic-es-de/_inc/systems`
- Upload your custom background images to that folder
- They should be named:
    - ${system.theme}.jpg
    - _default.jpg
- `${system.theme}.jpg` should be named for the system you are looking to override.  For example if you wanted to override the artwork for `snes` you would create an image called `snes.jpg` in the backgrounds folder.
- If a given ${system.theme}.jpg image is not found, it will use _default.jpg image, so make sure to keep that file.
  
### Overlays
- Overlays that help make images pop can also be added similar to the main theme images.
- These should be in a 16:9 1920x1080 aspect ratio and a .png format to have the desired effect.
- Use th folder called `custom-Overlay` in ES-DE's theme directory at: `ES-DE/themes/iconic-es-de/_inc/systems`
- Upload your custom overlay images to that folder. These will appear on top of all other assets on the screen.
- They should be named:
    - ${system.theme}.png

## **Additional Notes**

This theme may be resource intensive due to the layering of images. This is especially true when utilizing the grid view. Increasing the VRAM limit under "Other Settings" within the ES-DE menu is useful if pop-in is experienced.

## **Acknowledgments**


**Artwork was designed and created by the following artists and credit is provided to them.**
   - A lot of the original artwork and layouts were designed and created by [fagnerpc](https://github.com/fagnerpc)
   - Earthworm Jim: Created by [Robert Fink](https://finklematter.artstation.com/) 
   - Super Metroid background SNES: Created by [Mark Van Haitsma](https://www.artstation.com/mvhaitsma)
   - Donkey Kong Country 2 art for SNES: Created by [Renato Giacomo](https://www.artstation.com/renatogiacomini)
   - Yoshi Mario Kart on Wii: Modifications made to art by [Yoshiyaki](https://www.deviantart.com/yoshiyaki) & [Renato Giacomo](https://www.artstation.com/renatogiacomini)
      NES background: Created by [m4d3](https://www.reddit.com/r/gaming/comments/1kspxe/my_take_on_super_mario_wallpaper_3d_rendering/)
   - Delfino Plaza wallpaper on Gamecube: Created by [Vincent Moubeche](https://www.artstation.com/artwork/Xn4Xo3)
   - Mario on Gamecube: Created by [SonicJeremy](https://www.deviantart.com/sonicjeremy)
   - Balloon Fighter Render: Created by [Hydro-Plumber](https://www.deviantart.com/hydro-plumber/gallery)
   - Chrono on SFC: Created by [Pik](https://gamebanana.com/mods/383835)
   - Mario on NES: (https://www.freepnglogos.com/images/mario-11641.html)
   - Multiple character renders: [Nibroc-Rock](https://www.deviantart.com/nibroc-rock)
   - Mario Curtain for Now--Playing: [Blueamnesiac](https://www.deviantart.com/blueamnesiac/art/SMB3-Curtain-Wallpaper-369156625)
   - Pit on Famicom and Banjo Kazooie on N64: [Adverse56](https://www.deviantart.com/adverse56)
   - Tyranitar for GBC Hacks: [Chris Silva](https://www.artstation.com/artwork/obBlyB)
   - Wallpaper for Gameboy Hacks: [trollkarl3] (https://www.deviantart.com/trollkarl3/art/Realistic-Super-Mario-Bros-1-first-stage-Wallpaper-375538304)
   - Other publicly available wallpapers or characters are credited to their original creators.
     
## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
