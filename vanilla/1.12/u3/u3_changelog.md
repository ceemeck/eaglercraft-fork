# Eaglercraft 1.12.2 u3

## Change log:

### Performance
- Updated to u53 platform classes and port some 1.8 optimizations
- Ported various optimizations from Sodium, Lithium, BetterFPS, Universal Tweaks, VintageFix and VanillaFix
- Ported AI Improvements mod
- Ported Alternate Current mod
- Instanced particle renderer
- Migrated over to fastutil for a handful of stuff
- Prevent spawn chunks from staying loaded

### Bug fixes
- Fixed crash with importing worlds
- Fixed bootstrap bug
- Fixed lingering potions crash
- Fixed /give command
- *POSSIBLY* fixed chunk reset bug
- Fixed world list conversion crash from old leaked builds being used
- Fixed achievements
- Fixed recipe book
- Fixed fireball crash
- Fixed command blocks
- Fixed book and quils
- Fixed notification bug
- Fixed water flowing in the wrong direction
- Fixed rendering of some player skulls
- Fixed rendering of some transparent skins
- Fixed texture "corruption" bug
- Fixed rendering of some transparent items/blocks
- Fixed chunk read counter in TPS stats
- Fixed banner colors
- Fixed debug worlds not loading
- Fixed elytra textures with a cape
- Fixed version number and spacing in debug info
- Fixed multiplayer boats, TNT, polar bears, horses, llama's and shields
- Fixed master volume slider
- Fixed vanilla bug where certain entity ID's don't load
- Fixed vanilla entity tracking bug
- Fixed vanilla duplicate entity UUID bug
- Fixed vanilla entity lists not updating correctly
- Fixed vanilla mem leak with players and paintings
- Fixed vanilla client state loss bug when chaning dimensions
- Fixed webgl1 crash with mipmaps
- Fixed indentation in credits GUI

### Other changes
- Updated to v5 eagler protocol
- Shared world support
- Exporting worlds support
- Voice chat
- Screen recording
- Optifine CIT, zoom and custom tooltips
- Eagler dynamic lights
- World icons
- Biome blend and particle culling from sodium
- Desktop runtime can now load audio from resource packs
- Settings warning screen from 1.8
- Changed close gui key to backtick (`)
- Update client credits
- Better disclaimer screen