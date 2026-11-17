Below you will find a complete list of every known and reported Minecraft RTX issue, as well as their current status on Mojang's issue reporting site, [Mojira](https://bugs.mojang.com/).

The issues are listed based on priority, if an issue you've encountered is missing from this list, and you believe it is related to the game, report it through Mojira, but if you think it is related to Vanilla RTX, or Vanilla RTX App, report it to Cubeir 

If a reported or known Minecraft RTX issue is missing from this list in particular, a bug is miscategorized, has the wrong link, etc... please [open an issue](https://github.com/vanilla-rtx/Minecraft-RTX-Bug-Tracking/issues) or [a pull request](https://github.com/vanilla-rtx/Minecraft-RTX-Bug-Tracking/pulls).

## Table of Contents

- [🟥 Unresolved Issues](#-unresolved)
- [🟧 Issues Mojang Won't Fix](#-mojang-wont-fix)
- [🟨 Issues worked around by Supervanilla RTX, Vanilla RTX or other means](#-worked-around)
  - [Fixed by Supervanilla RTX](#fixed-by-supervanilla-rtx)
  - [Fixed by Vanilla RTX](#fixed-by-vanilla-rtx)
  - [Worked around by the Vanilla RTX App](#worked-around-by-the-vanilla-rtx-app)
- [🟩 Resolved Issues](#-resolved)
- [⚒️ Vanilla RTX Bug Tracking](#vanilla-rtx-bug-tracking)

## 🟥 Unresolved

These issues have been reported on Mojira, regardless of confirmation status, they remain unresolved. (Sorted based on severity, from highest to lowest).  
You will need to login or create an account to be able to vote.

- [MCPE-183773](https://bugs.mojang.com/browse/MCPE/issues/MCPE-183773) - Entity UV Animations do not work once RTX is enabled.
- [MCPE-241723](https://bugs.mojang.com/browse/MCPE/issues/MCPE-241723) - Animated flipbook textures no longer animate smoothly with ray tracing enabled
- [MCPE-176104](https://bugs.mojang.com/browse/MCPE/issues/MCPE-176104) - Chunks stop updating and become stuck after toggling Ray Tracing
- [MCPE-145467](https://bugs.mojang.com/browse/MCPE/issues/MCPE-145467) - The Ray Tracing denoiser causes a major reduction in reflection, shadow and ambient occlusion quality
- [MCPE-227473](https://bugs.mojang.com/browse/MCPE/issues/MCPE-227473) - Underwater torch lacks point light (Education Edition)
- [MCPE-105261](https://bugs.mojang.com/browse/MCPE/issues/MCPE-105261) - Ray Tracing experiences render errors in certain scenes and conditions
- [MCPE-105028](https://bugs.mojang.com/browse/MCPE/issues/MCPE-105028) - No player shadows or reflections are visible in first person with Ray Tracing
- [MCPE-119895](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119895) - Glass loses transparency at a distance with Ray Tracing on
- [MCPE-119941](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119941) - Transparent parts of an entity's texture stop particles from rendering behind them
- [MCPE-111406](https://bugs.mojang.com/browse/MCPE/issues/MCPE-111406) - Chests are culled when off screen with Ray Tracing on
- [MCPE-110757](https://bugs.mojang.com/browse/MCPE/issues/MCPE-110757) - Entities are culled when off screen with Ray Tracing on
- [MCPE-127107](https://bugs.mojang.com/browse/MCPE/issues/MCPE-127107) - Glass and glass panes render incorrectly underwater
- [MCPE-153963](https://bugs.mojang.com/browse/MCPE/issues/MCPE-153963) - Ray Traced entities shimmer during movement when DLSS is enabled
- [MCPE-122733](https://bugs.mojang.com/browse/MCPE/issues/MCPE-122733) - Toggling Ray Tracing is much slower than it should be
- [MCPE-147520](https://bugs.mojang.com/browse/MCPE/issues/MCPE-147520) - The irradiance cache causes frosted leaves to emit light
- [MCPE-141852](https://bugs.mojang.com/browse/MCPE/issues/MCPE-141852) - The irradiance cache occasionally fails to propagate light
- [MCPE-119900](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119900) - God rays appear in underground water caves despite there being no physical path for light to reach them
- [MCPE-137580](https://bugs.mojang.com/browse/MCPE/issues/MCPE-137580) - Lava and colored glass emit light inconsistently with RTX
- [MCPE-118768](https://bugs.mojang.com/browse/MCPE/issues/MCPE-118768) - The Light Block does not function with RTX
- [MCPE-115674](https://bugs.mojang.com/browse/MCPE/issues/MCPE-115674) - Dyeable items render as white with Ray Tracing enabled
- [MCPE-119887](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119887) - Entities on featured servers are completely black with Ray Tracing on
- [MCPE-132674](https://bugs.mojang.com/browse/MCPE/issues/MCPE-132674) - Specific water texture opacity prevents underwater volumetric fog from appearing (🟨Fixed by BetterRTX)
- [MCPE-155625](https://bugs.mojang.com/browse/MCPE/issues/MCPE-155625) - The Darkness effect does not function correctly with Ray Tracing (🟨Fixed by BetterRTX)
- [MCPE-136281](https://bugs.mojang.com/browse/MCPE/issues/MCPE-136281) - Maps and items placed in Glow Item Frames don't emit light with Ray Tracing on (🟨Partially fixed by Supervanilla RTX)
- [MCPE-117722](https://bugs.mojang.com/browse/MCPE/issues/MCPE-117722) - Conduit PBR textures do not load
- [MCPE-219635](https://bugs.mojang.com/browse/MCPE/issues/MCPE-219635) - Marketplace packs override all other texture packs when used with Ray Tracing or Vibrant Visuals
- [MCPE-181917](https://bugs.mojang.com/browse/MCPE/issues/MCPE-181917) - The world thumbnail shows the player's hand and held items when Ray Tracing is enabled
- [MCPE-138222](https://bugs.mojang.com/browse/MCPE/issues/MCPE-138222) - The sky directly above the player is darker with Ray Tracing (🟨Fixed with a custom LUT preset from [the app](https://github.com/vanilla-rtx/Vanilla-RTX-App/))
- [MCPE-104310](https://bugs.mojang.com/browse/MCPE/issues/MCPE-104310) - The sky occasionally becomes multicoloured with Ray Tracing on (Mojang could not reproduce, but reports continue)
- [MCPE-125936](https://bugs.mojang.com/browse/MCPE/issues/MCPE-125936) - Powder Snow fog shows the skybox instead of a solid colour with Ray Tracing on
- [MCPE-116279](https://bugs.mojang.com/browse/MCPE/issues/MCPE-116279) - Text on signs renders incorrectly behind transparent blocks and some items
- [MCPE-138682](https://bugs.mojang.com/browse/MCPE/issues/MCPE-138682) - Text on signs is not reflected with Ray Tracing
- [MCPE-119885](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119885) - Selection box lines render above dropped items
- [MCPE-111329](https://bugs.mojang.com/browse/MCPE/issues/MCPE-111329) - Campfire smoke renders above dropped items
- [MCPE-133050](https://bugs.mojang.com/browse/MCPE/issues/MCPE-133050) - Banners display a random pattern with certain resource packs applied under Ray Tracing
- [MCPE-130350](https://bugs.mojang.com/browse/MCPE/issues/MCPE-130350) - Banner patterns don't render with Ray Tracing
- [MCPE-129315](https://bugs.mojang.com/browse/MCPE/issues/MCPE-129315) - The fishing rod line becomes offset with Ray Tracing on
- [MCPE-129202](https://bugs.mojang.com/browse/MCPE/issues/MCPE-129202) - The skybox retains its position when time changes if Ray Tracing is on and Beautiful Skies is off
- [MCPE-104447](https://bugs.mojang.com/browse/MCPE/issues/MCPE-104447) - Ray Tracing cannot be toggled while in a boat
- [MCPE-95662](https://bugs.mojang.com/browse/MCPE/issues/MCPE-95662) - Reloading Minecraft causes mobs' body parts to swap around
- [MCPE-238296](https://bugs.mojang.com/browse/MCPE/issues/MCPE-238296) - When RTX is enabled, all of the texturs might display wrong.
- [MCPE-232858](https://bugs.mojang.com/browse/MCPE/issues/MCPE-232858) - Entity dithering (and other accessibility settings) don't work with RTX.
- [MCPE-194473](https://bugs.mojang.com/browse/MCPE/issues/MCPE-194473) - Stars are not anti-aliased with RTX

## 🟧 Mojang Won't Fix

Mojang has been made aware of these issues and has explicitly decided they will not be fixing them. These will likely remain unresolved forever.

- [MCPE-161751](https://bugs.mojang.com/browse/MCPE/issues/MCPE-161751) - The display driver crashes after idling in the main menu with Ray Tracing
- [MCPE-119904](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119904) - Chunk culling causes light leaks underground in caves with Ray Tracing on
- [MCPE-159164](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159164) - Barriers and Light Blocks on chunk borders are darkened with Ray Tracing
- [MCPE-168015](https://bugs.mojang.com/browse/MCPE/issues/MCPE-168015) - A chunk renders strangely when using the end_portal blockshape with Ray Tracing


## 🟨 Worked Around

These issues are also unresolved, but have fortunately been worked around through other means.  
In order to get the maximum number of bug fixes at once, use Vanilla RTX or Vanilla RTX Normals, alongside the Supervanilla RTX shader mod from the Vanilla RTX App.

### Fixed by Supervanilla RTX

[Supervanilla RTX](https://vanillartx.net/supervanilla-rtx) is a shader mod for Minecraft RTX, installed through the [Vanilla RTX App](https://vanillartx.net/app). It fixes these in the ray tracing shaders themselves. A few of them rely on the resource pack providing the right textures; Vanilla RTX does, and the [creator docs](https://vanillartx.net/supervanilla-rtx-docs) explain how for other packs.

- [MCPE-194207](https://bugs.mojang.com/browse/MCPE/issues/MCPE-194207) - Placing or breaking blocks causes surrounding blocks to flicker with Ray Tracing enabled
- [MCPE-227510](https://bugs.mojang.com/browse/MCPE/issues/MCPE-227510) - The block destruction (breaking) animated texture overlay appears glitchy with Ray Tracing
- [MCPE-240950](https://bugs.mojang.com/browse/MCPE/issues/MCPE-240950) - Flipbook textures' heightmaps do not render correctly in ray-traced graphics mode
- [MCPE-230978](https://bugs.mojang.com/browse/MCPE/issues/MCPE-230978) - Redstone torches always render their alpha channel at full opacity with ray tracing
- [MCPE-128708](https://bugs.mojang.com/browse/MCPE/issues/MCPE-128708) - Glass has reflections on the bottom of blocks and panes with RTX
- [MCPE-137654](https://bugs.mojang.com/browse/MCPE/issues/MCPE-137654) - Ray Traced shadows have flickering edges
- [MCPE-136109](https://bugs.mojang.com/browse/MCPE/issues/MCPE-136109) - The irradiance cache resets at sunset too jarring
- [MCPE-237181](https://bugs.mojang.com/browse/MCPE/issues/MCPE-237181) - End Flashes don't work correctly with ray tracing
- [MCPE-71754](https://bugs.mojang.com/browse/MCPE/issues/MCPE-71754) - Emissive blocks don't emit light while held with Ray Tracing
- [MCPE-139002](https://bugs.mojang.com/browse/MCPE/issues/MCPE-139002) - Bows are darkened when Ray Tracing is on (also fixed by BetterRTX)
- [MCPE-126983](https://bugs.mojang.com/browse/MCPE/issues/MCPE-126983) - Blocks on the edge of clouds cause graphical glitches with Ray Tracing
- [MCPE-159473](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159473) - Some areas of the world render incorrectly with Ray Tracing when Render Clouds is on
- [MCPE-159474](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159474) - Clouds experience render errors and jitter with Ray Tracing
- [MCPE-121746](https://bugs.mojang.com/browse/MCPE/issues/MCPE-121746) - Cave vines render incorrectly with Ray Tracing on
- [MCPE-120037](https://bugs.mojang.com/browse/MCPE/issues/MCPE-120037) - Placed maps have a rendering issue with Ray Tracing
- [MCPE-132570](https://bugs.mojang.com/browse/MCPE/issues/MCPE-132570) - Odd dots appear on clouds when seen through glass or water with Ray Tracing on
- [MCPE-158951](https://bugs.mojang.com/browse/MCPE/issues/MCPE-158951) - Blocks are not transparent in spectator mode with Ray Tracing (also fixed by BetterRTX)
- [MCPE-157198](https://bugs.mojang.com/browse/MCPE/issues/MCPE-157198) - Hand position becomes incorrect at small window sizes with Ray Tracing
- [MCPE-69351](https://bugs.mojang.com/browse/MCPE/issues/MCPE-69351) - Hand and held items become disjointed from the body at high FOV with RTX enabled
- [MCPE-151923](https://bugs.mojang.com/browse/MCPE/issues/MCPE-151923) - Frog spawn renders incorrectly with Ray Tracing on
- [MCPE-167174](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167174) - Decorated Pots can't use PBR textures (Mojang won't fix this one)

#### With no Mojira report

- Water renders inside boats
- Mobs with glowing parts in vanilla Minecraft now glow the same way with Ray Tracing, the Creaking's and Copper Golem's eyes included (the emissive textures come with Vanilla RTX)
- Blocks now show their PBR fully even when rendered as entities, for instance the block you hold now shows its PBR, a Glowstone inside a sulfur cube now lights up, your held blocks, items, and emissive parts of entities, can now light up properly
- Nether portals and beacon cores now emit light into the world, instead of merely appearing emissive
- Glass panes no longer have seams, and slabs, stairs, leaves or other blocks flush with glass no longer z-fight. Beacon cores and the inner cubes of slime and honey aren't inside out
- A second glass body seen through glass no longer renders black, and water seen beyond glass is no longer nearly black
- Volumetric fog no longer disappears through glass, and shows up in reflections like the surface of water and mirrors
- Lily pads, frogspawn, big dripleaf, and sunflower heads now show the side facing you
- Shelves are darkened with ray tracing when rendered as an entity
- The caps of iron and copper bars no longer z-fight with the block above or below
- Half of screen turning black with superultrawide resolutions (such as 5120x1440) without upscaling.
- Faces seen from behind no longer show their normal map's relief inverted
- Banner poles no longer take the cloth's dye
- The appearance of enchanted items has been restored to look like fancy graphics
- The End portal now features a new VFX instead of appearing black
- The End's sky is no longer black
- The sky's gradient no longer shows a visible band at every row of the sky texture
- Terrain seen behind the player through a mirror no longer ends in a hard cut where the game drops chunks
- The screen no longer stays dark until the window is resized after a shader pass hits an invalid value

### Fixed by Vanilla RTX

These are worked around by the Vanilla RTX resource packs, with or without Supervanilla RTX.

- [MCPE-227624](https://bugs.mojang.com/browse/MCPE/issues/MCPE-227624) - Point lights have been unintentionally removed from several light sources in ray tracing graphics mode - lanterns, torches, and the end rod among them (still impacts some blocks even with Vanilla RTX's workaround)
- [MCPE-183631](https://bugs.mojang.com/browse/MCPE/issues/MCPE-183631) - The Breeze's wind texture doesn't animate with Ray Tracing, appearing completely black instead
- [MCPE-141530](https://bugs.mojang.com/browse/MCPE/issues/MCPE-141530) - Wither visuals don't function properly with Ray Tracing
- [MCPE-157438](https://bugs.mojang.com/browse/MCPE/issues/MCPE-157438) - The Warden renders incorrectly with Ray Tracing
- [MCPE-111414](https://bugs.mojang.com/browse/MCPE/issues/MCPE-111414) - Villagers are displayed differently with RTX
- [MCPE-121412](https://bugs.mojang.com/browse/MCPE/issues/MCPE-121412) - Doors appear darkened with Ray Tracing on (also fixed by Supervanilla RTX)
- [MCPE-189266](https://bugs.mojang.com/browse/MCPE/issues/MCPE-189266) - Cross-shaped blocks, foliage and crops have widespread rendering errors with Ray Tracing (also fixed by Supervanilla RTX)
- [MCPE-166159](https://bugs.mojang.com/browse/MCPE/issues/MCPE-166159) - Chiseled Bookshelves don't render properly in RTX
- [MCPE-167161](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167161) - Decorated Pots have Z-fighting issues with Ray Tracing (also fixed by Supervanilla RTX)
- [MCPE-168100](https://bugs.mojang.com/browse/MCPE/issues/MCPE-168100) - The newer Decorated Pot model still renders incorrectly with Ray Tracing (also fixed by Supervanilla RTX)
- [MCPE-227815](https://bugs.mojang.com/browse/MCPE/issues/MCPE-227815) - Tamed cats' shadows don't render except for their collar with Ray Tracing enabled
- [MCPE-180359](https://bugs.mojang.com/browse/MCPE/issues/MCPE-180359) - The Soul Torch does not have a point light in ray-traced graphics mode
- [MCPE-183629](https://bugs.mojang.com/browse/MCPE/issues/MCPE-183629) - The XP orb's broken UV animation makes it always appear small
- [MCPE-227676](https://bugs.mojang.com/browse/MCPE/issues/MCPE-227676) - The Copper Golem is missing its eyes
- [MCPE-232873](https://bugs.mojang.com/browse/MCPE/issues/MCPE-232873) - Iron Golem cracked texture rapidly flickers in Ray Traced graphics mode
- [MCPE-113992](https://bugs.mojang.com/browse/MCPE/issues/MCPE-113992) - Chain PBR textures don't load and start emitting light in certain locations
- [MCPE-238815](https://bugs.mojang.com/browse/MCPE/issues/MCPE-238815) - Sulfur Cube has transparency issues when in water. (also fixed by Supervanilla RTX)

#### With no Mojira report

These don't have a Mojira ticket to link, so they're just mentioned briefly here.

- The Invisibility effect now properly hides the Spider, Cave Spider, Phantom, and Enderman models with Ray Tracing
- Candles now have an emissive wick, since they lack a point light like other light sources do (1.21.80+ only)
- Tropical fish patterns no longer fail to composite when the fish's base layer is transparent, which was making large parts of their fins invisible
- Water in a cauldron no longer uses the wrong texture, which gave it a rough, non-water-like appearance
- Jack o'Lanterns now emit light from all sides, matching their vanilla appearance and function more closely
- In-world enchanted tridents and firework rockets no longer render completely black (tridents also fixed by Supervanilla RTX)
- The Creaking's eyes stay visible even while the Creaking itself is invisible; its black texture issues are also resolved
- Iron Golem texture crack rendering issues have been resolved
- The Sulfur Cube's rendering issues with Ray Tracing have been resolved
- Entities and blocks with invisible or unintentionally rasterized parts - the Snow Golem's head, the Mooshroom's mushrooms, and blocks inside minecarts - are corrected (tracked as Vanilla RTX issue #28)
- Every rasterized particle has been adjusted to blend in with the ray-traced world

### Worked around by the Vanilla RTX App

- [MCPE-191513](https://bugs.mojang.com/browse/MCPE/issues/MCPE-191513) - Ray Tracing can no longer be enabled from the main menu, only from within a loaded world (worked around by the Vanilla RTX App)
- [MCPE-152158](https://bugs.mojang.com/browse/MCPE/issues/MCPE-152158) - PBR textures don't load properly, leaving every block shiny, when Ray Tracing is enabled right after a fresh game launch (worked around by the Vanilla RTX App)
- [MCPE-121850](https://bugs.mojang.com/browse/MCPE/issues/MCPE-121850) - Ray Tracing suffers severe performance starvation when the game's VSync is enabled (worked around by the Vanilla RTX App)

Tip: installing a BetterRTX preset will also help fix several more issues from the unresolved list (particularly the ones marked as (🟨Fixed by BetterRTX))

## 🟩 Resolved

These issues should no longer happen in the most recent versions of Minecraft, but there is always a chance they might return if Mojang runs out of ideas to add bugs.

- [MCPE-162107](https://bugs.mojang.com/browse/MCPE/issues/MCPE-162107) - Loading an RTX resource pack crashed the game (fixed in Preview 1.19.70.26)
- [MCPE-152645](https://bugs.mojang.com/browse/MCPE/issues/MCPE-152645) - The engine switched to DX11 after quitting a world with RTX on, disabling DXR (fixed in Hotfix 1.18.31)
- [MCPE-161517](https://bugs.mojang.com/browse/MCPE/issues/MCPE-161517) - RTX GPUs had worse performance than GTX GPUs (fixed in Release 1.19.80)
- [MCPE-243629](https://bugs.mojang.com/browse/MCPE/issues/MCPE-243629) - Ray Tracing crashes the game every time it is used except after the very first time
- [MCPE-145618](https://bugs.mojang.com/browse/MCPE/issues/MCPE-145618) - Performance was poor during new world generation with Ray Tracing, also filed as MCPE-143156 (fixed in Hotfix 1.17.41)
- [MCPE-111547](https://bugs.mojang.com/browse/MCPE/issues/MCPE-111547) - Held and dropped items with high-res textures caused an excessive performance drop with RTX (fixed in Preview 1.19.80.21)
- [MCPE-113380](https://bugs.mojang.com/browse/MCPE/issues/MCPE-113380) - High-res resource packs fell back incorrectly on Beta and Stable even on supported hardware (fixed in Hotfix 1.19.81)
- [MCPE-135157](https://bugs.mojang.com/browse/MCPE/issues/MCPE-135157) - RTX had dark spots everywhere and light failed to spread from most blocks (fixed in Beta 1.17.30.22)
- [MCPE-163622](https://bugs.mojang.com/browse/MCPE/issues/MCPE-163622) - Albedo colour arrays in texture sets displayed as completely black (fixed in Preview 1.19.60.20)
- [MCPE-194870](https://bugs.mojang.com/browse/MCPE/issues/MCPE-194870) - Most entity textures appear completely black with Ray Tracing
- [MCPE-242595](https://bugs.mojang.com/browse/MCPE/issues/MCPE-242595) - Entities appear glossy with ray tracing because they use a wrong fallback PBR material.
- [MCPE-140674](https://bugs.mojang.com/browse/MCPE/issues/MCPE-140674) - Some devices that support RTX are occasionally marked as unsupported
- [MCPE-166846](https://bugs.mojang.com/browse/MCPE/issues/MCPE-166846) - RTX textures can load incorrectly
- [MCPE-166947](https://bugs.mojang.com/browse/MCPE/issues/MCPE-166947) - All RTX point lights were white (fixed in Preview 1.19.80.20)
- [MCPE-162445](https://bugs.mojang.com/browse/MCPE/issues/MCPE-162445) - Night behaved like day with Ray Tracing (fixed in Hotfix 1.19.41)
- [MCPE-156577](https://bugs.mojang.com/browse/MCPE/issues/MCPE-156577) - Player skins turned black with Ray Tracing (fixed in Preview 1.19.20.23)
- [MCPE-132747](https://bugs.mojang.com/browse/MCPE/issues/MCPE-132747) - The horse base coat texture was completely black with Ray Tracing on (fixed in Preview 1.19.20.23)
- [MCPE-220313](https://bugs.mojang.com/browse/MCPE/issues/MCPE-220313) - "Allow In-game Graphics Mode Switching" had to be toggled on for PBR textures to load with Ray Tracing (fixed in Preview 1.21.100.23)
- [MCPE-218920](https://bugs.mojang.com/browse/MCPE/issues/MCPE-218920) - Player and entity name tags did not render with Ray Tracing
- [MCPE-183959](https://bugs.mojang.com/browse/MCPE/issues/MCPE-183959) - The Ender Dragon's healing beams disappeared when Ray Tracing was enabled
- [MCPE-142040](https://bugs.mojang.com/browse/MCPE/issues/MCPE-142040) - The fire overlay was not displayed with Ray Tracing (fixed in Preview 1.19.30.22)
- [MCPE-153958](https://bugs.mojang.com/browse/MCPE/issues/MCPE-153958) - The sun's Ray Traced point of emission stopped changing with the time of day (fixed in Preview 1.19.0.29)
- [MCPE-159485](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159485) - Several emissive blocks had incorrect point lights with Ray Tracing (fixed in Preview 1.19.20.24)
- [MCPE-159488](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159488) - Lanterns and end rods had randomly positioned point lights (fixed in Preview 1.19.40.24)
- [MCPE-167638](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167638) - Sign text didn't show with RTX on (fixed in Hotfix 1.19.71)
- [MCPE-167551](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167551) - The block outline didn't show with RTX on (fixed in Hotfix 1.19.71)
- [MCPE-240625](https://bugs.mojang.com/browse/MCPE/issues/MCPE-240625) - Hoppers inside minecarts use the entire texture atlas instead of a single texture in ray-traced graphics mode
- [MCPE-126617](https://bugs.mojang.com/browse/MCPE/issues/MCPE-126617) - PBR textures didn't work when using texture variations (fixed in Preview 1.21.50.24)
- [MCPE-124562](https://bugs.mojang.com/browse/MCPE/issues/MCPE-124562) - PBR textures loaded incorrectly when toggling full screen (fixed in Beta 1.17.0.56)
- [MCPE-159471](https://bugs.mojang.com/browse/MCPE/issues/MCPE-159471) - Heightmap edges were no longer seamless when padding was set to 0 (fixed in Preview 1.19.20.24)
- [MCPE-167550](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167550) - The panorama in the main menu glitched with RTX on (fixed in Preview 1.19.80.20)
- [MCPE-132021](https://bugs.mojang.com/browse/MCPE/issues/MCPE-132021) - Candles didn't accept PBR textures (fixed in Preview 1.21.110.20)
- [MCPE-142918](https://bugs.mojang.com/browse/MCPE/issues/MCPE-142918) - Holding two shields with Ray Tracing only displayed one of them (fixed in Release 1.20.10)
- [MCPE-120504](https://bugs.mojang.com/browse/MCPE/issues/MCPE-120504) - The RTX toggle key could not be rebound (fixed in 1.21.50.20 Preview)
- [MCPE-119949](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119949) - Some blocks had offset textures with Education Edition mode and a resource pack enabled (fixed in Hotfix 1.20.71)
- [MCPE-97466](https://bugs.mojang.com/browse/MCPE/issues/MCPE-97466) - The thumbnail image for a saved world was not taken with Ray Tracing (fixed in Preview 1.20.10.20)
- [MCPE-118898](https://bugs.mojang.com/browse/MCPE/issues/MCPE-118898) - Moon lighting originated from the opposite angle underwater at night (fixed in Preview 1.20.0.20)
- [MCPE-112916](https://bugs.mojang.com/browse/MCPE/issues/MCPE-112916) - Soul torches emitted the wrong colour of light
- [MCPE-119972](https://bugs.mojang.com/browse/MCPE/issues/MCPE-119972) - Blocks with flipbook textures didn't animate their PBR maps
- [MCPE-190607](https://bugs.mojang.com/browse/MCPE/issues/MCPE-190607) - DLSS doesn't work on RTX 50000 Series
- [MCPE-167902](https://bugs.mojang.com/browse/MCPE/issues/MCPE-167902) - Particles are always at maximum brightness with RTX

# Vanilla RTX Bug Tracking
For issues related to the Vanilla RTX App, Vanilla RTX, or other related projects, visit their respective GitHub repositories and check the issues there.

- [Vanilla RTX – Issues](https://github.com/vanilla-rtx/Vanilla-RTX/issues)

- [Vanilla RTX App & RTX Reactor – Issues](https://github.com/vanilla-rtx/Vanilla-RTX-App/issues)

- [Vanilla RTX Add-ons & Extras – Issues](https://github.com/vanilla-rtx/Vanilla-RTX-Extras/issues)

You may also report issues directly through the [Vanilla RTX Discord server's](https://discord.gg/A4wv4wwYud) forum channel.
