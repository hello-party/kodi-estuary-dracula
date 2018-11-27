# Dracula Theme for Estuary (Kodi 18)

This is a fairly low-contrast color scheme compared to other Dracula setups. 

1. Save this to `C:\Program Files\Kodi\addons\skin.estuary\colors\`
2. In Kodi, go to `Settings > Interface > Colors` and select `Dracula`

To modify the xml, change the colors, use the normal hex value and prepend it with a single hex value for transparency -- e.g. `00282a36` is transparent, where `FF282a36` is opaque. 

---

Notes:

Unlike most people, I access everything in Kodi through the `Favourites` screen. I have created the 'posters' for items like Netflix (which goes directly to my profile) and the individual sets for Movies and TV.

To force Kodi to boot straight to the `Favourites` menu, modify `C:\Program Files\Kodi\addons\skin.estuary\xml\Home.xml` starting on line `833`. Find the item for favorites and cut and paste it up to the top of that `<content>` group.
