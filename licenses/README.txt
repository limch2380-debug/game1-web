Combat Drone - Free Sampler  -  version 2.0.5

1 top-down character(s), 8 directions each.

- Combat Drone: attack, attack2, attack3, death, hurt, idle, run, walk (222x192 px frames); attack 12, attack2 12, attack3 12, death 12, hurt 11, idle 12, run 12, walk 12 frames per direction

Includes PNG artwork, animation metadata and Godot 4 SpriteFrames. Other engines can import the PNGs; their animation setup must be configured separately.

SMOOTH CLIPS
  Every idle, walk, run, attack and hurt animation (and every effect) also comes as <animation>_smooth: the same animation with twice the frames, played at twice the fps (same frame size, feet pivot and row order). Sheets, single frames, 128 px copies, colour variations and recolour masks included; Godot 4 SpriteFrames in godot/<name>_smooth_spriteframes.tres (animations <animation>_smooth_<direction>); the JSON lists them. Effects: <clip>_smooth sheets next to the originals, listed in each effect JSON.

COLOUR VARIATIONS (ColourVariations/, optional: delete the folder if you don't need it)
  ColourVariations/<variation>/<name>/  every animation of a character in another colour variation: the same
      sheets, frame size, feet pivot and Godot SpriteFrames as characters/<name>/ (sheets only; slice
      them like the main sheets). Previews: previews/<name>_colour_variations.png
  - Combat Drone: Faction Red (red/), Military Olive (military/), Desert (desert/), Black Ops (blackops/)
  ColourVariations/recolour_masks/<name>/<clip>.png  material masks in the same layout as the sheets
      (red = main material, green = second material) for your own colours at runtime.
  ColourVariations/godot/recolour_mask.gdshader + recolour_masks.gd  Godot 4: give the AnimatedSprite2D a
      ShaderMaterial with the shader, attach the script, set masks_dir, then pick colour_main / colour_second.

MORE IN THIS STYLE
  Combat Drones: https://sovdigital.itch.io/combat-drones
  Robots & Drones Set: https://sovdigital.itch.io/robots-and-drones-set
  Complete Edition (every pack, boss and effect in one download): https://sovdigital.itch.io/complete-edition
  Everything by Sova Digital: https://sovdigital.itch.io/
