# Texture pack for Conker's Bad Fur Day: Recompiled for the PS5

One texture pack for [Conker's Bad Fur Day: Recompiled for the PS5](https://github.com/Samclay8/CBFD-Recompiled-PS5),
ready to copy to the console: three community packs merged into a single file. **None of the texture work is mine.**
Each pack belongs to its author, credited below with a link to where they share it.

**[Download CBFD-PS5-Texture-Pack.rtz](../../releases/latest/download/CBFD-PS5-Texture-Pack.rtz)** (about 450 MB)

## Installing

1. Copy `CBFD-PS5-Texture-Pack.rtz` into the `mods` folder inside the game's `PPSA64065` folder (the game makes it on
   its first start).
2. Start the game, open the menu with the touchpad, and switch on **4K + HD Icons + AI Upscale** under **Mods**.

## What's in it

Each texture comes from the first of these that has it:

1. **4K Ultimate Texture Pack** by **GameBeast92**, a work in progress: Conker and the other characters, the title
   and intro, the HUD and menus, and parts of several chapters and the multiplayer maps, redrawn in 4K.
2. **HD Icons** by **dahmedvall95**, from GameBeast92's artwork: only the pictures the 4K pack doesn't have yet,
   mostly letters of the speech bubbles. Without them, those letters would show in their original low resolution.
3. **AI Upscale** by **Nikachu**: nearly every other texture, upscaled.

## Why it's here

Installing these on the PS5 separately was harder than it should be. AI Upscale is only shared in an older GLideN64
format, which has to be converted on a PC with a Python script first. The latest 4K build is only shared in its
author's Discord. And with three packs, the order in the **Mods** list decides which version of a texture shows. This
puts all three in one file, in the order that looks best on the console.

If you're one of the authors and would rather your work weren't included, open an issue and it will be taken down.

## Credits and sources

- **4K Ultimate Texture Pack** by **GameBeast92**: the build of 23 October 2026, shared in
  [GameBeast92's Discord](https://discord.gg/up8wah5hFu), where the newest builds appear first. Project page:
  [GameBeast92/Conker-s-Bad-Fur-Day-4k-Ultimate-Texture-Pack](https://github.com/GameBeast92/Conker-s-Bad-Fur-Day-4k-Ultimate-Texture-Pack)
  (its GitHub release is CC BY 4.0; this Discord build was shared without a stated licence). Included in full,
  unchanged.
- **HD Icons** by **dahmedvall95**, from GameBeast92's artwork:
  [Conker's Bad Fur Day: Reloaded v1.4.7](https://github.com/DahSidiAbdallah/ConkerBFDReloaded/releases/tag/v1.4.7),
  CC BY 4.0 (`LICENSE-HD-Icons.txt` in the pack). Changed: only the 26 of its 414 pictures that the 4K pack doesn't
  have are included, unchanged.
- **AI Upscale** by **Nikachu** (2022): [N64Textures](https://www.n64textures.com/downloads/?lang=en). No licence
  stated. Changed: converted from the GLideN64 `.htc` with the PS5 port's
  [`tools/gliden64_to_rt64.py`](https://github.com/Samclay8/CBFD-Recompiled-PS5/blob/main/tools/gliden64_to_rt64.py).
  It's matched by its textures' CRCs alone, which only the PS5 port's texture matching does, so this pack is for the
  PS5 port only.

Thank you to all three authors.

---

Conker's Bad Fur Day and its original artwork are © Rare Ltd. These are fan-made packs, not affiliated with or
endorsed by Rare, Microsoft, Nintendo or Sony.
