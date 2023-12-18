# Alpha Effects (AFX)
A few QoL additions to [Alpha Frontier](https://github.com/carriontrooper/Alpha-Frontier) of personal taste.

Currently sporting some base textures. 

Doesn't seem to work atm as a mod. :/ Not with perm audio/visual either. Hmm!

Tiles here look like this, but transparencies don't really render in the browser:

![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Coast.png)
![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Lakes.png)
![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Ocean.png)
![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Grassland.png)
![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Plains.png)
![](https://raw.githubusercontent.com/hackedpassword/AFX/main/Images.Tileset/TileSets/FantasyHex/Tiles/Desert.png)

Finally got the proper, or best-it's-gonna-get, dimensions for a 256px tile. Looking great imo!

Intention is to eventually update map [Tranquility](https://github.com/hackedpassword/Nextgen-Maps/tree/main/maps).

Here's a preview of the tiles in action, final prototype:

![](https://raw.githubusercontent.com/hackedpassword/Unciv-Assets/main/Images/AFX/Screenshot_20231218-023126_Unciv.jpg)

I'll post a better screenshot later. What you see here is transparency in water tiles, grass/plains overdraw, 256px texture quality. Plains wraps perfectly, grasslands wrap nicely, the remaining do not wrap - might change that.

The dimensions of the high res tiles do not conform to FantasyHex entirely so there are awkward gaps at mixed edges. The aliasing and offset of 32px isn't exactly compatible with the sharpness of 256px. Planning on updating the rest of the base terrain. 
