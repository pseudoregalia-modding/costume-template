# Usage
- open in unreal engine 5.1 (other versions won't work in-game)
- go to `Content/Meshes/Characters`
- right-click `new` and click export in asset actions to export mesh to fbx
- import to blender or your preferred modelling software
- make your edits and export back to fbx
- open `new` and reimport with the new fbx (try to match material slots)
- rename `new` to whatever you want
- package your project for windows
- where you packaged your project there should be a `Windows\pseudoregalia\Content\Paks` folder
- pak chunk 1 is your outfit by default
- rename the costume chunk to what you renamed `new` to
- place in mods folder
- install [attire ui overhaul](https://www.nexusmods.com/pseudoregalia/mods/8) if you haven't already
- you should see your creation in all its glory!

# Custom Textures
- go to `Content/MatTex/Materials/Characters`
- right-click either `MI_n64_Playergoat` or `MI_n64_PlayergoatFace` and click duplicate
- rename the duplicate to whatever you want
- open the duplicate and change the texture being used
- link the mesh to the duplicate
- add your duplicate and the custom texture to the data asset in `Content`

# Blinking and First Person Hiding
- by default the template has sybil set up to blink by using the game's setup
- the material slot for the eyes is named `Material_Eyes` to allow for blinking
- the material slots which are hidden in first person are named `Material` or `Material_Eyes`
