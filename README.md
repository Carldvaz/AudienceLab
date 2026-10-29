# AudienceLab for WWE 2K26

AudienceLab is the crowd tool for WWE 2K26. It adds the crowds that come with mods to
your game, lets you create your own crowd inside your mod, and designs the extras'
shirts in 3D.

- **Add crowds.** Mods that bring their own crowd include a `.audiencelab` file. Drop
  it on AudienceLab (or double-click it, or browse to it) to add the crowd to your
  game's crowd list. Uninstalling a mod? Remove its crowd just as easily.
- **Create a crowd.** Start from any game crowd (default, Mexican, Japanese...) and
  choose how many men, women and kids it has. AudienceLab writes the crowd and a
  `.audiencelab` file to share it with your mod; then pick it for your arena in
  ArenaLab.
- **Design the shirts in 3D.** All the extras of a crowd in one place, on a 3D model.
  Put logos on the chest or back, lift a logo that's already painted on a shirt to
  move or resize it, recolor shirts, build a jersey from a flat template or a photo,
  or fill the whole shirt with a seamless pattern. Logos follow the shirt's folds.
- **Shirt sheets.** Prefer your own image editor? Export every extra of a crowd group
  to one sheet, paint it, and bring it back: AudienceLab builds the whole group,
  textures included.

AudienceLab never touches the game's own files: your crowds and shirts go in your mod,
and the crowd list in your BakeMe.

## Download

Get **AudienceLab_&lt;version&gt;.zip** from the [latest release](../../releases/latest)
and unzip the AudienceLab folder anywhere. Keep `texconv.exe` next to
`AudienceLab.exe`: it turns the shirts into game textures.

## Getting started

1. Run **AudienceLab.exe**. The first time, choose your BakeMe folder: the game's crowd
   list (`Audience\AudienceDefs.jsfb`) lives there. If it's missing, AudienceLab helps
   you add it.
2. The game's plain shirts come with the app. To start from other crowds' shirts,
   extract the game files with CakeView and choose that folder.
3. After adding, removing or changing a crowd, bake your BakeMe (and your mod) again
   with CakeView. AudienceLab reminds you.

**Bake the folder that contains `Audience`, never the `Audience` folder itself.** If you
bake `Audience` on its own, the game can't find the crowds on its list and freezes
before it starts.

## Updates

When it starts, AudienceLab checks this page for a newer version. If there is one, it
shows what's new and an **Update now** button: it downloads the new version, checks it,
replaces itself and restarts. That check is the only time it goes online.

## Uninstall

There's no installer. If you turned on double-click for `.audiencelab` files, turn it
off in the Add Crowd tab, then delete the folder.

## Notes

- The game can only use the crowds on its list: an arena whose crowd isn't on it
  crashes when it loads. When you uninstall a mod, remove its crowd in AudienceLab and
  bake again.
- Windows only.

## Credits

- texconv by Microsoft ([DirectXTex](https://github.com/microsoft/DirectXTex), MIT
  license), included with its license.
